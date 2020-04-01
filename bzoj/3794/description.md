
# Description

<div class="content"><div>Ertanis一直谋划着送给XXX很多很多糖果。</div>
<div>经过了很久的准备后，Ertanis共买好了k种不同口味的糖果，共计n包，每包均有10^s（0&lt;=s&lt;=2）颗糖果，且这n包现在杂乱的在桌面上排成一排。由于种种奇葩原因，Ertanis每次只会选择连在一起的同种糖果送给XXX， 而XXX则会一颗一颗很快把得到的糖果吃完。不幸的是，由于量子理论的扰动，对于第i种糖果的每一颗均有Ci的概率不好吃。但糖果本身还是很对XXX胃口的，若XXX在吃到难吃糖果或吃完了Ertanis这次送的所有糖果时已连续吃了k颗好的第i种糖果，可得到k^Pi的快乐指数（1&lt;=Pi&lt;=4）。</div>
<div>自然，Ertanis希望糖果给XXX带来的快乐指数越大越好，但他是一个蒟蒻，对此完全没有一点头绪，就只好请你帮他算出采用最优方案时糖果所能带来的快乐指数的期望值。算完后Ertanis会给你100颗Ci=1的糖果作为奖励。</div>
<p></p></div>

# Input

<div class="content"><div>    第一行两个整数n，k， 表示糖果总数和口味数。</div>
<div>    第二行n个整数Gi（1&lt;=Gi&lt;=k）,表示第i颗糖的口味。</div>
<div>    第3～k+2行，每行先给出一个整数Pi，然后是一个实数Ci，含义如描述中所示。 </div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>      一个实数， 表示Ertanis采用最优方案时快乐指数的期望值，保留至小数点后3位。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">【输入样例1】<br/>
3 2 0<br/>
1 2 1<br/>
2 0.5<br/>
1 0.4<br/>
<br/>
【输入样例2】<br/>
5 2 0<br/>
1 2 1 2 1<br/>
4 0.5<br/>
2 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">【输出样例1】<br/>
2.100<br/>
<br/>
【输出样例2】<br/>
16.750<br/>
</span></div>

# Hint

<div class="content"><p></p><div></div><br/>
<div>样例解释：</div><br/>
<div>第一组样例中最优方案是先寄出第2颗糖，期望为0.6，序列变为{1,1}，再将剩下的全部寄出，期望为（4+1+1+0）/4=1.5，故总期望为2.1</div><br/>
<div>第二组样例中最优方案为先寄出第2颗糖，期望1.0，序列变为{1,1,2,1}，再寄出第3颗糖，期望1.0，序列变为{1,1,1}，最后将剩下的全部寄出，期望为（81+16+16+2+1+1+1+0）/8=14.75，故总期望为16.75</div><br/>
<div>【数据范围】</div><br/>
<div>    对于30%数据保证k=1</div><br/>
<div>对于另外40%的数据保证对任意Ci(1&lt;=i&lt;=k)存在Ci = 0 或 Ci=1</div><br/>
<div>对于100%的数据保证  1&lt;=n&lt;=200  ,  1&lt;=k&lt;=max(n,15) ， 数据中所有实数小数部分不超过2位</div><br/>
<div>数据不保证每种糖果都出现</div><br/>
<div>数据保证任意糖果总数量均不大于50000</div><br/>
<div>保证答案不大于10^15</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

