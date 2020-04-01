
# Description

<div class="content">    Farmer John养了N(1 &lt;= N &lt;= 5,000)头奶牛，每头牛都有一个不超过32位二进制数的正整数编号。FJ希望奶牛们在进食前，能按编号从小到大的顺序排好队，但奶牛们从不听他的话。为了让奶牛们养成这个习惯，每次开饭时，FJ从奶牛中顺序地挑出一些，这些奶牛的编号必须按挑出的顺序递增。然后FJ让被挑出的奶牛们吃饭——其他奶牛就只能饿肚子了。

    现在，你得到了这一次开饭前队伍中从前到后所有奶牛的编号。奶牛们想请你计算一下，按照FJ的规定，最多有多少头奶牛能吃上饭？

比如说，有11头奶牛按以下顺序排好了队（数字代表奶牛的编号）

2 5 18 3 4 7 10 9 11 8 15

    对于这个队列，最多可以让7头奶牛吃上饭，她们的编号分别为2,3,4,7,10,11,15。队列2,5,3,10,15是不合法的，因为第3头奶牛的编号(3)小于她前面一头奶牛的编号(5)。

</div>

# Input

<div class="content">* 第1行: 一个整数，N

* 第2..?行: 除了最后一行，每一行都包含恰好20个用空格隔开的整数，依次表             示队伍中从前到后的奶牛的编号。如果N不能整除20，那么最后一              行包含的数字不到20个
</div>

# Output

<div class="content">* 第1行: 输出按照FJ的规定，最多可以挑出的奶牛的数目
</div>

# Sample Input

<div class="content"><span class="sampledata">11<br/>
2 5 18 3 4 7 10 9 11 8 15<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">7</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

