# Windows Software

### 📢 前提

如果你是第一次阅读此文档，并从未了解**软件许可证**，建议先看下面的「🪪 软件许可证」。下面的软件清单中大部分**开源 / 自由软件**都带有许可证。

<details markdown='1'><summary>🪪 软件许可证</summary>

[软件许可证 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/%E8%BD%AF%E4%BB%B6%E8%AE%B8%E5%8F%AF%E8%AF%81) / [自由软件 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/%E8%87%AA%E7%94%B1%E8%BD%AF%E4%BB%B6%E8%AE%B8%E5%8F%AF%E8%AF%81)

编程随想的《[澄清“自由软件、开源软件”相关概念及许可证的误解](https://program-think.blogspot.com/2019/03/Misunderstand-Free-and-Open-Source-Software.html)》、《[如何选择开源项目](https://program-think.blogspot.com/2009/02/how-to-choose-opensource-project.html)》
> 依靠**License（授权协议、许可证）**、技术层面的因素、**普及程度（用户的人气）**、**活跃程度（开发的人气）**、其它的风险 选择开源项目<br>（加粗的方法是**非技术者**能做到的）

<br>

| 许可证图标 | 许可证名称 |
| --- | --- |
| ![GPLv3](_res/GPLv3.png) | [GNU通用公共许可证 ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/GNU%E9%80%9A%E7%94%A8%E5%85%AC%E5%85%B1%E8%AE%B8%E5%8F%AF%E8%AF%81) |
| ![LGPLv3](_res/LGPLv3.png) | [GNU宽通用公共许可证 ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/GNU%E5%AE%BD%E9%80%9A%E7%94%A8%E5%85%AC%E5%85%B1%E8%AE%B8%E5%8F%AF%E8%AF%81) |
| ![AGPLv3](_res/AGPLv3.png) | [GNU Affero通用公共许可证 ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/GNU_Affero%E9%80%9A%E7%94%A8%E5%85%AC%E5%85%B1%E8%AE%B8%E5%8F%AF%E8%AF%81) |
| ![BSD](_res/BSD.png) | [BSD许可证 ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/BSD%E8%AE%B8%E5%8F%AF%E8%AF%81) |
| ![Mozilla](_res/Mozilla.png) | [Mozilla公共许可证 ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/Mozilla%E5%85%AC%E5%85%B1%E8%AE%B8%E5%8F%AF%E8%AF%81) |
| ![ASF](_res/ASF.png) | [Apache许可证 ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/Apache%E8%AE%B8%E5%8F%AF%E8%AF%81) |
| ![MIT](_res/MIT.png) | [MIT许可证 ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/MIT%E8%A8%B1%E5%8F%AF%E8%AD%89) |
| ![Cc-zero](_res/Cc-zero.png) | [公有领域 ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/%E5%85%AC%E6%9C%89%E9%A2%86%E5%9F%9F) |
| ![WTFPL](_res/WTFPL.png) | [WTFPL ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/WTFPL) |

</details>

<br>

<details markdown='1'><summary>📥 下载「.exe」、「.msi」等安装包的建议</summary>

优先选 **Github Releases** ![Github](_res/Github.png) 下载「.exe」、「.msi」、「.zip」等文件。因为有些官网不提供「.exe」等文件。若没有 **Github Releases** ![Github](_res/Github.png) 超链接就选官网。<br><br>(注意区分「**Github Releases** ![Github](_res/Github.png)」与「**Github 源代码** ![Github](_res/Github.png)」，后者只有源代码)

</details>

<br>

***

### 🪟 Windows 10 loT LTSC 2021

![Windows_10](_res/Windows_10.png) LTSC 2021 x64 简体中文<br>
[官网](https://software-download.microsoft.com/download/db/444969d5-f34g-4e03-ac9d-1f9786c69161/19044.1288.211006-0501.21h2_release_svc_refresh_CLIENT_LTSC_EVAL_x64FRE_zh-cn.is)

<details markdown='1'><summary>LTSC 2021 详情</summary>

LTSC 2021 x64 简体中文 SHA256：

    2181EAAEED2F1A78BE41F45692671DB050D9FF76291F767AB696147C8A322DA3

其他 LTSC 2021 版本请看[零度解说的博客](https://www.freedidi.com/4805.html)。

Windows 10 LTSC 2021 生命周期结束日期为 **2027年1月12日**。详见[官网](https://learn.microsoft.com/zh-cn/lifecycle/products/windows-10-enterprise-ltsc-2021)。

Windows 10 loT LTSC 2021 生命周期结束日期为**2032年1月13日**，详见
[官网](https://learn-microsoft-com.translate.goog/en-us/lifecycle/products/windows-10-iot-enterprise-ltsc-2021?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN)。

怎么用上 loT LTSC 2021？目前没有 loT LTSC 2021 镜像，但可以在刚安装的 LTSC 2021 上用特定激活密钥转换成 loT LTSC 2021。

</details>

<br>

<details markdown='1'><summary>安装 Windows 10 LTSC 2021 后要干的几件事</summary>

1. 转换 loT LTSC 版本

    打开「设置」→「更新与安全」→「激活」→「激活产品密钥」，然后输入转换 loT LTSC 版本密钥：

    QPM6N-7J2WJ-P88HH-P3YRH-YY74H

    激活后如果不能激活系统，再进行第二步。

2. 激活 Windows 10

    运行前记得先关闭 Windows 安全中心！打开「设置」→「更新与安全」→「Windows 安全中心」→「病毒和威胁防护」，在「“病毒和威胁防护”设置」下点击「管理设置」，关闭「实时保护」、「云提供的保护」、「自动提交样本」、「篡改保护」。

    下载 [![Github](_res/Github.png) HEU KMS 激活工具](https://github.com/zbezj/HEU_KMS_Activator/releases)的 .rar 包，解压后运行 .exe 程序，在「智能激活」里只勾选「数字许可证激活」，再按「开始」，等待激活完成。

    激活完后再打开 Windows 安全中心。

3. 优雅又不失尊严地使用 Win 10 自动更新

    > 相比彻底关闭自动更新。以下方法更妥当。设置后只会提示更新，可以根据实际情况手动下载和安装更新，而不会打扰正常工作与生活。

    按「Win」+「R」，在弹窗里输入「gpedit.msc」打开「本地组策略编辑器」。在左侧依次点击「计算机配置」→「管理模版」→「Windows 组件」→「Windows 更新」，在右侧双击「配置自动更新」，在弹窗里选择「已启用(E)」,选择「2 - 通知下载和自动安装」，最后点击「确定」，完成。

    ![Win_10_自动更新](_res/Win_10_自动更新.png)

4. 设置低权限用户

    ① 按「Win + X」键，在弹窗里选择「计算机管理」，依路径「系统工具 → 本地用户与组 → 用户」；

    ② 右击空白处，在弹窗里选「新用户」；

    ③ 输入「用户名」与「密码」，只勾选「密码永不过期」，最后点「创建」，完成。

5. 其他

    **快速访问设置：**

    打开「文件资源管理器」，在「快速访问」下右击对于文件夹，点「从“快速访问”取消固定」；

    上方「查看」→「选项」，在「打开文件资源管理器时打开：」旁选「此电脑」；在「隐私」下关掉「在“快速访问”中显示...」，完成。

    **将默认文件夹路径设置到D盘并隐藏：**

    在D盘创建对应的文件夹；

    在「此电脑」下右击文件夹，点「属性」，在弹窗点「位置」→「移动(M)...」，选择D盘对于的文件夹，最后点「确定」；

    右击文件夹，点「属性」，选择「隐藏」，点「确定」，在弹窗内选「仅将更改应用于所选项」，完成。

</details>

<br>

***

### ⌨️ 基础工具

![Rime](_res/Rime.png) **Rime 输入法** ![BSD](_res/BSD.png)<br>
自由、开源、免费、跨平台的中文输入法<br>
[官网](https://rime.im/download/) / [Github Releases ![Github](_res/Github.png)](https://github.com/rime/weasel/releases)<br>
[维基百科 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.wikipedia.org/zh-cn/%E4%B8%AD%E5%B7%9E%E9%9F%BB%E8%BC%B8%E5%85%A5%E6%B3%95%E5%BC%95%E6%93%8E)

![Localsend.png](_res/Localsend.png) **LocalSend** ![ASF](_res/ASF.png)<br>
局域网文件传输工具<br>
[官网](https://localsend.org/download) / [Github Releases ![Github](_res/Github.png)](https://github.com/localsend/localsend/releases)

![7zip.png](_res/7zip.png) **7zip** ![LGPLv3](_res/LGPLv3.png)<br>
文件压缩、解压、效验文件哈希值工具<br>
[官网](https://www.7-zip.org/download.html) / [Github Releases ![Github](_res/Github.png)](https://github.com/ip7z/7zip/releases)<br>
[维基百科 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.wikipedia.org/wiki/7-Zip)

![FastCopy](_res/FastCopy.png) **FastCopy**  ![GPLv3](_res/GPLv3.png)<br>
快速拷贝文件工具<br>
[官网](https://fastcopy.jp/)<br>
[维基百科 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.wikipedia.org/wiki/FastCopy)

![GnuPG](_res/GnuPG.png) **GPG4win** ![GPLv3](_res/GPLv3.png)<br>
加密、签名工具<br>
[官网](https://gnupg.org/download/index.html) / [Github 源代码 ![Github](_res/Github.png)](https://github.com/gpg/gnupg)<br>
[维基百科 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.wikipedia.org/wiki/GnuPG)

![KeePassXC](_res/KeePassXC.png) **KeePassXC** ![GPLv3](_res/GPLv3.png)<br>
本地密码管理器，支持 Password / 口令认证、[Key File / 密钥文件 ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/%E5%AF%86%E9%92%A5%E6%96%87%E4%BB%B6)认证、硬件认证<br>
[官网](https://keepassxc.org/download/#linuxhttps://keepassxc.org/download/) / [Github Releases ![Github](_res/Github.png)](https://github.com/keepassxreboot/keepassxc/releases)<br>
[维基百科 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/KeePassXC) / [粉碎棱镜⚡推荐](https://prism-break.org/zh-CN/projects/keepassxc/)

![GeekUninstaller.png](_res/GeekUninstaller.png) **GeekUninstaller**<br>
强力卸载工具<br>
[官网](https://geekuninstaller.com/download)

![Dimmer](_res/Dimmer.png) **Dimmer**<br>
降低屏幕亮度工具<br>
[官网](https://www.nelsonpires.com/software/dimmer)

![ContextMenuManager](_res/ContextMenuManager.png) **ContextMenuManager** ![GPLv3](_res/GPLv3.png)<br>
管理 Windows 右键菜单工具<br>
[官网](https://bluepointlilac.github.io/ContextMenuManager/) / [Github Releases ![Github](_res/Github.png)](https://github.com/BluePointLilac/ContextMenuManager/releases)

> Windows 10 LTSC 2021 就下载「.NET.4.0」版

![Everything](_res/Everything.png) **Everything**<br>
文件搜索工具<br>
[官网](https://www.voidtools.com/downloads/)<br>
[维基百科 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/Everything_(%E8%BD%AF%E4%BB%B6))

<br>

***

### 🖼️ 图片

![JEPGView.png](_res/JEPGView.png) **JPEGView**  ![GPLv3](_res/GPLv3.png)<br>
图片查看器<br>
[官网](https://jpegview.en.lo4d.com/windows) / [Github Releases ![Github](_res/Github.png)](https://github.com/sylikc/jpegview/releases)

> 该项目最后一次更新在2023年10月7日

![Krita.png](_res/Krita.png) **Krita**  ![GPLv3](_res/GPLv3.png)<br>
自由、开源、免费、跨平台的绘图工具<br>
[官网](https://krita.org/zh-cn/) / [Github 源代码 ![Github](_res/Github.png)](https://github.com/KDE/krita)<br>
[维基百科 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.wikipedia.org/wiki/Krita)

<br>

### ▶️ 视频

![VLC.png](_res/VLC.png) **VLC**  ![GPLv3](_res/GPLv3.png) ![LGPLv3](_res/LGPLv3.png)<br>
视频翻放器<br>
[官网](https://www.videolan.org/vlc/download-windows.html) / [Github 源代码 ![Github](_res/Github.png)](https://github.com/videolan/vlc)<br>
[维基百科 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.wikipedia.org/zh-cn/VLC%E5%A4%9A%E5%AA%92%E9%AB%94%E6%92%AD%E6%94%BE%E5%99%A8)

![HandBrake.png](_res/HandBrake.png) **HandBrake**  ![GPLv3](_res/GPLv3.png)<br>
自由、开源、免费、跨平台的视频压缩工具<br>
[官网](https://handbrake.fr/downloads.php) / [Github Releases ![Github](_res/Github.png)](https://github.com/HandBrake/HandBrake/releases)<br>
[维基百科 ![Wikipedia.png](_res/Wikipedia.png)](https://en.wikipedia.org/wiki/HandBrake)

<br>

### 📑 文档

![Notepad++](_res/Notepad++.png) **Notepad++** ![GPLv3](_res/GPLv3.png)<br>
笔记本<br>
[官网](https://notepad-plus-plus.org/downloads/) / [Github Releases ![Github](_res/Github.png)](https://github.com/notepad-plus-plus/notepad-plus-plus/releases)<br>
[维基百科 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.wikipedia.org/wiki/Notepad%2B%2B)

<details markdown='1'><summary>Notepad++ 设置简体中文</summary>

依次点击「Setting」→「Preferences」，在弹窗内 Localization 选择「简体中文」，完成。

</details>

![Visual-Studio-Code](_res/Visual-Studio-Code.png) **Visual Studio Code** <br>
功能丰富的编辑器<br>
[官网](https://code.visualstudio.com/download#) / [Github 源代码 ![Github](_res/Github.png)](https://github.com/microsoft/vscode)<br>
[维基百科 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.wikipedia.org/wiki/Visual_Studio_Code)

<details markdown='1'><summary>Visual Studio Code 设置自动保存</summary>

自动保存非常重要。当发生意外（忘记手动保存、电脑意外关机）这个功能能救文档数据的命的！（俺因为没开自动保存，差点丢失几个小时编辑的文案 :-( ）

但 VScode 默认不开启自动保存。我不知道官方是怎么想的。

在 VScode 主界面点击左下角齿轮图标，在弹窗里点击「设置」，在搜索栏输入「auto save」,在「Auto Save」一项选择「afterDelay」（意思是设定自动延迟保存文件）。默认延迟保存时间为 1000 毫秒，如果要修改时间，就在「Auto Save Delay」下修改。（单位是毫秒）

> 参考：[Visual Studio Code (VS Code) 设置自动保存功能](https://www.cnblogs.com/kaige050218/p/18454581)

</details>

> 这里不得不吐槽一下 ![Yank_Note](_res/Yank_Note.png) **Yank Note**，本身就是从 ![Visual-Studio-Code](_res/Visual-Studio-Code.png) **Visual Studio Code** 改来，暗黑模式还收费？！

![LibreOffice.png](_res/LibreOffice.png) **LibreOffice** ![Mozilla](_res/Mozilla.png)<br>
自由、开源、免费、跨平台的办公套件<br>
[官网](https://www.libreoffice.org/download/download-libreoffice/)<br>
[维基百科 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.wikipedia.org/zh-cn/LibreOffice)

![Sumatra-PDF](_res/Sumatra-PDF.png) **Sumatra PDF** ![GPLv3](_res/GPLv3.png)<br>
Microsoft Windows 专属开源轻量 PDF 阅读器<br>
[官网](https://www.sumatrapdfreader.org/download-free-pdf-viewer) / [Github 源代码 ![Github](_res/Github.png)](https://github.com/sumatrapdfreader/sumatrapdf)<br>
[维基百科 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/Sumatra_PDF)

<br>

### 📥 数据同步

![FreeFileSync.png](_res/FreeFileSync.png) **Free File Sync**  ![GPLv3](_res/GPLv3.png)<br>
跨平台文件同步工具<br>
[官网](https://freefilesync.org/download.php) / [Github Releases ![Github](_res/Github.png)](https://github.com/hkneptune/FreeFileSync/releases)<br>
[维基百科 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.wikipedia.org/zh-cn/FreeFileSync)

![Syncthing](_res/Syncthing.png) **Syncthing** ![Mozilla](_res/Mozilla.png) ![MIT](_res/MIT.png)<br>
跨平台分布式文件同步工具<br>
[官网](https://syncthing.net/downloads/) / [Github  Releases ![Github](_res/Github.png)](https://github.com/syncthing/syncthing/releases)<br>
[维基百科 ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/Syncthing) / [粉碎棱镜⚡推荐](https://prism-break.org/zh-CN/projects/syncthing/)

![Syncthing](_res/Syncthing.png) **SyncTrayzor** ![MIT](_res/MIT.png)<br>
**Syncthing** 的 Windows 托管程序<br>
[Github Releases ![Github](_res/Github.png)](https://github.com/canton7/SyncTrayzor/releases)
/ [SourceForge 源代码 ![SourceForge](_res/SourceForge.png)](https://sourceforge.net/projects/synctrayzor.mirror/)

> 此项目在2025年4月3日归档

<details markdown='1'><summary>SyncTrayzor 与 Syncthing 的关系</summary>

由于 **Syncthing** 是一个命令行程序，前端界面要用浏览器打开，比较麻烦。所以新手可以先下载 **SyncTrayzor**，这是 **Syncthing** 在  Windows 上的托管程序。[![Video_Bilibili](_res/Video_Bilibili.png)](https://bilibili.com/BV12V4y1H7Z5/?t=0h1m17s)

</details>

<br>

<details markdown='1'><summary>SyncTrayzor 开机静默启动</summary>

![Syncthing_开机静默启动_1](_res/Syncthing_开机静默启动_1.png)

![Syncthing_开机静默启动_2](_res/Syncthing_开机静默启动_2.png)

</details>

<br>

### 📥 下载器

![Motrix.png](_res/Motrix.png) **Motrix** ![MIT](_res/MIT.png)<br>
功能丰富的下载器<br>
[官网](https://motrix.app/download) / [Github Releases ![Github](_res/Github.png)](https://github.com/agalwood/Motrix/releases)

![QBittorrent.png](_res/QBittorrent.png) **QBittorrent 增强版**  ![GPLv3](_res/GPLv3.png)<br>
[Github Releases ![Github](_res/Github.png)](https://github.com/c0re100/qBittorrent-Enhanced-Edition/releases)<br>
[维基百科 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.wikipedia.org/wiki/QBittorrent)

<details markdown='1'><summary> QBittorrent 增强版与普通版的区别</summary>

相比 [![QBittorrent.png](_res/QBittorrent.png) QBittorrent 简单版](https://www.qbittorrent.org/download)，**增强版**功能更多，比如：Ban 掉*迅雷用户*、Ban 掉*BT媒体功能*、自动更新 Tracker 功能 [![Video_Bilibili.png](_res/Video_Bilibili.png)](https://bilibili.com/BV1iG4y1975n/?t=0h1m31s)

</details>

<br>

<details markdown='1'><summary>QBittorrent 增强版的基础设置</summary>

1. 点击左上角齿轮图标；<br><br>![QBittorrent增强版_基础设置_1](_res/QBittorrent增强版_基础设置_1.png)

2. 点击左侧「行为」：

    1. 在「桌面」下的「启动时的窗口状态」选择「隐藏」；

    2. 关闭「检查程序更新」；

    3. 在「电源管理」下勾选「下载时禁止系统自动睡眠」

    ![QBittorrent增强版_基础设置_2](_res/QBittorrent增强版_基础设置_2.png)

3. 点击左侧「BitTorrent」：

    1. 在「做种限制」下勾选「当分享率达到...」和「达到总做种时间时...」；

    2. 在「达到上限后」选择「删除 torrent」；
        > 注：下好文件后不要改名、剪切、删除（本体或子文件），等待种完成后自动删除，及时备份。

    3. 勾选「Automatically update public tracker list:」；

    4. 输入 Tracker 地址：<br>https://trackerslist.com/all.txt

    ![QBittorrent增强版_基础设置_3](_res/QBittorrent增强版_基础设置_3.png)

4. 点击左侧「高级」，勾选「Auto Ban Bittorrent Media Player Peer」和「Anto Ban Unknown Peer from China」，最后点击「确定」，完成。<br><br>![QBittorrent增强版_基础设置_4](_res/QBittorrent增强版_基础设置_4.png)

</details>

<br>
 
***

### 🌐 浏览器

推荐阅读编程随想的《[基于安全性考虑，如何选择及切换 Firefox 版本？ ](https://program-think.blogspot.com/2018/10/How-to-Choose-Firefox-Version.html)》

![Firefox.png](_res/Firefox.png) **Firefox** ![Mozilla](_res/Mozilla.png)<br>
火狐浏览器<br>
[官网](https://www.mozilla.org/en-US/firefox/all/#product-desktop-release)<br>
[维基百科 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.wikipedia.org/zh-cn/Firefox%E7%80%8F%E8%A6%BD%E5%99%A8) / [粉碎棱镜⚡推荐](https://prism-break.org/zh-CN/projects/firefox/)


<details markdown='1'><summary>🦊 怎么选择 Firefox 的版本？</summary>

建议下载 [ESR 版 / 延长支持版 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.wikipedia.org/zh-cn/Mozilla_Firefox#%E5%BB%B6%E9%95%B7%E6%94%AF%E6%8F%B4%E7%89%88)

注：要下载 [Mozilla 基金会 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/Mozilla)的「国际版」，不要下载[谋智网络 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/%E8%B0%8B%E6%99%BA%E7%BD%91%E7%BB%9C)定制的「中国版」！

</details>

<br>

<details markdown='1'><summary>🦊 设置 Firefox 为默认浏览器</summary>

 依次点击「开始」→「设置」→「应用」，左侧点击「默认应用」，在右侧的「Web 浏览器」选择 Firefox。
 
 ![Windows换默认浏览器](_res/Windows换默认浏览器.png)
 
</details>

<br>

<details markdown='1'><summary>🦊 桌面端 Firefox / Librewolf 离线安装扩展</summary>

Firefox 扩展后缀名为 **.xpi**，将下载好的 .xpi 文件拖到 Firefox / Librewolf 即可。

</details>

<br>

<details markdown='1'><summary>📖 导出 Firefox / LibreWolf 书签</summary>

点击右上角「≡」，在弹窗选择「书签」，点击「管理书签」，在「我的足迹」弹窗点击「导入和备份(I)」，选择「备份...(B)」，将导出「.json」文件。

</details>

![Librewolf.png](_res/Librewolf.png) **LiberWolf** ![Mozilla](_res/Mozilla.png) ![AGPLv3](_res/AGPLv3.png)<br>
基于 **Firefox** 的隐私浏览器，内置 ![uBlock_Origin](_res/uBlock_Origin.png) **uBlock Origin** 扩展<br>
[官网](https://librewolf.net/installation/windows/)<br>
[维基百科 ![Wikipedia.png](_res/Wikipedia.png)](https://en.wikipedia.org/wiki/LibreWolf)

![Zen-Browser](_res/Zen-Browser.png) **Zen Browser** ![Mozilla](_res/Mozilla.png)<br>
基于 **Firefox** 改造的浏览器，外观继承自 [![Arc-Browser](_res/Arc-Browser.png) Ace 浏览器 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/Arc浏览器) <br>
[官网](https://zen-browser.app/) / [Github Releases ![Github](_res/Github.png)](https://github.com/zen-browser/desktop/releases)<br>
[维基百科 ![Wikipedia.png](_res/Wikipedia.png)](https://en.m.wikipedia.org/wiki/Zen_Browser)

![Tor_Browser.png](_res/Tor_Browser.png) **Tor Browser** ![BSD](_res/BSD.png)<br>
基于 **Firefox** 改造的匿名浏览器，内置 ![NoScript](_res/NoScript.png) **NoScript** 扩展<br>
[官网](https://www.torproject.org/download/) / [GitLab 源代码 ![GitLab](_res/GitLab.png)](https://gitlab.torproject.org/tpo/core/tor/)<br>
[维基百科 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.wikipedia.org/wiki/Tor)	/ [粉碎棱镜⚡推荐](https://prism-break.org/zh-CN/projects/tor/)

<details markdown='1'><summary>🌰 如何使用 Tor Browser / 洋葱浏览器翻墙？</summary>

Tor Browser 的作用是匿名上网，但在屏蔽 Tor 网络的地区（中国大陆、俄罗斯、伊朗等）无法正常使用。官方推出的网桥可以在封锁地区连接 Tor 网络，其中 meek 网桥可以实现「永不被封」（缺点是**网速极慢**，只推荐在其他代理工具无法使用的情怳下**应急**）

在首页点击「配置连接」，在「网桥」下打开「使用网桥」，在「更换网桥」下点击「选择内置网桥...」，在弹窗里选择「meek-azure」，最后回到首页点击「连接」等待 Tor Browser 连接 Tor 网络。（连接过程极长！请保持耐心）

但不要以为连上 Tor 网络就高枕无忧了，还要担心「蜜罐节点」（尤其是中国大陆、香港、澳门的蜜罐节点！！！）解决方法是修改 Tor 的 torrc 文件，规避不安全国家的节点。

首先找到并打开 torrc 文本文件（ Windows 中 torrc 文件位置：你的 Tor Browser 文件夹 /Browser/TorBrowser/Data/Tor），在文本最后添加以下内容，最后保存退出：

***

    ExcludeNodes {cn},{hk},{mo},{kp},{ir},{sy},{pk},{cu},{vn},{ru},{by}
    # ExcludeNodes 表示排除某些危险国家或地区的节点。
    # 后面的国家 / 地区分别是：中国、香港、澳门、朝鲜、伊朗、叙利亚、巴基斯坦、古巴、越南、俄罗斯、白俄罗斯。
    
    StrictNodes 1
    # StrictNodes 1 表示强制执行，即使 Tor 找不到其他国家的节点，也不会连接这些节点
    
    # 表示注释，在 torrc 中所有以 # 开头的行都会被视为注释并且不会影响 Tor 的配置

*** 

推荐阅读：

编程随想《[“如何翻墙”系列：关于 Tor 的常见问题解答](https://program-think.blogspot.com/2013/11/tor-faq.html)》里的《[【隐私】相关的问题](https://program-think.blogspot.com/2013/11/tor-faq.html#head-5)》

拾风记博客《[从国产浏览器到 Tor Browser—— 该如何选择、配置及使用？](https://pickwind.github.io/2022/07/3040192682/)》里的《[三、Tor Browser 浏览器的安装、配置及使用](https://pickwind.github.io/2022/07/3040192682/#h3)》

> 注：以上博文只介绍桌面端的 Tor Browser 修改，没有移动端

</details>

<br>

### 📍 浏览器扩展

推荐阅读编程随想的《[如何防止黑客入侵[5]：Web相关的防范（上） ](https://program-think.blogspot.com/2012/08/howto-prevent-hacker-attack-5.html)》的《[★如何选择插件和扩展？](https://program-think.blogspot.com/2012/08/howto-prevent-hacker-attack-5.html#head-4)》

![Tampermonkey](_res/Tampermonkey.png) **Tampermonkey / 篡改猴** ![GPLv3](_res/GPLv3.png)<br>
自定义网页工具，同[油猴 ![Greasemonkey](_res/Greasemonkey.png) ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/Greasemonkey)<br>
[官网](https://www.tampermonkey.net/index.php?browser=firefox&locale=zh) / [Github 源代码 ![Github](_res/Github.png)](https://github.com/Tampermonkey/tampermonkey) / [Firefox ![Firefox.png](_res/Firefox.png)](https://addons.mozilla.org/zh-CN/firefox/addon/tampermonkey/)<br>
[维基百科 ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/%E7%AF%A1%E6%94%B9%E7%8C%B4)

<details markdown='1'><summary>脚本推荐</summary>

用户脚本网站 [Greasy Fork ![Greasy_Fork](_res/Greasy_Fork.png)](https://greasyfork.org/zh-CN)

[修复“编程随想（阮晓寰）”部落格评论无法显示及评论的问题](https://greasyfork.org/zh-CN/scripts/463052-修复-编程随想-阮晓寰-部落格评论无法显示及评论的问题)

</details>

![Dark_Readed](_res/Dark_Readed.png) **Dark Readed**<br>
显示网页暗色主题<br>
[官网](https://darkreader.org/) / [Github Releases ![Github](_res/Github.png)](https://github.com/darkreader/darkreader/releases) / [Firefox ![Firefox.png](_res/Firefox.png)](https://addons.mozilla.org/en-US/firefox/addon/darkreader/)

![沉浸式翻译](_res/沉浸式翻译.png) **沉浸式翻译**<br>
双语对照网页翻译<br>
[官网](https://immersivetranslate.com/zh-Hans/) / [Github Releases ![Github](_res/Github.png)](https://github.com/immersive-translate/immersive-translate/releases) / [Firefox ![Firefox.png](_res/Firefox.png)](https://addons.mozilla.org/zh-CN/firefox/addon/immersive-translate/)

> 新版不开源，[旧版扩展](https://github.com/immersive-translate/old-immersive-translate)己归档

![Markdown-Viewer-Webext](_res/Markdown-Viewer-Webext.png) **Markdown Viewer Webext** ![MIT](_res/MIT.png)<br>
在浏览器浏览 Markdown 文档<br>
[Github 源代码 ![Github](_res/Github.png)](https://github.com/Cimbali/markdown-viewer) / [Firefox ![Firefox.png](_res/Firefox.png)](https://addons.mozilla.org/zh-CN/firefox/addon/markdown-viewer-webext/)

![SingleFile](_res/SingleFile.png) **SingleFile** ![AGPLv3](_res/AGPLv3.png)<br>
将网页保存到一个 html 文件的扩展<br>
[官网](https://www.getsinglefile.com/) / [Github 源代码 ![Github](_res/Github.png)](https://github.com/gildas-lormeau/SingleFile) / [Firefox ![Firefox.png](_res/Firefox.png)](https://addons.mozilla.org/zh-CN/firefox/addon/single-file/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search)

> 用 Firefox 自带的保存网页功能（也就是「另存网页为...」）保存一个网页，会在本地保存一个文件夹和一个 html 文件，很不简洁 :(

**以下是隐私保护扩展**

![uBlock_Origin](_res/uBlock_Origin.png) **uBlock Origin** ![GPLv3](_res/GPLv3.png)<br>
移除所有广告和网站追踪器<br>
[官网](https://ublockorigin.com/zh) / [Github Releases ![Github](_res/Github.png)](https://github.com/gorhill/uBlock/releases) / [Firefox ![Firefox.png](_res/Firefox.png)](https://addons.mozilla.org/zh-CN/firefox/addon/ublock-origin/)<br>[维基百科 ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/UBlock_Origin) / [粉碎棱镜⚡推荐](https://prism-break.org/zh-CN/projects/ublock-origin/)

![Privacy_Badger](_res/Privacy_Badger.png) **Privacy Badger / 隐私獾** ![GPLv3](_res/GPLv3.png)<br>
阻止不遵守 [DNT ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/%E8%AF%B7%E5%8B%BF%E8%BF%BD%E8%B8%AA) 协议的广告商跟踪行为<br>
[官网](https://privacybadger.org/zh-cn/) / [Github 源代码 ![Github](_res/Github.png)](https://github.com/EFForg/privacybadger) / [Firefox ![Firefox.png](_res/Firefox.png)](https://addons.mozilla.org/zh-CN/firefox/addon/privacy-badger17/)<br>
[维基百科 ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/%E9%9A%90%E7%A7%81%E7%8D%BE) / [粉碎棱镜⚡推荐](https://prism-break.org/zh-CN/projects/privacy-badger/)

![ResizedImage](_res/ResizedImage.png) **Decentraleyes** ![Mozilla](_res/Mozilla.png)<br>
保护用户免遭集中的 [CDN ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/%E5%85%A7%E5%AE%B9%E5%82%B3%E9%81%9E%E7%B6%B2%E8%B7%AF) 的跟踪<br>
[官网](https://decentraleyes.org/) / [Github Releases ![Github](_res/Github.png)](https://github.com/Synzvato/decentraleyes/releases) / [Firefox ![Firefox.png](_res/Firefox.png)](https://addons.mozilla.org/zh-CN/firefox/addon/decentraleyes/)<br>
[维基百科 ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/Decentraleyes) / [粉碎棱镜⚡推荐](https://prism-break.org/zh-CN/projects/decentraleyes/)

> 该扩展于2018年6月8日在 Github 归档

![NoScript](_res/NoScript.png) **NoScript** ![GPLv3](_res/GPLv3.png)<br>
以白名单选择性执行 [JavaScript ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/JavaScript)、[Java ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/Java)、[Flash ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/Adobe_Flash)、[Sliverlight ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/Microsoft_Silverlight) 以及其它插件和脚本内容<br>
[官网](https://noscript.net/) / [Github Releases ![Github](_res/Github.png)](https://github.com/hackademix/noscript/releases) / [Firefox ![Firefox.png](_res/Firefox.png)](https://addons.mozilla.org/zh-CN/firefox/addon/noscript/)<br>
[维基百科 ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/NoScript) / [粉碎棱镜⚡推荐](https://prism-break.org/zh-CN/projects/noscript/)

<br>

### 🔍 搜索引擎

推荐阅读编程随想的《[Startpage——保护隐私的搜索引擎，搜索质量等同 Google ](https://program-think.blogspot.com/2018/11/Private-Search-Engine-Startpage.html)

![DuckDuckGo](_res/DuckDuckGo.png) **DuckDuckGo** <br>
匿名、无记录的 Web 搜索<br>
[URL](https://duckduckgo.com/) / [Github 源代码 ![Github](_res/Github.png)](https://github.com/duckduckgo/duckduckgo)<br>
[维基百科 ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/DuckDuckGo) / [粉碎棱镜⚡推荐](https://prism-break.org/zh-CN/projects/duckduckgo/)

![Startpage](_res/Startpage.png) **Startpage** <br>
保护隐私的搜索引擎，使用 Google 搜索 API<br>
[URL](https://www.startpage.com/)<br>
[维基百科 ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/Startpage) / [粉碎棱镜⚡推荐](https://prism-break.org/zh-CN/subcategories/gnu-linux-web-search)

<details markdown='1'><summary>🔍  浏览器添加搜索引擎</summary>

![Firefox.png](_res/Firefox.png) **Firefox** / ![Librewolf.png](_res/Librewolf.png) **Librewolf** / ![Zen-Browser](_res/Zen-Browser.png) **Zen Browser**<br>
依次打开右上角「≡」→「设置」→左侧「搜索」→快速搜索下的「添加（A）」，在弹窗里填「搜索引擎名称」与「搜索引擎 URL」（URL 后面要添加「/search?q=%s」字符）。

其他浏览器请自行找方法。

</details>

<br>

### 🪜 翻墙工具

推荐阅读[编程随想的 Blog（桌面端）](https://program-think.blogspot.com/p/search.html?m=0)右侧「推荐帖子（翻墙技术）」相关博文，但服务于桌面端，移动端极少。

翻墙很折腾，但不要因此放弃自由的互联网，被墙国局域网**体制化**！（相关博文：[谈谈【体制化】，并推荐《肖申克的救赎》](https://program-think.blogspot.com/2010/11/institutionalize.html)）强烈推荐阅读编程随想的[学习一下德国人民的翻墙精神](https://program-think.blogspot.com/2009/07/break-through-berlin-wall.html)，德国人为争得自由用生命翻柏林墙，我们翻 [GFW ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/%E9%98%B2%E7%81%AB%E9%95%BF%E5%9F%8E) 遇到的困难又如何？

<br>

![Clash_Verge_Rev](_res/Clash_Verge_Rev.png) **Clash Verge Rev**  ![GPLv3](_res/GPLv3.png)<br>桌面端代理工具<br>[Github Releases ![Github](_res/Github.png)](https://github.com/Clash-Verge-rev/clash-verge-rev/releases)

![v2rayN.png](_res/v2rayN.png) **v2rayN** ![GPLv3](_res/GPLv3.png)<br>桌面端代理工具<br>[官网](https://en.v2rayn.org/download/) / [Github Releases ![Github](_res/Github.png)](https://github.com/2dust/v2rayN/releases)<br>[维基百科 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/V2Ray)

🎄 公益免费 v2ray 节点（每日更新）：<br>
[Github - 1 ![Github](_res/Github.png)](https://github.com/aiboboxx/v2rayfree) / [Github - 2 ![Github](_res/Github.png)](https://github.com/Aclashv2rayfree/freevpn)

<details markdown='1'><summary>代理工具防 DNS 泄露设置</summary>

参考：不良林 [进阶•DNS泄漏篇 ![Video_Youtube](_res/Video_Youtube.png)](https://m.youtube.com/watch?v=fqREM6b25SY) / [DNS leak / DNS 泄露 ![Wikipedia](_res/Wikipedia.png)](https://en.m.wikipedia.org/wiki/DNS_leak)

![v2rayN.png](_res/v2rayN.png) **v2rayN**：<br>在下方「路由」选择「绕过大陆」即可。更进一步的话，依次点击上方「设置」→「路由设置」，在「域名解析策略」选择「AsIs」其他配置默认即可。

![Clash_Verge_Rev](_res/Clash_Verge_Rev.png) **Clash Verge Rev**：
<br>Clash系比较麻烦，因为分流规则都写在订阅文件，所以用订阅转换网址转换节点链接。详情了解[视频 ![Video_Youtube](_res/Video_Youtube.png)](https://youtu.be/fqREM6b25SY/?t=0h12m53s)

</details>

![Proton_VPN.png](_res/Proton_VPN.png) **Proton VPN**  ![GPLv3](_res/GPLv3.png)<br>由瑞士公司 Proton Technologies AG 运营的 VPN 服务<br>[官网](https://protonvpn.com/download-windows) / [Github Releases ![Github](_res/Github.png)](https://github.com/ProtonVPN/win-app/releases)<br>[维基百科 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/ProtonVPN)

![迷雾通](_res/迷雾通.png) **迷雾通** ![GPLv3](_res/GPLv3.png)<br>抵御运营商级别审查的 VPN<br>[官网](https://geph.io/zhs) / [Github 源代码 ![Github](_res/Github.png)](https://github.com/geph-official/geph4-client) / [官方免翻墙镜像](https://f001.backblazeb2.com/file/geph4-dl/geph-releases/dl.html)

![WireGuard.png](_res/WireGuard.png) **WireGuard**  ![GPLv3](_res/GPLv3.png)<br>自由开源的加密VPN工具<br>[官网](https://download.wireguard.com/windows-client/)<br>[维基百科 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/WireGuard) / [粉碎棱镜⚡推荐](https://prism-break.org/zh-CN/projects/wireguard/)

> 最好下载 WireGuard MSIs 下的「.msi」文件。因为安装「.exe」文件时要连接 WireGuard 官网，但其官网已被墙。

![FreeBrowser.png](_res/FreeBrowser.png) **FreeBrowser / 自由浏览**<br>基于 ![Chrome](_res/Chrome.png) **Chrome** 定制，专为打破信息封锁的代理浏览器<br>[官网](https://freebrowser.org/)<br>[维基百科 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/%E8%87%AA%E7%94%B1%E6%B5%8F%E8%A7%88)

![自由门](_res/自由门.png) **自由门**<br>打破信息封锁的代理工具<br>[官网](https://github.com/freegate-release/website/archive/fglatest.zip)<br>[维基百科 ![Wikipedia](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/%E8%87%AA%E7%94%B1%E9%97%A8)

</details>

<br>

<details markdown='1'><summary>💸 免费获得代理工具和节点的经验总结</summary>

1. Web 代理：<br>在浏览器搜索「web代理」。但免费的 Web 代理难免会有广告。

2. 免费机场节点：<br>常用的代理工具有 ![v2rayN.png](_res/v2rayN.png) **v2rayN**、![Clash_Verge_Rev](_res/Clash_Verge_Rev.png) **Clash Verge Rev**、![Nekobox](_res/Nekobox.png) **Nekobox** 等。在**浏览器**或 **Youtube** 搜「20XX年X月X日免费机场节点」，下好节点导入代理工具。速度有快有慢。

    > 这个方法有风险，因为机场主能看到使用者的机场账号、使用时间、IP、访问的网站等信息。详见：[不良林 - 实战演示机场搭建运作原理 ![Video_Youtube](_res/Video_Youtube.png)](https://youtu.be/KfOEabr38WU/?t=0h13m57s)
    > 
    > 更糟糕的可能会得到钓鱼节点！详见：[不良林 - 免费节点钓鱼 ![Video_Youtube](_res/Video_Youtube.png)](https://youtu.be/vuF6rDLp3pg)
    > 
    > 若特别在乎隐私就自己搭建节点。

3. ![WireGuard](_res/WireGuard.png) **WireGuard** 隧道：<br>由于优选 IP 后配置的隧道已经不能用了，所以只能用别人配置好的隧道。比如[翻墙公益](https://github.com/w1g2)。速度时快时慢，而且游戏玩不了的。过期了再搞个新的。（建议直接访问不要开代理「[直链](https://45.79.165.151/)」）

4. GreatFire 工具：<br>[GreatFire 官方](https://zh.greatfire.org/)提供的 ![FreeBrowser](_res/FreeBrowser.png) **FreeBrowser**

5. VPN：<br>目前开源免费的 VPN 很少，就只有 ![Proton_VPN](_res/Proton_VPN.png) **Proton VPN**、![迷雾通](_res/迷雾通.png) **迷雾通**还能用。但登录帐号要开代理，而且速度不快，迷雾通的免费账户限速125kb/s。

</details>

<br>

<details markdown='1'><summary>修改 Windows DNS</summary>

详见不良林的[进阶•DNS泄漏篇 ![Video_Youtube](_res/Video_Youtube.png)](https://m.youtube.com/watch?v=fqREM6b25SY)

> 本次以 Windows 10 LTSC 2021 为例

1. 点击状态栏的网络图标，选择「打开 ‘‘网络和Internat’’ 设置」;

2. 在「状态」一项里「高级网络设置」下选择「更改适配器设置」;

3. 右击正在使用的网卡，在弹窗里选择「属性」；

4. 在「此连接使用下列项目」下点击「Internet 协议版本4（TCP/IPV4）」，并点击「属性」；

5. 在弹窗里选择「使用下面的 DNS 服务器地址」，并填写 DNS 服务器地址（「首选...」与「备用...」都填），最后点击「确认」，完成。

海外 DNS 服务器推荐：

| DNS 服务提供商 | 首选地址 | 备用地址 |
| --- | --- | --- |
| Google | 8.8.8.8 | 8.8.4.4 |
| IBM Quad9 | 9.9.9.9 | 149.112.112.112 |
| OpenDNS | 208.67.222.222 | 208.67.220.220 |
| Cloudflare | 1.1.1.1 | 1.0.0.1 |
| AdGuard | 94.140.14.14 | 94.140.15.15 |
| 台湾中华电讯 | 168.95.192.1 | 168.95.192.2 |
| 诺顿（安全） | 199.85.126.10 | 199.85.127.10 |
| ... | ... | ... |

</details>

<br>

***

### 🚩 第三方平替

![FreeTube](_res/FreeTube.png) **FreeTube** ![AGPLv3](_res/AGPLv3.png)<br>
YouTube 桌面播放器，没有广告与追踪<br>
[官网](https://freetubeapp.io/#download) / [Github Releases ![Github](_res/Github.png)](https://github.com/FreeTubeApp/FreeTube/releases)

> 视频加载速度比网页快一点

<br>

***

###  🖇️ 制作启动盘工具

![Rufus.png](_res/Rufus.png) **Rufus**  ![GPLv3](_res/GPLv3.png)<br>
系统盘制作工具<br>
[官网](https://rufus.ie/zh/) / [Github Releases ![Github](_res/Github.png)](https://github.com/pbatard/rufus/releases)<br>
[维基百科 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.wikipedia.org/wiki/Rufus)

> 注：![Rufus.png](_res/Rufus.png) **Rufus** 只能烧录一个系统镜像，且只有 Windows 版。

![Ventoy](_res/Ventoy.png) **Ventoy** ![GPLv3](_res/GPLv3.png)<br>跨平台多系统盘制作工具<br>[官网](https://www.ventoy.net/) / [Github Releases ![Github](_res/Github.png)](https://github.com/ventoy/Ventoy/releases)<br>[维基百科 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/Ventoy)

> 用 ![Ventoy](_res/Ventoy.png) **Ventoy** 制作完系统盘后，就能把多个系统镜像文件复制到U盘里，且跨平台。

![微PE](_res/微PE.png) **微PE工具箱**<br>微PE盘<br>[官网](https://www.wepe.com.cn/download.html)

> 推荐下载 **V2.3 64位** 版

<details markdown='1'><summary>🖇️ 安装微PE工具箱</summary>

> 此方法只适用于我的旧电脑，请勿盲目操作！

![安装微PE工具箱_1](_res/安装微PE工具箱_1.png)

![安装微PE工具箱_2](_res/安装微PE工具箱_2.png)

> 注：我用的主板是 Foxconn G31MXP-K G3，只兼容 FAT32 格式。如果用较新的主板就选 NTFS 或 exFAT 格式。
> 
> 详见：<br>[FAT(File Allocation Table) / 文件分配表 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/%E6%AA%94%E6%A1%88%E9%85%8D%E7%BD%AE%E8%A1%A8)<br>[NTFS(New Technology File System) / 专用文件系统 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/NTFS)

</details>

<br>

### 🖥️ 其他工具

![VirtualBox.png](_res/VirtualBox.png) **VirtualBox**  ![GPLv3](_res/GPLv3.png)<br>
虚拟机工具<br>
[官网](https://www.virtualbox.org/wiki/Downloads)<br>
[维基百科 ![Wikipedia.png](_res/Wikipedia.png)](https://zh.wikipedia.org/wiki/VirtualBox)

![tbtool](_res/tbtool.png) **图吧工具箱**<br>硬件检测工具合集<br>[官网](https://www.tbtool.cn/)

<details markdown='1'><summary>用 DiskGenius 检查硬盘坏道</summary>

> 此方法适用于检测新硬盘或二手盘

1. 完全格式化硬盘

    右击「开始」→ 弹窗里的「磁盘管理(K)」，右击要检测的磁盘，点击弹窗里的「格式化(F)」，在弹窗里，取消勾选「执行快速格式化(P)」,最后点「确定」，等待格式化完成。

    > 完全格式化硬盘的目的：修复逻辑坏道。但物理坏道无法修复。

2. 打开 ![tbtool](_res/tbtool.png) **图吧工具箱** ，点击左侧的「磁盘工具」，双击打开 ![DiskGenius](_res/DiskGenius.png) **DiskGenius**

3. 扫描硬盘坏道

    打开 DiskGenius，在左侧右击对于硬盘，点击「坏道检测与修复(Y)」，在弹窗右下角点击「开始检测」，等待扫盘完成。

</details>

![Scrcpy](_res/Scrcpy.png) **Srcrpy** ![ASF](_res/ASF.png)<br>
跨平台屏幕镜像工具，显示和控制 Android 设备<br>
[官网](https://scrcpy.org/) / [Github Releases ![Github](_res/Github.png)](https://github.com/Genymobile/scrcpy/releases/)<br>
[维基百科  ![Wikipedia.png](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/Scrcpy)

![Quod_Libet](_res/Quod_Libet.png) **Quod Libet** ![GPLv3](_res/GPLv3.png)<br>
跨平台的音频播放器、标签编辑器和库管理器。<br>
[官网](https://quodlibet.readthedocs.io) / [Github Releases ![Github](_res/Github.png)](https://github.com/quodlibet/quodlibet/releases)<br>
[维基百科 ![Wikipedia.png](_res/Wikipedia.png)](https://en.m.wikipedia.org/wiki/Quod_Libet_(software))

<br>

***

### 🛠️ 搞机

![Android](_res/Android.png) **Android SDK**<br>
软件开发工具包，内置 [ADB ![Wikipedia.png](_res/Wikipedia.png)](https://zh.wikipedia.org/zh-cn/Android%E8%B0%83%E8%AF%95%E6%A1%A5) 与 [Fastboot  ![Wikipedia.png](_res/Wikipedia.png)](https://zh.m.wikipedia.org/wiki/Fastboot_(Android)) 等命令行工具<br>
[官网](https://developer.android.com/tools/releases/platform-tools)<br>
[维基百科  ![Wikipedia.png](_res/Wikipedia.png)](https://en.m.wikipedia.org/wiki/Android_SDK)

<details markdown='1'><summary>🛠️ Windows 配置 ADB 当前用户环境变量</summary>

目的是快捷调出 CMD 命令框

1. 按 Win 键 + R 键，在「运行」弹窗输入以下字符并点击「确定」；
    > rundll32 sysdm.cpl,EditEnvironmentVariables

    ![Windows配置ADB环境变量_1.png](_res/Windows配置ADB环境变量_1.png)

<br>

2. 解压 SDK 压缩包，并存放好；
    > 注：用来配置环境变量的 SDK 文件夹不要移动、删除或篡改某一文件，否则会导致环境变量失效，不能快捷调出 CMD 命令框。若出现这些意外重新配置环境变量即可。

<br>

3. 在「XXX 的用户变量」中单击变量「Path」，点击「编辑」；
    ![Windows配置ADB环境变量_2.png](_res/Windows配置ADB环境变量_2.png)

<br>

4. 在弹窗里点击「新建」，输入 SDK 文件的路径，最后点「确定」保持更改；
    ![Windows配置ADB环境变量_3.png](_res/Windows配置ADB环境变量_3.png)

<br>

5. 为验证配置成功，按 Win 键 + R 键，在「运行」弹窗输入「cmd」后回车，在命令框输入指令「adb」并回车，接下来会有以下两个结果：
- 若回复“Android Debug Bridge version （版本号）...”则代表配置成功；
    ![Windows配置ADB环境变量_4.png](_res/Windows配置ADB环境变量_4.png)

- 若回复“‘adb’不是内部或外部命令，也不是可运行的程序或批处理文件”则代表配置失败，需重启电脑或重新配置环境变量。
    ![Windows配置ADB环境变量_5.png](_res/Windows配置ADB环境变量_5.png)

</details>

<br>

***

> 正方形图标大小是**20xp*20xp**，长方形图标高度为**20xp**。
> 
> 遵循「Just do it」原则：点超链接跳转到下载界面

