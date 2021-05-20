## Changelog
> 把下载地址copy到浏览器上下载。
>
> 四位版本号时，前三位为发版版本号，第四位为测试号

#### Version 4.3.7 & 2

##### 时间：

2021.5.20

##### 修改内容：

新需求：

1. 升级Pangle V3.5.1.2 & adapter 1.0.2.1
2. 升级Adcolony V4.6.0 & adapter 1.0.6.5 
3. 升级内推V2.3.7.5
4. Pangle、Vungle、Adcolony SKAdnetwork更新
5. 内推支持bidding

线上bug修复：  

1. 修复内推ad_network_enabled判断错误问题
2. 修复内推参数缺少nonce，导致点击崩溃问题
3. 修复内推video，在close按钮延迟过短时，导致的timer内存泄漏的问题
4. 修复内推的关闭时长不对的问题

疑似bug尝试修复：

1. 变现联盟减少对CTTelephonyNetworkInfo API的访问频率
2. 变现联盟的运营商字段，暂不提供 
3. 内推减少对CTTelephonyNetworkInfo API的访问频率
4. 内推的运营商字段，暂不提供 

Debug 为YES、内推只能用develop环境

> 此版本废弃的需求：
>
> 1. Vungle升级：第三方渠道进行了代码回退，产品不再让接此版本
> 2. Chartboost修证bidding展示数：产品要求服务器做处理，SDK不动
> 3. Pangle CCPA适配：经和第三方沟通，支持的CCPA版本为非公开beta版本，第三方不建议接入，产品让仅作升级，不进行CCPA的适配
> 4. Mopub升级：未告知解决线上问题的版本，等待通知

##### 下载地址：

itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/liushuai-fotoable/SDK_Demo/main/FORADS/manifest_4.3.7.2.plist

#### Version 4.3.7 & 1

##### 时间：

2021.5.13

##### 修改内容：

1. 升级Pangle V3.5.1.2 & adapter 1.0.2.1
2. 升级Vungle V6.10.0 & adapter 1.0.8.3 
3. 升级Adcolony V4.6.0 & adapter 1.0.6.5 
4. Pangle、Vungle、Adcolony SKAdnetwork更新
5. 变现联盟减少对CTTelephonyNetworkInfo API的访问频率
6. 变现联盟的运营商字段，暂不提供
7. Debug 为YES

##### 下载地址：

itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/liushuai-fotoable/SDK_Demo/main/FORADS/manifest_4.3.7.1.plist

#### Version 4.3.6 & 4

##### 时间：

2021.5.8

##### 修改内容：

1. 升级Unity V3.7.1 & adapter 1.0.11
2. 升级Admob V8.4.0 & adapter 1.0.12
3. 公有库测试
4. Debug 为NO
5. Admob、Unity SKAdnetwork更新

##### 下载地址：

itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/liushuai-fotoable/SDK_Demo/main/FORADS/manifest_4.3.6.4.plist

#### Version 4.3.6 & 3

##### 时间：

2021.5.7

##### 修改内容：

1. 升级Unity V3.7.1 & adapter 1.0.11
2. 升级Admob V8.4.0 & adapter 1.0.11
3. 公有库测试
4. Debug 为NO
5. Admob、Unity SKAdnetwork更新

##### 下载地址：

itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/liushuai-fotoable/SDK_Demo/main/FORADS/manifest_4.3.6.3.plist

#### Version 4.3.6 & 2

##### 时间：

2021.5.7

##### 修改内容：

1. 升级Unity V3.7.1 & adapter 1.0.11
2. 升级Admob V8.4.0 & adapter 1.0.11
3. 公有库测试

##### 下载地址：

itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/liushuai-fotoable/SDK_Demo/main/FORADS/manifest_4.3.6.2.plist

#### Version 4.3.6 & 1

##### 时间：

2021.5.6

##### 修改内容：

1. 升级Unity V3.7.1
2. 升级Admob V8.4.0
3. 私有库测试

##### 下载地址：

itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/liushuai-fotoable/SDK_Demo/main/FORADS/manifest_4.3.6.1.plist

#### Version 4.3.2 & 0

##### 时间：

2021.4.19

##### 修改内容：

1. 修改升级AppLovin V10.1.1
2. 升级AppLovin、Unity的 SKAdnetwork

##### 下载地址：

itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/liushuai-fotoable/SDK_Demo/main/FORADS/manifest_4.3.2.plist



