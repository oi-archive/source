# 

 
 # 题目背景 
为庆祝Tyvj恢复正常，Mr.Phone特意奉献此题。<BR>作为Tyvj的忠实用户，Mr.Phone非常喜爱编写各种各样的C++程序，但是由于Tyvj在公元2011年9～10月期间出了点小问题，导致Mr.Phone上传自己的程序异常缓慢。<BR>众所周知，上传文件的时间是和文件大小正相关的，所以Mr.Phone为了尽可能快地将自己写的程序上传至Tyvj接受评测，需要将C++代码进行压缩后再上传。<BR> 

 
 # 题目描述 
在Mr.Phone的程序中，空白字符只有三种：制表符、空格、换行。<BR>Mr.Phone压缩代码时，会采用如下手段：<BR>&nbsp;&nbsp;&nbsp;&nbsp;1、将注释去掉。<BR>&nbsp;&nbsp;&nbsp;&nbsp;2、将所有能够换成空格而不影响程序语义的空白字符(不包括空格)换为空格。<BR>&nbsp;&nbsp;&nbsp;&nbsp;3、将所有去掉而不影响程序语义的空白字符去掉。<BR>Mr.Phone会不断使用以上手段，直到代码不能再被压缩为止。<BR>你将得到一段Mr.Phone写的C++代码，请将它按Mr.Phone的方法压缩后输出代码最终的长度(以字节为单位)。<BR>输入的C++代码符合下列要求：<BR>&nbsp;&nbsp;&nbsp;&nbsp;1、没有预处理语句。(即不存在以#开头的行)<BR>&nbsp;&nbsp;&nbsp;&nbsp;2、没有语法错误。(即一旦加上预处理语句就可以通过编译)<BR>&nbsp;&nbsp;&nbsp;&nbsp;3、所有字符串常量的内容不含有双引号，所有字符常量内容不是单引号。<BR>需要注意的是，编译这段代码的编译器不支持C++0x规范。例如：<BR>vector&lt;pair&lt;long,long&gt;&nbsp;&gt;v;<BR>不可以压缩为<BR>vector&lt;pair&lt;long,long&gt;&gt;v;<BR> 

 
 # 输入格式 
一段C++程序代码。<BR> 

 
 # 输出格式 
压缩后的代码长度。<BR> 

 
 # 提示 
样例解释：<BR>&nbsp;&nbsp;&nbsp;&nbsp;压缩后的代码为<BR>int&nbsp;main(){long&nbsp;a,b;scanf("%ld&nbsp;%ld",&a,&b);printf("%ld",a+b);return&nbsp;0;}<BR>&nbsp;&nbsp;&nbsp;&nbsp;共71字节。<BR><BR>数据说明：<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于10%的数据，输入的代码与压缩后的代码相同。<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于30%的数据，输入的代码不含有字符串常量、字符常量及注释。<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于90%的数据，输入的代码长度不超过500字节。<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于100%的数据，输入的代码长度不超过1MB。<BR><BR>如欲查看本题测试数据，可以提交下面的C++代码：<BR>[b]<BR>#include&nbsp;&lt;cstdio&gt;<BR>int&nbsp;main(){<BR>while(!feof(stdin))<BR>fputc(getchar(),stderr);<BR>return&nbsp;0;<BR>}<BR>[/b]Mr.Phone原创 
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
<tr><td>int main(){
	long a,b;
	scanf("%ld %ld",&a,&b);/* Input two numbers.*/
	printf("%ld",a+b);//Output a+b.
	return 0;
}
</td><td>71
</td></tr></table>
