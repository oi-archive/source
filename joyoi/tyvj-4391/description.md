# 

 
 # 题目背景 
<p>wangyurzee是一名蒟蒻。</p>

<p>植树节就要到了，wangyurzee却仍苦逼地被埋在作业海中。他遇到了一道奇难无比的数学作业。</p> 

 
 # 题目描述 
<p>题目是这样的，给定一个数列H，定义如下：</p>

<p>H(0)=0</p>

<p>H(0)=0</p>

<p>H(1)=C</p>

<p>H(i)=H(i-1)+H(i-2)&nbsp;(i&gt;=2)</p>

<p>给定A,B,C,L，求下列式子的值（如果你看不懂下面的这个叫做sigma的求和符号，你可以自行百度/google，也可以结合样例食用。）</p>

<p><img alt="" src="data:image/png;base64,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" style="width: 283px; height: 125px;" /></p>

<p>蒟蒻wangyurzee一脸懵逼，不知所措，他只好向你求助，为了方便起见，你只需要输出答案对1000000007（10^9+7，一个质数）取模的结果。作为报酬，他能让你在tyvj的3月月赛中多得100分。</p>

<p>wangyurzee有好几道这样的题目，所以本题有多组数据。</p> 

 
 # 输入格式 
<p>第1行为一个正整数T，表示数据组数。</p>

<p>第2行开始的T行，每行4个非负整数A,B,C,L，意义与题目描述一致。</p> 

 
 # 输出格式 
<p>对于每组数据输出一行，即所求式子mod&nbsp;1000000007的结果。</p> 

 
 # 提示 
<p>【样例说明】</p>

<p>对于第一组数据，H(1)=1，H(2)=1，答案为H(1)*H(2)=1</p>

<p>对于第二组数据，H(1)=3，H(3)=6，H(5)=15，H(6)=24，H(8)=63，H(10)=165，答案为H(5)*H(10)-H(3)*H(8)+H(1)*H(6)=2169</p>

<p>对于第三组数据，答案为H(8)*H(8)-H(6)*H(6)+H(4)*H(4)-H(2)*H(2)+H(0)*H(0)=&nbsp;111265</p>

<p>【数据范围】</p>

<p>对于10%的数据，A,B&lt;=100,000；</p>

<p>对于30%的数据，L&lt;=50,000；</p>

<p>对于另外20%的数据，|A-B|&lt;=1；</p>

<p>对于100%的数据，A,B&lt;=10^18；</p>

<p>对于100%的数据，T&lt;=10，C&lt;1000000007，2*L&lt;=A,B。</p>

<p>【出题人的话】</p>

<p>祝大家AK愉快！</p> 
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
<tr><td>4
1 2 1 0
5 10 3 2
8 8 17 4
6666 666 2333 233
</td><td>1
2169
111265
907571554
</td></tr></table>
