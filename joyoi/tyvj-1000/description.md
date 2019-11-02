# 

 
 # 题目背景 
<p>为大家熟悉本系统创建本题！<br />
请千万注意，Tyvj所有题目不需要加文件，加文件操作会导致您0分！</p> 

 
 # 题目描述 
<p>输入两个自然数，输出他们的和<br />
&nbsp;</p> 

 
 # 输入格式 
<p>输出两个自然数&nbsp;x,y<br />
&nbsp;</p> 

 
 # 输出格式 
<p>一个数，即x和y的和<br />
&nbsp;</p> 

 
 # 提示 
<p>请千万注意，Tyvj所有题目不需要加文件！</p>

<p><b style="font-size: 13.3333px; line-height: 21.3333px;">C&nbsp;Code:</b><br style="font-size: 13.3333px; line-height: 21.3333px;" />
<span style="font-size: 13.3333px; line-height: 21.3333px;">-------------------</span></p>

<p><span class="hljs-preprocessor" style="color: rgb(153, 153, 153); font-weight: bold; font-family: monospace; font-size: 13.3333px; line-height: 20px; white-space: pre;">#<span class="hljs-keyword" style="color: rgb(51, 51, 51);">include</span>&lt;stdio.h&gt;</span><span style="font-family: monospace; font-size: 13.3333px; line-height: 20px; white-space: pre; background-color: rgb(248, 248, 248);">&nbsp;</span></p>

<p><span class="hljs-keyword" style="font-weight: bold; font-family: monospace; font-size: 13.3333px; line-height: 20px; white-space: pre;">int</span><span style="font-family: monospace; font-size: 13.3333px; line-height: 20px; white-space: pre; background-color: rgb(248, 248, 248);">&nbsp;main(){&nbsp;</span></p>

<p><span class="hljs-keyword" style="font-weight: bold; font-family: monospace; font-size: 13.3333px; line-height: 20px; white-space: pre;">int</span><span style="font-family: monospace; font-size: 13.3333px; line-height: 20px; white-space: pre; background-color: rgb(248, 248, 248);">&nbsp;a,b;&nbsp;</span></p>

<p><span class="hljs-built_in" style="color: rgb(0, 134, 179); font-family: monospace; font-size: 13.3333px; line-height: 20px; white-space: pre;">scanf</span><span style="font-family: monospace; font-size: 13.3333px; line-height: 20px; white-space: pre; background-color: rgb(248, 248, 248);">(</span><span class="hljs-string" style="color: rgb(221, 17, 68); font-family: monospace; font-size: 13.3333px; line-height: 20px; white-space: pre;">&quot;%d&nbsp;%d&quot;</span><span style="font-family: monospace; font-size: 13.3333px; line-height: 20px; white-space: pre; background-color: rgb(248, 248, 248);">,&amp;a,&amp;b);&nbsp;</span></p>

<p><span class="hljs-built_in" style="color: rgb(0, 134, 179); font-family: monospace; font-size: 13.3333px; line-height: 20px; white-space: pre;">printf</span><span style="font-family: monospace; font-size: 13.3333px; line-height: 20px; white-space: pre; background-color: rgb(248, 248, 248);">(</span><span class="hljs-string" style="color: rgb(221, 17, 68); font-family: monospace; font-size: 13.3333px; line-height: 20px; white-space: pre;">&quot;%d&quot;</span><span style="font-family: monospace; font-size: 13.3333px; line-height: 20px; white-space: pre; background-color: rgb(248, 248, 248);">,a+b);</span></p>

<p><span class="hljs-keyword" style="font-weight: bold; font-family: monospace; font-size: 13.3333px; line-height: 20px; white-space: pre;">return</span><span style="font-family: monospace; font-size: 13.3333px; line-height: 20px; white-space: pre; background-color: rgb(248, 248, 248);">&nbsp;</span><span class="hljs-number" style="color: rgb(0, 128, 128); font-family: monospace; font-size: 13.3333px; line-height: 20px; white-space: pre;">0</span><span style="font-family: monospace; font-size: 13.3333px; line-height: 20px; white-space: pre; background-color: rgb(248, 248, 248);">;&nbsp;</span></p>

<p><span style="font-family: monospace; font-size: 13.3333px; line-height: 20px; white-space: pre; background-color: rgb(248, 248, 248);">}</span><br />
<b>Free&nbsp;Pascal&nbsp;Code:</b><br />
-------------------<br />
var&nbsp;a,b:longint;<br />
begin<br />
&nbsp;&nbsp;readln(a,b);<br />
&nbsp;&nbsp;writeln(a+b);<br />
end.<br />
<br />
<b>C++&nbsp;Code:</b><br />
-------------------<br />
#include&nbsp;&lt;iostream&gt;<br />
using&nbsp;namespace&nbsp;std;<br />
int&nbsp;main(){<br />
&nbsp;&nbsp;int&nbsp;a,b;<br />
&nbsp;&nbsp;cin&gt;&gt;a&gt;&gt;b;<br />
&nbsp;&nbsp;cout&lt;&lt;a+b&lt;&lt;endl;<br />
&nbsp;&nbsp;return&nbsp;0;<br />
}<br />
<br />
<b>C++&nbsp;with&nbsp;Boost&nbsp;Code:</b><br />
-------------------<br />
#include&nbsp;&lt;iostream&gt;<br />
#include&nbsp;&lt;boost/multiprecision/cpp_int.hpp&gt;<br />
<br />
using&nbsp;namespace&nbsp;std;<br />
using&nbsp;namespace&nbsp;boost::multiprecision;<br />
<br />
int&nbsp;main()<br />
{<br />
&nbsp;&nbsp;&nbsp;&nbsp;cpp_int&nbsp;a,&nbsp;b;<br />
&nbsp;&nbsp;&nbsp;&nbsp;cin&gt;&gt;a&gt;&gt;b;<br />
&nbsp;&nbsp;&nbsp;&nbsp;cout&lt;&lt;a+b&lt;&lt;endl;<br />
}<br />
<br />
<b>Java&nbsp;Code:</b><br />
-------------------<br />
import&nbsp;java.util.*;<br />
<br />
public&nbsp;class&nbsp;Main&nbsp;{<br />
&nbsp;&nbsp;public&nbsp;static&nbsp;void&nbsp;main(String[]&nbsp;args)&nbsp;{<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Scanner&nbsp;reader=new&nbsp;Scanner(System.in);<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;int&nbsp;a,b;<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a=reader.nextInt();<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b=reader.nextInt();<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;System.out.println(a+b);<br />
&nbsp;&nbsp;}<br />
}<br />
<br />
<b>Python&nbsp;2.7&nbsp;Code:</b><br />
-------------------<br />
import&nbsp;sys&nbsp;<br />
for&nbsp;line&nbsp;in&nbsp;sys.stdin:&nbsp;<br />
&nbsp;&nbsp;&nbsp;&nbsp;a&nbsp;=&nbsp;line.split()&nbsp;<br />
&nbsp;&nbsp;&nbsp;&nbsp;print&nbsp;int(a[0])&nbsp;+&nbsp;int&nbsp;(a[1])<br />
&nbsp;</p> 
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
<tr><td>123 500

</td><td>623

</td></tr></table>
