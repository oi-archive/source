
# Description

<div class="content"><div><span style="font-size: medium">    那N只可爱的奶牛刚刚学习了有关密码的许多算法，终于，她们创造出了属于奶牛的加密方法．由于她们并不是经验十足，她们的加密方法非常简单：</span><span style="font-size: medium">第i只奶牛掌握着密码的第i个数字，起始的时候是Ci(0≤Ci&lt;90000000).加密的时候，</span><span style="font-size: medium">第i只奶牛会计算其他所有奶牛的数字和，并将这个数字和除以98765431取余．在所有奶牛计算完毕之后，每一只奶牛会用自己算得的数字代替原有的数字．也就是说，</span></div>
<div><span style="font-size: medium"><img height="103" width="173" alt="" src="/source/bzoj/1712/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMS8yMigxMCkuanBn.jpg"/></span></div>
<div><span style="font-size: medium">这样，她们就完成了一次加密．    在十一月，奶牛们把这个加密法则告诉了驼鹿卡门，卡门惊呆了．之后，在一个浓雾弥漫的平安夜，卡门与奶牛们：“你们的算法十分原始，很容易就被人破解．所以你们要重复这个加密过程T(1≤T≤1414213562)次，才能达到加密效果．”    这回轮到奶牛们惊呆了．很显然，奶牛们特别讨厌做同样的无聊的事情很多次．经过了漫长的争论，卡门和奶牛们终于找到的解决办法：你被刚来加密这些数字．</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">    第1行输入N和T，之后N行每行一个整数表示初始的Ci．</span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">    共N行，每行一个整数，表示T次加密之后的Ci．</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 4<br/>
1<br/>
0<br/>
4<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
Three cows, with starting numbers 1, 0, and 4; four repetitions of the<br/>
encryption algorithm.<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">26<br/>
25<br/>
29<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
The following is a table of the cows&#39; numbers for each turn:<br/>
<br/>
          Cows&#39; numbers<br/>
Turn    Cow1  Cow2  Cow3<br/>
 0        1     0     4<br/>
 1        4     5     1<br/>
 2        6     5     9<br/>
 3       14    15    11<br/>
 4       26    25    29<br/>
</span></div>

# Hint

<div class="content"><p></p><p> <span style="font-family: arial, verdana, helvetica, sans-serif;">N&lt;=50000</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

