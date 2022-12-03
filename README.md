# 纱依按钮

[![](http://i1.hdslb.com/bfs/archive/4633093bf4f942d1bc3ce80302eacac011b7898d.jpg@400h.webp)](https://live.bilibili.com/26168663)

### LICENSE
- 此项目使用了**blacktunes**(https://github.com/blacktunes) 编写的**hiiro-button**(https://github.com/blacktunes/hiiro-button) 为模板

### 项目链接

 - http://shayi.love/
 
 ### 相关链接：

- [纱依 的 Bilibili 主页](https://space.bilibili.com/3461576189282324)
- [纱之匣 的 Bilibili 主页](https://space.bilibili.com/3493088020400738)

### 参与完善本项目

- 您可以在[Issues](https://github.com/jiajiu123/shayi-button/issues)提出您的建议

  - 若是请求添加新语音，请使用指定的**issues模板**
  - 如能直接提供截取好的mp3音频请在Issues中附上下载链接
  - 不熟悉**github**的用法也可以到[Bilibili](https://space.bilibili.com/160080754)或[QQ](https://qm.qq.com/cgi-bin/qm/qr?k=Q20bRU3bej3KGC3d5jZKc1M2eIvxVauR)和我联系

- 如果您可以进行开发，那么请**Fork**本项目进行修改，完成修改后在本项目中发起一个**Pull Request**
   > **Pull Request**请提交至**dev**分支

### 添加或修改音频

音频文件推荐使用**mp3**格式，请放入`public/voices/`目录

所有的分类和音频信息都存储在`setting/translate`目录的`json`文件中，**添加或修改音频信息**，你需要修改对应文件中的内容

`locales.json`和`category.json`分别为 UI 界面翻译和分类信息，请不要修改文件名，语音信息可以使用除此外的任意名称，可使用多个`json`文件方便管理语音

可使用`schema`文件夹中的`json`文件增加`json schema`约束和代码提醒

`category.json`结构示例如下：

```jsonc
[
  {
    "name": "mua",
    "translate": {
      "zh-CN": "mua"
    }
  }
]
```

语音文件结构示例如下：

```jsonc

[
  {
    "name": "mua",
    "path": "mua.mp3",
    "date": "2022-11-20",
    "translate": {
      "zh-CN": "mua"
    },
    "category": "mua",
    "mark": {
      "title": "2022-11-20【纱依】出道纪念直播后日谈",
      "time": "23:28~23:29",
      "url": "https://www.bilibili.com/video/BV1Ad4y1b7un"
    }
  }
]
```
