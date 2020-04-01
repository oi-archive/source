
# Description

<div class="content"><p>澳洲猴和澳洲袋鼠是好朋友，他们经常在一起交流拳♂击，摔♂跤的经验。 <br/>
众所周知，澳洲袋鼠的胸前有一个袋子，我们认为一个澳洲袋鼠的体积为Ai，那么它的袋子的大小就是Bi，显然Bi是严格小于Ai的，当然如果有东西装在这个袋鼠的袋子里面，那么袋鼠的体积仍然是Ai。 <br/>
某一次，澳洲猴在摔♂跤比赛中赢了袋鼠，于是，袋鼠答应澳洲猴来做一个游戏。这个游戏是这样的：全程都是澳洲猴操作，每次他可以选择一个袋鼠i放到袋鼠j的袋子里，但是这要满足：1、袋鼠i目前不在其他袋鼠的袋子里；2、袋鼠j目前袋子里没有其他袋鼠；3、Ai澳洲猴每次会将这n个袋鼠操作到不能操作为止，它想求出最终状态一共有多少可能，由于数字很大，请模(1e9+7)输出。 <br/>
</p></div>

# Input

<div class="content"><p>输入的第一行为n。 <br/>
接下来n行是Ai,Bi，表示每个袋鼠的大小和它的袋子大小。</p></div>

# Output

<div class="content"><p>输出一行，即总共的方案数模(1e9+7)的余数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 <br/>
4 3 <br/>
3 1 <br/>
6 5 <br/>
2 1 <br/>
4 2 </span></div>

# Sample Output

<div class="content"><span class="sampledata">4 </span></div>

# Hint

<div class="content"><p></p><p>样例解释： <br/><br/>
1、将袋鼠4放入袋鼠3； <br/><br/>
2、将袋鼠4放入袋鼠1，将袋鼠1放入袋鼠3； <br/><br/>
3、将袋鼠4放入袋鼠1，将袋鼠2放入袋鼠3； <br/><br/>
4、将袋鼠4放入袋鼠1，将袋鼠5放入袋鼠3。 <br/><br/>
对于100%的数据 n&lt;=300,1&lt;=Ai<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

