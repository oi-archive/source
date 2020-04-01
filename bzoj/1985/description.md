
# Description

<div class="content">You are to write a program which will divide set Q of squares into two parts, in such a way that one of them can be presented as other after rotations on 90 degrees and shifts along some vector. Set Q is the subset of NxN square. 


对于1*1的骨牌
判断这些放在棋盘里的骨牌能否划分成两个完全相等的部分。
这里规定，“完全相等”是指划分成两部分中的任一部分可以通过旋转一个整90度（0，90，180或270度	）之后，再经过一些杂乱的平移后使两部分完全重合。这里定义旋转90度可以看作，将整个棋盘旋转90度得到的骨牌的新位置就是这个骨牌原来的位置旋转90度后的位子。
例如

左图的骨牌通过整体顺时针旋转90度后可以得到
   110    001
   010    111
   010    000

</div>

# Input

<div class="content">第一行，一个整数T（T≤20），表示数据组数。
每组数据第一行一个整数N（N≤20）,表示一个N*N的棋盘。
下面接N行01串，表示骨牌的摆放情况，1表示有骨牌，0表示没有骨牌。

</div>

# Output

<div class="content">输出有T行，如果可以将骨牌分成“完全相等”的两部分，则输出“YES”，否则输出“No”表示不可以。

</div>

# Sample Input

<div class="content"><span class="sampledata">2                           <br/>
3                            <br/>
100<br/>
110<br/>
010<br/>
3<br/>
000<br/>
010<br/>
000<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">YES<br/>
No</span></div>

# Hint

<div class="content"><p>N≤20<br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

