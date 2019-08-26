
# Description

<div class="content"><div>有一枚硬币，抛出正面H的概率为a/b，抛出反面T的概率为1-a/b。现在TT小朋友开始玩丢硬币的游戏，并且把每次</div>
<div>抛出的结果记录下来，正面记为H，反面记为T，于是她得到了一个抛硬币序列HTHHT…。她突然想到一个问题：在</div>
<div>抛出正面和反面概率都是1/2的情况下，要使得抛出的序列出现目标序列HT，期望要抛多少次。然而经过1秒的思考</div>
<div>以后她发现，若第一次抛出的是T，那么还需要期望抛出HT的次数，如果第一次抛出的是H，则期望只需要抛出T的</div>
<div>次数，而期望抛出T的次数显然是2。她设抛出HT的期望次数是x，则得到了方程：</div>
<div></div>
<div>x=1+(1/2*x+1/2*2) </div>
<div></div>
<div>解得x=4，所以抛出HT的期望次数是4次。</div>
<div></div>
<div>她在解决了这个弱化很多的问题以后，开始思考对于一般情况下，抛出正反面的概率不一定相同，且抛出的目标序</div>
<div>列不一定为HT时需要的期望步数。然而经过很长一段时间的苦思冥想仍然无果，于是她开始求助于你。</div>
<div></div></div>

# Input

<div class="content"><div>第一行两个数a,b。意义如题目描述。</div>
<div>接下来1行一个只包含’H’和’T’的字符串S。表示要抛出的目标序列。</div>
<div>a=b,b=100,|s|&lt;=1000</div>
<div></div></div>

# Output

<div class="content"><div>输出仅一行p/q，其中p和q均为正整数且互质，表示抛出目标序列S所需要的期望步数。</div>
<div>注意，若q为1时，不省略/1。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">1 2<br/>
HT</span></div>

# Sample Output

<div class="content"><span class="sampledata">4/1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

