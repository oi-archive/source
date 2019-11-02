<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一年一度的假面舞会又开始了，栋栋也兴致勃勃的参加了今年的舞会。 今年的面具都是主办方特别定制的。每个参加舞会的人都可以在入场时选择 一个自己喜欢的面具。每个面具都有一个编号，主办方会把此编号告诉拿该面具 的人。 为了使舞会更有神秘感，主办方把面具分为 k (k≥3)类，并使用特殊的技术将 每个面具的编号标在了面具上，只有戴第 i 类面具的人才能看到戴第 i+1 类面具 的人的编号，戴第 k 类面具的人能看到戴第 1 类面具的人的编号。 参加舞会的人并不知道有多少类面具，但是栋栋对此却特别好奇，他想自己 算出有多少类面具，于是他开始在人群中收集信息。 栋栋收集的信息都是戴第几号面具的人看到了第几号面具的编号。如戴第 2 号面具的人看到了第 5 号面具的编号。栋栋自己也会看到一些编号，他也会根据 自己的面具编号把信息补充进去。 由于并不是每个人都能记住自己所看到的全部编号，因此，栋栋收集的信息 不能保证其完整性。现在请你计算，按照栋栋目前得到的信息，至多和至少有多 少类面具。由于主办方已经声明了 k≥3，所以你必须将这条信息也考虑进去。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件 party.in 第一行包含两个整数 n, m，用一个空格分隔，n 表示主办 方总共准备了多少个面具，m 表示栋栋收集了多少条信息。 接下来 m 行，每行为两个用空格分开的整数 a, b，表示戴第 a 号面具的人看 到了第 b 号面具的编号。相同的数对 a, b 在输入文件中可能出现多次。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件 party.out 包含两个数，第一个数为最大可能的面具类数，第二个数 为最小可能的面具类数。如果无法将所有的面具分为至少 3 类，使得这些信息都 满足，则认为栋栋收集的信息有错误，输出两个-1。&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【输入样例一】 <br>6 5 1 2 2 3 3 4 4 1 3 5 <br>【输入样例二】 <br>3 3 1 2 2 1 2 3 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">【输出样例一】 </span><br>4 4 <br>【输出样例二】 <br>-1 -1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>50%的数据，满足 n ≤ 300, m ≤ 1000；</p>
<p>100%的数据，满足 n ≤ 100000, m ≤ 1000000。 </p>
</div>
</div>