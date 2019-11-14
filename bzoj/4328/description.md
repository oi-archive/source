
# Description

<div class="content"><div>最近，进香河地带出现了一家“始祖鸟专卖店”，然而这并不只是一时的心血来潮。 </div>
<div>早在远古时期，进香河地带就以其秀美的环境和适宜的温度吸引了成群的始祖鸟。始祖鸟是一种团结的鸟类，它们总是通过各种方式来增强种群内部的交流，聚会则是其中之一。因为聚会不但可以增强朋友之间的友谊，而且可以认识新的朋友。 </div>
<div>现在有N只始祖鸟，我们从1开始编号。对于第i只始祖鸟，有Mi个认识的朋友，它们的编号分别是Fi,1，Fi,2，…，Fi,Mi。朋友的认识关系是单向的，也就是说如果第s只始祖鸟认识第t只始祖鸟，那么第t只始祖鸟不一定认识第s只始祖鸟。 </div>
<div>聚会的地点分为两处，一处在上游，一处在下游。对于每一处聚会场所，都必须满足对于在这个聚会场所中的始祖鸟，有恰好有偶数个自己认识的朋友与之在同一个聚会场所中。当然，每一只始祖鸟都必须在两处聚会场所之一。 </div>
<div>现在需要你给出一种安排方式。你只需要给出在上游的始祖鸟编号，如果有多组解，请输出任何一组解。 </div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>输入数据包含N+1行，第一行是数字N，代表始祖鸟的个数。 </div>
<div>
<div>之后的N行，第i+1行的第一个数字是M[i]，表示第i只鸟的朋友个数。之后有M[i]个数字依次为</div>
<div>F[i][1]，F[i][2]，…，F[i][M[i]]表示第i只始祖鸟朋友的标号。 </div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>输出数据包含2行，第一行有一个非负整数k，表示在上游参加聚会的始祖鸟个数。第二行有k个正整数，表示在这个k只始祖鸟的编号，你可以以任意顺序输出这些编号。如果无法满足要求，只输出一行“Impossible”。 </div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
3 2 3 4<br/>
2 1 3<br/>
4 2 1 4 5<br/>
2 1 3<br/>
1 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
1 2 3</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据满足1&lt;=N&lt;=2000</p><br/>
<p>应上传者要求，此题不公开，如有异议，请提出.</p><br/>
<p>鸣谢<span style="font-family: Arial; font-size: 14.3999996185303px; line-height: 19.0399990081787px;">Sakura_Lemon加强数据(未重测)--2017.7.29</span></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

