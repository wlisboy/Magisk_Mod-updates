Magisk_Mod合集
===
******
LSPosed
----

>介绍：
Riru / Zygisk 模块试图提供一个 ART 挂钩框架，该框架利用 LSPlant 挂钩框架提供与 OG Xposed 一致的 API。
>
>特性：
Xpose 是一个模块框架，可以在不接触任何 APK 的情况下更改系统和应用程序的行为。这很好，因为这意味着模块可以适用于不同的版本，甚至无需任何更改的 ROM（只要原始代码没有更改太多）。它也很容易撤消。由于所有更改都在内存中完成，您只需停用模块并重新启动即可恢复原始系统。还有许多其他优点，但这里仅介绍一个：多个模块可以对系统或应用程序的同一部分进行更改。对于修改后的 APK，您必须选择一个。无法将它们组合起来，除非作者使用不同的组合构建多个 APK。
>
>支持的版本
Android 8.1 ~ 14

- 更新地址：https://github.com/LSPosed/LSPosed
  
- [分支]更新地址：https://github.com/JingMatrix/LSPosed/actions

LSPatch
---

>介绍：
LSPosed框架的无根实现，通过在目标APK中插入dex等方式集成Xposed API。
>
>支持的版本
Min: Android 9
Max: In theory, same with LSPosed

- 更新地址：https://github.com/LSPosed/LSPatch


Shamiko
---

>介绍：
略

- 更新地址：https://github.com/LSPosed/LSPosed.github.io/releases

@xiaorun_Ruru
---

>介绍：
 软件更名，不与给空空带来困扰
 增加vpn，usb调试,开发者选项

- 更新地址：https://github.com/byxiaorun/Ruru/releases

@Dr-TSNG_Hide-My-Applist
---

>介绍：
隐藏我的应用程序列表

- 更新地址：https://github.com/Dr-TSNG/Hide-My-Applist/releases

@Xposed-Modules-Repo_cn.geektang.privacyspace
---

>介绍：
这是一个Xpose模块。该模块的作用是“隐藏”应用程序，可以实现MIUI的“第二空间”功能。

- 更新地址：https://github.com/Xposed-Modules-Repo/cn.geektang.privacyspace/releases

@Dr-TSNG_ZygiskNext
---

>介绍：
Zygisk 的独立实现，为 KernelSU 提供 Zygisk API 支持并替代 Magisk 的内置 Zygisk。
>
>特性
适用Magisk官方&&KSU

- 更新地址：https://github.com/Dr-TSNG/ZygiskNext/releases

@oxy2ray_safetynet-fix
---

>介绍：
Magisk 模块用于解决 Google 的 SafetyNet 和 Play Integrity 认证。

**注意！TEE损坏不可使用**

- 更新地址：http://github.com/oxy2ray/safetynet-fix/releases

@chiteroman_PlayIntegrityFix
---

>介绍：
该模块尝试修复 Play Integrity 判决，以便在引导加载程序解锁的设备上获得经过认证的设备。

**注意！TEE损坏可用**

- 更新地址：https://github.com/chiteroman/PlayIntegrityFix/releases


Android starts Mod
===
******

@ReChronoRain_Cemiuiler_old
---

**Make MIUI Great Again!**

>支持的版本：
Android 11 ~ 13 的 MIUI 12.5 ~ 14
不支持 修改较多的第三方 MIUI Rom、修改较多的系统软件，以及部分国外 MIUI Rom，目前 Cemiuiler 是基于 Android 13 的 MIUI 14 的手机端设备进行适配，覆盖不是很完整，需要不断测试和改进。

- 下载地址：https://github.com/ReChronoRain/Cemiuiler/releases

@ReChronoRain_HyperCeiler_New
---

**Make HyperOS Great Again!**

>支持的版本：
Android 11 ~ 14 的 MIUI 12.5 ~ 14/Xiaomi HyperOS1.0
不支持 修改较多的第三方 MIUI/Xiaomi HyperOS Rom、修改较多的系统软件，以及部分国外 MIUI/Xiaomi HyperOS Rom；目前 HyperCeiler 是基于 Android 14 的 Xiaomi HyperOS1.0 的手机端设备进行适配，覆盖不是很完整，需要不断测试和改进。

- 更新地址：https://github.com/ReChronoRain/HyperCeiler


@LuckyPray_XAutoDaily
---

>介绍：
XAutoDaily 是一个兼容QQ大部分版本(包括新版TIM)的开源签到 Xposed 模块

- 更新地址：https://github.com/LuckyPray/XAutoDaily

@cinit_QAuxiliary
---

>介绍：
QAuxiliary 是一个基于 QNotified 的开源 Xposed 模块

- 更新地址：https://github.com/cinit/QAuxiliary

@KimmyXYC_BiliRoaming
---

>介绍：
[Chinese]解除B站客户端番剧区域限制的Xposed模块，并且提供其他小功能
[English]An Xposed module that unblocks bangumi area limit of BILIBILI, and miscellaneous features

- 更新地址：https://github.com/KimmyXYC/BiliRoaming

@rong862_bear
---
>解锁逗音某隐藏特性

- 更新地址：https://github.com/rong862/bear

@GangJust_FreedomPlus
---
>依赖于抖音运行的开源Xposed模块，Lsposed正常使用，其他框架自测

- 更新地址：https://github.com/GangJust/FreedomPlus

@gkd-kit_gkd
---

>介绍：
基于 无障碍 + 高级选择器 + 订阅规则 的自定义屏幕点击 APP
>
>功能：
基于 **高级选择器 + 订阅规则 + 快照审查** 
它可以实现点击跳过任意开屏广告/点击关闭应用内部任意弹窗广告, 如关闭百度贴吧帖子广告卡片/知乎回答底部推荐广告卡片；一些快捷操作, 如微信电脑登录自动同意/微信扫描登录自动同意/微信自动领取红包

- 更新地址：https://github.com/gkd-kit/gkd/releases

第三方订阅规则汇总 By @adproqwq
---
- 更新地址：https://github.com/Adpro-Team/GKD_THS_List

@fankes_MIUINativeNotifyIcon
---

>介绍：
修复被 MIUI 开发组丢弃的原生通知图标，支持 MIUI 11~14 以及 HyperOS 1.0
>
>适配说明:
此模块仅支持 LSPosed (作用域“系统界面”)、EdXposed(随时停止支持)、不支持太极、无极
请确保你使用的是 MIUI 官方版本，任何第三方官改包发生的问题，开发者没有义务去解决和修复，请自求多福
目前最低支持基于 Android 9 版本的 MIUI 11 或 MIUI 12、12.5 (最低建议)
建议最低从 MIUI 12.5 2021-5-18 开发版以后开始使用模块，之前的版本可能或多或少存在 MIUI 自身 BUG 不生效、图标黑白块的问题
请始终保持最新版本的 LSPosed，旧版本可能会出现 Hook 不生效的问题，若最新版本依然不生效请在作用域中长按“系统界面” (“系统 UI”) 选择重新优化

- 更新地址：https://github.com/fankes/MIUINativeNotifyIcon/releases

@Block-Network_StatusBarLyric
---

>介绍：
状态栏歌词适配

-  更新地址：https://github.com/Block-Network/StatusBarLyric/releases

@sothx_mipad-magic-window
---

>介绍：
Xiaomipad平行窗口适配、完美横屏应用计划

[HyperOS For Pad/Fold 完美横屏应用计划 - MIUI MagicWindow+](https://hyper-magic-window.sothx.com/)

- 更新地址：https://github.com/sothx/mipad-magic-window

