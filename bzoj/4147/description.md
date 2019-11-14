
# Description

<div class="content"><div>Euclid和Pythagoras在玩取石子游戏，一开始有n颗石子。</div>
<div>Euclid为先手，他们按如下规则轮流操作：</div>
<div>·若为Euclid操作，如果n&lt;p，则他只能新放入p颗石子，否则他可以拿走p的倍数颗石子。</div>
<div>·若为Pythagoras操作，如果n&lt;q，则他只能新放入q颗石子，否则他可以拿走q的倍数颗石子。</div>
<div>拿光所有石子者胜利。假设他们都以最优策略操作，那么获胜者是谁？</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个正整数t(1&lt;=t&lt;=1000)，表示数据组数。</div>
<div>接下来t行，每行三个正整数p,q,n(1&lt;=p,q,n&lt;=10^9)，表示一组数据。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出t行。第i行输出第i组数据的答案，如果Euclid必胜，输出E，如果Pythagoras必胜，输出P，</div>
<div>
<div>如果游戏永远不会停止，输出R。</div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
3 2 1<br/>
2 3 1<br/>
3 4 5<br/>
2 4 3<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">P<br/>
P<br/>
E<br/>
R</span></div>

# Hint

<div class="content"><p></p><p>在第一组数据中，Euclid必须新放入3颗石子，然后Pythagoras拿走4颗石子并获胜。</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris上传">鸣谢Claris上传</a></p></div>

