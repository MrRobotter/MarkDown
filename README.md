# README.md 使用教程

## 基础语法
### 标题使用

标题一共分为六个级别使用#个数来区分

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
#####五级标题
###### 六级标题

另外也可在文字下使用三个以上的“=”来表示一级标题或者三个“-”以上代表二级标题，亦称为大标题和中标题，分别与一级标题二级标题对应如：

大标题
====
中标题
----
### 普通文本

直接输入的文字就是普通文本。
需要注意的是要换行的时候不能直接通过回车来换行，需要使用\<br>(或者\<br/>)。也就是html里面的标签。事实上，markdown支持一些html标签，你可以试试。当     然如果你完全使用html来写的话，就丧失意义了，毕竟markdown并非专门做前端的，然而仅实现一般效果的话，它会比html写起来要简洁得多得多啦。<br/>

这是一段普通的文本,
直接回车不能换行，<br>要使用\<br>

### 单行文本
单行文本使用两个Tab实现如下所示：

    大家好，我是机器人先森
    
### 多行文本

    初次见面，多多指教
    你回来了，
    大家好，我是野原新之助，我喜欢跳大象舞
    
### 超链接 

直接输入这个链接的URL就好了，显示出来会自动变成可链接的形式的，如： <br>百度网址https://www.baidu.com/

### 部分文字高亮

如果你想使一段话中部分文字高亮显示，<br>起到突出作用，那么可以使用``包围起来。<br>注意这个符号不是单引号，而是Tab键上方，数字键1左边的键（使用英文输入法）如：。<br/>

你好，我叫`野原新之助`,我来自`日本`,我今年 `5岁` 了。
    
### 文字超链接 

给一段文字加入超链接的格式是这样的\[要显示的文字\]\(链接的地址\)。比如：<br/>
<br/>
欢迎大家关注[我的博客](https://github.com/MrRobotter)
<br/>
<br/>我们还可以给他加上一个鼠标鼠标悬停显示的文本。<br/>
<br/>欢迎大家关注[我的博客](https://github.com/MrRobotter "查看详情")<br/>
<br>即在URL之后 加个空格 用双引号括起来一个字符串。同样要注意这里是英文双引号。<br/>

### 插入符号
#### 圆点符
一般在文章列出条目时使用，编辑是使用星号*来表示如：
* 昵称：机器人先森
* 性别：男
* 职业：程序猿
此外还有二级圆点和三级圆点，就是多加个Tab如：
* 中国
    * 浙江
        * 杭州
#### 缩进
>集合
>>Collection
>>>List
>>>>ArrayList

可用于文章的引用。自己多摸索。

### 插入图片
我们写文章或者做文档图片说明是有必要的，我们使用这样使用图片：
#### 使用网络图片
<br>使用格式为：叹号！+方括号[]+括号()<br/>其中方括号里是图片说明，<br>括号里是图片地址，如：<br/>
<br>
![avatar](https://avatars2.githubusercontent.com/u/32949039?s=400&u=5652794a3c34a025d97c9ae57bf100975545ec3c&v=4 "我的头像")<br/>
#### 使用GitHub仓库里的图片
<br> 书写格式与使用网络图片一致，不同的是URL里面的写法。<br/>

        https://github.com/ 你的用户名 / 你的项目名 / raw / 分支名 / 存放图片的文件夹 / 该文件夹下的图片
<br>
![无人机](https://github.com/MrRobotter/test/images/无人机3.jpeg "无人机")
