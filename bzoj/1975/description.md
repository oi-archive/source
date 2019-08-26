
# Description

<div class="content">iPig在假期来到了传说中的魔法猪学院，开始为期两个月的魔法猪训练。经过了一周理论知识和一周基本魔法的学习之后，iPig对猪世界的世界本原有了很多的了解：众所周知，世界是由元素构成的；元素与元素之间可以互相转换；能量守恒……。

能量守恒……iPig 今天就在进行一个麻烦的测验。iPig 在之前的学习中已经知道了很多种元素，并学会了可以转化这些元素的魔法，每种魔法需要消耗 iPig 一定的能量。作为 PKU 的顶尖学猪，让 iPig 用最少的能量完成从一种元素转换到另一种元素……等等，iPig 的魔法导猪可没这么笨！这一次，他给 iPig 带来了很多 1 号元素的样本，要求 iPig 使用学习过的魔法将它们一个个转化为 N 号元素，为了增加难度，要求每份样本的转换过程都不相同。这个看似困难的任务实际上对 iPig 并没有挑战性，因为，他有坚实的后盾……现在的你呀！

注意，两个元素之间的转化可能有多种魔法，转化是单向的。转化的过程中，可以转化到一个元素（包括开始元素）多次，但是一但转化到目标元素，则一份样本的转化过程结束。iPig 的总能量是有限的，所以最多能够转换的样本数一定是一个有限数。具体请参看样例。

</div>

# Input

<div class="content">第一行三个数 N、M、E 表示iPig知道的元素个数（元素从 1 到 N 编号）、iPig已经学会的魔法个数和iPig的总能量。
后跟 M 行每行三个数 si、ti、ei 表示 iPig 知道一种魔法，消耗 ei 的能量将元素 si 变换到元素 ti 。

</div>

# Output

<div class="content">一行一个数，表示最多可以完成的方式数。输入数据保证至少可以完成一种方式。

</div>

# Sample Input

<div class="content"><span class="sampledata">4 6 14.9<br/>
1 2 1.5<br/>
2 1 1.5<br/>
1 3 3<br/>
2 3 1.5<br/>
3 4 1.5<br/>
1 4 1.5<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
<br/>
</span></div>

# Hint

<div class="content"><p>样例解释<br/>
有意义的转换方式共4种：<br/>
1-&gt;4，消耗能量 1.5<br/>
1-&gt;2-&gt;1-&gt;4，消耗能量 4.5<br/>
1-&gt;3-&gt;4，消耗能量 4.5<br/>
1-&gt;2-&gt;3-&gt;4，消耗能量 4.5<br/>
显然最多只能完成其中的3种转换方式（选第一种方式，后三种方式仍选两个），即最多可以转换3份样本。<br/>
如果将 E=14.9 改为 E=15，则可以完成以上全部方式，答案变为 4。<br/>
<br/>
数据规模<br/>
占总分不小于 10% 的数据满足 N &lt;= 6，M&lt;=15。<br/>
占总分不小于 20% 的数据满足 N &lt;= 100，M&lt;=300，E&lt;=100且E和所有的ei均为整数（可以直接作为整型数字读入）。<br/>
所有数据满足 2 &lt;= N &lt;= 5000，1 &lt;= M &lt;= 200000，1&lt;=E&lt;=107，1&lt;=ei&lt;=E，E和所有的ei为实数。<br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Sdoi2010 Contest2 Day2">Sdoi2010 Contest2 Day2</a></p></div>

