<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="font-family: arial, verdana, helvetica, sans-serif; font-variant: normal; font-weight: normal;"> 在实现程序自动分析的过程中,常常需要判定一些约束条件是否能被同时满足。</p><p>考虑一个约束满足问题的简化版本：假设x1,x2,x3,…代表程序中出现的变量，给定n个形如xi=xj或xi≠xj的变量相等/不等的约束条件，请判定是否可以分别为每一个变量赋予恰当的值，使得上述所有约束条件同时被满足。例如，一个问题中的约束条件为：x1=x2，x2=x3，x3=x4，x1≠x4，这些约束条件显然是不可能同时被满足的，因此这个问题应判定为不可被满足。</p><p>现在给出一些约束满足问题，请分别对它们进行判定。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="font-family: arial, verdana, helvetica, sans-serif; font-variant: normal; font-weight: normal;">输入文件的第1行包含1个正整数t，表示需要判定的问题个数。注意这些问题之间是相互独立的。</p><p>对于每个问题，包含若干行：</p><p>第1行包含1个正整数n，表示该问题中需要被满足的约束条件个数。</p><p>接下来n行，每行包括3个整数i,j,e，描述1个相等/不等的约束条件，相邻整数之间用单个空格隔开。若e=1，则该约束条件为xi=xj；若e=0，则该约束条件为xi≠xj。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="font-family: arial, verdana, helvetica, sans-serif; color: rgb(0, 0, 0); font-size: 18px; font-style: normal; font-variant: normal; font-weight: normal; letter-spacing: normal; line-height: normal; orphans: auto; text-align: left; text-indent: 0px; text-transform: none; white-space: normal; widows: 1; word-spacing: 0px; -webkit-text-stroke-width: 0px;">输出文件包括t行。</p><p>输出文件的第k行输出一个字符串“YES”或者“NO”（不包含引号，字母全部大写），“YES”表示输入中的第k个问题判定为可以被满足，“NO”表示不可被满足。</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p><p>2</p><p>1 2 1</p><p>1 2 0</p><p>2</p><p>1 2 1</p><p>2 1 1<br>
</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>NO</p><p>YES<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style="font-family: arial, verdana, helvetica, sans-serif; font-variant: normal; font-weight: normal;">在第一个问题中，约束条件为：x1=x2,x1≠x2。这两个约束条件互相矛盾，因此不可被同时满足。</p><p><br style="font-family: arial, verdana, helvetica, sans-serif; font-variant: normal; font-weight: normal;"></p><p>在第二个问题中，约束条件为：x1=x2,x2=x1。这两个约束条件是等价的，可以被同时满足。</p><p><br style="font-family: arial, verdana, helvetica, sans-serif; font-variant: normal; font-weight: normal;"><br style="font-family: arial, verdana, helvetica, sans-serif; font-variant: normal; font-weight: normal;"></p><p>1≤n≤1000000</p><p><br style="font-family: arial, verdana, helvetica, sans-serif; font-variant: normal; font-weight: normal;"></p><p>1≤i,j≤1000000000</p><p><br></p>
</div>
</div>