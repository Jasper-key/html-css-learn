## 一、结构  
    <!DOCTYPE>：文档类型声明，作用是告诉浏览器使用的哪种HTML版本来显示网页

    <html lang="en">：定义当前文档显示的语言；en=英语、zh-CN=中文
    
    <heand>：头部，可写入元素、标题、引入css\js

    <meta charset="UTF-8">：定义使用哪种字符编码，UTF-8包含了所有国家用到的字符

## 二、常用标签

    '<h1>-<h6>'：标题文字；字体变大变粗。

    <p>：段落；段落中的文字会根据浏览器大小自动换行；段落间会保留间隙。

    <br />：单标签，强制换行;行和行间有垂直间距

    <strong>/<b>：字体加粗，推荐使用第一种

    <em>/<i>：倾斜，推荐使用第一种

    <del>/<s>：删除线，推荐使用第一种

    <ins>/<u>：下划线，推荐使用第一种

    <div>：没语义，相当于容器，块级元素，独占一行

    <span>：没语义，相当于容器，行内元素，只占用内容所需区域

    <img>：图像标签
        src：img标签的必要属性，指定图像文件的路径和文件名
        alt：替换文本，图像不能显示文字时显示此文字
        title：提示文本，鼠标放到图像上所显示的文字
        width：图像的长
        height：图像的宽（长和宽要么只设置一个，要么设置成图像的原本大小，避免图像失真）
        border：图像的边框

    <a>：超链接，
        href：
        指定目标的url地址；
        如果连接是一个压缩包，则会下载；
        #为空链接；
        #+元素id可以跳转到对应的位置。
        target：打开连接的方式；_self为默认值，在当前页面打开；_blank为在新页面打开。

    <!-- 注释内容 -->：注释

    特殊字符：https://blog.csdn.net/qq_41229582/article/details/80637346

*表格是用来展示数据，列表是用来布局*
### 表格
    <table>：定义表格的标签：
        align：规定表格相对周围元素的对齐方式。参数：left、center、right
        border：规定单元格是否有边框，默认没有
        cellpadding：规定单元边沿与内容之间的边缘，默认1px
        cellspacing：规定单元格之间的空白，默认2px
        width：表格宽度
        height：表格高度

    <thead>：表格的头部区域，嵌套在<table>中

    <tbody>：表格的主题区域，嵌套在<table>中

    <tr>：行，嵌套在<thead>或<tbody>中

    <th>：表头，嵌套在<tr>中；文本会加粗，居中显示

    <td>：列，嵌套在<tr>中，数据则嵌套在<td>中
        rowspan：跨行合并，目标单元格为最上侧的单元格
        colspan：跨列合并，目标单元格为最左侧的单元格
### 列表
    <ul>：无序列表；<ul>中只能嵌套<li>

    <ol>：有序列表；<ol>中只能嵌套<li>

    <li>：列表项，嵌套在<ul>或<ol>中，<li>中能嵌入任何元素

    <dl>：自定义列表，只能嵌套<dt>、<dd>

    <dt>：定义名字，嵌套在<dl>，能嵌套所有元素

    <dd>：描述名字，和<dt>是上下级关系，对<dt>进行说明；嵌套在<dl>，能嵌套所有元素

### 表单
    1. 作用：使用表单的目的是收集用户信息
    2. 表单的组成：表单域、表单控件、提示信息

    <form>：表单域；包含表单元素的区域，将表单元素值提交给服务器。
        action：指定接收数据的服务器URL地址
        method：表单提交方式，例：ｐｏｓｔ／ｇｅｔ
        name：指定表单域名称，用于区分
        input：输入（单标签）
            type：输入框的类型
                button：点击按钮
                checkbox：复选框
                file：输入字段和“浏览”按钮，供文件上传
                hidden：隐藏的输入字段
                image：图像形式的提交按钮
                password：密码字段，输入的字符会被掩盖
                radio：单选按钮
                reset：重置按钮，清除表单中的所有数据
                submit：提交按钮
                text：单行文本，默认20个字符
            name：表单元素名，单选和复选的name都需要一致
            value：表单的值
            checked：表单首次加载时应该被选中，属性值：checked
            maxlength：规定字符最大长度，属性值：正整数
            placeholder：提示

        <label>：input元素的标签；用于绑定一个表单，当鼠标点击label标签文本时，光标会自动聚焦到对应的表单元素中
            for：绑定表单元素；值为表单元素的id值

        <select>：下拉框，至少包含一对option，默认显示第一对option

            <option>：下拉选项
                selected：默认选中，值为selected

        <textarea>：多行文本框
            cols：每行的字符
            rows：显示的行数
            基本上使用css代替cols/rows
### MDN文档：  
https://developer.mozilla.org/zh-CN/






下节看P62  
地址：https://www.bilibili.com/video/BV14J4114768?p=46
