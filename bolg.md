Markdown基础语法

    #一级标题 默认带下分割线 标题H1
    ##二级标题 默认带下分割线
    ###### 六级标题
#一级标题 标题H1
##二级标题 标题H2
###### 六级标题 标题H6

    **加粗文字**
    *倾斜文字*`
    ***斜体加粗文字***
    ~~加删除线文字~~
	上标：X<sub>2</sub>，下标：O<sup>2</sup>
    O<sup>3<sup>3<sup>3<sup>3<sup>3<sup>3<sup>3</sup></sup></sup></sup></sup></sup></sup>
    
**加粗文字**
*倾斜文字*
***斜体加粗文字***
~~加删除线文字~~
下标：O<sub>2</sub>
上标：O<sup>3</sup>
O<sup>3<sup>3<sup>3<sup>3<sup>3<sup>3<sup>3</sup></sup></sup></sup></sup></sup></sup>

    >引用内容 
    >>>引用内容 可多级引用 
	`<br />标签` 在 <br/>前键入两个空格
>引用内容 
>>>引用内容  `<br />标签`


    分割线上边非代码块要隔一行 最少需要三个标识符
    ---
    ***
---
	分割线内的内容
***
    链接
    [百度](http://www.baidu.com) <br>
	<http://www.baidu.com>
    <a href="baidu.com" target="_blank">百度</a>
[百度](http://www.baidu.com)
<http://www.baidu.com>
<a href="http://www.baidu.com" target="_blank">百度</a>


<br/>

    表格 | --- | 为必须 
    默认标题居中文本靠左, | ---: |右对齐
    原生的语法两边都要用 |
    | 标题---1 | 标题---2 |标题---3 |
    | --- | :---: | ---: | 
    | 文本 | 文本 | 文本 |
    | 文本 | 文本 | 文本 |
| 标题---1 | 标题---2 |标题---3 |
| --- | :---: | ---: | 
| 文本 | `文本` | 文本 |
| `文本` | 文本 | `文本` |

	JS代码
	```javascript
	function test() {
		console.log("Hello world!");
	}
	```
```javascript
function test() {
	console.log("Hello world!");
}
```

---
    图片引用
	![](https://www.cnblogs.com/images/cnblogs_com/chen-g-x/1379448/t_ao.jpg )
![](https://www.cnblogs.com/images/cnblogs_com/chen-g-x/1379448/t_ao.jpg )

	列表
	- 列表一
		* 列表
	- 列表二
		+ 列表

- 列表一
	* 列表
- 列表二
	+ 列表


	选项
	- [x] 已选中的
		- [ ] 未选中的


- [x] 已选中的
	- [ ] 未选中的


	特殊符号
	&copy; &  &uml; &trade; &iexcl; &pound;
	&amp; &lt; &gt; &yen; &euro; &reg; &plusmn; &para; &sect; &brvbar; &macr; &laquo; &middot;
	X&sup2; Y&sup3; &frac34; &frac14;  &times;  &divide;   &raquo;
	18&ordm;C  &quot;  &apos;

&copy; &  &uml; &trade; &iexcl; &pound;&amp; &lt; &gt; &yen; &euro; &reg; &plusmn; &para; &sect; &brvbar;
&macr; &laquo; &middot;
X&sup2; Y&sup3; &frac34; &frac14;  &times;  &divide;   &raquo;
18&ordm;C  &quot;  &apos;


    Emoji表情
    :star:
    :smiley:
    :blossom:
    :eyes:
    
:star:
:smiley:
:blossom:
:eyes:



----------
----------



	科学公式 TeX(KaTeX)
	$$E=mc^2$$
	$$x > y$$
	$$\(\sqrt{3x-1}+(1+x)^2\)$$
	$$\sin(\alpha)^{\theta}=\sum_{i=0}^{n}(x^i + \cos(f))$$

$$E=mc^2$$

$$x > y$$

$$\(\sqrt{3x-1}+(1+x)^2\)$$

$$\sin(\alpha)^{\theta}=\sum_{i=0}^{n}(x^i + \cos(f))$$

	多行公式：
	```math
	\displaystyle
	\left( \sum\_{k=1}^n a\_k b\_k \right)^2
	\leq
	\left( \sum\_{k=1}^n a\_k^2 \right)
	\left( \sum\_{k=1}^n b\_k^2 \right)
	```
	```katex
	\displaystyle
	    \frac{1}{
	        \Bigl(\sqrt{\phi \sqrt{5}}-\phi\Bigr) e^{
	        \frac25 \pi}} = 1+\frac{e^{-2\pi}} {1+\frac{e^{-4\pi}} {
 	       1+\frac{e^{-6\pi}}
 	       {1+\frac{e^{-8\pi}}
	         {1+\cdots} }
 	       }
 	   }
	```
```latex
f(x) = \int_{-\infty}^\infty
    \hat f(\xi)\,e^{2 \pi i \xi x}
    \,d\xi
```

```math
\displaystyle
\left( \sum\_{k=1}^n a\_k b\_k \right)^2
\leq
\left( \sum\_{k=1}^n a\_k^2 \right)
\left( \sum\_{k=1}^n b\_k^2 \right)
```
```katex
\displaystyle
    \frac{1}{
        \Bigl(\sqrt{\phi \sqrt{5}}-\phi\Bigr) e^{
        \frac25 \pi}} = 1+\frac{e^{-2\pi}} {1+\frac{e^{-4\pi}} {
        1+\frac{e^{-6\pi}}
        {1+\frac{e^{-8\pi}}
         {1+\cdots} }
        }
    }
```
```latex
f(x) = \int_{-\infty}^\infty
    \hat f(\xi)\,e^{2 \pi i \xi x}
    \,d\xi
```

### 绘制流程图 Flowchart

```flow
st=>start: 用户登陆
op=>operation: 登陆操作
cond=>condition: 登陆成功 Yes or No?
e=>end: 进入后台

st->op->cond
cond(yes)->e
cond(no)->op
```
[========]

### 绘制序列图 Sequence Diagram

```seq
Andrew->China: Says Hello
Note right of China: China thinks\nabout it
China-->Andrew: How are you?
Andrew->>China: I am good thanks!
```
### End

---