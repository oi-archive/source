# 题目描述


<p>
<strong>【题目描述】</strong> 
</p>
<p>
7月17日是Mr.W的生日，ACM-THU为此要制作一个体积为N*π的M层，生日蛋糕，每层都是一个圆柱体。
</p>
<p>
设从下往上数第i(1&lt;=i&lt;=M)层蛋糕是半径为$R_i$, 高度为$H_i$的圆柱。当i&lt;M时，要求$R_i$&gt;$R_{i+1}$且$H_i$&gt;$H_{i+1}$。
</p>
<p>
<br/>
</p>
<p>
由于要在蛋糕上抹奶油，为尽可能节约经费，我们希望蛋糕外表面（最下一层的下底面除外）的面积Q最小。
</p>
<p>
令Q= S*π
</p>
<p>
请编程对给出的N和M，找出蛋糕的制作方案（适当的$R_i$和$H_i$的值），使S最小。
</p>
<p>
（除Q外，以上所有数据皆为正整数）
</p>
<p>
<img alt="" src="/upload/image/20181022/20181022192611_61098.png"/> 
</p>
<p>
<strong>【输入输出格式】</strong> 
</p>
<p>
<strong>输入格式：</strong> 
</p>
<p>
有两行，第一行为N（N&lt;=20000），表示待制作的蛋糕的体积为Nπ；第二行为M(M&lt;=15)，表示蛋糕的层数为M。
</p>
<p>
<br/>
</p>
<p>
<strong>输出格式：</strong> 
</p>
<p>
仅一行，是一个正整数S（若无解则S=0）。
</p>
<p>
<br/>
</p>
<p>
<strong>【输入输出样例】</strong> 
</p>
<p>
<strong>输入样例：</strong> 
</p>
<p>
100
</p>
<p>
2
</p>
<p>
<br/>
</p>
<p>
<strong>输出样例：</strong> 
</p>
<p>
68
</p>
