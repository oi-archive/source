<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>&lt;font color="#4b4b4b" face="Verdana, Geneva, Arial, Helvetica, sans-serif" size="2"&gt;<span style="">(题目正在修改中，请勿交题)</span>&lt;/font&gt;</p><p><span style="font-family: Verdana, Geneva, Arial, Helvetica, sans-serif;">Astronomers often examine star maps where stars are represented by points on a plane and each star has Cartesian coordinates. Let the level of a star be an amount of the stars that are not higher and not to the right of the given star. Astronomers want to know the distribution of the levels of the stars. </span></p><p><span style="font-family: Verdana, Geneva, Arial, Helvetica, sans-serif;"><img src="/source/codevs/codevs-5307/img/aHR0cDovL3Bvai5vcmcvaW1hZ2VzLzIzNTJfMS5qcGc=.jpg"></span></p><p><span style="font-family: Verdana, Geneva, Arial, Helvetica, sans-serif;">For example, look at the map shown on the figure above. Level of the star number 5 is equal to 3 (it's formed by three stars with a numbers 1, 2 and 4). And the levels of the stars numbered by 2 and 4 are 1. At this map there are only one star of the level 0, two stars of the level 1, one star of the level 2, and one star of the level 3. </span><br style="font-family: Verdana, Geneva, Arial, Helvetica, sans-serif;"><br style="font-family: Verdana, Geneva, Arial, Helvetica, sans-serif;"><span style="font-family: Verdana, Geneva, Arial, Helvetica, sans-serif;">You are to write a program that will count the amounts of the stars of each level on a given map.</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: Verdana, Geneva, Arial, Helvetica, sans-serif;">The first line of the input file contains a number of stars N (1&lt;=N&lt;=15000). The following N lines describe coordinates of stars (two integers X and Y per line separated by a space, 0&lt;=X,Y&lt;=32000). There can be only one star at one point of the plane. Stars aren't listed in ascending order of Y coordinate. </span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(75, 75, 75); font-family: Verdana, Geneva, Arial, Helvetica, sans-serif; font-size: 13px; line-height: 19px; background-color: rgb(255, 255, 255);">The output should contain N lines, one number per line. The first line contains amount of stars of the level 0, the second does amount of stars of the level 1 and so on, the last line contains amount of stars of the level N-1.</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p><p>1 1</p><p>5 1</p><p>7 1</p><p>3 3</p><p>5 5</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p><p>2</p><p>1</p><p>1</p><p>0</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: Verdana, Geneva, Arial, Helvetica, sans-serif;">Range:</span></p><p><span style="font-family: Verdana, Geneva, Arial, Helvetica, sans-serif;">1&lt;=N&lt;=15000</span></p><p><span style="font-family: Verdana, Geneva, Arial, Helvetica, sans-serif;"><span style="font-family: Verdana, Geneva, Arial, Helvetica, sans-serif;">0&lt;=X,Y&lt;=32000</span></span></p><p><span style="font-family: Verdana, Geneva, Arial, Helvetica, sans-serif;"><span style="font-family: Verdana, Geneva, Arial, Helvetica, sans-serif;">HInt:</span></span></p><p><span style="font-family: Verdana, Geneva, Arial, Helvetica, sans-serif;"><span style="font-family: Verdana, Geneva, Arial, Helvetica, sans-serif;"><span style="font-family: 'Times New Roman', Times, serif;">This problem has huge input data,use scanf() instead of cin to read data to avoid time limit exceed.</span></span></span></p>
</div>
</div>