
# Description

<div class="content"><div>下课了，露露、花花和萱萱在课桌上用正三棱柱教具和尺子摆起了一个“跷跷板”。</div>
<div>     这个“跷跷板”的结构是这样的：底部是一个侧面平行于地平面的正三棱柱教具，</div>
<div>上面 摆着一个尺子，尺子上摆着若干个相同的橡皮。尺子有 2n + 1 条等距的刻度线，</div>
<div>第 n + 1 条 刻度线恰好在尺子的中心，且与正三棱柱的不在课桌上的棱完全重合。</div>
<div>     露露发现这个“跷跷板”是不平衡的（尺子不平行于地平面）。于是，她又在尺</div>
<div>子上放 了几个橡皮，并移动了一些橡皮的位置，使得尺子的 2n + 1 条刻度线上都恰</div>
<div>有一块相同质 量的橡皮。“跷跷板”平衡了，露露感到很高兴。</div>
<div>     花花觉得这样太没有意思，于是从尺子上随意拿走了 k 个橡皮。令她惊讶的事</div>
<div>情发生了： 尺子依然保持着平衡！</div>
<div>     萱萱是一个善于思考的孩子，她当然不对尺子依然保持平衡感到吃惊，因为这</div>
<div>只是一个 偶然的事件罢了。令她感兴趣的是，花花有多少种拿走 k 个橡皮的方法</div>
<div>，使得尺子依然保 持平衡？</div>
<div>当然，为了简化问题，她不得不做一些牺牲——假设所有橡皮都是拥有相同质量的</div>
<div> 质点。但即使是这样，她也没能计算出这个数目。放学后，她把这个问题交给了她</div>
<div>的哥哥/ 姐姐——Hibarigasaki 学园学生会会长，也就是你。当然，由于这个问题</div>
<div>的答案也许会过于 庞大，你只需要告诉她答案 mod p 的值。</div>
<div></div></div>

# Input

<div class="content"><p>第一行，一个正整数，表示数据组数 T（萱萱向你询问的次数）。   </p>
<div>
<div>  接下来 T 行，每行 3 个正整数 n, k, p。 </div>
<div></div>
</div></div>

# Output

<div class="content"><p>共 T 行，每行一个正整数，代表你得出的对应问题的答案。 </p>
<div>
<div></div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">10 <br/>
6 5 10000 <br/>
4 1 10000 <br/>
9 6 10000 <br/>
4 6 10000 <br/>
5 1 10000 <br/>
8318 10 9973 <br/>
9862 9 9973 <br/>
8234 9 9973 <br/>
9424 9 9973 <br/>
9324 9 9973  </span></div>

# Sample Output

<div class="content"><span class="sampledata">73<br/>
1<br/>
920<br/>
8<br/>
1<br/>
4421<br/>
2565<br/>
0<br/>
446<br/>
2549</span></div>

# Hint

<div class="content"><p></p><p> T &lt;= 20，1 &lt;= n &lt;= 10000，1 &lt;= k &lt;= 10，2 &lt;= p &lt;= 10000，且 k &lt;= 2n+1。 </p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢佚名上传">鸣谢佚名上传</a></p></div>

