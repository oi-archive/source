
# Description

<div class="content"><div style="line-height: 150%"><span style="font-size: 12pt; line-height: 150%">    </span><span style="font-size: 12pt; line-height: 150%">斗兽棋是一项有趣的棋类游戏。双方分别控制一些动物，在棋盘上按照一定的规则轮流行动，先占领对方巢穴为胜。任意两种不同的动物</span><span style="font-size: 12pt; line-height: 150%">A</span><span style="font-size: 12pt; line-height: 150%">和</span><span style="font-size: 12pt; line-height: 150%">B</span><span style="font-size: 12pt; line-height: 150%">相遇，要么</span><span style="font-size: 12pt; line-height: 150%">A</span><span style="font-size: 12pt; line-height: 150%">胜</span><span style="font-size: 12pt; line-height: 150%">B</span><span style="font-size: 12pt; line-height: 150%">，要么</span><span style="font-size: 12pt; line-height: 150%">B</span><span style="font-size: 12pt; line-height: 150%">胜</span><span style="font-size: 12pt; line-height: 150%">A</span><span style="font-size: 12pt; line-height: 150%">。</span></div>
<div style="line-height: 150%"><span style="font-size: 12pt; line-height: 150%">    </span><span style="font-size: 12pt; line-height: 150%">不过，原先的斗兽棋中动物种类较少，玩久了就会略显无聊。于是，某公司决定开发一种超级斗兽棋，含有</span><span style="font-size: 12pt; line-height: 150%">N</span><span style="font-size: 12pt; line-height: 150%">种动物，编号为</span><span style="font-size: 12pt; line-height: 150%">1,2</span><span style="font-size: 12pt; line-height: 150%">，……，</span><span style="font-size: 12pt; line-height: 150%">N</span><span style="font-size: 12pt; line-height: 150%">，并已经制定好了任意两种不同动物相遇时的胜负关系。</span></div>
<div style="line-height: 150%"><span style="font-size: 12pt; line-height: 150%">    </span><span style="font-size: 12pt; line-height: 150%">下一步工作是测试超级斗兽棋的趣味性。经调查发现，若动物间相互制约，则游戏的趣味性将大大增加。所谓动物间相互制约，即可以将动物按某种次序排成一个序列</span><span style="font-size: 12pt; line-height: 150%">P1</span><span style="font-size: 12pt; line-height: 150%">，</span><span style="font-size: 12pt; line-height: 150%">P2</span><span style="font-size: 12pt; line-height: 150%">，……，</span><span style="font-size: 12pt; line-height: 150%">Pn</span><span style="font-size: 12pt; line-height: 150%">，满足</span><span style="font-size: 12pt; line-height: 150%">P1</span><span style="font-size: 12pt; line-height: 150%">胜</span><span style="font-size: 12pt; line-height: 150%">P2</span><span style="font-size: 12pt; line-height: 150%">，</span><span style="font-size: 12pt; line-height: 150%">P2</span><span style="font-size: 12pt; line-height: 150%">胜</span><span style="font-size: 12pt; line-height: 150%">P3</span><span style="font-size: 12pt; line-height: 150%">，……，</span><span style="font-size: 12pt; line-height: 150%">P</span><span style="font-size: 12pt; line-height: 150%">（</span><span style="font-size: 12pt; line-height: 150%">n-1</span><span style="font-size: 12pt; line-height: 150%">）胜</span><span style="font-size: 12pt; line-height: 150%">Pn</span><span style="font-size: 12pt; line-height: 150%">，</span><span style="font-size: 12pt; line-height: 150%">Pn</span><span style="font-size: 12pt; line-height: 150%">胜</span><span style="font-size: 12pt; line-height: 150%">P1</span><span style="font-size: 12pt; line-height: 150%">。如果动物间不能相互制约，但可以半相互制约（在相互制约的条件中去掉“</span><span style="font-size: 12pt; line-height: 150%">Pn</span><span style="font-size: 12pt; line-height: 150%">胜</span><span style="font-size: 12pt; line-height: 150%">P1<span>”</span>，其他条件不变）的话，那么这款游戏虽然趣味性有所降低，但勉强可以接受。不过，如果连半相互制约都不能满足的话，呵呵，对不起，重新设计吧。</span></div>
<div style="line-height: 150%"><span style="font-size: 12pt; line-height: 150%">    </span><span style="font-size: 12pt; line-height: 150%">你的任务就是帮助测试这款超级斗兽棋的趣味性。</span></div>
<div style="line-height: 150%"> </div></div>

