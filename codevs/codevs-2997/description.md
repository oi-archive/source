<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>经过千辛万苦小 A 得到了一块切糕，切糕的形状是长方体，小 A 打算拦腰将切糕切成两半分给小 B。出于美观考虑，小 A 希望切面能尽量光滑且和谐。于是她找到你，希望你能帮她找出最好的切割方案。 <br>出于简便考虑，我们将切糕视作一个长 P、宽 Q、高 R 的长方体点阵。我们将位于第 z层中第 x 行、第 y 列上(1≤x≤P, 1≤y≤Q, 1≤z≤R)的点称为(x,y,z)，它有一个非负的不和谐值 v(x,y,z)。一个合法的切面满足以下两个条件： <br>1. 与每个纵轴(一共有 P*Q 个纵轴)有且仅有一个交点。即切面是一个函数 f(x,y)，对于所有 1≤x≤P, 1≤y≤Q,我们需指定一个切割点 f(x,y),且 1≤f(x,y)≤R。 <br>2. 切面需要满足一定的光滑性要求，即相邻纵轴上的切割点不能相距太远。对于所有的 1≤x,x’≤P 和 1≤y,y’ ≤Q，若|x-x’|+|y-y’|=1，则|f(x,y)-f(x’,y’)| ≤D，其中 D 是给定的一个非负整数。 <br>可能有许多切面f 满足上面的条件，小A 希望找出总的切割点上的不和谐值最小的那个，即 ∑v(x,y, f(x,y))最小。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件第一行是三个正整数P,Q,R，表示切糕的长P、宽Q、高R。第二行有一个非负整数D，表示光滑性要求。接下来是R个P行Q列的矩阵，第z个矩阵的第x行第y列是v(x,y,z) (1≤x≤P, 1≤y≤Q, 1≤z≤R)。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出仅包含一个整数，表示在合法基础上最小的总不和谐值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>input1<br>2 2 2 <br>1 <br>6 1 <br>6 1 <br>2 6 <br>2 6 <br>input2 <br>2 2 2 <br>0 <br>5 1 <br>5 1 <br>2 5 <br>2 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>output1<br>6 <br>output2<br>12</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>100%的数据满足P,Q,R≤40，0≤D≤R，且给出的所有的不和谐值不超过1000。 </p>
</div>
</div>