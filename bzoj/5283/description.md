
# Description

<div class="content"><div>
<div>大家的好朋友小 L 来到了博弈的世界。Alice 和 Bob 在玩一个双人游戏。每一轮中，Alice 有 p 的概率胜利，1</div>
<div>-p 的概率失败，不会出现平局。双方初始时各有 0 分，当一个人胜利的时候，他会获得一分，失败则扣掉一分。</div>
<div>遗憾的是，博弈论世界的人目前是无法理解负数的，因此，如果某个人输掉一轮比赛的时候他只有 0 分，那么他</div>
<div>就不会被扣分（对方会照常加一分）。游戏一共要进行 N+M 轮，Alice 想请你帮她算算在游戏结束时她的得分的</div>
<div>数学期望。&#34;这算啥，我小 L 分分钟搞定！&#34;。比小 L 更熟练的你当然也是随手就算出来了，但就在你打算告诉 A</div>
<div>lice 答案之前，博弈论世界之神--temporaryDO 出现了，他给大家带来了一个重要信息：这 N+M 轮游戏中， Ali</div>
<div>ce 恰好赢了 N 轮！熟知条件概率那套理论的你立刻注意到，你需要修改自己的计算方法来得到正确的答案了。为</div>
<div>了避免精度问题，请将结果对 10^9+7 取模。即，我们的数据保证答案是一个有理数 p/q ，且有 10^9+7与q互质</div>
<div>，你只需要找到一个整数 x∈[0,10^9+7) 使得 qx≡p(mod 10^9+7) 即可。</div>
</div></div>

# Input

<div class="content"><div>
<div>输入的第一行包含两个正整数 T, P&#39;</div>
<div>其中 T 表示数据组数，P&#39;/1000 表示 p ，即 Alice 在每轮游戏中的获胜概率。</div>
<div>接下来 T 行，每行两个非负整数 N,M，表示一组数据。</div>
<div>N+M,T≤2.5×10^5， 0&lt;P′&lt;1000</div>
</div></div>

# Output

<div class="content"><div>输出 T 行，每行一个整数，表示对应数据的答案。</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 500<br/>
1 1<br/>
2 3<br/>
4 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">500000004<br/>
200000002<br/>
728571435<br/>
样例 1 解释<br/>
每一轮游戏 Alice 均有 1/2 的概率胜利。<br/>
对于第一组数据，Alice 的胜利可能在第一轮或第二轮，并且概率相等。<br/>
若她在第一轮胜利，则最终得分为 0，否则她的得分为 1。故期望为 1/2，验证发现 2×500000004≡1(mod10^9+7)。<br/>
对于第二组数据，所求期望为 3/5。</span></div>

# Hint

<div class="content"><p></p><p><span style="color: rgba(0, 0, 0, 0.870588); font-family: &#39;Open Sans&#39;, &#39;Source Han Sans SC&#39;, &#39;Noto Sans CJK SC&#39;, &#39;PingFang SC&#39;, &#39;Hiragino Sans GB&#39;, &#39;Microsoft Yahei&#39;, sans-serif; font-size: 14px; line-height: 19.9990005493164px;">来自 CodePlus 2018 3 月赛，清华大学计算机科学与技术系学生算法与竞赛协会 荣誉出品。</span><br style="box-sizing: inherit; color: rgba(0, 0, 0, 0.870588); font-family: &#39;Open Sans&#39;, &#39;Source Han Sans SC&#39;, &#39;Noto Sans CJK SC&#39;, &#39;PingFang SC&#39;, &#39;Hiragino Sans GB&#39;, &#39;Microsoft Yahei&#39;, sans-serif; font-size: 14px; line-height: 19.9990005493164px;"/><br/>
<span style="color: rgba(0, 0, 0, 0.870588); font-family: &#39;Open Sans&#39;, &#39;Source Han Sans SC&#39;, &#39;Noto Sans CJK SC&#39;, &#39;PingFang SC&#39;, &#39;Hiragino Sans GB&#39;, &#39;Microsoft Yahei&#39;, sans-serif; font-size: 14px; line-height: 19.9990005493164px;">Credit：idea/吕欣　命题/吕欣　验题/陈俊锟</span><br style="box-sizing: inherit; color: rgba(0, 0, 0, 0.870588); font-family: &#39;Open Sans&#39;, &#39;Source Han Sans SC&#39;, &#39;Noto Sans CJK SC&#39;, &#39;PingFang SC&#39;, &#39;Hiragino Sans GB&#39;, &#39;Microsoft Yahei&#39;, sans-serif; font-size: 14px; line-height: 19.9990005493164px;"/><br/>
<span style="color: rgba(0, 0, 0, 0.870588); font-family: &#39;Open Sans&#39;, &#39;Source Han Sans SC&#39;, &#39;Noto Sans CJK SC&#39;, &#39;PingFang SC&#39;, &#39;Hiragino Sans GB&#39;, &#39;Microsoft Yahei&#39;, sans-serif; font-size: 14px; line-height: 19.9990005493164px;">Git Repo：</span><a href="https://git.thusaac.org/publish/CodePlus3" style="box-sizing: inherit; color: rgb(65, 131, 196); text-decoration: none; font-family: &#39;Open Sans&#39;, &#39;Source Han Sans SC&#39;, &#39;Noto Sans CJK SC&#39;, &#39;PingFang SC&#39;, &#39;Hiragino Sans GB&#39;, &#39;Microsoft Yahei&#39;, sans-serif; font-size: 14px; line-height: 19.9990005493164px; background-image: initial; background-attachment: initial; background-size: initial; background-origin: initial; background-clip: initial; background-position: 0px 0px; background-repeat: initial;">https://git.thusaac.org/publish/CodePlus3</a><br style="box-sizing: inherit; color: rgba(0, 0, 0, 0.870588); font-family: &#39;Open Sans&#39;, &#39;Source Han Sans SC&#39;, &#39;Noto Sans CJK SC&#39;, &#39;PingFang SC&#39;, &#39;Hiragino Sans GB&#39;, &#39;Microsoft Yahei&#39;, sans-serif; font-size: 14px; line-height: 19.9990005493164px;"/><br/>
<span style="color: rgba(0, 0, 0, 0.870588); font-family: &#39;Open Sans&#39;, &#39;Source Han Sans SC&#39;, &#39;Noto Sans CJK SC&#39;, &#39;PingFang SC&#39;, &#39;Hiragino Sans GB&#39;, &#39;Microsoft Yahei&#39;, sans-serif; font-size: 14px; line-height: 19.9990005493164px;">感谢腾讯公司对此次比赛的支持。</span></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

