<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Lostmonkey费了好大劲才得到fsk公司基层流水线操作员的职位。流水线上有n个位置，从0到n-1依次编号，一开始的初始状态为：0号位置为空位，对0&lt;i&lt;n，i号位置上有编号为i的盒子。<br>Lostmonkey要按以下规则重新排列这些盒子。 <br>重新排列的规则由5个数q，p，m，d，s来描述，其中s表示要求s号位置最终为空位。为了确定所有盒子的最终位置，首先生成一个序列c，c0=0，ci+1=(ci*q+p) mod m。然后从编号为1的盒子开始按编号从小到大的顺序依次生成每个盒子的最终位置直到给编号为n-1的盒子生成最终位置。假设编号为i的盒子最终被放到posi号位置，那么posi=(ci+d*xi+yi) mod n，其中xi和yi是为确保编号为i的盒子不与编号小于i的盒子放到相同位置而由你设定的非负整数，且posi不能为s。若有多个xi和yi满足要求，你必须选择最小的yi，在yi相同时必须选择最小的xi。 <br>这样，根据以上规则你可以确定所有盒子的最终位置，也就是终止状态。 <br>假设通过一次移动你可以把某个盒子移到空位上，移动后被移盒子原来所在位置变成空位。 <br>请问最少需要多少次移动才能把所有盒子从初始状态转换成终止状态？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件第一行是一个整数t，表示数据组数（每组数据描述一个要重新排列的问题） 。接下来从输入文件第二行开始有t组数据，每组数据只有一行，是用空格隔开的六个整数n，s，q，p，m，d，其含义如上所述。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>包含t行，第i行输出对输入中给出的第i个重新排列问题把所有盒子从初始状态转换成终止状态需要的最少移动次数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1 <br>8 3 5 2 7 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>输入的数据保证30%的数据满足n≤100。</p>
<p>100%的数据满足t≤20,n≤100000,s&lt;n。其余的所有数字均为不超过100000的正整数。</p>
</div>
</div>