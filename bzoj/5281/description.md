
# Description

<div class="content"><div>FarmerJohn要带着他的N头奶牛，方便起见编号为1…N，到农业展览会上去，参加每年的达牛秀！他的第i头奶牛重</div>
<div>量为wi，才艺水平为ti，两者都是整数。在到达时，FarmerJohn就被今年达牛秀的新规则吓到了：</div>
<div></div>
<div>（一）参加比赛的一组奶牛必须总重量至少为W</div>
<div></div>
<div>（这是为了确保是强大的队伍在比赛，而不仅是强大的某头奶牛），并且</div>
<div></div>
<div>（二）总才艺值与总重量的比值最大的一组获得胜利。</div>
<div></div>
<div>FJ注意到他的所有奶牛的总重量不小于W，所以他能够派出符合规则（一）的队伍。帮助他确定这样的队伍中能够</div>
<div>达到的最佳的才艺与重量的比值。</div>
<div></div></div>

# Input

<div class="content"><div>输入的第一行包含N和W。下面N行，每行用两个整数wi和ti描述了一头奶牛。</div>
<div>1≤N≤250</div>
<div>1≤W≤1000</div>
<div>1≤wi≤10^6</div>
<div>1≤ti≤10^3</div>
<div></div></div>

# Output

<div class="content"><div>请求出Farmer用一组总重量最少为W的奶牛最大可能达到的总才艺值与总重量的比值。</div>
<div>如果你的答案是A，输出1000A向下取整的值，以使得输出是整数</div>
<div>（当问题中的数不是一个整数的时候，向下取整操作在向下舍入到整数的时候去除所有小数部分）。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 15<br/>
20 21<br/>
10 11<br/>
30 31</span></div>

# Sample Output

<div class="content"><span class="sampledata">1066<br/>
在这个例子中，总体来看最佳的才艺与重量的比值应该是仅用一头才艺值为11、重量为10的奶牛，但是由于我们需<br/>
要至少15单位的重量，最优解最终为使用这头奶牛加上才艺值为21、重量为20的奶牛。这样的话才艺与重量的比值<br/>
为(11+21)/(10+20)=32/30=1.0666666...，乘以1000向下取整之后得到1066。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

