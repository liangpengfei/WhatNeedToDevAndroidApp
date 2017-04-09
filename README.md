开发一个Android App需要什么
===================

* [开发一个Android App需要什么](#开发一个android-app需要什么)
     * [简介](#简介)
     * [标准](#标准)
     * [说明](#说明)
     * [交流](#交流)
     * [UI控件类开源库](#ui控件类开源库)
     * [工具类开源库](#工具类开源库)
     * [平台服务](#平台服务)
     * [开发小技巧](#开发小技巧)

### 简介
本库总结了一个能够进行快速开发一个Android App所需的开源库、开发技巧、开发工具等。主要是为了做索引，方便开发新应用的时候快速进入状态。

###	标准
- 有益：确实能够解决文件，提高开发效率。
- 有用：常用的一些在线工具或者技巧。

### 说明
- 非商业，不推广，纯收录，不排名。
- 来源网站不能违反相关的法律法规，广告尽可能少，访问速度最好要快。
- 请多多使用Ctrl+F。
- 如果出现网页失效，请提交issues。

### 交流
欢迎大家将珍藏已久的好网站、好工具、好方法共享出来，您可以：

* 提交 [Issues](https://github.com/liangpengfei/WhatNeedToDevAndroidApp/issues/new)
* 发起 [Pull Request](https://github.com/liangpengfei/WhatNeedToDevAndroidApp/compare)

贡献者名单: https://github.com/liangpengfei/WhatNeedToDevAndroidApp/graphs/contributors

### UI控件类开源库

* [XRecyclerView](https://github.com/jianghejie/XRecyclerView) 
	* 支持**pullRefresh**和**loadMore**，功能简单但是很实用。
	* 方便对**header**进行自定义。
* [PhotoView](https://github.com/chrisbanes/PhotoView)
	* 可以直接从Play Store中下载[Sample.apk](https://play.google.com/store/apps/details?id=uk.co.senab.photoview.sample)，方便自己有直观的感受再去找相应部分的代码(Attention:现在Google Play中的应用不是最新版本，所以想体验最新版本的，要直接去编译Github上的代码或者从我编好的[百度云盘](https://pan.baidu.com/s/1eSiQCIu)中下载)
	* 和**ViewPager**合作良好
	* 支持**zooming**、 **multi-touch**  、 **double-tap**，基本上功能够用
	* 支持用户点击图片通知

* [AwesomeImagePicker](https://github.com/myinnos/AwesomeImagePicker)
	* 简单轻量，可以同时选多张图片。仅仅选择相册图片的时候使用这个还不错。
	* 而且自己重新修改源码满足自己的项目需求也比较简单。
	* 缺点就是没有处理从相机获取图片的逻辑

* [TakePhoto](https://github.com/crazycodeboy/TakePhoto)
	* 功能比较全，稍微大一点。。定制化程度也算比较高了。
	- 支持通过相机拍照获取图片
	- 支持从相册选择图片
	- 支持从文件选择图片  
	- 支持批量图片选取
	- 支持图片压缩以及批量图片压缩
	- 支持图片裁切以及批量图片裁切
	- 支持照片旋转角度自动纠正
	- 支持自动权限管理(无需关心SD卡及摄像头权限等问题)
	- 支持对裁剪及压缩参数个性化配置  
	- 提供自带裁剪工具(可选)  
	- 支持智能选取及裁剪异常处理
	- 支持因拍照Activity被回收后的自动恢复   
	- 支持Android7.0
	- +支持多种压缩工具
	- +支持多种图片选择工具
	
* [materialdatetimepicker](https://github.com/wdullaer/MaterialDateTimePicker)
	* 使用简单，风格可定制。
	* 很轻量，如果仅仅是想用一个Date 和 Time选择器，非常推荐这个。

* [MaterialDialog](https://github.com/afollestad/material-dialogs)
	* 直接看[Sample.apk](https://github.com/afollestad/material-dialogs/blob/master/sample/sample.apk)，方便定位代码。
	* Dialog的使用方式比较全，多种风格，基本上能满足需求，一直都在用。

### 工具类开源库
* [PermissionGen](https://github.com/lovedise/PermissionGen)
	* 方便处理Android M之后的动态权限的问题，使用很方便。
	* 再也不用自己去判断版本那些琐碎的操作了。

* [butterknife](https://github.com/JakeWharton/butterknife)
	* 快速注入视图，再也不用findViewById了。非常推荐
* [Realm](https://realm.io/cn/)
	* 小的项目可以考虑。
	* 文档比较全，使用起来很顺手。

### 平台服务
* [LenaCloud](http://leancloud.cn)
	* API开发文档做的很人性化，使用起来也比较方便。
	* 相比于其他的几家，比较推荐

* [班邦加固](https://www.bangcle.com)
	* 一直再用这个，也没有用过其他的，因为平时都是小型的项目，加密防护的需求不是很大。

* [IconFont](http://iconfont.cn)
	* 图标比较全，也开放下载，自己写小项目的时候在上面找图标。

* [JPG2PNG](http://jpg2png.com)
	* 在线转换JPG到PNG。

### 开发小技巧
* 使用最新Android Studio的Vector Asset
	* 支持从SVG图标（图标可以从[IconFont](http://iconfont.cn)下载）转换成xml的**VectorDrawable**格式的文件

* 尽可能的使用Android的模板，可以减少很多工作量
	* 例如使用BasicActivity、LoginActivity等，用习惯了很好用。
