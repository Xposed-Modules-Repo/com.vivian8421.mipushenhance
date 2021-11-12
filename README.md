# 小米push增强模块
## [酷安@vivian8421]

> 启用模块 --> 冻结app --> mipush通知 （--> 打开app --> 点击进入通知）

> 众所周知，为了防止app后台通过恶意行为驻留内存，部分用户选择使用冻结类软件停用(pm disable) App，当App处于停用状态时其package或component不可用。然而，在这种情况下，一些必要的通知将会受到影响(Alipay,DingTalk,Bank,Stock,etc...)

#### 本模块为此设计，在App冻结的情况下，实现接收各类app的push，让您在不消耗内存、保障隐私的同时，轻量接收推送消息，让您不再错过动账、交易类消息，福利活动不再后知后觉！

完全兼容冰箱、黑白门等冻结类App！

注意：

#### 不建议精简或者修改版定制系统使用(可能会卡米)。如果您冻结了部分关键系统app或者破解卡米,请谨慎使用(可能会卡米或者第二屏)。
1. 目前仅仅支持adb shell pm disable停用方式的冻结类App，对于挂起方式(变灰)的冻结(scene应用偏见...)，其应用状态可能留有后台，此方式冻结不彻底，不推荐使用，且此状态下push消息已经推送到通知栏，由于某些限制导致通知栏不能正常展示，后期视情况适配。

2. 时间及技术有限，目前只能实现接收消息，暂时不能通过点击通知无法拉起已经冻结的App，需要手动进入App再点击通知查看。

3. 本模块完全免费且开源，一切开发仅供学习参考，请勿用于非法用途。

适配机型/环境:小米MIUI系列机型ROM+Magisk。

测试机型和进度:

```sh
Mi10 Ultra/Pro 开发板每天跟随官方更新 小米服务框架版本如下:
5.3.1 已测试，冻结不自动注册，最新版已修复
5.3.3 已测试，(部分用户未能正常接收push，官方已确认bug，不建议使用)
5.3.6 已测试，(部分用户未能正常接收push，官方已确认bug，不建议使用)
5.3.8 已测试，未发现问题(20211026-now)
5.3.9 已测试，未发现问题(20211111-20211112)
```

## 使用方法
~~1. 确认应用列表中"小米服务框架" 版本为：5.3.1及以上。 （低版本请自行尝试，不保证可以正常使用）~~
1. 目前已经适配低版本(5.0+)小米服务框架，仅非修改/精简/冻结/卸载状态即可。
2. 作用域已经默认勾选：系统框架 、小米服务框架。（com.xiaomi.xmsf）。
3. 修改系统框架需要重启手机，单独修改小米服务框架停止其运行即可。
4. 手机管家App处于正常状态(非冻结/卸载/版本过低)

## Thanks

Thanks [@Soulpursuit](https://github.com/soulpursuit)  for providing the project requirements and completing the testing of each version 

## Maintainers

[@Vivian8421](https://github.com/vivian8421)

[Report Bug](https://github.com/vivian8421/MiPush-Enhance/issues)





 # Xiaomi push enhancement module

> Enable module -- > freeze app -- > mipush notification (- - > Open app -- > Click to enter notification)

>As we all know, in order to prevent the app background from residing in memory through malicious behavior, some users choose to use frozen software to disable the app. When the app is disabled, its package or component is unavailable. However, in this case, some necessary notifications will be affected (Alipay, dingtalk, bank, stock, etc...)

> 

#### This module is designed for this purpose. When the app is frozen, it can receive the push of all kinds of apps, so that you can receive push messages lightly without consuming memory and ensuring privacy, so that you will no longer miss the dynamic account and transaction messages, and welfare activities will no longer be delayed!

> Fully compatible pm disable and other frozen apps!

> Note: time and technology are limited. At present, we can only receive messages. For the time being, we can't click the notification to pull up the frozen app. We need to manually enter the app and click the notification to view it. We welcome all great gods PR and good people to give advice~

> Note: This module is completely free and open source. All development is for learning reference only. Do not use it for illegal purposes.

> Applicable model / environment: Xiaomi MIUI series model ROM + magisk.

#### Note: it is not recommended to use the simplified or modified customized system . If you freeze some key system apps , please use it with caution.

## Method of use

~~1. Confirm that the version of "Xiaomi service framework" in the application list is 5.3.1 and above. (please try the lower version by yourself, and it is not guaranteed that it can be used normally)~~

2. Scope check: system framework and Xiaomi service framework. （com.xiaomi.xmsf）

3. To modify the system framework, you need to restart the mobile phone, modify the Xiaomi service framework separately and stop its operation.

