# Android Rom

### 🤖 类原生系统

> 刷机有风险，记得备份数据！

![LineageOS](_res/LineageOS.png) **LineageOS** ![GPLv3](_res/GPLv3.png) ![ASF](_res/ASF.png)<br>
自由、开源、免费的 Android 系统<br>
[官网](https://lineageos.org/) / [Github 源代码 ![Github](_res/Github.png)](https://github.com/LineageOS)<br>
[维基百科 ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/LineageOS)

![LineageOS for microG](_res/LineageOS_for_microG.png) **LineageOS for microG** ![GPLv3](_res/GPLv3.png)<br>
内置 ![MicroG](_res/MicroG.png) **MicroG** 的 **LineageOS**<br>
[官网](https://lineage.microg.org/) / [Github 源代码 ![Github](_res/Github.png)](https://github.com/lineageos4microg)<br>
[维基百科 ![Wikipedia](_res/Wikipedia.png)](https://en.wikipedia.org/wiki/LineageOS_for_microG)

<details markdown='1'><summary>MicroG</summary>

![MicroG](_res/MicroG.png) **MicroG**  ![ASF](_res/ASF.png)<br>
Google 移动服务的开源版，使用服务同时不被 Google 监视与追踪<br>
[官网](https://microg.org/) / [Github 源代码 ![Github](_res/Github.png)](https://github.com/microg)<br>
[维基百科 ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/MicroG)

</details>

![crDroid](_res/crDroid.png) **crDroid** ![GPLv3](_res/GPLv3.png) ![ASF](_res/ASF.png)<br>
基于 ![LineageOS](_res/LineageOS.png) **LineageOS** 的 Android 系统，功能比较丰富<br>
[官网](https://crdroid.net/) / [Github 仓库 ![Github](_res/Github.png)](https://github.com/crdroidandroid)<br>
[维基百科 ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/CrDroid)

<br>


### 🔓 第三方 REC

> [Recovery / 恢复分区 ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/Android恢复模式)

![TWRP](_res/TWRP.png) **TWRP / TeamWin Recovery Project** ![GPLv3](_res/GPLv3.png)<br>
[官网](https://twrp.me/) / [Github 源代码 ![Github](_res/Github.png)](https://github.com/Teamwin/android_bootable_recovery)<br>
[维基百科 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.wikipedia.org/zh-cn/TWRP)

![OrangeFox](_res/OrangeFox.png) **OrangeFox REC**<br>
[官网](https://orangefox.download/zh-CN) / [Gitlab 源代码 ![Gitlab](_res/Gitlab.png)
](https://gitlab.com/OrangeFox/infrastructure/dsite)


<details markdown='1'><summary>💻 用 ADB 刷入第三方 REC</summary>

> 刷入第三方 REC 前必须了解 Android  设备有无 Recovery 分区。若无 Recovery 分区则无法刷入第三方 REC！<br><br>建议观看：<br>[查看卡刷包的 payload.bin 文件 ![Video_Bilibili](_res/Video_Bilibili.png)](https://bilibili.com/BV1Ht8veiE47)<br>[给有 Recovery 分区的小米6刷机 ![Video_Bilibili](_res/Video_Bilibili.png)](https://bilibili.com/BV1KJ4m1u7or)<br>[给无 Recovery 分区的小米平板6刷机 ![Video_Bilibili](_res/Video_Bilibili.png)](https://bilibili.com/BV1sT421a7VS)

> 手机要打开「开发者选项」和「USB 调试」，电脑要准备好 [![Android](_res/Android.png) ADB](https://developer.android.com/tools/releases/platform-tools?hl=zh-cn) 工具，操作时用**数据线**连接电脑与手机，并逐行执行**命令**。

- 识别设备：<br>adb devices

- 重启到 Fastboot：<br>adb reboot bootloader

- 在 Fastboot 识别设备：<br>fastboot devices

- 刷入 TWRP / OrangeREC：<br>fastboot flash recovery 「第三方 REC 路径」（将镜像拖入命令框）

- 从 Fastboot 重启到第三方 REC ：<br>fastboot reboot recovery<br>（成功率较低，有可能重启到系统)，

- 从 System 重启到 第三方 REC：<br>adb reboot recovery

</details>

<br>

***

### 🔧 用 ADB 修复类原生系统问题

<details markdown='1'><summary>ADB 调试 Android 手机</summary>

> 注：手机打开「开发者选项」和「USB 调试」，电脑准备 [![Android](_res/Android.png) SDK](https://developer.android.com/tools/releases/platform-tools?hl=zh-cn) 工具，操作时用**数据线**连接电脑与手机，并逐行执行**命令**。

在 ![设置](_res/设置.png) **设置**依次点击「关于本机」，连续点击「Build 号」直到提示「您已经启用了开发者选项！」；

接着返回首页，依次点击「系统」→「开发者选项」，打开「USB 调试」。

</details>

<br>

<details markdown='1'><summary>ADB 无线调试 Android 手机</summary>

> 注：无线调试仅在 Android 11 及以上拥有；电脑与手机得连接在同一 WIFI
> 
> Windows 直接输入指令，Linux 上要在指令前加「./」

1. 手机打开「开发者模式」，并在里面打开「USB 调试」与「无线调试」；

2. 进入「无线调试」点击「使用配对码配对设备」，在终端里输 `adb pair (弹窗里的IP与端口)` 并回车，在「Enter pairing code:」输入配对码，提示「Successfully paired to 192.168.124.xxx...」即配对成功；

3. 在终端输入 `adb connect 192.168.124.xxx:xxxxx (无线调试的IP与端口)`并回车，提示「connected to 192.168.124.xxx:xxxxx」即连接成功。

4. 退出无线调试：在终端输入 `adb disconnect`

</details>

<br>

<details markdown='1'><summary>去除 WIFI 图标感叹号</summary>

- 删除默认服务器：

    adb shell settings delete global captive_portal_https_url

    adb shell settings delete global captive_portal_http_url

- 添加新的服务器（MIUI）：

    adb shell settings put global captive_portal_https_url https://connect.rom.miui.com/generate\_204

    adb shell settings put global captive_portal_http_url http://connect.rom.miui.com/generate\_204

- 重连 WIFI 即生效。

    > 为什么不用  [![NoExclamation](_res/NoExclamation.png) **NoExclamation**](https://github.com/Noisyfox/NoExclamation/releases) 或 ![CaptiveMgr](_res/CaptiveMgr.png) **CaptiveMgr**？（这两个软件需要 ROOT）
    > 
    > **NoExclamation** 最后一次更新在2017年，高安卓版本不适用。我没找到 **CaptiveMgr** 官网和源代码，第三方分享的不安全。

</details>

<br>

<details markdown='1'><summary>修复时间同步问题</summary>

- 设置中国时区：

    adb shell setprop persist.sys.timezone Asia/Shanghai

- 设置 NTP 服务器：

    adb shell settings put global ntp_server ntp1.aliyun.com

</details>

<br>

<details markdown='1'><summary>应用双开</summary>

> 参考：
> 
> [Android原生系统应用双开](https://blog.shinoaa.com/2024/01/02/App%20clone/)
> 
> [「root/adb」无视系统限制，双开任意app](https://bbs.oneplus.com/thread/5817716)

- 创建名为「myspace」的「影子用户」（默认用户 id 为10）：<br>adb shell pm create-user --profileOf 0 --managed myspace

- 列出当前所有用户及 id：<br>adb shell pm list users

- 使 id 为10的用户启动：<br>adb shell am start-user 10		

- 为 id 为10的用户安装 app：<br>adb install --user 10 <apk包名>

</details>

<br>




