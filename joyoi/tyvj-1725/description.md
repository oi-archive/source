# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;LT很喜欢模仿别人的程序。最近，他又做出了一个仿“Excel”的表格软件，LT为了区分出这是他的“杰作”，他给这个软件取名为“Ixcel表格软件”。（“Ixcel”读音和“Excel”相同）。Ixcel虽说是仿造的，但是与Excel还是有很大区别。For&nbsp;example，我们来看看Ixcel中的行列号规定。<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;Ixcel中的行列号（不为零！列号或行号为0的单元格是不存在的！）都是使用大写字母标识的，但是行列号之间有不同的标识规定：<BR>&nbsp;&nbsp;&nbsp;&nbsp;·Ixcel中的行号，第1行是A，第2行是B，然后依次标下去，第26行是Z。之后行号变为两位从AA~ZZ以字母顺序标识(AA,AB,AC..AZ,BA,BB,BC..ZZ)。再之后行号变为三位大写字母AAA~ZZZ(AAA,AAB,AAC..AAZ,ABA...ZZZ)，依次类推。行数是没有限制的。<BR>&nbsp;&nbsp;&nbsp;&nbsp;·Ixcel中的列号，第1列是A，第2列是B，然后依次标下去，第26列是Z。与行号不同的是，合法的列号的标识前面一个字母的ASCII码必须小于后一个字母的ASCII码，所以接下来的列号变为两位从AB~YZ根据合法顺序标识(AB,AC,AD..AZ,BC,BD,BE..YZ)。再之后列号变为三位大写字母ABC~XYZ(ABC,ABD,ABE..ABC,ACD...XYZ)，依次类推。因为Ixcel列号的独特性，列数并不是没有限制的，列号最大是26位，超过列数限制的单元格是不存在的。<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;MK很荣幸地成为了第一个使用Ixcel的用户。他想知道一份非常大的表格数据中的某些单元格的内容，但他不知道Ixcel中这些单元格的行号和列号分别是什么，请你来编程帮帮MK。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;输入的第1行包括两个正整数，数据表格允许的最大行列数M和要查询的单元格数量N。<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来N行，每行一条格式为“X1&nbsp;N1&nbsp;X2&nbsp;N2”的查询。X1代表大写字母‘R’或‘C’，X2也代表大写字母‘R’或‘C’。‘R’表示行，‘C’表示列。N1和N2都为一个自然数。数据并不保证一定存在这样的单元格。合法的单元格是表示为‘R&nbsp;NUM&nbsp;C&nbsp;NUM’或‘C&nbsp;NUM&nbsp;R&nbsp;NUM’的形式，行号或列号不能大于M且在表格中能够找到的单元格。<BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;输出共N行，对每一条查询，输出所在单元格的行号和列号，用一个空格隔开。如果单元格不存在（即不合法），则输出-1。每条查询的输出占一行。格式可参照输入输出样例。 

 
 # 提示 
【数据范围】<BR>M≤100,000,000<BR>N≤100<BR>0≤NUM≤1,000,000,000<BR>寒假模拟赛&nbsp;普及组&nbsp;第二题 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>123 3
R 26 C 27
R 27 C 26
R 124 C 10
</td><td>Z AB
AA Z
-1
</td></tr></table>
