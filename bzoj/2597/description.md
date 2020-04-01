
# Description

<div class="content"><div style="text-indent: 20.5pt"><span style="font-size: 12pt">在一些一对一游戏的比赛（如下棋、乒乓球和羽毛球的单打）中，我们经常会遇到</span><span style="font-size: 12pt">A</span><span style="font-size: 12pt">胜过</span><span style="font-size: 12pt">B</span><span style="font-size: 12pt">，</span><span style="font-size: 12pt">B</span><span style="font-size: 12pt">胜过</span><span style="font-size: 12pt">C</span><span style="font-size: 12pt">而</span><span style="font-size: 12pt">C</span><span style="font-size: 12pt">又胜过</span><span style="font-size: 12pt">A</span><span style="font-size: 12pt">的有趣情况，不妨形象的称之为<b><u>剪刀石头布</u></b>情况。有的时候，无聊的人们会津津乐道于统计有多少这样的<b><u>剪刀石头布</u></b>情况发生，即有多少对<b><u>无序</u></b>三元组</span><span style="font-size: 12pt">(A, B, C)</span><span style="font-size: 12pt">，满足其中的一个人在比赛中赢了另一个人，另一个人赢了第三个人而第三个人又胜过了第一个人。注意这里<b><u>无序</u></b>的意思是说三元组中元素的顺序并不重要，将</span><span style="font-size: 12pt">(A, B, C)</span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">(A, C, B)</span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">(B, A, C)</span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">(B, C, A)</span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">(C, A, B)</span><span style="font-size: 12pt">和</span><span style="font-size: 12pt">(C, B, A)</span><span style="font-size: 12pt">视为相同的情况。</span></div>
<div style="text-indent: 20.5pt"><span style="font-size: 12pt">有</span><i><span style="font-size: 12pt">N</span></i><span style="font-size: 12pt">个人参加一场这样的游戏的比赛，赛程规定任意两个人之间都要进行一场比赛：这样总共有</span><span style="font-size: 12pt">场比赛。比赛已经进行了一部分，我们想知道在极端情况下，比赛结束后最多会发生多少<b><u>剪刀石头布</u></b>情况。即给出已经发生的比赛结果，而你可以任意安排剩下的比赛的结果，以得到尽量多的<b><u>剪刀石头布</u></b>情况。</span></div></div>

# Input

