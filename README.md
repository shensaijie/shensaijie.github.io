# web实践

## 点击[预览blog](https://shensaijie.github.io)

## html实现
1. 显示图片
    * 图像要放在<p>标签中，text-align: 设置对齐格式
    * 标签名 img 
    * 图片路径 src 
    * 宽度、高度 width、heigth %或px
2. 显示文本
    * 标签名 <p> 块级元素，一个新段落，与
    * 列表
        - ul 无序列表
        - ol 有序列表
        - dl 定义列表 内含 <dt> <dd>
    
3. 超链接
    * 基本语法 < a href=" 链接目标"  name="" title="提示信息" target="">超链接标题</a>
    * target打开方式 _blank新窗口 _self同一窗口
    * 书签 href = # + 连接name
4. 语法
    * 单标记与双标记 < br>换行 < hr>水平分割线
    * 属性语法 < hr size="3" color="red" align="center" >
    * <html> <head></head> <body></body> </html>
5. 其他
    * 注释
    <! -- 注释信息 -- >
    <comment>注释信息</comment>
    * 标题文字 <h#>标题</h#> 1~6
    * 空格 &nbsp

## CSS实现

1. icon圆形
    * border-radius:50% 圆角 overflow:hidden 超出盒子去掉
    * margin-top 上外边距为负实现头像一半在背景上