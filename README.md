# scroll-video
uniapp仿抖音视频滑动效果
# 说明
插件在uni-app编译模式下实现效果。

默认为weex编译模式，在 manifest.json 的源码视图里配置是切换模式， manifest.json -> app-plus -> nvueCompiler 切换编译模式。

swiper在非App端内嵌video性能比较差，不建议导入过多视频。
# 1.0.0更新内容
1.视频滑动效果

2.视频滑动后自动播放和暂停功能

3.点击暂停与播放

4.视频拖动效果

5.解决iostouch无效

6.点赞功能
# 1.1.0更新内容
1.更改uni-app编译模式下使用swiper组件实现。
# 1.2.0更新内容
1.新增css3实现效果

2.css3支持点击播放和暂停功能

3.移除swiper中点击视频播放和暂停事件，尽量减少swiper中的事件 

4.index索引首视频设置为自动播放

5.新增进度条

6.修复h5多个视频播放问题

# 测试
安卓真机调试 小程序模拟器 Chrome ios真机
