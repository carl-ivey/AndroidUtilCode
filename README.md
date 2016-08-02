# Android开发人员不得不收集的代码(不断更新)  
为方便查找，已进行大致归类，其目录如下所示：  
> - [尺寸相关](https://github.com/Blankj/AndroidUtilCode/blob/master/about_size.md)→[SizeUtils.java](https://github.com/Blankj/AndroidUtilCode/blob/master/androidframework/src/main/java/com/blankj/androidframework/utils/SizeUtils.java)
>    - dp与px转换 *dp2px*、*px2dp*
>    - sp与px转换 *sp2px*、*px2sp*
>    - 各种单位转换 *applyDimension*
>    - 在onCreate()即可强行获取View的尺寸 *forceGetViewSize*
>    - ListView中提前测量View尺寸(注释萌萌哒) *measureView*
> - [设备相关](https://github.com/Blankj/AndroidUtilCode/blob/master/about_device.md)→[DeviceUtils.java](https://github.com/Blankj/AndroidUtilCode/blob/master/androidframework/src/main/java/com/blankj/androidframework/utils/DeviceUtils.java)
>    - 获取设备MAC地址 *getMacAddress*
>    - 获取设备厂商，如Xiaomi *getManufacturer*
>    - 获取设备型号，如MI2SC *getModel*
>    - 获取设备SD卡是否可用 *isSDCardEnable*
>    - 获取设备SD卡路径 *getSDCardPath*
> - [手机相关](https://github.com/Blankj/AndroidUtilCode/blob/master/about_phone.md)→[PhoneUtils.java](https://github.com/Blankj/AndroidUtilCode/blob/master/androidframework/src/main/java/com/blankj/androidframework/utils/PhoneUtils.java)
>    - 判断设备是否是手机 *isPhone*
>    - 获取手机的IMIE *getDeviceIMEI*
>    - 获取手机状态信息 *getPhoneStatus*
>    - 拨打电话 *callDial*
>    - 发送短信 *sendSms*
>    - 获取手机联系人 *getAllContactInfo*
>    - 打开手机联系人界面点击联系人后便获取该号码(注释萌萌哒) *getContantNum*
>    - 获取手机短信并保存到xml中 *getAllSMS*
> - [网络相关](https://github.com/Blankj/AndroidUtilCode/blob/master/about_network.md)→[NetworkUtils.java](https://github.com/Blankj/AndroidUtilCode/blob/master/androidframework/src/main/java/com/blankj/androidframework/utils/NetworkUtils.java)
>    - 打开网络设置界面 *openWirelessSettings*
>    - 判断是否网络连接 *isConnected*
>    - 判断wifi是否连接状态 *isWifiConnected*
>    - 获取移动网络运营商名称 *getNetworkOperatorName*
>    - 获取移动终端类型 *getPhoneType*
>    - 获取连接的网络类型(2G,3G,4G) *getCurNetworkType*
>    - 获取当前手机的网络类型(WIFI,2G,3G,4G) *getNetWorkStatus*
> - [App相关](https://github.com/Blankj/AndroidUtilCode/blob/master/about_app.md)→[AppUtils.java](https://github.com/Blankj/AndroidUtilCode/blob/master/androidframework/src/main/java/com/blankj/androidframework/utils/AppUtils.java)
>    - 安装指定路径下的Apk *installApk*
>    - 卸载指定包名的App *uninstallApp*
>    - 获取当前App信息 *getAppInfo*
>    - 获取所有已安装App信息 *getAllAppsInfo*
>    - 打开指定包名的App *openAppByPackageName*
>    - 打开指定包名的App应用信息界面 *openAppInfo*
>    - 可用来做App信息分享 *shareAppInfo*
>    - 判断当前App处于前台还是后台 *isApplicationBackground*
> - [屏幕相关](https://github.com/Blankj/AndroidUtilCode/blob/master/about_screen.md)→[ScreenUtils.java](https://github.com/Blankj/AndroidUtilCode/blob/master/androidframework/src/main/java/com/blankj/androidframework/utils/ScreenUtils.java)
>    - 获取手机分辨率 *getDeviceWidth*、*getDeviceHeight*
>    - 设置透明状态栏(api >= 19方可使用) *setTransparentStatusBar*
>    - 隐藏状态栏(注释萌萌哒) *hideStatusBar*
>    - 获取状态栏高度 *getStatusBarHeight*
>    - 获取状态栏高度＋标题栏(ActionBar)高度 *getTopBarHeight*
>    - 设置屏幕为横屏(注释萌萌哒) *setLandscape*
>    - 获取屏幕截图 *snapShotWithStatusBar*、*snapShotWithoutStatusBar*
> - [键盘相关](https://github.com/Blankj/AndroidUtilCode/blob/master/about_keyboard.md)→[KeyboardUtils.java](https://github.com/Blankj/AndroidUtilCode/blob/master/androidframework/src/main/java/com/blankj/androidframework/utils/KeyboardUtils.java)
>    - 避免输入法面板遮挡
>    - 动态隐藏软键盘 *hideSoftInput*
>    - 点击屏幕空白区域隐藏软键盘(注释萌萌哒) *clickBlankArea2HideSoftInput0*
>    - 动态显示软键盘 *showSoftInput*
>    - 切换键盘显示与否状态 *toggleSoftInput*
> - [正则相关](https://github.com/Blankj/AndroidUtilCode/blob/master/about_regular.md)→[RegularUtils.java](https://github.com/Blankj/AndroidUtilCode/blob/master/androidframework/src/main/java/com/blankj/androidframework/utils/RegularUtils.java)
>    - 正则工具类
> - [加解密相关](https://github.com/Blankj/AndroidUtilCode/blob/master/about_encrypt.md)→[EncryptUtils.java](https://github.com/Blankj/AndroidUtilCode/blob/master/androidframework/src/main/java/com/blankj/androidframework/utils/EncryptUtils.java)
>    - MD5加密 *encryptMD5*
>    - SHA加密 *encryptSHA*
> - [未归类](https://github.com/Blankj/AndroidUtilCode/blob/master/unclassified.md)→[UnclassifiedUtils.java](https://github.com/Blankj/AndroidUtilCode/blob/master/androidframework/src/main/java/com/blankj/androidframework/utils/UnclassifiedUtils.java)
>    - 获取服务是否开启 *isRunningService*
> - [更新Log](https://github.com/Blankj/AndroidUtilCode/blob/master/about_log.md)

  
**做这份整理只是想把它作为Android的一本小字典，当遇到一些琐碎问题时，不用再面向百度或者谷歌查询API的使用，费时费力，这里有的话，大家尽管撸走。希望它能逐日壮大起来，期待你的Star和完善，用途的话大家想把它们整理成工具类或者什么的话都可以，之后我也会封装工具类并分享之，但本篇只是提供查阅，毕竟看md比看类文件要爽多了，其中好多代码我也是各种搜刮来的，也要谢谢各位的总结，大部分代码已验证过可行，如有错误，请及时告之，开设QQ群提供讨论，群号：74721490**  
  
# 更新Log
#### 2016/07/31 新增点击屏幕空白区域隐藏软键盘
#### 2016/07/31 新增目录跳转功能（然而简书不支持所以这里没更新）
#### 2016/08/01 新增获取当前App版本Code
#### 2016/08/01 新增目录中显示方法名
#### 2016/08/01 新增获取SD卡路径，手机和设备进行分类，代码bug修改部分，小修排版，正在封装类
#### 2016/08/02 wifi设置界面bug修复，注释排版还在修改，获取mac地址增加判空，新增QQ群：74721490，欢迎加入
#### 2016/08/02 新增隐藏状态栏，注释更加全面，工具类已封装，写的时候真的是一个一个测试过去的，宝宝心里苦

  
##[关于Blankj](http://blankj.com/about)