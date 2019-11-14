<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">    给定一张n<span style="">个顶点m<span style="">条边的无向图(顶点编号为 1,2,<span style="">…,n)，每条边上带有权值。所有权值都<br>可以分解成<span style="">2<sup>a</sup>3<sup>b</sup>的形式。<br>    现在有q<span style="">个询问，每次询问给定四个参数<span style="">u、v<span style="">、a<span style="">和b<span style="">，请你求出是否存在一条顶点u<span style="">到v<span style="">之<br>间的路径，使得路径依次经过的边上的权值的最小公倍数为<span style="">2</span><sup style="">a</sup><span style="">3</span><sup style="">b</sup><span style="">。注意：路径可以不是简单路<br>径。<br>下面是一些可能有用的定义：<br>最小公倍数：k<span style="">个数a<sub><span style="">1</span></sub><span style="">,a<sub>2</sub>,…,a<sub>k</sub>的最小公倍数是能被每个a<sub>i</sub><span style="">整除的最小正整数。<br>路径：路径P<span style="">:p<sub>1</sub>,p<sub>2</sub>,…,p<sub>k</sub>是顶点序列，满足对于任意<span style="">1≤i&lt;k，节点p<sub>i</sub><span style="">和p<sub>i<span style="">+1</span></sub><span style="">之间都有边相连。<br>简单路径：如果路径<span style="">P:p<sub>1</sub>,p<sub>2</sub>,…,p<sub>k</sub>中，对于任意<span style="">1≤s≠t≤k都有p<sub>s</sub><span style="">≠p<sub>t</sub>，那么称路径P<span style="">为简单路径。</span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">输入文件的第一行包含两个整数n<span style=""><span style="">和m,<span style=""><span style="">分别代表图的顶点数和边数。<br>接下来m<span style=""><span style="">行，每行包含四个整数u<span style=""><span style="">、v<span style=""><span style="">、a<span style=""><span style="">和b<span style=""><span style="">，代表一条顶点u<span style=""><span style="">和v<span style=""><span style="">之间、 权值为<span style="">2</span><sup style="">a</sup><span style="">3</span><sup style="">b</sup><span style=""><span style=""><span style=""><span style="">的边。<br>接下来一行包含一个整数q<span style=""><span style="">，代表询问数。<br>接下来q<span style=""><span style="">行，每行包含四个整数<span style=""><span style="">u</span><span style=""><span style="">、v<span style=""><span style="">、a<span style=""><span style="">和b,</span></span></span></span></span></span><span style=""><span style=""><span style=""><span style=""><span style=""><span style=""><span style="">代表一次询问。询问内容请参见问题描述。</span></span></span><br style=""></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 宋体; font-size: 10pt;">对于每次询问，如果存在满足条件的路径，则输出一行 <span style="font-size: 10pt;">Yes<span style="font-size: 10pt;">，否则输出一行 <span style="font-size: 10pt;">No<span style="font-size: 10pt;">（ 注意： 第<br/><span style="font-size: 10pt;">一个字母大写， 其余字母小写）。</span><br style="orphans: 2; text-align: -webkit-auto; white-space: normal; widows: 2;"/></span></span></span></span></span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">4 5<br><span style="">1 2 0 3<br><span style="">1 3 0 2<br><span style="">1 4 2 0<br><span style="">2 4 3 2<br><span style="">3 4 2 2<br><span style="">5<br><span style="">1 4 3 3<br><span style="">4 2 2 3<br><span style="">1 3 2 2<br><span style="">2 3 2 2<br><span style="">1 3 4 4</span></span></span></span></span></span></span></span></span></span></span><br style=""></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">Yes<br><span style="">Yes<br><span style="">Yes<br><span style="">No<br><span style="">No</span></span></span></span><br style=""></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">样例解释</span></p><p><span style=""><br></span></p><p><span style="">在第一个询问中，一条可行的路径为</span><span style="">1 − 2 − 4</span><span style="">。</span><br></p><p><span style="">在第二个询问中，一条可行的路径为4 − 3 − 1 − 2。<br>在第三个询问中，一条可行的路径为1 − 4 − 1 − 3。</span><span style=""><br style=""></span></p><p><span style=""><br></span></p><p><span style=""><span style="">对于所有测试数据， <span style="font-family: 'Cambria Math';">1 ≤ </span></span></span></p>
</div>
</div>