# Input

<div class="content"><div style="line-height: 150%"><span style="font-size: 12pt; line-height: 150%">第一行是一个整数</span><span style="font-size: 12pt; line-height: 150%">n</span><span style="font-size: 12pt; line-height: 150%">，表示动物种类数。接下来是一个</span><span style="font-size: 12pt; line-height: 150%">n*n</span><span style="font-size: 12pt; line-height: 150%">的矩阵，为动物间的胜负关系，第</span><span style="font-size: 12pt; line-height: 150%">i</span><span style="font-size: 12pt; line-height: 150%">行第</span><span style="font-size: 12pt; line-height: 150%">j</span><span style="font-size: 12pt; line-height: 150%">列为</span><span style="font-size: 12pt; line-height: 150%">1</span><span style="font-size: 12pt; line-height: 150%">则</span><span style="font-size: 12pt; line-height: 150%">i</span><span style="font-size: 12pt; line-height: 150%">胜</span><span style="font-size: 12pt; line-height: 150%">j</span><span style="font-size: 12pt; line-height: 150%">，为</span><span style="font-size: 12pt; line-height: 150%">0</span><span style="font-size: 12pt; line-height: 150%">则</span><span style="font-size: 12pt; line-height: 150%">j</span><span style="font-size: 12pt; line-height: 150%">胜</span><span style="font-size: 12pt; line-height: 150%">i</span><span style="font-size: 12pt; line-height: 150%">（保证胜负关系不会矛盾，即不同的</span><span style="font-size: 12pt; line-height: 150%">i</span><span style="font-size: 12pt; line-height: 150%">和</span><span style="font-size: 12pt; line-height: 150%">j</span><span style="font-size: 12pt; line-height: 150%">相遇有且仅有一个胜者；主对角线上全为</span><span style="font-size: 12pt; line-height: 150%">0</span><span style="font-size: 12pt; line-height: 150%">）。</span></div>
<div style="line-height: 150%"> </div>
<div style="line-height: 150%"><span style="font-size: 12pt; line-height: 150%">第一行是一个整数</span><span style="font-size: 12pt; line-height: 150%">s</span><span style="font-size: 12pt; line-height: 150%">，表示测试结果：</span><span style="font-size: 12pt; line-height: 150%">0</span><span style="font-size: 12pt; line-height: 150%">表示动物间相互制约，</span><span style="font-size: 12pt; line-height: 150%">1</span><span style="font-size: 12pt; line-height: 150%">表示动物间不相互制约但半相互制约，</span><span style="font-size: 12pt; line-height: 150%">-1</span><span style="font-size: 12pt; line-height: 150%">表示都不满足。若测试结果不为</span><span style="font-size: 12pt; line-height: 150%">-1</span><span style="font-size: 12pt; line-height: 150%">，则在第二行输出满足响应条件的任一序列</span><span style="font-size: 12pt; line-height: 150%">P</span><span style="font-size: 12pt; line-height: 150%">（即测试结果为</span><span style="font-size: 12pt; line-height: 150%">0</span><span style="font-size: 12pt; line-height: 150%">时输出满足相互制约条件的序列，为</span><span style="font-size: 12pt; line-height: 150%">1</span><span style="font-size: 12pt; line-height: 150%">时输出半相互制约条件的序列）。</span></div>
<div style="line-height: 150%"> </div></div>

# Output

<div class="content"><div><span style="font-size: 12pt">5</span></div>
<div><span style="font-size: 12pt">0 0 1 1 1 </span></div>
<div><span style="font-size: 12pt">1 0 1 1 0 </span></div>
<div><span style="font-size: 12pt">0 0 0 1 0 </span></div>
<div><span style="font-size: 12pt">0 0 0 0 1 </span></div>
<div><span style="font-size: 12pt">0 1 1 0 0</span></div>
<div style="line-height: 150%"> </div></div>

# Sample Input

<div class="content"><span class="sampledata">0<br/>
1 3 4 5 2<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"></span></div>

# Hint

<div class="content"><p></p><p>100%的数据，2&lt;=n&lt;=200</p><br/>
<p>请不要提交，期待SPJ</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

