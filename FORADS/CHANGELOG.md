## Changelog
> 把下载地址copy到浏览器上下载。
>
> 四位版本号时，前三位为发版版本号，第四位为测试号

#### Version 4.4.1 &2

##### 时间：

2021.08.10

##### 修改内容：

新需求： 

- [x] Mintegral的SKAdNetWork更新
- [x] Adcolony的SKAdNetWork更新
- [x] Mintegral 升级 adatper  V6.9.6.2
- [x] Adcolony升级 adapter V4.7.0.1 
- [x] 更新Adapter命名方式，第三方版本号+SDK版本号命名，如：AdcolongAdapter V4.7.0.1 , 4.7.0是Adcolony版本号，1是SDK版本号

线上bug修复：   

- [x] $\textcolor{red}{修复内推物料清理时长} $

疑似bug尝试修复： 

优化： 

- [x] Mintegral判断缓存，添加id判空

Debug 为YES​​，私有库版本测试 

##### 下载地址：

itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/liushuai-fotoable/SDK_Demo/main/FORADS/manifest_4.4.1.2.plist

#### Version 4.4.1 &1

##### 时间：

2021.08.05

##### 修改内容：

新需求： 

- [x] Mintegral的SKAdNetWork更新
- [x] Adcolony的SKAdNetWork更新
- [x] Mintegral 升级 adatper  V6.9.6.2
- [x] Adcolony升级 adapter V4.7.0.1 
- [x] 更新Adapter命名方式，第三方版本号+SDK版本号命名，如：AdcolongAdapter V4.7.0.1 , 4.7.0是Adcolony版本号，1是SDK版本号

线上bug修复：   

疑似bug尝试修复： 

优化： 

- [x] Mintegral判断缓存，添加id判空

Debug 为YES​​，私有库版本测试 

##### 下载地址：

itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/liushuai-fotoable/SDK_Demo/main/FORADS/manifest_4.4.1.1.plist

#### Version 4.4.0 & 9

##### 时间：

2021.7.22

##### 修改内容：

新需求： 

- [x] 所有渠道的SKAdNetWork更新
- [x] 第三方指定版本，不再允许小范围内版本浮动 
- [x] Facebook 升级 adatper  V6.5.0
- [x] Admob升级 adapter V8.8.0 
- [x] Ironsource升级 adapter V7.1.6.1
- [x] AppLovin升级 adapter   V10.3.2（接口变动）
- [x] Mopub升级 adapter V5.17.0
- [x] Unity升级升级 adapter   V3.7.2
- [x] Chartboost升级 adapter  V8.4.2
- [x] Pangle升级 adapter  V3.7.0.5（接口变动）
- [x] Tapjoy升级 adapter V12.8.1
- [x] Adcolony 升级 adapter   V4.6.1
- [x] mintegral接入（waterfall）adapter  V6.9.5.0  
- [x] mintegral接入 （bidding） adapter  V6.9.5.0 
- [x] 添加是否是测试环境

线上bug修复：   

- [x] Mopub修复delegate回调异常的问题
- [x] 内推和客服存在分类的冲突的问题
- [x] 配置文件标记为False时，集成界面同步显示为未集成

疑似bug尝试修复： 

优化： 

- [x] FTCore修改分类命名发版
- [x] FTLogger修改分类命名发版
- [x] Vungle 指定三方库   6.9.2
- [x] 变现联盟、内推根据infer修复相关问题 
  - [x] 内推修改字典转JSON
  - [x] 内推删除废弃方法
- [x] 变现联盟底层回调方式更改，字典转maptable
- [x] 此版本pod引入 客服、BI、登录、支付SDK

$\textcolor{red}{Debug 为NO } $​​，公有库版本测试 

##### 下载地址：

itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/liushuai-fotoable/SDK_Demo/main/FORADS/manifest_4.4.0.9.plist

#### Version 4.4.0 & 8

##### 时间：

2021.7.22

##### 修改内容：

新需求： 

