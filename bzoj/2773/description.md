
# Description

<div class="content"><div style="text-indent: 21.75pt"><span style="font-size: medium">期末考试快到了，每个人都想用最少的努力通过考试，这当然不容易。Alice认识到最好去请教一个成绩比他好的，每个人都想这样做。</span></div>
<div style="text-indent: 21.75pt"><span style="font-size: medium">我们规定一个学生成绩的好坏用两个整数A和B来表示，A表示对功课的理解力，B表示知识面。</span></div>
<div style="text-indent: 21.75pt"><span style="font-size: medium">作为班长，Alice规定去请教的这个学生的理解力不得低于自己的理解力，同样知识面也不得低于自己的知识面，在这个基础上选择一个知识面（B值）跟自己差距最小的，如果还有多种选择，则在此基础上选择一个理解力（A值）跟自己差距最小的。</span></div>
<div style="text-indent: 21.75pt"><span style="font-size: medium">该学校不断有学生转进来，这给每个人的选择带来困难，现在请你来帮忙。</span></div></div>

# Input

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">输入的第一行包含一个整数N（1&lt;=N&lt;=200000），表示询问和转进学生的总数，接下来N行，格式为以下两种之一：</span></div>
<div style="text-justify: inter-ideograph; margin: 3pt 0cm 3pt 36pt; text-indent: -18pt"><span style="font-size: medium"><span style="color: black">·</span>“D A B”，表示新转进一名学生，理解力为A，知识面为B；</span></div>
<div style="text-indent: 18pt"><span style="font-size: medium">·<span style="color: windowtext">“</span><span style="color: windowtext">P i</span><span style="color: windowtext">”，要求输出第</span><span style="color: windowtext">i</span><span style="color: windowtext">个转进的学生当前应该去请教谁（不能在后转进的学生中寻找）。</span></span></div>
<div style="text-indent: 15.75pt"><span style="font-size: medium"><span style="color: windowtext">数据保证：</span><span style="color: windowtext">1&lt;=A,B&lt;=2*10^9</span><span style="color: windowtext">，不会存在两个学生的</span><span style="color: windowtext">A</span><span style="color: windowtext">和</span><span style="color: windowtext">B</span><span style="color: windowtext">都相等。</span></span></div></div>

# Output

<div class="content"><div> </div>
<div style="text-indent: 21pt"><span style="font-size: medium">对于每个“P i”询问，输出应该请教的学生的编号，学生的编号按照转进的顺序从1开始编号，如果无人可以请教，则输出“NE”。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">7 <br/>
D 5 2 <br/>
D 5 3 <br/>
P 1 <br/>
D 7 1 <br/>
D 8 7 <br/>
P 3 <br/>
P 2 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
4<br/>
4<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

