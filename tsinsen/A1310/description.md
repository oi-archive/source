<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　输入一个n*m的矩阵，矩阵的每一个元素都是一个整数，然后有q个询问，每次询问一个子矩阵的权值。矩阵的权值是这样定义的，对于一个整数x，如果它在该矩阵中出现了p次，那么它给该矩阵的权值就贡献p<sup>2</sup>。</div>
# 输入格式

<div class="pdcont">　　第一行两个整数n，m表示矩阵的规模。<br/>
　　接下来n行每行m个整数，表示这个矩阵的每个元素。<br/>
　　再下来一行一个整数q，表示询问个数。<br/>
　　接下来q行每行四个正整数x1，y1，x2，y2，询问以第x1行第y1列和第x2行第y2列的连线为对角线的子矩阵的权值。</div>
# 输出格式

<div class="pdcont">　　输出q行每行一个整数回答对应询问。</div>
# 样例输入

<div class="pddata">3 4<br/>
1 3 2 1<br/>
1 3 2 4<br/>
1 2 3 4<br/>
8<br/>
1 2 2 1<br/>
1 1 2 1<br/>
1 1 3 4<br/>
1 1 1 1<br/>
2 2 3 3<br/>
3 4 2 2<br/>
1 3 3 1<br/>
2 4 3 4</div>
# 样例输出

<div class="pddata">8<br/>
4<br/>
38<br/>
1<br/>
8<br/>
12<br/>
27<br/>
4</div>
# 数据规模和约定

<div class="pdcont">　　对于全部数据<br/>
　　1&lt;=n,m&lt;=200<br/>
　　q&lt;=100000<br/>
　　|矩阵元素大小|&lt;=2*10<sup>9</sup><br/>
<table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">case1<br/>
</td><td valign="top" colspan="2" style="border:solid 1.0pt">3 3<br/>
-1 1 2<br/>
-1 -1 1<br/>
10 2 1<br/>
3<br/>
1 3 3 1<br/>
1 3 2 2<br/>
2 1 3 2<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">case2<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=10,m&lt;=10,q&lt;=100000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">case3<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=100,m&lt;=100,q&lt;=5000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">case4<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=200,m&lt;=200,q&lt;=1000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">case5<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=200,m&lt;=200,q&lt;=1000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">case6<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=200,m&lt;=200,q&lt;=1000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">case7<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=100,m&lt;=100,q&lt;=50000<br/>
</td><td valign="top" style="border:solid 1.0pt">原矩阵中的不同元素不超过200<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">case8<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=100,m&lt;=100,q&lt;=50000<br/>
</td><td valign="top" style="border:solid 1.0pt">原矩阵中的不同元素不超过200<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">case9<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=100,m&lt;=100,q&lt;=50000<br/>
</td><td valign="top" style="border:solid 1.0pt">原矩阵中的不同元素不超过200<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">case10<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=200,m&lt;=200,q&lt;=100000<br/>
</td><td valign="top" style="border:solid 1.0pt">原矩阵中的不同元素不超过200<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">case11<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=200,m&lt;=200,q&lt;=100000<br/>
</td><td valign="top" style="border:solid 1.0pt">原矩阵中的不同元素不超过200<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">case12<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=200,m&lt;=200,q&lt;=100000<br/>
</td><td valign="top" style="border:solid 1.0pt">原矩阵中的不同元素不超过200<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">case13<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=100,m&lt;=100,q&lt;=100000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">case14<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=100,m&lt;=100,q&lt;=100000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">case15<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=200,m&lt;=200,q&lt;=100000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">case16<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=200,m&lt;=200,q&lt;=100000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">case17<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=200,m&lt;=200,q&lt;=100000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">case18<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=200,m&lt;=200,q&lt;=100000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">case19<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=200,m&lt;=200,q&lt;=100000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">case20<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=200,m&lt;=200,q&lt;=100000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr></tbody></table></div>

</div>