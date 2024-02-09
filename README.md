# yunluo-complements / Redmi Pad 反阉割指南
## For English Readers
This tutorial is designed for the China Mainland version of Redmi Pad(yunluo), which means the oprations below may not work on other version of Redmi Pad. Also, I(hrsthrt74) doesn't have much time to write the English version of this tutorial. If you have written one, you can give a PR. Sorry for the inconvenience :(.
## 前言
　　本文中，绝大多数操作都需要 Root 权限，请在进行操作前⚠️备份重要数据⚠️，并安装救砖模块！本文/本人不对可能造成的数据丢失/损坏负责，如您认为某操作是危险的，那么请不要那么做。
  
　　关于如何获取 Root 权限此处不再赘述，请自行查找相关教程。

　　本文一些方法并非我（hrsthrt74）原创，如某个方法对您有帮助，请感谢教程的原作者/发现者。（*下文中标注的可能并非原作者/发现者）

　　本文中提到的部分操作仅在搭载 HyperOS 中国大陆版的，安装 Magisk 的，安装 LSPosed 的 Redmi Pad 中实验可行，可能不适用于其他软件/硬件版本，也可能适用于其他机型。

　　本文**不是**如何增强/优化某系统功能的教程，如“如何关闭状态栏上的三点”等问题不在本文范围内，请自行搜索教程。

　　本文为**不完全**的指南，可能有一些地方无法反阉割，或还没有发现反阉割的方法。 
  
## 基础模糊
### ⚠️Root　⚠️Magisk
　　用于补全「通知中心模糊」「控制中心模糊」「电源菜单模糊」。

　　教程（via [hrsthrt74](https://github.com/hrsthrt74)）[>>>](https://www.coolapk.com/feed/43847865)

## 大文件夹
### ⚠️Root　⚠️Magisk
　　用于补全桌面「大文件夹」。（Pad 端只有 2×2 的大文件夹）。
  
　　教程（via [hrsthrt74](https://github.com/hrsthrt74)）[>>>](https://www.coolapk.com/feed/43847865) 
  
　　也有理论可行的无 Root 方法，但未经验证。在其他支持大文件夹的平板上，在桌面上放置大文件夹，然后使用系统备份备份桌面数据，再恢复到目标设备上。

## 桌面小组件
### ⚠️Root　⚠️Magisk
　　用于补全桌面的新版「小组件」。
  
　　先进行[此操作](https://www.coolapk.com/feed/43847865)，再下载安装 Pad 版「智能助理」应用，最后将其固化（转系统应用）即可。（可在 AppShare 等平台找到「智能助理」应用。）

## 完整动画
### ⚠️Root（⚠️核心破解）（⚠️Xposed）
　　用于恢复完整桌面动画。
  
　　可以选择使用[「Hyperceiler」](https://github.com/ReChronoRain/HyperCeiler)等 Xposed 模块对桌面进行修改，也可以使用 @绵狗 大佬的 Pad 版修改版桌面。

## 工作台模式
### 可选：Root
　　用于强制开启工作台模式。但可能会有 Bug，如无法默认以小窗打开应用。
  
　　教程（via [hrsthrt74](https://github.com/hrsthrt74)）[>>>](https://www.coolapk.com/feed/53173603)

## 主题
### 此处介绍的方法需要使用搭载 MIUI / HyperOS 的手机来获取主题地址。
　　教程（via D哇咔咔咔（酷安））[>>>](https://www.coolapk.com/feed/39924007)

## 高级材质
### ⚠️Root　⚠️Magisk
　　用于恢复高级材质。
  
　　教程（via [hrsthrt74](https://github.com/hrsthrt74)）[>>>](https://www.coolapk.com/feed/52771506)

## 平滑圆角
### ⚠️Root　⚠️Magisk
　　用于恢复平滑圆角。
  
　　教程（via [hrsthrt74](https://github.com/hrsthrt74)）[>>>](https://www.coolapk.com/feed/52771506)

## 音量条模糊
### ⚠️Root　⚠️Magisk　⚠️Xposed
　　需要至少先开启「基础模糊」。用于恢复音量条处的模糊。
  
　　需要使用[「Hyperceiler」](https://github.com/ReChronoRain/HyperCeiler)或类似的 Xposed 模块。在其中的选项里搜索「音量条模糊」，开启即可。

## 临时旋转按钮
　　恢复可能不会显示的「旋转建议按钮」（方向锁定时转屏，显示在左下角的临时旋转按钮）。
  
　　教程（via [Amktiao](https://github.com/Amktiao)）[>>>](https://www.coolapk.com/feed/39511934)

## 三倍速进游戏
　　恢复 HyperOS 原本支持的倍速进入游戏的功能。（部分游戏可能不支持）如使用 ADB / Shizuku 来开启的话，重启后可能会失效，需要重新开启。
  
　　教程（via 穿白衬衫的少年（酷安））[>>>](https://www.coolapk.com/feed/52594458)

## 应用隐藏
　　用于恢复在低运存版本上被阉割的「应用隐藏」。
  
　　使用「创建快捷方式」应用，在勾选系统应用和活动列表后，搜索「隐藏」，然后打开平板管家，再打开其中的「应用隐藏」活动即可。

## 谷歌服务（GMS）
### ⚠️Root　⚠️Magisk
　　根据系统版本的不同，安装对应版本的修改版 LiteGapps 模块。
  
　　MIUI14（Android 13，via FQEGG（酷安））[>>>](https://www.coolapk.com/feed/45658145)
  
　　HyperOS（Android 14，via [随意之光](https://github.com/Suiyi-Light)）[>>>](https://github.com/Suiyi-Light/LiteGapps-Android-14-HyperOS-Version/releases/tag/v3.0.0.1)

## GPS
### 需要一台支持 GPS 和蓝牙的手机。
　　教程（via 漏电耗子小皮卡（酷安））[>>>](https://www.coolapk.com/feed/48530453)

## 实时字幕
### ⚠️Root　⚠️Magisk　⚠️Xposed
　　仅适用于网络版的实时字幕，不适用于端侧实时字幕。
  
　　开启「[MIUI QOL](https://github.com/chsbuffer/MIUIQOL)」模块中的「解锁实时字幕」即可。
