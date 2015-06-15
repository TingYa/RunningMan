# RunMan
使用百度地图实现运动轨迹记录等功能<br>
使用百度基础地图SDK和定位SDK<br>
现在能够实现使用GPS定位以及使用手机方向传感器判断前进方向<br>
每隔一秒钟定位一个当前点并在上一个点和当前点之间划折线，记录运动轨迹***但是偏差比较大***

##已知Bug
* Bug 1：~~关闭手机屏幕会销毁监听事件，没有进行绘制轨迹~~*fix done* 

##效果截图
![测试截图](http://7ktpcg.com1.z0.glb.clouddn.com/RunMan测试截图.png)
##2015.6.9

###增加的功能
* 点击开始按钮后跳转到第二个activity并开始绘制路线
* 增加回到定位点
* 增加方向传感器
* 修改资源图片

###Fix Bug
* Bug 1 删去onstop中的停止定位代码即可

###已知Bug
* Bug 2点击暂停以后会继续绘制路径

##2015.6.12
* 修改布局

##2015.6.15
* 增加记录步数，距离，卡路里数据
* 修改支持的最小SDK为 Android 5.0(Lollipop)
![测试截图](http://7ktpcg.com1.z0.glb.clouddn.com/RunningMan_2.png)
* 下一步尝试修改主题，尝试一下**Android Material Design**

###Fix Bug
* Bug 2：已修改监听类中的判断逻辑

###已知Bug
* Bug 3：点击第二次暂停后不会打点