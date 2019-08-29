<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　给你一个N*N的矩阵，不用算矩阵乘法，但是每次询问一个子矩形的第K小数。</div>
# 输入格式

<div class="pdcont">　　第一行两个数N,Q，表示矩阵大小和询问组数；<br/>
　　接下来N行N列一共N*N个数，表示这个矩阵；<br/>
　　再接下来Q行每行5个数描述一个询问：x1,y1,x2,y2,k表示找到以(x1,y1)为左上角、以(x2,y2)为右下角的子矩形中的第K小数。</div>
# 输出格式

<div class="pdcont">　　对于每组询问输出第K小的数。</div>
# 样例输入

<div class="pddata">2 2<br/>
2 1<br/>
3 4<br/>
1 2 1 2 1<br/>
1 1 2 2 3</div>
# 样例输出

<div class="pddata">1<br/>
3</div>
# 数据规模和约定

<div class="pdcont">　　矩阵中数字是10<sup>9</sup>以内的非负整数；<br/>
　　20%的数据：N&lt;=100,Q&lt;=1000；<br/>
　　40%的数据：N&lt;=300,Q&lt;=10000；<br/>
　　60%的数据：N&lt;=400,Q&lt;=30000；<br/>
　　100%的数据：N&lt;=500,Q&lt;=60000。</div>

</div>