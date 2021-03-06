# 主要功能

- 几行代码轻松实现底部导航栏（Tab文字图片高度随意更改）；
- 中间可添加加号按钮，也可添加文字；（足够的属性满足你需要实现的加号样式）
- 如果还不能满足、中间可添加自定义View；
- Tab中随意添加小红点提示、数字消息提示；
- 点击按钮可跳转界面、也可作为Tab切换Fragment；
- 更多使用参考简书；



简书地址:[https://www.jianshu.com/p/ce8e09cda486](https://www.jianshu.com/p/ce8e09cda486 "悬停显示")


# 效果图

![image](https://github.com/forvv231/EasyNavigition/blob/master/screenshot/pre.gif)



![image](https://github.com/forvv231/EasyNavigition/blob/master/screenshot/pre5.jpg)
![image](https://github.com/forvv231/EasyNavigition/blob/master/screenshot/pre3.jpg)
![image](https://github.com/forvv231/EasyNavigition/blob/master/screenshot/pre4.jpg)


# 实现
- 依赖

Step 1. Add it in your root build.gradle at the end of repositories:
```
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
Step 2. Add the dependency
```
	 implementation 'com.github.forvv231:EasyNavigition:1.0.0'
```



---
# 更新（1.0.0）

1、中间加号下可添加文字；

2、中间加号位置可添加自定义View;

3、可设置点击加号后同其他Tab一样切换Fragment；




- **移除addIcon属性、添加中间的图片文字同Tab一样**；
- **移除onAddClickListener、监听事件同Tab、实现onTabClickListener**；
------------
- **新增addAlignBottom属性（加号是否同Tab文字底部对齐  RULE_BOTTOM时有效）**
- **新增addTextTopMargin属性（加号文字距离加号图片的距离）**
- **新增addTextSize属性（加号文字大小）**
- **新增addNormalTextColor属性（加号文字未选中时字体颜色）**
- **新增addSelectTextColor属性（加号文字选中时字体颜色）**
------------
- **更改addIconBottom方法名为addLayoutBottom**；
- **更改addIconRule方法名为addLayoutRule**；



---
# Demo
github：[https://github.com/forvv231/EasyNavigition](https://github.com/forvv231/EasyNavigition)

apk：[ https://fir.im/7r4d]( https://fir.im/7r4d)

![image.png](https://upload-images.jianshu.io/upload_images/5739496-ee76fbfee10046d1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

