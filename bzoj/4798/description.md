
# Description

<div class="content"><div>有n个人参加一场比赛，需要把他们分成若干组，然后就会给他们每人一个编号。</div>
<div>编号发放的规则：</div>
<div>1：每个组的队长为组员中名字字典序最小的那个人</div>
<div>2：每个组的编号为这个组的队长名字的排名（按字典序，且只有队长参与排名）</div>
<div>3：每个人的编号即为他所在组的编号</div>
<div>然后将所有人按字典序排好，根据他们的编号就可以产生一个序列。</div>
<div></div>
<div>例如：</div>
<div>有6个人，分为3组</div>
<div>（Calvin，Hobbes，Susie），（Batman），（Jerry ，Tom）  下划线的是队长</div>
<div>（Batman）为第一组，（Calvin，Hobbes，Susie）为第二组，（Jerry ，Tom）为第三组</div>
<div>所以6人编号分别为Batman 1 ，Calvin 2，Hobbes 2，Susie 2，Jerry 3，Tom 3。</div>
<div>再将6人名字排序，有</div>
<div>Batman 1</div>
<div>Calvin 2</div>
<div>Hobbes 2</div>
<div>Jerry 3</div>
<div>Susie 2</div>
<div>Tom 3</div>
<div>所以序列为1 2 2 3 2 3。</div>
<div>现在给出一个序列，求它按照字典序是第多少大的，答案mod  1000007。（具体意思见样例解释）</div>
<p></p></div>

# Input

<div class="content"><div>第一行一个n代表有多少个人参赛</div>
<div>接下来一行n个数，代表序列</div>
<div>n&lt;=10000，保证给出的序列是存在的</div>
<p></p></div>

# Output

<div class="content"><div>输出这个序列是第几大的，mod 1000007。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
1 2 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
样例解释<br/>
有三个人，假设他们叫A、B、C<br/>
当为（A，B，C）时，序列为 1 1 1<br/>
当为（A，B），（C）时，序列为1 1 2<br/>
当为（A，C），（B）时，序列为1 2 1<br/>
当为（A），（B，C）时，序列为1 2 2<br/>
当为（A），（B），（C）时，序列为1 2 3.<br/>
所以，1 2 2是第4大的<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

