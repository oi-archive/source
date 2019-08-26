
# Description

<div class="content"><div>小Q同学正在和糖老师一起打(d)牌(p)。这个游戏需要52张牌，分为四种花色（H表示红心，S表示黑桃，C表示梅花</div>
<div>，D表示方块），每种花色有A,K,Q,J,10,9,8,7,6,5,4,3,2这么多张牌，其中A是最大的，2是最小的。游戏的第一</div>
<div>轮从小Q同学开始，他会先展示一张牌，然后轮到糖老师展示一张牌。双方都展示完手牌之后进入结算环节，展示</div>
<div>较大的牌的人会获得这一轮的胜利（如果两个人展示的牌大小相同那么先展示牌的人获胜），并且得到较大的牌对</div>
<div>应的分值，分值就是牌上的数字，比如J是11，Q是12，K是13，A是1。结算后扔掉这一轮展示的牌，然后从上一轮</div>
<div>的获胜者开始下一轮，游戏进行到双方打完所有牌为止。为了简单起见，现在每个人都只有两张牌，并且全过程中</div>
<div>双方都能看到对方的手牌，也就是明牌打。你需要求出两个人都使用最优策略的情况下，小Q同学的得分减去糖老</div>
<div>师的得分的最大值。</div>
<div></div>
<div></div>
<div></div></div>

# Input

<div class="content"><div>第一行是一个正整数 T (1≤T≤10000)，表示测试数据的组数。</div>
<div>每组测试数据包含两行，每行有两张牌，分别表示小Q和糖老师手上的牌。每张牌会按照 XY 的格式给出，其中 X </div>
<div>是A,K,Q,J,T(表示10),9,8,7,6,5,4,3,2,1之一， Y 是花色(H,S,C,D之一)。保证任何一张牌至多出现一次。</div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每组测试数据，输出一个整数，表示结果。</div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
AH 2S<br/>
3C 4D<br/>
2H 5S<br/>
3C 4D</span></div>

# Sample Output

<div class="content"><span class="sampledata">-3<br/>
1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tangjz提供试题">鸣谢Tangjz提供试题</a></p></div>

