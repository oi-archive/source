
# Description

<div class="content"><div></div>
<div>他突然发现比赛中有一个Hack功能：</div>
<div>在比赛过程中，若提交了一道题的代码，并且过了这道题的pretest，那么你可以选择“锁定”这</div>
<div>道题，而一旦“锁定”，这道题的代码就不能更改了，此时你可以查看其他选手此题的代码，你可以</div>
<div>对有问题的代码进行Hack，即构造一组数据，使得它不能Accepted。若Hack成功，会得到一些加</div>
<div>分，当然Hack失败是会扣分的。</div>
<div>这天Wayne又在参加比赛。A题是一道比较简单的字符串题目，Wayne在做出了此题后想尝</div>
<div>试 Hack，于是他点开了一些人的代码。他发现很多人用哈希过了pretest，而且大部分人的哈希算</div>
<div>法是这样的：</div>
<div>设字符串S，长度为N，设一个正整数P，那么计H=∑P^(N-i-1)*Si(其中0&lt;=i&lt;N)</div>
<div>符串下标从 0 开始，而Si代表对应字符的ASCII码值。注意H可能会很大，所以可以做一项简单</div>
<div>的处理，就是把Hmod 232 作为哈希值。</div>
<div>Wayne看到这些简单的代码非常不爽，所以他找了K个长度不超过L的字符串S，想知道是</div>
<div>否存在长度不超过L的字符串T，使得T不同于S但是哈希值相同。若有，他还想知道字典序最</div>
<div>小的T是什么。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div></div>
<div>第一行三个正整数P，L和K。</div>
<div>接下来共K行，每行一个字符串S。</div>
<div>
<p></p>
</div></div>

# Output

<div class="content"><div></div>
<div>对每个字符串S输出一行。</div>
<div>若找得到字符串T，则输出字典序最小的；否则输出-1。</div>
<div>
<p></p>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">32768 3 2<br/>
ZZZ<br/>
A</span></div>

# Sample Output

<div class="content"><span class="sampledata">BZZ<br/>
-1<br/>
</span></div>

# Hint

<div class="content"><p></p><div>P&lt;=2^31,L&lt;=8,K&lt;=15</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

