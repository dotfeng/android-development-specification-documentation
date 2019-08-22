# Android 命名规范


##前言

> 为了增加代码的可阅读性和可维护性，让开发或维护的小伙伴可以赏心悦目的进行代码阅读，因此制定项目代码规范文档。


## 一.类名
- 大写字母开头，按照大驼峰命名方式 UpperCamelCase, 尽量避免缩写。除非该缩写是众所周知的，比如 HTML、URL，如果类名称中包含单词缩写，则单词缩写的每个字母均应大写。


-  根据不同的功能类型附带的后缀比如：MainActivity、HomeFragment、BaseView、ToastUtils 等。

类类型	 | 类名
:-: | :-: Activity	| xxxActivity.javaApplication |	xxxApplication.javaFragment	|xxxFragment.javaService	|xxxService.javaBroadcastReceiver	|xxxBroadcastReceiver.javaContentProvider|	xxxContentProvider.javaAdapter|	xxxAdapter.javaHandler	|xxxHandler.java接口实现类|	xxxImpl.javaPersenter	|xxxPersenter.java公共父类	|BaseActivity.java/BaseFragment.java/BaseAdapter 等Util 类	|Logger.java数据库类	|BaseSQLiteDBHelper.java



## 二. 布局文件名


布局文件类型|布局文件名
:-: | :-: Activity |activity_xxx.xmlfragment	|fragment_xxx.xmlDialog	|dialog_描述.xml列表条目命名|item_模块_描述.xml包含项命名	|include_模块.xml



## 三.控件 ID 

-  下划线命名法，通常开头是控件的缩写，如：

控件	|命名
:-: | :-: Button	|btn_TextView	|tv_ImageView	|iv_ListView	|lv_RecyclerView	|rv_LinearLayout	|llayout_RelativeLayout	|rlayout_



## 四.变量名/常量名


变量类型	|变量名
:-: | :-: 成员变量	|mContext、mFileName(m+大驼峰命名)常量	 |BASE_URL、CONSTANT_KEY_NAME控件名称	|mButtonStart(遵循: m+控件全称+功能描述)


## 五.方法命名


-  采用小驼峰命名规则：首单词首字母小写，其余单词首字母大写，尽量 XX 不要使用下划线：

方法类型	|方法名
:-: | :-: initXX()	|初始化相关方法，使用 init 为前缀标示，如初始化布局 initView()isXX()	|checkXX() 方法返回值为 boolean 类型的请使用 is 或 check 为前缀getXX()	|返回某个值的方法handleXX()	|对数据进行处理showXX()	|弹出提示框和显示某些信息saveXX()	|保存某些数据resetXX()	|重置clear()	|清除removeXX()	|移除



## 六.Drawable 目录下的命名


名称	|功能
:-: | :-: ic_xx	|图片资源selector_xx	|选择效果shape_xx	|视图形状bg_xx	|背面图片default_xx	|默认图片






# 不断更新完善中！！！




















