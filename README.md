# KonJac

## KonJac译者版使用介绍

1. KonJac是一个实现图文分离的漫画译文加载器，因此服务器不存储除SVG格式外任何图片资源，译者在使用时，需要在支持的网站提取图片到编辑器中，才能使用。
2. 开始一个项目，在目标网页提取图片，可选择新建项目，或者将图片导入已打开的项目页面中，新建项目时需先选择翻译语言后才能创建。
3. 项目基本信息包括标题，关键词，马甲，留言，标题和关键词用于译文搜索，标题不能空白，在6-64字节内，留言需在240字节内（都是在别人网站上加载的内容，禁止广告）
4. 目前编辑器可添加，文本框，图片截图（矩形/自定义截图），SVG（创建或导入[也不要导入太大的SVG文件，项目有大小限制]）三种元素内容。
5. 编辑器-文本框介绍：
    - 因为文本描边是一个硬需求，而目前浏览器CSS只支持居中描边，所以实际上的文本框是有3个元素，本体、背景、容器，背景用于帮助实现外描边，及文本阴影，容器用于背景（可纯色或引用图片截图）以及溢出处理等。
    - 通过使用预设样式，可以快速套用不同样式。
    - 如果开放的CSS样式不够用，可以使用自定义样式，格式为JSON
    - 编辑文本框时，有富文本工具栏，可以作用于文本框内部。
6. 编辑器-图片截图介绍：
    - 支持矩形截图及自定义截图
    - 截图可用于遮掩以及作为文本框背景等
7. 编辑器默认自动保存项目（10分钟/次），也可手动保存。
8. 译文有审核上架机制，目前默认通过。
9. 联系 QQ：852452748 邮件852452748@qq.com 
