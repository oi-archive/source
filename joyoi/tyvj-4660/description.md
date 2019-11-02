# 

 
 # 题目描述 
<p>豆豆从小对数字很敏感，小学里就显露出超常的能力，老师为了防止他太过骄傲，给了他一个可怕的难题：求一串给定整数某一段的平均值，保留3位小数。每个整数都是小于2^31的。老师做梦也没想到豆豆全都回答出来了，原来豆豆有一个擅长编程的朋友你。</p> 

 
 # 输入格式 
<p>第一行一个整数N(1&lt;=N&lt;=100000)，表示一串整数的个数&nbsp;第二行用空格隔开的N个非负整数&nbsp;第三行一个整数M(1&lt;=M&lt;=100000)，表示M次询问&nbsp;接下来M行，每行两个整数i和j(1&lt;=i,j&lt;=N)，表示询问第i个到第j个整数的平均值，不保证i&lt;j</p> 

 
 # 输出格式 
<p>M行，每行一个小数，表示平均值</p> 

 
 # 提示 
<p>【样例输入1】</p>

<p><span style="line-height: 1.6em;">&nbsp;5&nbsp;</span></p>

<p>&nbsp;0&nbsp;25&nbsp;0&nbsp;23&nbsp;2</p>

<p>&nbsp;1</p>

<p>&nbsp;1&nbsp;5</p>

<p>【样例输出1】</p>

<p>&nbsp;10.000</p>

<p>【样例输入2】</p>

<p>&nbsp;3</p>

<p>&nbsp;40&nbsp;60&nbsp;100</p>

<p>&nbsp;2</p>

<p>&nbsp;1&nbsp;3</p>

<p><span style="line-height: 1.6em;">&nbsp;2&nbsp;3&nbsp;</span></p>

<p><span style="line-height: 1.6em;">【</span><span style="line-height: 1.6em;">样例输出2】&nbsp;</span></p>

<p><span style="line-height: 1.6em;">&nbsp;66.667&nbsp;</span></p>

<p><span style="line-height: 1.6em;">&nbsp;80.000</span></p>

<p>【数据范围】&nbsp;80%的数据保证N&lt;=1000,每个整数Ai(0&lt;=Ai&lt;=1000000)&nbsp;100%的数据保证N个整数和小于2^63</p> 
