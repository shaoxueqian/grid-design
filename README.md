栅格系统
=================

栅格化设计 是把网页分格成相同宽度的区域，列出很多排列组合可能性，在不同设备屏幕上可以很容易达到完整展现的目的。
下面是一个12列栅格布局，页面整体很有规则性，内容按照栅格排列。
![ABC](https://raw.githubusercontent.com/ColdXu/grid-design/master/img/11.gif) 


约定
=================

通常我们会把网页分成12等分，会有4种适用于不同尺寸设备屏幕的方案，设计师需要遵循以下网页宽度使用栅格系统设计。
![ABC](https://raw.githubusercontent.com/ColdXu/grid-design/master/img/icon.gif) 

* 超小屏幕 手机 = 750px [(参考retina屏解决方案)](#jump)
* 小屏幕 平板 = 720px
* 中等屏幕 桌面显示器 = 940px
* 大屏幕 大桌面显示器 = 1140px

[PSD模板文件下载](https://github.com/ColdXu/grid-design/raw/master/%E6%A0%85%E6%A0%BC%E6%A8%A1%E6%9D%BF.rar)</br>
<code>建议使用最新版[Photoshop CC 2015](http://www.52pojie.cn/forum.php?mod=viewthread&tid=376249&from=album)，因为支持画板功能。</code>

实例
=================

下面的页面使用的是我们事先约定好的12列栅格系统的设计。
<code>grid = 栅格数</code>
</br>
[整体对比图](https://raw.githubusercontent.com/ColdXu/grid-design/master/img/img1.gif)
&nbsp;&nbsp;｜&nbsp;&nbsp;
[栅格线对比图](https://raw.githubusercontent.com/ColdXu/grid-design/master/img/img2.gif)
</br>

* 中等屏幕 桌面显示器940px尺寸
> LOGO grid=5，导航栏grid＝7，导航栏宽度相对增加。

* 小屏幕 平板720px尺寸
> LOGO grid=9，导航栏grid＝3，使头部布局合理；主体文字grid=12,两列为一列。

* 超小屏幕 手机750px尺寸(页面显示为375px，750px是为了适应return屏幕)
> LOGO grid=4，导航栏grid=8，导航栏文字过多，替换成了按钮。

例子中利用栅格数量的变化，使得布局发生改变，达到适应屏幕布局的目的<code>一行中总栅格要等于12，不能多也不可少。</code>
</br>
设计师一定确保内容不得超出栅格线以外，确定内容块所暂用栅格数，这样前端有依据在不同尺寸下用控制栅格数，达到自适应的目的。

适应retina屏幕解决方案
=================
<div id="jump"></div>

手机端设计稿基准尺寸为375px，普通屏显示正常，但在retina屏幕下会出现图片模糊问题。
</br>
对于retina屏幕，为了达到高清效果，视觉稿的画布大小会是基准的2倍，也就是说像素点个数是原来的4倍（对iphone6而言：原先的375×667，就会变成750×1334）所以手机端设计稿尺寸是<code>750px</code>[参考移动端高清、多屏适配方案](http://div.io/topic/1092?page=1#4713)。

---------------------------------------

#### 参考
[参考移动端高清、多屏适配方案](http://div.io/topic/1092?page=1#4713)</br>
[栅格系统设计](http://ued.taobao.org/blog/2008/09/grid_systems/)</br>
[栅格设计页面展示](http://mediaqueri.es/)

#### 下载 
[PSD模板文件下载](https://github.com/ColdXu/grid-design/raw/master/%E6%A0%85%E6%A0%BC%E6%A8%A1%E6%9D%BF.rar)</br>
[Photoshop CC 2015下载](http://www.52pojie.cn/forum.php?mod=viewthread&tid=376249&from=album)