<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>《思远高考绿色通道》(Green Passage, GP)是唐山一中常用的练习册之一，其题量之大深受lsz等许多oiers的痛恨，其中又以数学绿色通道为最。2007年某月某日，soon-if (数学课代表)，又一次宣布收这本作业，而lsz还一点也没有写……</p>
<p> </p>
<p>高二数学《绿色通道》总共有n道题目要写(其实是抄)，编号1..n，抄每道题所花时间不一样，抄第i题要花a[i]分钟。由于lsz还要准备NOIP，显然不能成天写绿色通道。lsz决定只用不超过t分钟时间抄这个，因此必然有空着的题。每道题要么不写，要么抄完，不能写一半。一段连续的空题称为一个空题段，它的长度就是所包含的题目数。这样应付自然会引起马老师的愤怒。马老师发怒的程度(简称发怒度)等于最长的空题段长度。</p>
<p>现在，lsz想知道他在这t分钟内写哪些题，才能够尽量降低马老师的发怒度。由于lsz很聪明，你只要告诉他发怒度的数值就可以了，不需输出方案。(快乐融化：那么lsz怎么不自己写程序？lsz：我还在抄别的科目的作业……)</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为两个整数n,t，代表共有n道题目，t分钟时间。</p>
<p>以下一行，为n个整数，依次为a[1], a[2],... a[n]，意义如上所述。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅一行，一个整数w，为最低的发怒度。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>17 11</p>
<p>6 4 5 2 5 3 4 5 2 3 4 5 2 3 6 3 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>60%数据 n&lt;=2000</p>
<p>100%数据 0&lt;n&lt;=50000，0&lt;a[i]&lt;=3000，0&lt;t&lt;=100000000</p>
</div>
</div>