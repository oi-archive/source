
# Description

<div class="content"><p>在这个问题中，你需要设计一个简单的底层数据库。<br/>
简单的说，你需要写一个程序支持以下三个函数：<br/>
Init、CountPoint、InsertPoint。<br/>
下面是实现细节：<br/>
Init<br/>
C语言函数原型：void Init()。<br/>
Pascal语言函数原型：procedure Init。<br/>
没有输入参数，没有返回值，仅在程序开始时被调用一次。<br/>
CountPoint<br/>
C语言函数原型：int CountPoint(int Leftside, int Rightside)<br/>
Pascal语言函数原型：function CountPoint(Leftside,Rightside:longint):longint<br/>
两个参数分别为查询的左右边界，你应该返回之前有多少个点在当前给定左右边界内，在边界上的点视为在边界内。<br/>
参数类型：int/int(C/C++)，longint/longint(pascal)<br/>
返回值类型：int(C/C++)，longint(pascal)<br/>
InsertPoint<br/>
C语言函数原型：void InsertPoint(int Position)<br/>
Pascal语言函数原型：procedure InsertPoint(Position:longint)<br/>
输入参数为插入的点的坐标。<br/>
参数类型：int(C/C++)，longint(pascal)<br/>
没有返回值</p>
<p>================================================================</p>
<p>本题已改成传统类型题,请自觉写在线算法</p></div>

# Input

<div class="content"></div>

# Output

<div class="content"></div>

# Sample Input

<div class="content"><span class="sampledata">8<br/>
0 0<br/>
1 0 1<br/>
0 1<br/>
1 0 2<br/>
0 2<br/>
0 6<br/>
1 2 6<br/>
1 1 8<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2<br/>
2<br/>
3<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

