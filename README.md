# 说明文档
本文档记录一些Markdown文件基本格式及用法示例
# 目录
* [**标题层级**](#标题层级)
* [**无序列表**](#无序列表)
* [**有序列表**](#有序列表)
* [**引用**](#引用)
* [**分割线**](#分割线)
* [**表格**](#表格)
* [**链接**](#链接)
    * [*行内式*](#行内式)
    * [*参数式*](#参数式)
* [**图片**](#图片)
* [**代码框**](#代码框)
    * [*单行代码段*](#单行代码段)
    * [*多行代码段*](#多行代码段)
* [**强调**](#强调)
* [**转义**](#转义)
* [**删除线**](#删除线)
# 标题层级
## 二级标题
### 三级标题
#### 四级标题
> 一级标题下自带分割线

> 标题、列表需要注意空格
* abc
> abc
----------------
# 无序列表
* abc
* abc
* abc
----------------
# 有序列表
1. 第一行
2. 第二行
3. 第三行
1. 第四行
1. 第五行
----------------
# 引用
引用是否使用空格无影响
>一级引用
>>二级引用
>>>三级引用
>>>>四级引用
>>>>>五级引用
----------------
# 分割线
> 分割线可以由* - _（星号，减号，底线）这3个符号的至少3个符号表示，注意至少要3个，且不需要连续，有空格也可以
----------------
# 表格
> 第一种的分割线后面的冒号表示对齐方式，写在左边表示左对齐，右边为右对齐，两边都写表示居中

> Q:外部线框如何包裹？

|age|year|name|
|:--:|:--:|:--:|
|18|1992|Max|
|19|1991|Cinderella|
----------------
# 链接
>支持2种链接方式：行内式和参数式，不管是哪一种，链接文字都是用 [方括号] 来标记。
## 行内式
>### [百度](www.baidu.com)是什么意思

>### eg.[tag](www.baidu.com "title") 、[标签](/home "tag标签")
>
>链接还可以带title属性，好像也只能带title，带不了其他属性，注意，是链接地址后面空一格，然后用引号引起来
## 参数式
>把链接当成参数，适合多出使用相同链接的场景，注意参数的对应关系，参数定义时，这3种写法都可以：
>```
>[foo1]: http://example.com/ "Optional Title Here"
>[foo2]: http://example.com/ 'Optional Title Here'
>[foo3]: http://example.com/ (Optional Title Here)
>
>还支持这种写法，如果不想混淆的话：
>[foo4]: <http://example.com/> "Optional Title Here"
>```
----------------
# 图片
> 在链接两种形式上多加一个！
>`![baidu](https://www.baidu.com/img/baidu_resultlogo@2.png "这是百度首页链接的地址")`
>
>![IBM](https://github.githubassets.com/images/modules/site/logos/ibm-logo.png "这是IBM Logo地址")
>
>![NASA](https://github.githubassets.com/images/modules/site/logos/nasa-logo.png "这是NASA Logo地址")
>![SWIFT](https://github.githubassets.com/images/modules/site/logos/swift-logo.png "这是SWIFT Logo地址")

----------------
# 代码框
> 类似注释 若是要写注释，写在多行第一个反引号之后
> * ## 单行代码段
>> 单引号`包裹
>>
>>`![baidu](https://www.baidu.com/img/baidu_resultlogo@2.png "这是百度首页链接的地址")`
> * ## 多行代码段
>> 三个反引号`包裹
>>
>>``` 此处可以写注释
>>[foo1]: http://example.com/ "Optional Title Here"
>>[foo2]: http://example.com/ 'Optional Title Here'
>>[foo3]: http://example.com/ (Optional Title Here)
>>
>>还支持这种写法，如果不想混淆的话：
>>[foo4]: <http://example.com/> "Optional Title Here"
>>```
----------------
# 强调
>
>*字体倾斜*:
>`*字体倾斜*`

>_字体倾斜_:
>`_字体倾斜_`

>**字体加粗**:
>`**字体加粗**`

>__字体加粗__:
>`__字体加粗__`
----------------
# 转义
\\
\*
\~
\`
\_
\-
\+
\.
\!
```
\\
\*
\~
\`
\_
\-
\+
\.
\!
```
----------------
# 删除线
>~~删除线~~:
>`~~删除线~~`
>[button](https://blog.csdn.net/renlzrz/article/details/83545521 "LearnFrom")
----------------