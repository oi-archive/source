
# Description

<div class="content"><div>
<div>
<div>六一儿童节到了， SHUXK 被迫陪着M个熊孩子玩一个无聊的游戏：有N个盒子从左到右排成一排，第i个盒子里装着Ai个气球。</div>
<div>SHUXK 要进行Q次操作，每次从某一个盒子里拿出一个没被踩爆的气球，然后熊孩子们就会立刻把它踩爆。</div>
<div>这M个熊孩子每个人都指定了一个盒子区间[Li, Ri]。 如果某一个时刻，一个熊孩子发现自己选定的盒子区间[Li, Ri]中的所</div>
<div>有气球都已经被踩爆了，他就会非常高兴（显然之后他一直会很高兴）。</div>
<div>为了不辜负将自己的任务强行塞给 SHUXK 的那个人的期望， SHUXK 想向你询问： </div>
<div>他每次操作过后会有多少个熊孩子很高兴。</div>
</div>
</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含两个正整数N和M，分别表示盒子和熊孩子的个数。</div>
<div>第二行包含N个正整数Ai（ 1 &lt; = Ai &lt; = 10^5），表示每个盒子里气球的数量。</div>
<div>以下M行每行包含两个正整数Li, Ri（ 1 &lt; = Li &lt; = Ri &lt; = N），分别表示每一个熊孩子指定的区间。</div>
<div>以下一行包含一个正整数Q，表示 SHUXK 操作的次数。</div>
<div>以下Q行每行包含一个正整数X，表示这次操作是从第X个盒子里拿气球。为</div>
<div>了体现在线，我们对输入的X进行了加密。</div>
<div>假设输入的正整数是x&#39;，那么真正的X = (x&#39; + Lastans − 1)Mod N + 1。其</div>
<div>中Lastans为上一次询问的答案。对于第一个询问， Lastans = 0。</div>
<div>输入数据保证1 &lt; = x&#39; &lt; = 10^9， 且第X个盒子中有尚未被踩爆的气球。</div>
<div>N &lt; = 10^5 ,M &lt; = 10^5 �,Q &lt; = 10^5</div>
<p></p></div>

# Output

<div class="content"><div>包含Q行，每行输出一个整数，表示 SHUXK 一次操作后询问的</div>
<div>答案。答案的顺序应与输入数据的顺序保持一致。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
1 1 1 1 1<br/>
5 5<br/>
2 2<br/>
1 3<br/>
5 <br/>
4 <br/>
2 <br/>
5 <br/>
2 <br/>
3</span></div>

# Sample Output

<div class="content"><span class="sampledata">0 <br/>
1 <br/>
1 <br/>
2 <br/>
3<br/>
【样例说明】<br/>
实际上每次操作的盒子是： 4 2 1 3 5<br/>
在第二次操作后，第二个熊孩子会高兴 （区间[2,2]中的气球已经全部被踩爆）。<br/>
在第四次操作后，第三个熊孩子会高兴（区间[1,3]中的气球已经全部被踩爆）。<br/>
在第五次操作后，第一个熊孩子会高兴（区间[5,5]中的气球已经全部被踩爆）。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

