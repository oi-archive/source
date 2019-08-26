
# Description

<div class="content"><div>酒足饭饱之后。</div>
<div>一帮人都喝醉了。</div>
<div>嘛，由于酒驾查的很严格，所以说接下来就是送客人回家的难题了。</div>
<div>嘛，接下来就是操蛋的设定。</div>
<div>小T把喝醉的人分成了好多组，每一组要用一部车把他们送回家睡大觉。</div>
<div>然后呢，每一组可以租用的车子也是不一样的，具体而言，对于第i组，有T[i]种的车子(型号可能相同)来把他们送回去。当然咯，小T只需要安排一辆车子就可以送走这一组所有的人了。由于囊中羞射，小T一定只会每组安排一辆车。</div>
<div>更具体的，送回家的费用，是所有租用的车子里面，型号最大的和型号最小的车子，型号的差距。（尼玛，你这是啥题面啊，有TM啥关系啊</div>
<div>但是呢= =，由于喝醉的人是相继的醉，不可能啊出现如下场景：</div>
<div>“大家一起醉吧。”</div>
<div>“好！”</div>
<div>一杯而下，全倒了。。。</div>
<div>所以呢，这样动态的安排车子，又给小T加了不少麻烦。也就是说，小T需要处理如下两个操作。</div>
<div>1.有一组人醉倒了。</div>
<div>2.询问当前所有醉倒的人送回家的费用。</div>
<div>但是又出现了一个问题。</div>
<div>小A说：“你能解决，老子给你1000W。”</div>
<div>小T说：“你还不如把车子全租了。”</div>
<div>小A说：“………………”</div>
<div>小A思考了一下又说：“既然不能全租，那就来个限定吧，租车的型号必须大于等于L。”</div>
<div>小T给了小A一巴掌。。。。。。</div>
<div>“GFS就能拽？”</div>
<div></div></div>

# Input

<div class="content"><div>
<div>第一行有一个正整数，N，表示操作的总数目。</div>
<div>接下来N行，每行首先包含了一个字母C或者Q。</div>
<div>如果是C，则表示，现在有一组人醉倒了，他们需要租车。C的后面有一个正整数T[]表示的是这一组有T[]部车子可以租。接下来有T[]个数字，分别表示他们可以租的车子的型号。</div>
<div>如果是Q，则后面有一个限制，L，表示对于当前所有已经醉的组，算出他们租车的最小费用。并且租车的最小型号是L。</div>
<div></div>
</div>
<div></div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每一个Q操作，输出最小费用。如果无法安排，请阁下输出-1。</div>
<div></div>
<div></div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
C 3 1 5 9<br/>
C 3 2 5 11<br/>
Q 0<br/>
C 3 2 8 19<br/>
Q 8</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
3</span></div>

# Hint

<div class="content"><p></p><div>第一问选择5 5。</div><br/>
<div>第二问选择8 9 11。1 2 2由于限制不能选择。</div><br/>
<div>M&lt;=200000,车子数量总和&lt;=550000, 所有车子的型号均&gt;=0，&lt;10^9。询问的L也&lt;10^9。</div><br/>
<p></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名提供">By 佚名提供</a></p></div>

