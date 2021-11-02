# 小米push增强模块


> 启用模块 --> 冻结app --> mipush通知 （--> 打开app --> 点击进入通知）

> 众所周知，为了防止app后台通过恶意行为驻留内存，部分用户选择使用冻结类软件停用app，当app处于停用状态时其package或component不可用。然而，在这种情况下，一些必要的通知将会受到影响(Alipay,DingTalk,Bank,Stock,etc...)
> 


#### 本模块为此设计，在App冻结的情况下，实现接收各类app的push，让您在不消耗内存、保障隐私的同时，轻量接收推送消息，让您不再错过的动账、交易类消息，福利活动不再后知后觉！

> 完全兼容冰箱、黑白门等冻结类app！

> 注：时间及技术有限，目前只能实现接收消息，暂时不能通过点击通知无法拉起已经冻结的App，需要手动进入app再点击通知查看，欢迎各路大神pr良人献策~

> 注:本模块完全免费且开源，一切开发仅供学习参考，请勿用于非法用途。

> 适配机型/环境:小米MIUI系列机型ROM+Magisk,如果您使用了精简或者修改版定制系统，建议您谨慎使用。
## 使用方法
1. 确认应用列表中"小米服务框架" 版本为：5.3.1及以上。 （低版本请自行尝试，不保证可以正常使用）
2. 作用域勾选：系统框架 、小米服务框架。（com.xiaomi.xmsf）
3. 修改系统框架需要重启手机，单独修改小米服务框架停止其运行即可。

## Thanks

Thanks [@Soulpursuit](https://github.com/soulpursuit)  for providing the project requirements and completing the testing of each version 

## Maintainers

[@Vivian8421](https://github.com/vivian8421)

[Report Bug](https://github.com/vivian8421/MiPush-Enhance/issues)
## [酷安@vivian8421]
