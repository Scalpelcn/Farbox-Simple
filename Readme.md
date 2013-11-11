# Farbox Simple 模版全新发布

之前一直在犹豫是否要切换到Farbox这个平台，前几天自己购买的虚拟主机也出了问题，主机商一直都没有解决问题。下定决心，咬咬牙把博客从Typecho转了过来。

在不同平台间转换博客最头疼的就是制作统一的模版。幸好自己喜欢极简风格，不需要书写太复杂的CSS。在上一个博客Typecho的基础上对CSS进行稍许的修改，Farbox Simple 模版就诞生了。

模版代码几处需要手动修改，故不采用官方推荐的clone模式。

## 模版功能

1. 代码高亮
2. 多说评论
3. 返回顶部

## 使用方法

1. 从GitHub Clone出模版源代码 - [模版下载][1]
2. 打开`include/comments.html`文件，将多说评论代码复制其中
3. 将`Farbox-Simple`文件夹重命名为`template`
4. 将`template`文件夹复制到Farbox根目录
5. 在Farbox根目录新建`about.md`(关于我)和`links.md`(友情链接)文件，
5. 进入Farbox设置页面
6. 点击网站模版，选择使用默认模版
7. 模版修改完成

第一次制作模版，在制作的过程中还存在很多的不足，希望大家能多给我提提意见。


[1]:https://github.com/Scalpelcn/Farbox-Simple