- [x] 所有渠道的SKAdNetWork更新
- [x] 第三方指定版本，不再允许小范围内版本浮动 
- [x] Facebook 升级 adatper  V6.5.0
- [x] Admob升级 adapter V8.8.0 
- [x] Ironsource升级 adapter V7.1.6.1
- [x] AppLovin升级 adapter   V10.3.2（接口变动）
- [x] Mopub升级 adapter V5.17.0
- [x] Unity升级升级 adapter   V3.7.2
- [x] Chartboost升级 adapter  V8.4.2
- [x] Pangle升级 adapter  V3.7.0.5（接口变动）
- [x] Tapjoy升级 adapter V12.8.1
- [x] Adcolony 升级 adapter   V4.6.1
- [x] mintegral接入（waterfall）adapter  V6.9.5.0  
- [x] mintegral接入 （bidding） adapter  V6.9.5.0 
- [x] 添加是否是测试环境

线上bug修复：   

- [x] Mopub修复delegate回调异常的问题
- [x] 内推和客服存在分类的冲突的问题
- [x] 配置文件标记为False时，集成界面同步显示为未集成

疑似bug尝试修复： 

优化： 

- [x] FTCore修改分类命名发版
- [x] FTLogger修改分类命名发版
- [x] Vungle 指定三方库   6.9.2
- [x] 变现联盟、内推根据infer修复相关问题 
  - [x] 内推修改字典转JSON
  - [x] 内推删除废弃方法
- [x] 变现联盟底层回调方式更改，字典转maptable
- [x] 此版本pod引入 客服、BI、登录、支付SDK

Debug 为YES，$\textcolor{red}{公有库版本测试  } $

##### 下载地址：

itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/liushuai-fotoable/SDK_Demo/main/FORADS/manifest_4.4.0.8.plist

#### Version 4.4.0 & 7

##### 时间：

2021.7.21

##### 修改内容：

新需求： 

- [x] 所有渠道的SKAdNetWork更新
- [x] 第三方指定版本，不再允许小范围内版本浮动 
- [x] Facebook 升级 adatper  V6.5.0
- [x] Admob升级 adapter V8.8.0 $\textcolor{red}{升级8.8.0} $  
- [x] Ironsource升级 adapter V7.1.6.1
- [x] AppLovin升级 adapter   V10.3.2（接口变动）
- [x] Mopub升级 adapter V5.17.0
- [x] Unity升级升级 adapter   V3.7.2
- [x] Chartboost升级 adapter  V8.4.2
- [x] Pangle升级 adapter  V3.7.0.5（接口变动）
- [x] Tapjoy升级 adapter V12.8.1
- [x] Adcolony 升级 adapter   V4.6.1
- [x] mintegral接入（waterfall）adapter  V6.9.5.0  $\textcolor{red}{更改为正式广告ID} $  
- [x] mintegral接入 （bidding） adapter  V6.9.5.0 $\textcolor{red}{更改为正式广告ID} $
- [x] 添加是否是测试环境

线上bug修复：   

- [x] Mopub修复delegate回调异常的问题
- [x] 内推和客服存在分类的冲突的问题
- [x] 配置文件标记为False时，集成界面同步显示为未集成

疑似bug尝试修复： 

优化： 

- [x] FTCore修改分类命名发版
- [x] FTLogger修改分类命名发版
- [x] Vungle 指定三方库   6.9.2
- [x] 变现联盟、内推根据infer修复相关问题 
  - [x] 内推修改字典转JSON
  - [x] 内推删除废弃方法
- [x] 变现联盟底层回调方式更改，字典转maptable
- [x] 此版本pod引入 客服、BI、登录、支付SDK

Debug 为YES，私有库版本测试  

##### 下载地址：

itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/liushuai-fotoable/SDK_Demo/main/FORADS/manifest_4.4.0.7.plist

#### Version 4.4.0 & 3

##### 时间：

2021.7.15

##### 修改内容：

新需求： 

- [x] 所有渠道的SKAdNetWork更新
- [x] 第三方指定版本，不再允许小范围内版本浮动 
- [x] Facebook 升级 adatper  V6.5.0
- [x] Admob升级 adapter V8.6.0
- [x] Ironsource升级 adapter V7.1.6.1
- [x] AppLovin升级 adapter   V10.3.2（接口变动）
- [x] Mopub升级 adapter V5.17.0
- [x] Unity升级升级 adapter   V3.7.2
- [x] Chartboost升级 adapter  V8.4.2
- [x] Pangle升级 adapter  V3.7.0.5（接口变动）
- [x] Tapjoy升级 adapter V12.8.1
- [x] Adcolony 升级 adapter   V4.6.1
- [x] mintegral接入（waterfall）adapter  V6.9.5.0
- [x] mintegral接入 （bidding） adapter  V6.9.5.0
- [x] 添加是否是测试环境

