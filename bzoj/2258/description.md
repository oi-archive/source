
# Description

<div class="content"><p align="center"><b> </b></p>
<p><font face="Times New Roman" size="3">为了给Wind买生日礼物，Jiajia不得不找了一份检查文本的工作。这份工作很无聊：给你一段文本 <br/>
要求比对从文本中某两个位置开始能匹配的最大长度是多少。但比无聊更糟糕的是，Jiajia的经理 <br/>
还可能往文本里面插入一些字符。 <br/>
Jiajia想用一个程序来解决这些繁琐的工作。这个程序的速度要足够快，因为Wind的生日就快要到了 <br/>
Jiajia必须赚到足够多的钱，也就是处理足够多的文本。 <br/>
<br/>
</font></p></div>

# Input

<div class="content"><p><font face="Times New Roman" size="3">输入文件第一行是原始文本。 <br/>
输入文件第二行是操作数n。此后n行，每行描述一条命令，命令有两种形式： <br/>
I ch p：表示将一个字符ch插入到当前文本的第p个字符之前，如果p大于当前文本长度则表示插入到当前文本末尾； <br/>
Q i j：表示询问当前文本从原始文本的第i个和第j个字符现在所在的位置开始能匹配的字符是多少。 <br/>
你可以认为文本初始长度不超过50000，I命令最多200条，Q命令最多20000条。 <br/>
<br/>
</font></p></div>

# Output

<div class="content"><p><font face="Times New Roman" size="3">对于每条Q命令输出一行，为最长匹配长度。 <br/>
<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">abaab<br/>
5<br/>
Q 1 2<br/>
Q 1 3<br/>
I a 2<br/>
Q 1 2<br/>
Q 1 3<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
0<br/>
1<br/>
0<br/>
3<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

