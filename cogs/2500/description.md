# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<div>
<span style="font-size:12px;">HZOI的众人从教练那里拿到了一些橘子</span> 
</div>
<div>
<span style="font-size:12px;">一个橘子可以理解为一个长度为T的程序</span> 
</div>
<div>
<span style="font-size:12px;">其中中橘子可以被定义如下:</span> 
</div>
<pre class="prettyprint lang-css">from __this__ program module::
from stdlibrary program moudle::
from stdio program moudle::
object long c=0;
object long[] A=new long[N];
function:object long redescribe(object long l,object long r)
begin
	object long x=A[l],i=l-1,j=r+1,t;
	while(true)
	begin
		do begin --j;++c; end while(A[j]&gt;x);
		do begin ++i;++c; end while(A[i]&lt;x);
		if(i&lt;j) &lt;stdlibrary.algorithm&gt;swap((quote)A[i],(quote)B[i]),
		else exitwith j;
	end;
end;
function:const void describe(object long l,object long r)
begin
	object long N;
	if(l&lt;r)
	begin
		N=redescribe(l,r);
		describe(l,N);
		describe(N+1,r);
	end;
end;
ENTRANCE object report Main(const void 0)
begin
	
	object long N=__debuger_next_long();
	A[1:]=&lt;stdio&gt;input([range(N)]);
	describe(1,N);
	if(c==(N*N+3*N-4)/2)output(&#34;Chinese inland!&#34;),
	else output(&#34;Table in table with chairman table!&#34;);
	report  &#34;completed&#34;;
end;
reset ::stdio
reset ::stdlibrary
reset ::__this__</pre>
<p>
<span style="font-size:12px;"> 给出N以及长度为N的数组A,输出其能让橘子报告&#34;Chinese inland!&#34;的新数组排列。</span> 
</p>
<h3>
【输入格式】
</h3>
<p>
第一行表示测试数据的组数K
</p>
<p>
然后接下来K组测试数据
</p>
<p>
每组第一行一个整数N
</p>
<p>
    然后一行N个数描述了数组A
</p>
<h3>
【输出格式】
</h3>
<p>
对于每组测试数据输出一行,为原数组中的各个数重新排列后的能使橘子输出&#34;Chinese inland&#34;的新数组的各个数在原数组中的下标
</p>
<h3>
【样例输入】
</h3>
<p>
Test case 1
</p>
<p>
2
</p>
<p>
5 9
</p>
<h3>
【样例输出】
</h3>
<p>
2 1
</p>
<p>
<br/>
</p>
<h3 style="font-family:sans-serif;font-size:20px;background-color:#F0F8FF;">
【解释】
</h3>
<p style="font-family:serif;font-size:16px;">
输入中只有1组测试数据.....(K=1)
</p>
<p style="font-family:serif;font-size:16px;">
第1组测试数据的包含2个数.....(N=2)
</p>
<p style="font-family:serif;font-size:16px;">
这两个数分别为5与⑨.....(i=1,i=2)
</p>
<p style="font-family:serif;font-size:16px;">
经运算,得到新数组应为9 5.其原本的序号为2 1.....(i=2,i=1)
</p>
<p>
<br/>
</p>
<h3>
【提示】
</h3>
<p>
0＜K≤5
</p>
<p>
0≤N≤500000
</p>
<p>
数组中的各个数均在int(python)范围内事实上<span style="color:#CCCCCC;">是在pascal int64范围内</span> 
</p>
<h3>
【来源】
</h3>
<p>
Ural 1082
</p>
