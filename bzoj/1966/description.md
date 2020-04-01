
# Description

<div class="content"><p><span style="font-size: medium">科学家们在Samuel星球上的探险仍在继续。非常幸运的，在Samuel星球的南极附近，探险机器人发现了一个巨大的冰湖！机器人在这个冰湖中搜集到了许多RNA片段运回了实验基地。科学家们经过几个昼夜的研究，发现这些RNA片段中有许多是未知的病毒！每个RNA片段都是由A、C、T、G组成的序列。科学家们也总结出了Samuel星球上的“病毒模版片段”。一个模版片段是由A、C、T、G的序列加上通配符 * 和 ? 来表示。其中 * 的意思是可以匹配上0个或任意多个字符，而 ? 的意思是匹配上任意一个字母。如果一个RNA片段能够和“病毒模版片段”相匹配，那么这个RNA片段就是未知的病毒。例如，假设“病毒模版片段”为A*G?C。RNA片段：AGTC，AGTGTC都是未知的病毒，而RNA片段AGTGC则不是病毒。由于，机器人搜集的这些RNA片段中除去病毒的其他部分都具有非常高的研究价值。所以科学家们希望能够分辨出其中哪些RNA片段不是病毒，并将不是病毒的RNA片段运回宇宙空间站继续进行研究。科学家将这项任务交给了小联。现在请你为小联编写程序统计哪些RNA片段不是病毒。 </span></p></div>

# Input

<div class="content"><p><span style="font-family: arial, verdana, helvetica, sans-serif; font-size: medium;">第一行有一个字符串，由A、C、T、G、*、? 组成。表示“病毒模版片段”。“病毒模版片段”的长度不超过1000。第二行有一个整数N（0&lt;N&lt;500），表示机器人搜集到的RNA片段的数目。随后的N行，每一行有一个字符串，由A、C、T、G组成，表示一个RNA片段。每个RNA片段的长度不超过500。注意：“病毒模版片段”和RNA片段的长度都至少为1。</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">只有一行输出，为整数M，即不是病毒的RNA片段的数目。 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">A*G?C<br/>
3<br/>
AGTC<br/>
AGTGTC<br/>
AGTGC<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>输入中的RNA片段AGTGC不是病毒。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

