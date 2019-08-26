
# Description

<div class="content"><p>墨墨购买了一套N支彩色画笔（其中有些颜色可能相同），摆成一排，你需要回答墨墨的提问。墨墨会像你发布如下指令： 1、 Q L R代表询问你从第L支画笔到第R支画笔中共有几种不同颜色的画笔。 2、 R P Col 把第P支画笔替换为颜色Col。为了满足墨墨的要求，你知道你需要干什么了吗？</p></div>

# Input

<div class="content"><p>第1行两个整数N，M，分别代表初始画笔的数量以及墨墨会做的事情的个数。第2行N个整数，分别代表初始画笔排中第i支画笔的颜色。第3行到第2+M行，每行分别代表墨墨会做的一件事情，格式见题干部分。</p></div>

# Output

<div class="content"><p>对于每一个Query的询问，你需要在对应的行中给出一个数字，代表第L支画笔到第R支画笔中共有几种不同颜色的画笔。</p></div>

# Sample Input

<div class="content"><span class="sampledata">6 5<br/>
1 2 3 4 5 5<br/>
Q 1 4<br/>
Q 2 6<br/>
R 1 2<br/>
Q 1 4<br/>
Q 2 6<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
4<br/>
3<br/>
4<br/>
</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据，N≤10000，M≤10000，修改操作不多于1000次，所有的输入数据中出现的所有整数均大于等于1且不超过10^6。</p><br/>
<p>2016.3.2新加数据两组by <font face="Microsoft Yahei"><span style="font-size: 14px; line-height: 22.399999618530273px;">Nano_Ape</span></font></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

