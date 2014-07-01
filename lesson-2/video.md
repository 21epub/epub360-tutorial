# 使用Video & Link

在多媒体交互内容中，视频非常常用。

在Epub360中，可使用Video对象来控制播放视频。另外，本节还将引入介绍Link对象。

本节将使用 **第二课/Video** 文件夹中的视频及图片文件，制作可以点击播放视频的交互操作效果。

<video width="90%" controls><source src="http://qn.media.epub360.com/materials/video/13413f95e45c668d315591a5abaa5039.mp4?avthumb/ipad_low" type="video/mp4"></video>

视频总长3m58s，讲解了基本的操作步骤：

1. 添加Video对象
2. 上传视频文件、并插入Video中 @ 7s
3. 设置Video自动播放 @ 1m06s
4. 添加背景图 @ 1m22s
5. 给视频添加播放动画 @ 2m14s
6. 添加Link，以支持点击播放 @ 2m45s
  - Link点击触发播放
  - Video初始设置为隐藏
  - Video设置不自动播放

按照本视频里操作，将完成交互效果：**在背景底图中心区域点击后，触发播放视频**。

