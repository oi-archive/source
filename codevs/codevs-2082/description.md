<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    最近在生物实验室工作的小 T 遇到了大麻烦。 <br>    由于实验室最近升级的缘故，他的分格实验皿是一个长方体,其尺寸为 a*b*c，a、b、c均为正整数。为了实验的方便，它被划分为 a*b*c 个单位立方体区域，每个单位立方体尺寸为 1*1*1。用(i,j,k)标识一个单位立方体，1≤i≤a，1≤j≤b，1≤k≤c。这个实验皿已经很久没有人用了，现在，小 T 被导师要求将其中一些单位立方体区域进行消毒操作（每个区域可以被重复消毒）。而由于严格的实验要求，他被要求使用一种特定的 F 试剂来进行消毒。</p>
<p>    这种 F 试剂特别奇怪，每次对尺寸为 x*y*z 的长方体区域（它由 x*y*z 个单位立方体组成）进行消毒时，只需要使用 min{x,y,z}单位的 F 试剂。F 试剂的价格不菲，这可难倒了小T。现在请你告诉他，最少要用多少单位的 F 试剂。(注：min{x,y,z}表示 x、y、z 中的最小者。)</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    输入文件第一行是一个正整数D，表示数据组数。 <br>    接下来是D组数据，每组数据开头是三个数a,b,c表示实验皿的尺寸。接下来会出现a个b行c列的用空格隔开的01矩阵，0表示对应的单位立方体不要求消毒，1表示对应的单位立方体需要消毒；例如，如果第1个01矩阵的第2行第3列为1，则表示单位立方体(1,2,3)需要被消毒。 <br>    输入保证满足a*b*c≤5000,T≤3。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; 仅包含 D 行，每行一个整数，表示对应实验皿最少要用多少单位的 F 试剂。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1 <br>4 4 4 <br>1 0 1 1 <br>0 0 1 1 <br>0 0 0 0 <br>0 0 0 0 <br>0 0 1 1 <br>1 0 1 1 <br>0 0 0 0 <br>0 0 0 0 <br>0 0 0 0 <br>0 0 0 0 <br>1 0 0 0 <br>0 0 0 0 <br>0 0 0 0 <br>0 0 0 0 <br>0 0 0 0 <br>1 0 0 0</p>

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
<p>对于区域(1,1,3)-(2,2,4)和(1,1,1)-(4,4,1)消毒，分别花费2个单位和1个单位的F试剂。</p>
</div>
</div>