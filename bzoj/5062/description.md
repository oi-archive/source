
# Description

<div class="content"><div>
<div>姚先生和王女士是很好的朋友，他们喜欢在闲暇的时候玩儿珠子游戏。珠子游戏是双人游戏，两人轮流移动：游戏</div>
<div>中的珠子为黑色或白色。在游戏开始阶段，这些珠子被插在4个柱子上。姚先生只能移动黑色珠子，王女士只能移</div>
<div>动白色珠子。轮到某个人移动时，他可以移动任意一个和他颜色相符的珠子。那个珠子和它上面的所有珠子都会被</div>
<div>移除。例如，一个柱子上有如下珠子（从下到上）：黑白黑白。如果姚先生把最底下的珠子移走，那么整个柱子都</div>
<div>会被移空，姚先生也可以移动第三个珠子，这样的话移动完成后柱子上只剩下2个珠子。如果王女士先手，她可以</div>
<div>移除第二个珠子，这样的话柱子上只剩下最后一个珠子了，王女士也可以移动第四个珠子。如果一个人不能移动了</div>
<div>，那么他（她）就输了。姚先生和王女士都足够聪明：如果姚先生存在必胜策略，他最后一定能赢，如果王女士存</div>
<div>在必胜策略，她也最后一定能赢。有时候，他们发现在一些局面下有一个人一定能赢，无论谁先手。如果一个局面</div>
<div>无论谁先手姚先生一定能赢，那么我们称为&#34;姚局面&#34;，如果一个局面无论谁先手王女士一定能赢，那么我们称为&#34;</div>
<div>王局面&#34;。更进一步，他们定义&#34;partial局面&#34;为三个柱子组成的局面。一个&#34;partial局面&#34;（标记为 ）再加上第四</div>
<div>个柱子（标记为 ）就可以组成一个完整局面（标记为（C，T））。一个&#34;partial局面&#34;C1不次于另外一个&#34;partial</div>
<div>局面&#34;C2当且仅当：对于任意的珠子T，如果(C2,T)是&#34;王局面&#34;那么(C1,T)也是&#34;王局面&#34;。另外一种说法：不存在柱</div>
<div>子T，(C2,T)是&#34;王局面&#34;但是(C1,T)不是 &#34;王局面&#34;。给定两个&#34;partial局面&#34;C1和C2，请你检查C1是否不次于C2。</div>
</div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行有一个正整数N，为测试数据组数。</div>
<div>每个测试数据要求你比较一组&#34;partial局面&#34;。第一行为测试数据编号，接下来按照 和 的顺序给出&#34;partial局面&#34;。</div>
<div>每个&#34;partial局面&#34;的第一行包含三个正整数： 标明三个柱子的高度(0&lt;=N1,N2,N3&lt;=50),</div>
<div>从第二行包含N1个字符(B或者W)用空格隔开，</div>
<div>第三行包含N2个字符(B或者W) 用空格隔开，</div>
<div>第四行包含N3个字符(B或者W) 用空格隔开，按照从底到顶的顺序给出。</div>
</div>
<p></p></div>

# Output

<div class="content"><div>
<div>输出数据包含N行，第i行位Yes如果C1不次于C2，否则为No，输出数据具体格式参见样例。</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
Test 1<br/>
3 3 1<br/>
W B B<br/>
W B W<br/>
B<br/>
3 3 3<br/>
B W W<br/>
B W W<br/>
W B B<br/>
Test 2<br/>
3 3 2<br/>
W B B<br/>
W B W<br/>
B B<br/>
3 3 3<br/>
B W W<br/>
B W W<br/>
W B B<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Test 1: Yes<br/>
Test 2: No</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

