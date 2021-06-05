# HTML5 和 CSS笔记



### 注释和类型



- 文档声明

  - 用于声明浏览器当前网页版本, html5的文档声明, 写于html文档开头，不区分大小写。

    ```html
    <!doctype html>
    <!Doctype heml>
    <!doctype HTML>
    ```

- 注释写法

  ```html
  <!-- /注释内容/ --!>
  ```

- meta标签

  - 用于标注网页的字符集，避免乱码的问题， 写于head标签内

  - 设置元数据。

  - 基本属性

    - charset 字符集
    - name 指定数据的名称
    - content 指定数据的内容
    - http-equiv = "refresh"  content=“3； url = 目标网址”  重定向标签
    - ...

  - 常用字符集 utf-8万国码

    ~~~ html
    <meta charset="utf-8">
    ~~~

    

- title标签

  - title中的内容会显示在标题栏中，搜索引擎主要用title标签判断是否符合搜索内容。

    ~~~html
    <title> 标题</title>
    ~~~

- h*标签

  ~~~html 
  <h1>
      一级标题
  </h1>
  <h2>
      二级标题
  </h2>
  <h3>
      三级标题
  </h3>
  ...
  <h6>
      六级标题
  </h6>
  
  <hgroup>逻辑相关的标题分为一组</hgroup>
  ~~~

  

- body标签

  - body是网页的子元素，表示网页的主题内容，所有可见内容应写在body中。

    ~~~ html
    <body>
        <h1>
            <!-- h1 网页的一级标题 -->
            网页的大标题
        </h1>
    </body>
    ~~~

- 工具推荐
  
  - zeal<[Download · Zeal (zealdocs.org)](https://zealdocs.org/download.html#windows)>
    - 用于离线查看html及其他语言文档的说明书。
  
- paragraph标签

  ~~~ html
  <p>
      这是一个段落。
  </p>
  ~~~

- 强调标签

  ~~~html
  <b> 加粗
  <strong>表示强调</strong>
  <blockquote>表示引用，头部缩进tab</blockquote>
  <q></q>
  ~~~

- 特殊符号输入需要实用转义字符 &；内容放在中间

  ~~~html
  &nbsp; 空格
  &gt; 大于号
  ...
  ~~~


- 