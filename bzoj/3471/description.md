
# Description

<div class="content"><p><span style="font-size: medium">Minecraft中有一种名叫“附魔”的操作，当走近附魔台时，周围书架上的书中会有一<br/>
些奇形怪状的符号飞向附魔台，打开附魔台后，附魔台上也会出现一些奇形怪状的文字，描<br/>
述了这次附魔的属性信息。这些奇怪的符号和文字被称作“龙语 (Dragon Scroll)”。由于附魔<br/>
是需要消耗经验值的，Rainbow企图破译龙语，以便于提前知道这次附魔是对他来说否物有<br/>
所值。 <br/>
经过对Minecraft内部程序的研究，Rainbow发现一条龙语实际上是由一串仅包含数字<br/>
和逗号的字符串转化而来的，并且字符串中用逗号隔开的各个数是递增的，在此前提下，前<br/>
面的数尽可能小。由于Rainbow的研究不够深入，他只能确定字符串中的一部分字符，还<br/>
有许多字符（数字或逗号）不能够确定，用问号代替。由于Rainbow还要研究字符串具体<br/>
是如何转化为龙语的，确定每个问号代表的是什么字符的任务就交给你了。  <br/>
 <br/>
 <br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">输入包含若干行，以EOF结尾。每行一个仅由数字、逗号和问号组成的字符串。  <br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">确定字符串中每个问号代表什么字符，并输出确定之后的字符串。注意你最终输出的字 符串中逗号隔开的各个数应该是递增的，并且每个数都不能有前导零；在此前提下，前面的<br/>
数尽可能小。如果输入数据不合法(有相邻的两个逗号或者开头结尾是逗号)或者不存在满足要求的字符串，输出impossible。 <br/>
 <br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">?2?5??6?,?? <br/>
10,???,12 <br/>
 <br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">12,50,60,61 <br/>
impossible <br/>
 <br/>
 <br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p></p><br/>
<p>对于100% 的数据，字符串长度不超过 200，每个测试点不超过100 组测试数据。 <br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Adera 2 杯省选模拟赛">Adera 2 杯省选模拟赛</a></p></div>

