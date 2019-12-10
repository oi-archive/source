<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>HNSDFZ<span style="">的同学们为了庆祝春节，准备排练一场舞会。 </span><br>表演者排成<span style="font-family: 'Times New Roman';">n</span><span style="">排，构成一个向前的正三角形（在屏幕上，即向下）。而就每个人，他有可能正面朝前（小的向前正三角形）、或向后三角形（小的向后正三角形）。 </span></p>
<p> </p>
<p>然而这些人在服装上有明显区别<span style="font-family: 'Times New Roman';">——</span><span style="">一部分穿冬季校服，其他的穿夏季校服。 </span><br>现在给出每个人的着衣情况，请你求穿夏季校服的同学所构成的最大正三角形，输出所含人数。 </p>

<img src="/source/codevs/codevs-1848/img/aHR0cDovL2NvZGV2cy5jbi9tZWRpYS9pbWFnZS9wcm9ibGVtLzE4NDguZ2lm.gif" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一排为<span style="font-family: 'Times New Roman';">n</span><span style="">。</span><br>接下来<span style="font-family: 'Times New Roman';">n</span><span style="">排，第</span><span style="font-family: 'Times New Roman';">i</span><span style="">排有</span><span style="font-family: 'Times New Roman';">2*i-1</span><span style="">个有效字符（</span><span style="font-family: 'Times New Roman';">“#”</span><span style="">或</span><span style="font-family: 'Times New Roman';">“-”</span><span style="">，分别表示此同学穿冬季校服或穿夏季校服）。输入文件中出现空格，且空格只是为了保持整个三角</span><span style="">形的形状。 </span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出人数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p>
<p>#-##----#</p>
<p> -----#-</p>
<p>  ---#-</p>
<p>   -#-</p>
<p>    -</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>n</span><span>＜</span><span>=100</span></p>
</div>
</div>