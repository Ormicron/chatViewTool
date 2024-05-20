# 声明
***该工具长期未更新维护，多数情况下已无法满足使用需求，本工具私有版/外部版本均已停止开发。***

# ChatViewTool

`ChatViewTool`是一个配合[`dumpkey`](https://github.com/Ormicron/Sharp-dumpkey)(微信数据库秘钥获取工具)使用的小工具，该工具实现了微信数据库解密以及展示数据库聊天记录的功能。

![capture350345](https://user-images.githubusercontent.com/26640179/174020513-2eb7133f-7605-4978-ae0d-5e8ca4a8d0da.png)

## 使用方法

在获取数据库秘钥之后将内容保存为文本文件`DBPass.Bin`，随后提取以下相关的数据库放于秘钥文件同目录。

```
C:\Users\test\Documents\WeChat Files\微信ID\Msg\MicroMsg.db
C:\Users\test\Documents\WeChat Files\微信ID\Msg\Multi\MSG*.db
```

随后打开`ChatViewTool`点击`数据库解密`并选择秘钥及数据库所在的目录，待解密完成后，点击`查看数据库`选择同目录即可完成会话展示，双击联系人列表可展示对应的聊天记录。

![capture000348](https://user-images.githubusercontent.com/26640179/174020563-f2862f0d-6cf5-4500-b448-3f529b0153c9.png)



## 引用

该工具基于`Java`编写，在编写过程中大量参考了网络上代码。

```
https://blog.csdn.net/Listening_Rift/article/details/105309990
https://zhuanlan.zhihu.com/p/340276760
```

![Visitor Count](https://profile-counter.glitch.me/chatViewTool/count.svg)
