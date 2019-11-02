# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;Maple博士发明了一个对表达式进行操作的函数op(i,e)。其描述如下：<BR>&nbsp;&nbsp;&nbsp;&nbsp;e是要操作的表达式。函数要将表达式分成若干个优先级最低的子表达式。例如：a*b+b*c+c*d经操作后变成了三个式子a*b,b*c,c*d，因为‘+’的优先级是最低的。函数先要把表达式做如上分离，再按次序取其中的第i个式子。例&nbsp;如：op(2,a*b+b*c+c*d)=b*c.<BR>&nbsp;&nbsp;&nbsp;&nbsp;很显然，这个函数有时是层层调用的，如：<BR>&nbsp;&nbsp;&nbsp;&nbsp;p:=a^b*c+(d*c)^f*z+b<BR>&nbsp;&nbsp;&nbsp;&nbsp;op(1,op(1,op(2,p)))=(d*c)&nbsp;&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;op(1,op(1,op(1,op(2,p))))=d*c<BR>&nbsp;&nbsp;&nbsp;&nbsp;op(2,op(2,p))=z<BR>&nbsp;&nbsp;&nbsp;&nbsp;op(3,p)=b<BR>&nbsp;&nbsp;&nbsp;&nbsp;op(1,op(3,p))=b<BR>&nbsp;&nbsp;&nbsp;&nbsp;Maple博士很懒，他把这任务交给了你，让你编出一个程序。<BR>&nbsp;&nbsp;&nbsp;&nbsp;注：在本题中认为(a+b)(b+c)为合法表达式，若p:=(a+b)(b+c)则op(1,p)=a+b;而p:=(a+b)+(b+c)则op(1,p)=(a+b)<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;数据分为两部分，第一部分是表达式（不需判错）。先是一个变量的名称，再是一个":="符号，再是表达式。<BR>&nbsp;&nbsp;&nbsp;&nbsp;表达式由小写字母和"+",&nbsp;"(",&nbsp;")",&nbsp;"*",&nbsp;"^"组成。括号优先级最高，接下来就是"^",再下来是"*"，再是"+"。<BR>&nbsp;&nbsp;&nbsp;&nbsp;下面就是要你算的几个op函数。先是函数个数n。<BR>&nbsp;&nbsp;&nbsp;&nbsp;下面n行是op的形式描述，由整数组成。<BR>&nbsp;&nbsp;&nbsp;&nbsp;例如：2&nbsp;1&nbsp;1表示op(1,op(1,op(2,e)))。怎样计算呢？先算op(2,e)，再将结果带入下一步，算op(1,op(1,op(2,e))，再用同一方法算op(1,op(1,op(2,e)))。<BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;看样例。。。<BR> 

 
 # 提示 
英文原题<BR>http://acm.zju.edu.cn/show_problem.php?pid=1014<BR>Tsuzuki&nbsp;Matsumoto&nbsp;<BR>From&nbsp;ZJU<BR> 
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
<tr><td>p:=a^b*c+(d*c)^f*z+b
4
2 1 1
2 2
3
3 1
</td><td>Expression p:
op(1,op(1,op(2,p)))=(d*c)
op(2,op(2,p))=z
op(3,p)=b
op(1,op(3,p))=b
</td></tr></table>
