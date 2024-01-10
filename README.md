Magisk_Mod合集
===
******
LSPosed
----

>介绍：
Riru / Zygisk 模块试图提供一个 ART 挂钩框架，该框架利用 LSPlant 挂钩框架提供与 OG Xposed 一致的 API。

>>特性：
Xpose 是一个模块框架，可以在不接触任何 APK 的情况下更改系统和应用程序的行为。这很好，因为这意味着模块可以适用于不同的版本，甚至无需任何更改的 ROM（只要原始代码没有更改太多）。它也很容易撤消。由于所有更改都在内存中完成，您只需停用模块并重新启动即可恢复原始系统。还有许多其他优点，但这里仅介绍一个：多个模块可以对系统或应用程序的同一部分进行更改。对于修改后的 APK，您必须选择一个。无法将它们组合起来，除非作者使用不同的组合构建多个 APK。

>支持的版本
Android 8.1 ~ 14

- 更新地址：https://github.com/LSPosed/LSPosed

LSPatch
---

>介绍：
LSPosed框架的无根实现，通过在目标APK中插入dex等方式集成Xposed API。

>支持的版本
Min: Android 9
Max: In theory, same with LSPosed

- 更新地址：https://github.com/LSPosed/LSPatch


Shamiko
---

>介绍：
略

-更新地址：https://github.com/LSPosed/LSPosed.github.io/releases

@xiaorun_Ruru
---

>介绍：
 软件更名，不与给空空带来困扰
 增加vpn，usb调试,开发者选项

-更新地址：https://github.com/byxiaorun/Ruru/releases

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

>>特性
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
@LuckyPray_XAutoDaily
---

>介绍：
XAutoDaily 是一个兼容QQ大部分版本(包括新版TIM)的开源签到 Xposed 模块

-更新地址：https://github.com/LuckyPray/XAutoDaily

@cinit_QAuxiliary
---

>介绍：
QAuxiliary 是一个基于 QNotified 的开源 Xposed 模块

-更新地址：https://github.com/cinit/QAuxiliary

@KimmyXYC_BiliRoaming
---

>介绍：
[Chinese]解除B站客户端番剧区域限制的Xposed模块，并且提供其他小功能
[English]An Xposed module that unblocks bangumi area limit of BILIBILI, and miscellaneous features

- 更新地址：https://github.com/KimmyXYC/BiliRoaming

@rong862_bear
---

>功能：
解锁逗音某隐藏特性

- 更新地址：https://github.com/rong862/bear

@gkd-kit_gkd
---

>介绍：
基于 无障碍 + 高级选择器 + 订阅规则 的自定义屏幕点击 APP

>>功能：
基于 **高级选择器 + 订阅规则 + 快照审查** 
它可以实现点击跳过任意开屏广告/点击关闭应用内部任意弹窗广告, 如关闭百度贴吧帖子广告卡片/知乎回答底部推荐广告卡片；一些快捷操作, 如微信电脑登录自动同意/微信扫描登录自动同意/微信自动领取红包
