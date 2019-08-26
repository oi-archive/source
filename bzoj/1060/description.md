
# Description

<div class="content"><div>　　小Q在电子工艺实习课上学习焊接电路板。一块电路板由若干个元件组成，我们不妨称之为节点，并将其用数</div>
<div>字1,2,3….进行标号。电路板的各个节点由若干不相交的导线相连接，且对于电路板的任何两个节点，都存在且仅</div>
<div>存在一条通路（通路指连接两个元件的导线序列）。在电路板上存在一个特殊的元件称为“激发器”。当激发器工</div>
<div>作后，产生一个激励电流，通过导线传向每一个它所连接的节点。而中间节点接收到激励电流后，得到信息，并将</div>
<div>该激励电流传向与它连接并且尚未接收到激励电流的节点。最终，激烈电流将到达一些“终止节点”——接收激励</div>
<div>电流之后不再转发的节点。激励电流在导线上的传播是需要花费时间的，对于每条边e，激励电流通过它需要的时</div>
<div>间为te，而节点接收到激励电流后的转发可以认为是在瞬间完成的。现在这块电路板要求每一个“终止节点”同时</div>
<div>得到激励电路——即保持时态同步。由于当前的构造并不符合时态同步的要求，故需要通过改变连接线的构造。目</div>
<div>前小Q有一个道具，使用一次该道具，可以使得激励电流通过某条连接导线的时间增加一个单位。请问小Q最少使用</div>
<div>多少次道具才可使得所有的“终止节点”时态同步？</div></div>

# Input

<div class="content"><div>　　第一行包含一个正整数N，表示电路板中节点的个数。第二行包含一个整数S，为该电路板的激发器的编号。接</div>
<div>下来N-1行，每行三个整数a , b , t。表示该条导线连接节点a与节点b，且激励电流通过这条导线需要t个单位时</div>
<div>间</div></div>

# Output

<div class="content"><p>　　仅包含一个整数V，为小Q最少使用的道具次数</p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
1<br/>
1 2 1<br/>
1 3 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">N ≤ 500000，te ≤ 1000000<br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