线上bug修复：   

- [x] Mopub修复delegate回调异常的问题
- [x] 内推和客服存在分类的冲突的问题
- [x] 配置文件标记为False时，集成界面同步显示为未集成

疑似bug尝试修复： 

优化： 

- [x] FTCore修改分类命名发版
- [x] FTLogger修改分类命名发版
- [x] Vungle 指定三方库   6.9.2
- [x] 变现联盟、内推根据infer修复相关问题 
  - [x] 内推修改字典转JSON
  - [x] 内推删除废弃方法
- [x] 变现联盟底层回调方式更改，字典转maptable
- [x] 此版本pod引入 客服、BI、登录、支付SDK

Debug 为YES，私有库版本测试  

##### 下载地址：

itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/liushuai-fotoable/SDK_Demo/main/FORADS/manifest_4.4.0.3.plist

#### Version 4.3.9 & 5

##### 时间：

2021.6.10

##### 修改内容：

新需求：

1.  内推添加清理模块
2.  内推新增物料缓存成功及失败、展示失败、缓存清理打点，失败时，通过msg上报原因
3.  内推增加点全屏击区域开关控制，默认YES
4.  变现联盟Vungle降级为6.9.2 & adapter 1.0.8
5.  变现联盟添加有缓存、无缓存、展示失败、低内存 打点上报

线上bug修复：  

1.  变现联盟unity请求日志修正
2.  变现联盟Vungle请求日志修正
3.  内推的close事件从WillClose 切换到didClose

疑似bug尝试修复：

1.  修复内推的LogEvent崩溃问题

优化：

1. 变现联盟md5警告消除
2. 删除废弃代码

Debug 为YES，公有库版本测试 

> 变现联盟的预加载日志，添加顺序，此需求由服务器做，SDK不做了

##### 下载地址：

itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/liushuai-fotoable/SDK_Demo/main/FORADS/manifest_4.3.9.5.plist

#### Version 4.3.9 & 4

##### 时间：

2021.6.9

##### 修改内容：

新需求：

1.  内推添加清理模块
2.  内推新增物料缓存成功及失败、展示失败、缓存清理打点，失败时，通过msg上报原因
3.  内推增加点全屏击区域开关控制，默认YES
4.  变现联盟Vungle降级为6.9.2 & adapter 1.0.8.4
5.  变现联盟添加有缓存、无缓存、展示失败、低内存 打点上报

线上bug修复：  

1.  变现联盟unity请求日志修正
2.  变现联盟Vungle请求日志修正
3.  内推的close事件从WillClose 切换到didClose

疑似bug尝试修复：

1.  修复内推的LogEvent崩溃问题

优化：

1. 变现联盟md5警告消除
2. 删除废弃代码

Debug 为YES，私有库版本测试 

> 变现联盟的预加载日志，添加顺序，此需求由服务器做，SDK不做了

##### 下载地址：

itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/liushuai-fotoable/SDK_Demo/main/FORADS/manifest_4.3.9.4.plist

#### Version 4.3.9 & 3

##### 时间：

2021.6.9

##### 修改内容：

新需求：

1.  内推添加清理模块
2.  内推新增物料缓存成功及失败、展示失败、缓存清理打点，失败时，通过msg上报原因
3.  内推增加点全屏击区域开关控制，默认YES
4.  变现联盟Vungle降级为6.9.2 & adapter 1.0.8.4
5.  变现联盟添加有缓存、无缓存、展示失败、低内存 打点上报

线上bug修复：  

1.  变现联盟unity请求日志修正
2.  变现联盟Vungle请求日志修正
3.  内推的close事件从WillClose 切换到didClose

疑似bug尝试修复：

1.  修复内推的LogEvent崩溃问题

优化：

1. 变现联盟md5警告消除
2. 删除废弃代码

Debug 为YES，私有库版本测试 

> 变现联盟的预加载日志，添加顺序，此需求由服务器做，SDK不做了

##### 下载地址：

itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/liushuai-fotoable/SDK_Demo/main/FORADS/manifest_4.3.9.3.plist

#### Version 4.3.7 & 5

##### 时间：

2021.5.21

##### 修改内容：

新需求：

1. 升级Pangle V3.5.1.2 & adapter 1.0.2 
2. 升级Adcolony V4.6.0 & adapter 1.0.6 
3. 升级变现联盟 4.3.7 
4. 升级内推V2.3.7 
5. Pangle、Vungle、Adcolony SKAdnetwork更新
6. 内推支持bidding
7. 内推支持通过变现联盟修改网络请求链接

线上bug修复：  

1. 修复内推ad_network_enabled判断错误问题
2. 修复内推参数缺少nonce，导致点击崩溃问题
3. 修复内推video，在close按钮延迟过短时，导致的timer内存泄漏的问题
4. 修复内推的关闭时长不对的问题
5. 修复内推的日志上报事件，不支持ASSIC码的问题

疑似bug尝试修复：

1. 变现联盟减少对CTTelephonyNetworkInfo API的访问频率
2. 变现联盟的运营商字段，暂不提供 
3. 内推减少对CTTelephonyNetworkInfo API的访问频率
4. 内推的运营商字段，暂不提供 

Debug 为YES，Release版本测试

> 此版本废弃的需求：
>
> 1. Vungle升级：第三方渠道进行了代码回退，产品不再让接此版本
> 2. Chartboost修证bidding展示数：产品要求服务器做处理，SDK不动
> 3. Pangle CCPA适配：经和第三方沟通，支持的CCPA版本为非公开beta版本，第三方不建议接入，产品让仅作升级，不进行CCPA的适配
> 4. Mopub升级：未告知解决线上问题的版本，等待通知

##### 下载地址：

itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/liushuai-fotoable/SDK_Demo/main/FORADS/manifest_4.3.7.5.plist

#### Version 4.3.7 & 4

##### 时间：

2021.5.20

##### 修改内容：

新需求：

1. 升级Pangle V3.5.1.2 & adapter 1.0.2.1
2. 升级Adcolony V4.6.0 & adapter 1.0.6.5 
3. 升级变现联盟 4.3.7.8
4. 升级内推V2.3.7.7
5. Pangle、Vungle、Adcolony SKAdnetwork更新
6. 内推支持bidding
7. 内推支持通过变现联盟修改网络请求链接

线上bug修复：  

1. 修复内推ad_network_enabled判断错误问题
2. 修复内推参数缺少nonce，导致点击崩溃问题
3. 修复内推video，在close按钮延迟过短时，导致的timer内存泄漏的问题
4. 修复内推的关闭时长不对的问题
5. 修复内推的日志上报事件，不支持ASSIC码的问题

疑似bug尝试修复：

1. 变现联盟减少对CTTelephonyNetworkInfo API的访问频率
2. 变现联盟的运营商字段，暂不提供 
3. 内推减少对CTTelephonyNetworkInfo API的访问频率
4. 内推的运营商字段，暂不提供 

Debug 为YES

> 此版本废弃的需求：
>
> 1. Vungle升级：第三方渠道进行了代码回退，产品不再让接此版本
> 2. Chartboost修证bidding展示数：产品要求服务器做处理，SDK不动
> 3. Pangle CCPA适配：经和第三方沟通，支持的CCPA版本为非公开beta版本，第三方不建议接入，产品让仅作升级，不进行CCPA的适配
> 4. Mopub升级：未告知解决线上问题的版本，等待通知

##### 下载地址：

itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/liushuai-fotoable/SDK_Demo/main/FORADS/manifest_4.3.7.4.plist

#### Version 4.3.7 & 3

##### 时间：

2021.5.20

##### 修改内容：

新需求：

1. 升级Pangle V3.5.1.2 & adapter 1.0.2.1
2. 升级Adcolony V4.6.0 & adapter 1.0.6.5 
3. 升级变现联盟 4.3.7.8
4. 升级内推V2.3.7.7
5. Pangle、Vungle、Adcolony SKAdnetwork更新
6. 内推支持bidding
7. 内推支持通过变现联盟修改网络请求链接

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

itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/liushuai-fotoable/SDK_Demo/main/FORADS/manifest_4.3.7.3.plist

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





