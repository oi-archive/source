# 题目描述


<div>题目描述：</div>
<div style="text-indent: 21.75pt">在一平面上给出一些线段以及它们之间的关系，判断这些关系是否符合逻辑。</div>
<div>输入：</div>
<div style="text-indent: 21.75pt">第一行有一个整数t表示共t组数据，</div>
<div style="text-indent: 21.75pt">第二行有两个整数n，m，n表示共n条线段，m表示接下来有m行</div>
<div style="text-indent: 21.75pt">接下来m行，每行有三个整数i，j，k表示i与j的的关系为k。（k只有2种情况，k=0平行,k=1垂直）</div>
<div>输出：</div>
<div><span>    </span>共t行，若n条线段的关系都符合逻辑那么输出线段1和n的关系(输出1表示垂直，0表示平行，2表示不确定），否则输出“No Answer”。</div>
<div>样例输入：</div>
<div>2</div>
<div>3 2</div>
<div>1 2 0</div>
<div>2 3 1</div>
<div>6 4</div>
<div>3 2 1</div>
<div>2 4 1</div>
<div>1 5 0</div>
<div>3 4 1</div>
<div>样例输出：</div>
<div>1</div>
<div>No Answer</div>
<p><span style="font-size: 10.5pt">数据规模：</span><span style="font-size: 10.5pt">t&lt;=10,n&lt;=300,m&lt;=40000</span></p>
<p><span style="font-size: 10.5pt">注示：如果一对线段关系出现了若干次，只取最后一次。</span></p>
