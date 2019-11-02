<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Hanks 博士是BT (Bio-Tech，生物技术) 领域的知名专家。现在，他正在为一个细胞实验做准备工作：培养细胞样本。<br>Hanks 博士手里现在有N 种细胞，编号从1~N，一个第i 种细胞经过1 秒钟可以分裂为Si 个同种细胞（Si 为正整数）。现在他需要选取某种细胞的一个放进培养皿，让其自由分裂，进行培养。一段时间以后，再把培养皿中的所有细胞平均分入M 个试管，形成M 份样本，用于实验。Hanks 博士的试管数M 很大，普通的计算机的基本数据类型无法存储这样大的M 值，但万幸的是，M 总可以表示为m1 的m2 次方，即M = m1^ m2 ，其中m1，m2 均为基本数据类型可以存储的正整数。<br>注意，整个实验过程中不允许分割单个细胞，比如某个时刻若培养皿中有4 个细胞，Hanks 博士可以把它们分入2 个试管，每试管内2 个，然后开始实验。但如果培养皿中有5个细胞，博士就无法将它们均分入2 个试管。此时，博士就只能等待一段时间，让细胞们继续分裂，使得其个数可以均分，或是干脆改换另一种细胞培养。<br>为了能让实验尽早开始，Hanks 博士在选定一种细胞开始培养后，总是在得到的细胞“刚好可以平均分入M 个试管”时停止细胞培养并开始实验。现在博士希望知道，选择哪种细胞培养，可以使得实验的开始时间最早。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>共有三行。<br>第一行有一个正整数 N，代表细胞种数。<br>第二行有两个正整数 m1，m2，以一个空格隔开， m1^ m2 即表示试管的总数M。<br>第三行有 N 个正整数，第i 个数Si 表示第i 种细胞经过1 秒钟可以分裂成同种细胞的个数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共一行，为一个整数，表示从开始培养细胞到实验能够开始所经过的最少时间（单位为秒）。<br />如果无论 Hanks 博士选择哪种细胞都不能满足要求，则输出整数-1。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1<br>2 1<br>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>-1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>经过 1 秒钟，细胞分裂成3 个，经过2 秒钟，细胞分裂成9 个，……，可以看出无论怎么分裂，细胞的个数都是奇数，因此永远不能分入2 个试管。</p>
</div>
</div>