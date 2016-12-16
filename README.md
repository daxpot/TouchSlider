# TouchSlider
图片触摸滑动


原生js写的触摸滑动图片

之前用js写的触摸滑动图片在安卓上面会出现掉帧的情况，表现的比原生app卡。

经过研究发现，在触摸的时候修改transform加上  translateZ(0px)后掉帧的情况则不见了。

经Google发现原来是因为加上类似translateZ(0px),有助于开启硬件加速。


具体效果参见
[zengkv.com/TouchSlider/](http://zengkv.com/TouchSlider/)


slider.html也是用来循环播放图片的，其增加了自定义每一个页面，以及每个页面多图播放
具体效果参见
[zengkv.com/TouchSlider/slider.html](http://zengkv.com/TouchSlider/slider.html)