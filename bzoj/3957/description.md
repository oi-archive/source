
# Description

<div class="content"><div>工业计算机处理器公司为顾客量身定做了非常快速、用于专门目的的处理单元。a-C-m系列的处理器（比如1-C-2和5-C-3）的指令集只有两种操作：</div>
<div>　　•<span class="Apple-tab-span" style="white-space:pre">	</span>A 数值加a</div>
<div>　　•<span class="Apple-tab-span" style="white-space:pre">	</span>M 数值乘m</div>
<div>　　处理器接收一个整数，执行一个A和M的指令序列（即程序）来修改输入，然后输出结果。举个例子，1-C-2处理器执行程序AAAM处理输入2返回输出10（计算过程是2→3→4→5→10）,然而5-C-3处理器用相同的程序和输入返回51（2→7→12→17→51）。</div>
<div>　　你是一个被指定做一个顶级秘密项目的a-C-m程序员。这意味着你不会被告知你的程序执行的精确输入。但会得到四个特别的值p，q，r，s，以及下列条件</div>
<div>　　1、输入保证是一个在p、q之间的数</div>
<div>　　2、输出必须是一个在r，s之间的数。</div>
<div>　　给你一个a-C-m处理器和p，q，r，s这四个数。你的工作是构想最短的a-C-m程序，使得任意任意x保证p≤x≤q，返回一个输出y使得r≤y≤s。如果有多个最短的程序，选择字典序最小的，而一个程序即是由A和M组成的字符串。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>输入包含多组数据。每组数据在一行中给你6个整数a，m，p，q，r，s，每个就像上面描述的一样。</div>
<div>末行输入6个0作为结束。</div>
<div></div>
</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每组数据，在你的程序前输出数据的编号，程序即像上面描述的一样。输出单词“empty”，如果最好的程序没有操作。输出单词“impossible”如果没有程序满足具体要求。</div>
<div>
<div>输出一个用空格分隔的字符串序列，任两个相邻的字符串形式分别为“nA”和“nM”，n&gt;0。前者表示n个连续的操作A，后者表示n个连续的操作M。</div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1 2 2 3 10 20<br/>
1 3 2 3 22 33<br/>
3 2 2 3 4 5<br/>
5 3 2 3 2 3<br/>
0 0 0 0 0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case 1: 1A 2M<br/>
Case 2: 1M 2A 1M<br/>
Case 3: impossible<br/>
Case 4: empty</span></div>

# Hint

<div class="content"><p></p><div>所有的的a,m,p,q,r,s∈[1,1000000000]，且p≤q,r≤s。</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

