<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>又是一节体育课的时间了，有n个同学排成了一排。他们都很讨厌排在第一个位置的同学，于是后面的同学中比第一个高的都会产生一个高兴值，这个高兴值等于他的身高减去第一个同学的身高。当然比第一个同学矮的同学产生兴奋值为0。</p>
<p>现在体育老师来了，他拥有神奇的魔法，现在他能做如下的三件事：</p>
<p>1：询问某段区间高兴值最大的那个是多少。</p>
<p>2：把某两个同学交换一下位置。</p>
<p>3：选取一段区间的人，把第一个人身高加上t，第二个加上2t，第三个加上3t以此类推。</p>
<p>但是体育老师不会数数，于是他找到你了，对于每一个询问，他要你帮他求出那个值。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个整数n,m表示有n个人，有m个操作。</p>
<p>第二行n个整数，顺序输入每个人的身高。（身高&lt;=10^8）</p>
<p>接下来m行，每行第一个数位一个type表示是做哪一件事情。</p>
<p>如果type=1，那么接下来有两个整数l，r，表示询问这段区间的最大的高兴值</p>
<p>如果Type=2，接下来两个整数a，b，表示交换这两个位置的人</p>
<p>如果type=3，接下来三个整数l,r,t，表示把l个人的升高增加t,l+1个人增加2t…第r个人增加(r-l+1)t, (0&lt;=t&lt;= 10000)</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">对于每个询问按照顺序输出每个操作1的答案。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6 8</p>
<p>109 827 100 530 10 826</p>
<p>3 1 6 1</p>
<p>2 2 6</p>
<p>1 2 4</p>
<p>1 2 3</p>
<p>2 2 6</p>
<p>1 2 6</p>
<p>1 2 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>431</p>
<p>0</p>
<p>817</p>
<p>431</p>
<p>719</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>有20%的数据：n,m&lt;=5000</p>
<p>另有10%的数据：没有第三种操作.</p>
<p>另有20%的数据: 没有第二种操作</p>
<p>对于100的数据：n,m&lt;=100000</p>
<p> </p>
</div>
</div>