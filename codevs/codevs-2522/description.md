<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>【问题描述】</p>
<p>代码自动生成器已经应用到各个领域，有根据界面生成代码的（C#，delphi），有根据wsdl生成代码的(axis) 。现在需要你做一个基于数据表的代码生成器，输入一个数据表和对应的字段、字段类型信息，生成固定格式的JAVA BEAN代码。</p>
<p>【数据表】</p>
<p>数据表的命名是由大写字母、数字、下划线组成的大写字母开头的长度小于30位的字符串，如 TB_SAMP_MACHINE ，SYSTEM_ID ，TEST2。</p>
<p>在java bean种，数据表的表名映射到java的类名，映射规则如下：</p>
<p>首字母大写，所有"_"符号删除，所有"_"后面的第一个字如果是字母则大写，其他字母小写，然后后面添加字符串“Bean”作为类名。</p>
<p> </p>
<p>       【字段】</p>
<p>一个数据表包含一个以上的字段，字段的信息包括字段名和字段类型。</p>
<p>字段命的命名规则和数据表相同。</p>
<p>在java bean种，字段名映射到java的类成员变量，映射规则如下：</p>
<p>首字母小写，所有"_"符号删除，所有"_"后面的第一个字如果是字母则大写，其他字母小写：</p>
<p>如果第二个字是大写字母，则把第二个字母改成小写。</p>
<p>字段类型为：</p>
<p>NUMBER   对应java的 long类型</p>
<p>VARCHAR2 对应java的 String类型</p>
<p>DATE      对应java的 Date类型</p>
<p>【GETTER/SETTER】</p>
<p>JAVA BEAN种每一个类成员变量都包含一个 GETTER方法和SETTER方法</p>
<p>对于GETTER方法，其方法名为 get+变量名(首字母大写) ；</p>
<p>对于 SETTER方法，其方法名为 get+变量名(首字母大写) ，带一个参数，参数类型和参数名就是对应变量的类型和变量名，例如：对于long类型的变量名为 actionId 的类成员变量，其GETTER/SETTER方法如下：</p>
<p>public long getActionId() {</p>
<p>     return this.actionId;</p>
<p>}</p>
<p> </p>
<p>public void setActionId(long actionId) {</p>
<p>     this.actionId=actionId;</p>
<p>}</p>
<p> </p>
<p>【代码格式】</p>
<p>代码格式必须严格按照如下模板输出，不允许增删改任何字符（包括空格、回车、制表符等等）</p>
<p> </p>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="432">
<p><strong>package</strong> com.gzio.match;</p>
<p> </p>
<p><strong>import</strong> java.util.Date;</p>
<p><strong> </strong></p>
<p><strong>public</strong> <strong>class</strong> 类名 <strong>implements</strong> java.io.Serializable</p>
<p>{</p>
<p>    <strong>private</strong> 类型 变量名;  (多个)</p>
<p> </p>
<p>    <strong>public </strong>类名() {</p>
<p>    }</p>
<p> </p>
<p>    对于所有的每一个变量提供 GETTER/SETTER方法，格式如下：</p>
<p>    <strong>public</strong> 类型 GETTER方法() {</p>
<p>        <strong>return</strong> 变量名;</p>
<p>    }</p>
<p> </p>
<p>    <strong>public</strong> <strong>void</strong> SETTER方法(类型 变量名) {</p>
<p>        <strong>this</strong>.变量名 = 变量名;</p>
<p>    }</p>
<p> </p>
<p>}</p>
<p> </p>
</td>
</tr>
</tbody>
</table>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>表名 table</p>
<p> 字段数目n, n∈[1,20]</p>
<p> 以下n行代表 字段名 字段类型  ，用空格隔开</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>完全符合上述格式的JAVA程序文件 。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>ACTION</p>
<p> 3</p>
<p> IF_ACTION_ID   NUMBER</p>
<p> IF_ACTION_CODE VARCHAR2</p>
<p> CREATE_DATE DATE</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="432">
<p>package com.gzio.match;</p>
<p> </p>
<p>import java.util.Date;</p>
<p> </p>
<p>public class ActionBean implements java.io.Serializable</p>
<p>{</p>
<p>       private long ifActionId;</p>
<p>       private String ifActionCode;</p>
<p>       private Date createDate;</p>
<p> </p>
<p>       public ActionBean() {</p>
<p>       }</p>
<p> </p>
<p>       public long getIfActionId() {</p>
<p>              return ifActionId;</p>
<p>       }</p>
<p> </p>
<p>       public void setIfActionId(long ifActionId) {</p>
<p>              this.ifActionId = ifActionId;</p>
<p>       }</p>
<p> </p>
<p>       public long getIfActionCode() {</p>
<p>              return ifActionCode;</p>
<p>       }</p>
<p> </p>
<p>       public void setIfActionCode(String ifActionCode) {</p>
<p>              this.ifActionCode = ifActionCode;</p>
<p>       }</p>
<p> </p>
<p>       public long getCreateDate() {</p>
<p>              return createDate;</p>
<p>       }</p>
<p> </p>
<p>       public void setCreateDate(Date createDate) {</p>
<p>              this.createDate = createDate;</p>
<p>       }</p>
<p> </p>
<p>}</p>
<p> </p>
</td>
</tr>
</tbody>
</table>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>格式说明：</p>
<p>1、  每一行代码最右面没有空格、制表符号。</p>
<p>2、  所见的空行没有空格、制表符号。</p>
<p>3、  每一行代码最左边没有空格，类中的变量、方法使用制表符号对齐。</p>
<p>4、  GETTER方法和SETTER方法内部的代码左边用两个制表符对齐。</p>
<p>5、  package , import , public class 开头的语句以及 class 对应的 { , } 括号向左顶格。</p>
<p>6、  方法名和左括号“(”之间没有空格，其他的见到有空格的部分只有一个空格。（比如 “public”和“void”, “SETTER方法(类型”和“变量名)”， “)”和“{”，“return”和变量名，“this.变量名”和“=”和“变量名;”之间也有一个空格隔开）。</p>
<p>7、  每个方法以”}”结束，下一个方法在上一个方法的”}”空一行之后编写。</p>
<p>8、  类定义结束的 } 后面有一个空行，然后文件结束</p>
</div>
</div>