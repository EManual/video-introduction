## video-introduction

### API

获取视频列表
```shell
GET https://emanual.github.io/video-introduction/video.json 
```

返回
```json
[
 { 
   "title":"How EManual works",   //视频标题
   "description": "简单介绍编程助手是如何工作的", // 视频描述
   "update_at":"Tue Dec 22 23:35:11 CST 2015", //更新时间
   "create_at":"Tue Dec 22 23:35:11 CST 2015", //创建时间
   "duration": "07:57", //视频播放时间
   "preview_img_url":"http://ww2.sinaimg.cn/mw690/6ee3e8b3gw1ez8vof9tpzj210w0mvwia.jpg", //预览图
   "url":"https://emanual.github.io/EManual/video-introduction/How EManual works.mp4" //视频链接
 }

]
```
