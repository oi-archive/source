<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>You are using an editor to type in a program that you hope solves another problem on this contest. Instead of thinking about solving this problem, you look at your editor and start to think of how to edit your program more quickly.</p><p>你正在参加一个编程比赛，使用一个新的编辑器来敲代码。你临时开了点小差，在想如何编辑程序能够使得效率更高。</p><p>Your editor has the following characteristics:</p><p>你的编辑器有如下的一些功能：</p><p>&amp;bull; you can move your cursor using the direction keys: up (&amp;uarr;), down (&amp;darr;) , left (&amp;larr;) or right (&amp;rarr;)</p><p>你可以使用上下左右按键来移动你的光标</p><p>&amp;bull; pressing &amp;rarr; will move the cursor one character to the right; if the cursor is on the rightmost character of a line, the cursor will move to the ﬁrst character of the next line below the current line; (the cursor will not move if it is in the bottom-right position)</p><p>按右键可以把光标往右移动一个字符，如果光标在当前行的最右边，光标就会移动到下一行的第一个字符。如果光标在最右下角，就不移动。</p><p>&amp;bull; pressing &amp;larr; will move the cursor one character to the left; if the cursor is on the leftmost character of a line, the cursor will move to the last character of the previous line above the current line; (the cursor will not move if it is in the top-left position)</p><p>按左键可以把光标往左移动一个字符，如果光标在当前行的最左边，光标就会移动到上一行的最后一个字符。如果光标在最左上角，就不移动。</p><p>&amp;bull; pressing&amp;uarr;will move the cursor to the character immediately above it; if there is no character immediately above the cursor, it will move to the last character of the previous line above the current line; (the cursor will not move if it is on the ﬁrst line)</p><p>按上键可以把光标往上移动一个字符，如果当前位置的正上方没有字符，那么光标就会移动到上一行的末尾。如果光标在第一行，就不移动。</p><p>&amp;bull; pressing&amp;darr;will move the cursor to the character immediately below it; if there is no character immediately below the cursor, it will move to the last character of the next line below the current line; (the cursor will not move if it is on the last line)</p><p>按下键可以把光标往下移动一个字符，如果当前位置的正下方没有字符，那么光标就会移动到下一行的末尾。如果光标在最后一行行，就不移动。</p><p>You would like to ﬁnd the least number of key presses that will cause you to move between posi- tions in your editor in a given program which you are editing.</p><p>你想要知道，要使得光标从当前位置移动到目标位置，至少要按键多少次</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>The ﬁrst line of input is N, the number of lines of your program (1 &amp;le; N &amp;le; 100000). The next N lines contain the number of characters on each line: you can assume there is at least one character per line, and at most 80 characters per line. The next line contains two integers RS CS, indicating the starting row and column of the cursor (1 &amp;le; RS &amp;le; N, 1 &amp;le; CS, and CS is at most the number of characters in row RS). The last line contains two integers RF CF, indicating the ﬁnishing row and column of the cursor (1 &amp;le; RF &amp;le; N, 1 &amp;le; CF, and CF is at most the number of characters in row RF).</p><p>第一行是正整数N表示行数，接下来共N行每行一个正整数Ai表示第i行的字符数。</p><p>接下来一行是两个正整数RS,CS表示光标当前位置是第RS行第CS列。</p><p>最后一行是两个正整数RF,CF表示需要将光标移动到第RF行第CF列。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>Output the minimum number of key presses that are required to move the cursor from row RS and column CS to row RF and column CF</p><p>输出最小的移动次数使得光标从(RS,CS)移动到(RF,CF)</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4</p><p>40</p><p>10</p><p>4</p><p>80</p><p>4 78</p><p>1 35</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>N&lt;=100,000，Ai&lt;=80</p>
</div>
</div>