<div class="content"><div style="text-indent: 20.5pt"><span style="font-size: 12pt">输入文件的第</span><span style="font-size: 12pt">1</span><span style="font-size: 12pt">行是一个整数</span><i><span style="font-size: 12pt">N</span></i><span style="font-size: 12pt">，表示参加比赛的人数。</span></div>
<div style="text-indent: 20.5pt"><span style="font-size: 12pt">之后是一个</span><i><span style="font-size: 12pt">N</span></i><span style="font-size: 12pt">行</span><i><span style="font-size: 12pt">N</span></i><span style="font-size: 12pt">列的数字矩阵：一共</span><i><span style="font-size: 12pt">N</span></i><span style="font-size: 12pt">行，每行</span><i><span style="font-size: 12pt">N</span></i><span style="font-size: 12pt">列，数字间用空格隔开。</span></div>
<div style="text-indent: 20.5pt"><span style="font-size: 12pt">在第</span><span style="font-size: 12pt">(<i>i</i>+1)</span><span style="font-size: 12pt">行的第</span><i><span style="font-size: 12pt">j</span></i><span style="font-size: 12pt">列的数字如果是</span><span style="font-size: 12pt">1</span><span style="font-size: 12pt">，则表示</span><i><span style="font-size: 12pt">i</span></i><span style="font-size: 12pt">在已经发生的比赛中赢了</span><i><span style="font-size: 12pt">j</span></i><span style="font-size: 12pt">；该数字若是</span><span style="font-size: 12pt">0</span><span style="font-size: 12pt">，则表示在已经发生的比赛中</span><i><span style="font-size: 12pt">i</span></i><span style="font-size: 12pt">败于</span><i><span style="font-size: 12pt">j</span></i><span style="font-size: 12pt">；该数字是</span><span style="font-size: 12pt">2</span><span style="font-size: 12pt">，表示</span><i><span style="font-size: 12pt">i</span></i><span style="font-size: 12pt">和</span><i><span style="font-size: 12pt">j</span></i><span style="font-size: 12pt">之间的比赛尚未发生。数字矩阵对角线上的数字，即第</span><span style="font-size: 12pt">(<i>i</i>+1)</span><span style="font-size: 12pt">行第</span><i><span style="font-size: 12pt">i</span></i><span style="font-size: 12pt">列的数字都是</span><span style="font-size: 12pt">0</span><span style="font-size: 12pt">，它们仅仅是占位符号，没有任何意义。</span></div>
<div style="text-indent: 20.5pt"><span style="font-size: 12pt">输入文件保证合法，不会发生矛盾，当</span><i><span style="font-size: 12pt">i</span></i><i><span style="font-size: 12pt">≠</span></i><i><span style="font-size: 12pt">j</span></i><span style="font-size: 12pt">时，第</span><span style="font-size: 12pt">(<i>i</i>+1)</span><span style="font-size: 12pt">行第</span><i><span style="font-size: 12pt">j</span></i><span style="font-size: 12pt">列和第</span><span style="font-size: 12pt">(<i>j</i>+1)</span><span style="font-size: 12pt">行第</span><i><span style="font-size: 12pt">i</span></i><span style="font-size: 12pt">列的两个数字要么都是</span><span style="font-size: 12pt">2</span><span style="font-size: 12pt">，要么一个是</span><span style="font-size: 12pt">0</span><span style="font-size: 12pt">一个是</span><span style="font-size: 12pt">1</span><span style="font-size: 12pt">。</span></div></div>

# Output

<div class="content"><div style="text-indent: 20.5pt"><span style="font-size: 12pt">输出文件的第</span><span style="font-size: 12pt">1</span><span style="font-size: 12pt">行是一个整数，表示在你安排的比赛结果中，出现了多少<b><u>剪刀石头布</u></b>情况。</span></div>
<div style="text-indent: 20.5pt"><span style="font-size: 12pt">输出文件的第</span><span style="font-size: 12pt">2</span><span style="font-size: 12pt">行开始有一个和输入文件中格式相同的</span><i><span style="font-size: 12pt">N</span></i><span style="font-size: 12pt">行</span><i><span style="font-size: 12pt">N</span></i><span style="font-size: 12pt">列的数字矩阵。第</span><span style="font-size: 12pt">(<i>i</i>+1)</span><span style="font-size: 12pt">行第</span><i><span style="font-size: 12pt">j</span></i><span style="font-size: 12pt">个数字描述了</span><i><span style="font-size: 12pt">i</span></i><span style="font-size: 12pt">和</span><i><span style="font-size: 12pt">j</span></i><span style="font-size: 12pt">之间的比赛结果，</span><span style="font-size: 12pt">1</span><span style="font-size: 12pt">表示</span><i><span style="font-size: 12pt">i</span></i><span style="font-size: 12pt">赢了</span><i><span style="font-size: 12pt">j</span></i><span style="font-size: 12pt">，</span><span style="font-size: 12pt">0</span><span style="font-size: 12pt">表示</span><i><span style="font-size: 12pt">i</span></i><span style="font-size: 12pt">负于</span><i><span style="font-size: 12pt">j</span></i><span style="font-size: 12pt">，与输入矩阵不同的是，在这个矩阵中没有表示比赛尚未进行的数字</span><span style="font-size: 12pt">2</span><span style="font-size: 12pt">；对角线上的数字都是</span><span style="font-size: 12pt">0</span><span style="font-size: 12pt">。输出矩阵要保证合法，不能发生矛盾。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
0 1 2<br/>
0 0 2<br/>
2 2 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
0 1 0<br/>
0 0 1<br/>
1 0 0</span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
100%的数据中，N≤ 100。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

