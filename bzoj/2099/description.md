
# Description

<div class="content">
FJ刚刚和邻居发生了一场可怕的争吵，他咽不下这口气，决定佚名发给他的邻居
一封脏话连篇的信。他有无限张完全相同的已经打印好的信件，都包含
N个字母(1 &lt;= N &lt;= 50,000)。他想剪出其中一些并且粘帖成一个很长的字母串。

FJ太懒了，他想用最少的次数裁剪信件。他有一把举世无双的剪刀，他可以从
一封信中只剪一刀剪出连续一段。同样，剪一刀可以得到整个完整的字符串。

他想知道他最少需要剪多少刀从而获得这封M个字母的长信？

保证这总是可能的。

考虑下面38个字母的信：

        THEQUICKBROWNFOXDO
        GJUMPSOVERTHELAZYDOG

以及FJ想要获得的9个字母的信：

        FOXDOG
        DOG

以上是为了读入方便，实际上这两封信就是：

        THEQUICKBROWNFOXDOGJUMPSOVERTHELAZYDOG
        FOXDOGDOG

由于FOXDOG已经存在了，FJ可以剪一刀得到FOXDOG。还剩下一个DOG，FJ可以选择
其中任何一个DOG剪下来。

因此，他一共要剪2刀。

</div>

# Input

<div class="content">
* 第一行： 两个空格分隔的整数： N, M

* 第2..?行： 一些行包含N个字母，FJ原来拥有的信，每行不会超过80个字母。

* 第?...?行： 一些行包含M个字母，FJ想要写的信，每行不会超过80个字母。

</div>

# Output

<div class="content">
* 第1行： FJ获得他想要写的信所需要切的最少次数。
</div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
38 9<br/>
THEQUICKBROWNFOXDO<br/>
GJUMPSOVERTHELAZYDOG<br/>
FOXDOG<br/>
DOG<br/>
<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
2<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

