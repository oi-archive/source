
# Description

<div class="content"><div>
<div>夏日那让人喘不过气的酷热将奶牛们的烦躁情绪推到了最高点．最终，约翰决定建一个人工湖供奶牛消暑之用．为</div>
<div>了使湖看起来更加真实，约翰决定将湖的横截面建成N(1≤N≤105)个连续的平台高低错落的组合状，所有的平台从</div>
<div>左到右按1到N依次编号．当然咯，在湖中注入水后，这些平台都将被淹没．    平台i在设计图上用它的宽度wi(l</div>
<div>≤wi≤1000)和高度（你可以理解为该平台顶离约翰挖的地基的高度）Hi.（1≤Hi≤1000000）来描述的．所有平台</div>
<div>的高度都是独一无二的．湖的边缘可以视为无限高的平台．下面给出了一张约翰的设计图：</div>
</div>
<div><img height="361" width="285" alt="" src="/source/bzoj/1595/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMS8yMigxMykuanBn.jpg"/></div>
<div> 按约翰的设想，在坑挖好后，他会以1单位每分钟的速度往最低的那个平台上注水．水在离开水管后立即下落，直</div>
<div>到撞到平台顶或是更早些时候注入的水然后，与所有常温下的水一样，它会迅速地流动、扩散．简单起见，你可以</div>
<div>认为这些都是在瞬间完成的．约翰想知道，对于每一个平台，它的顶部是从哪个时刻开始，与水面的距离至少为1</div>
<div>单位长度．注意：数据不保证答案全部在32位整型变量的范围内</div></div>

# Input

<div class="content"><div>* 第1行: 1个整数，N</div>
<div>* 第2..N+1行: 第i+1行为2个用空格隔开的整数W_i、H_i，描述了第i个平台</div></div>

# Output

<div class="content"><p><span style="font-size: medium">* 第1..N行: 第i行为1个整数，表示平台i的顶到水面的距离从何时开始大于1 单位长度 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
4 2<br/>
2 7<br/>
6 4<br/>
输入说明:<br/>
输入对应了题目中给出的例子，一共有3个平台，FJ选定的注水点在最低的<br/>
1号平台上方。</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
50<br/>
26<br/>
输入对应了题目中给出的例子，一共有3个平台，约翰选定的注水点在最低的1号平台上方．    <br/>
4分钟后乎台1被淹没．26分钟后平台3被淹没．50分钟后平台2被淹没．</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

