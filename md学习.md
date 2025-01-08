#  MarkDown基本语法学习

## 标题语法

使用#来标识标题，井字符的数量能表示标题的分级  
注意段落前与其前面的井字符之间加space

## 段落语法

使用空白来生成段落

## 换行语法

使用spacespace和  
回车键来换行  
注意：换行往往是必要的，在任何不希望文本出现在同一行情况下

## 强调语法

粗体 **使用**  
斜体 *使用*  
同时使用 ***粗体和斜体***  
>为了兼容性，在有前后文时，请在首尾星号前后分别加一个space

## 引用语法

>使用一个半角符号的大于号,表示这是被引用的内容  
>跨行引用  

引用的结束？ ***使用段落语法***
***问题1*** 如果不使用换行语法  
>本行末尾没有space
>这一句话会不会单独成行？

事实是，这一句话没有单独成行  
跨段落引用，需要在段落之间空白行添加一个大于号
>段落一  
>  
>段落二  

嵌套引用以及其他语法的使用  
>大菌老师，快更新  
>*拜托了，希耶尔老师*  

## 列表语法

有序列表，使用数字和句点加space  
注意在连续的列表中/即使列表内有插入内容/不需要手动换行，但是在列表结束时需要使用段落语法
1. 这是一号  
2. 这是二号  

>第一个数字必须是1  

无序列表  
- 这是爱尔奎特  
- 这是西耶尔
 
列表的嵌套
1. 嵌套段落
    需要缩进四个空格
2. 嵌套引用
    >在缩进四个空格后使用大于号
3. 嵌套列表
    - 同上
4. 图片  
    需要缩进四个空格`![这里是图片描述](这里是图片的地址)`  
    ![这是爱尔奎特](https://github.com/ArcLiquid/md-study/blob/main/arcuid.jpg)
6. 插入代码
        /需要缩进八个空格且空行/
     
        print("Ciaollo~~")  
        exit()
8. 无

## 代码语法

1. 反引号`this is code` 
2. 转移反引号，如果需要展示的代码已经包含反引号，使用``Use `code` in your Markdown file.``
3. 代码块
    >缩进式插入前方必须有空行；  
    >缩进 4 个空格或是 1 个制表符；  
    >一个代码区块会一直持续到没有缩进的那一行（或是文件结尾）

展示如下，这是一个龟龟代码，由`叶夜夜`分享

    import turtle       #导入turtle模块  
    p = turtle.Turtle() #创建海龟对象  
    p.color("red")      #设置绘制时画笔的颜色  
    p.pensize(3)        #定义绘制时画笔的线条宽度  
    turtle.speed(1)     #定义绘图的速度（“slowest”或者1）  
    p.goto(0,0)         #移动海龟到坐标原点(0,0)  
    p.forward(200)      #向前移动100  
    p.right(90)         #向右旋转90度  
    p.forward(100)      #向前移动100  
    p.right(90)         #向右旋转90度  
    p.forward(200)      #向前移动100  
    p.right(90)         #向右旋转90度  
    p.forward(150)      #向前移动100  
    p.right(90)         #向右旋转90度  
    p.forward(40)  
    p.left(90)  
    p.forward(40)  
    p.right(90)  
    p.forward(40)  
    p.left(90)  
    p.forward(60)  
    p.right(90)  
    p.forward(40)  
    p.right(90)  
    p.forward(60)  
    p.left(90)  
    p.forward(40)  
    p.right(90)  
    p.forward(40)  
    p.left(90)  
    p.forward(40)  
    p.right(90)  
    p.forward(50)

## 分隔线语法

在一行中使用`---`且不包含其他字符，为了`兼容性`，请在分隔线的前后均添加空白行

---

上面有分隔线

## 链接语法

1. 超链接Markdown语法代码：`[超链接显示名](超链接地址/这里有一个space/"超链接title")`
    >`超链接显示名`就是渲染后的蓝色可点击文本
    >`超链接title`是光标悬浮在`超链接显示名`上时展示的悬浮窗的内容
2. 网页和邮箱地址：使用尖括号/也就是大于号小于号/`</这里输入ULR/>`,实际效果就是把链接变成可以点击的链接
3. 带有不同格式的链接
    事实上也就是斜体、粗体、代码块三种 *[ArcLiquid的md学习记录](https://github.com/ArcLiquid/md-study/edit/main/.md)* ，**[ArcLiquid的md学习记录](https://github.com/ArcLiquid/md-study/edit/main/.md)** ，[`ArcLiquid的md学习记录`](https://github.com/ArcLiquid/md-study/edit/main/.md)/注意第三种格式反引号的位置/
4. 引用类型链接
    这种链接包含两部分：第一部分是在正文中被引用的部分，第二部分是脚注或者尾注  
[这里是显示名] [x]
[x]: <https://github.com/ArcLiquid/md-study/edit/main/.md>



         
 


