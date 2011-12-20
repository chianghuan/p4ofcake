Hello, world!
===
[cianghuan](https://github.com/chianghuan/)正在尝试在github上配置自己的笔记、备忘、博客、或知识库。文档使用[mark down](http://daringfireball.net/projects/markdown/)标记写成。该标记语言发明者为[John Gruber](http://daringfireball.net/)。

你好，世界！
===
[chianghuan](https://github.com/chianghuan/) is trying to putting his notes/memo/blog/knowledge-repo on github. The docs are written in [mark down](http://daringfireball.net/projects/markdown/). The markup is authored by [John Gruber](http://daringfireball.net/).

开始
===
下面开始将是一堆各种格式排版的文字或图片或链接。纯粹用于我学习、试用和列举mark up的各种标记，并留来方便以后查找。参考资料 [markdown:syntax](http://daringfireball.net/projects/markdown/syntax)。

标题
---
[atx](http://www.aaronsw.com/2002/atx/)形式的标题标记

> #这是一个大号标题 <br/>
> 看得出大号标题后的文字段落，末了会有一个华丽的分割线。
> ##这是一个次号标题 <br/>
> ###这个还更小一点 <br/>
> ####可以再小一点 <br/>
> #####还能再小点么 <br/>
> ######这是极限了 <br/>

正文
---
这个句子和下一个句子在.markdown文件中以换行符号分开了，但结果两个句子还是被放到了同一行，并没有换行：

> 这个句子，
> 下一个句子。

以下两个句子，以`<br/>`标记分开，则两个句子正确换行：

> 这个句子，<br/>
> 下一个句子。

以下文本中包含了不同的字体格式：\*注:此处用\*标记代替'<em>强调</em>'失效

> 这是<em>强调</em>文本<br/>
> 这是__粗体__文本 <br/>
> 这又是<em>强调</em>文本 <br/>
> 这又是**粗体**文本 <br/>

以下文本为多重引文：

> 这是一段引用的文字
> 
> > 它还引用了其它文字
> > 
> > > 并且其它文字还引用了其它它文字
> 
> 还好不是那么容易造成混乱

代码
---
小段行内代码使用反引号`` ` ``标记，而大段代码使用缩进tab或四个空格，如：

>     /* A hello world! */
>     #include <iostream>
>     using namespace std;
> 
>     int main()
>     {
>         //hello, world!
>         cout<<"Hello, world!";
>         return 0;
>     }

列表
---
无序列表

> * 表项1
> * 表项2

> + 表项1
> + 表项2

> - 表项1，第一段
> 
>     表项1，第二段
> - 表项2

有序列表

> 1. 有数字编号的表项
> 1. 有一个有数字编号的表项
> 1. 还是有数字编号的表项

引用资源
---
这是一个链接:

> [README.markdown](https://github.com/chianghuan/p4ofcake/blob/master/README.markdown)

这是另外一种链接标记方式:

> [README.markdown][1]
> 
> [1]: https://github.com/chianghuan/p4ofcake/blob/master/README.markdown

这是一张图片:

> ![图片文字](https://a248.e.akamai.net/assets.github.com/images/modules/header/logov7@4x-hover.png?1324325369)

分割线
---
最后是两条分割线

> 普通分割线
> 
> -----
> 两条分割线合体
> 
> * * *
> 
> - - -
