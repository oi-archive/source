<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>　　经过一番周折，精英队伍的队员们终于来到了关押applepi的牢狱面前。心中神一般的领袖applepi就在眼前，队员们都不由自主地跪烂膝盖……不过令他们沮丧的是，牢狱的大锁没有钥匙孔，黑魔法师Vani根本就没有指望它再被打开。幸好队员们携带了新研制的终极武器——k型氙激光器（Xenon Laser - k，代号XLk），可以用来破拆这把锁。不过作为一道终极武器，它的启用规则异常严格。<br>　　Xenon Laser - k上共有N个波段能够发射激光，每个波段可以用一个闭区间[a<sub>i</sub>，b<sub>i</sub>]来表示，其中a<sub>i</sub>，b<sub>i</sub>为正整数，b<sub>i-1</sub>＜a<sub>i</sub>≤b<sub>i</sub>。对于两个数字p和q，如果对于这N个波段内的任意一个整数num，把它在十进制表示下的后k位中某一位上的p换成q（或者q换成p），都满足得到的整数仍然在这N个波段内，那么称在该激光器中，数字p和q是k等价的。我们称两两之间k等价的数字组成一个k等价类。<br>　　激光器附带了9个发射匣，代表1~9这9个数字。只有把同一个等价类的数字对应的发射匣安置在一排上，Xenon Laser - k才能够启动。给定个波段，现在就请你求出1~9这9个数字分成了哪些等价类，并且每行输出一个等价类。<br>　　本题描述比较抽象，请参考样例解释。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>　　第一行两个整数N，k。<br>　　接下来N行每行两个整数a<sub>i</sub>，b<sub>i</sub>。a<sub>i</sub>，b<sub>i</sub>为正整数，满足b<sub>i-1</sub>＜a<sub>i</sub>≤b<sub>i</sub>。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>　　每行一个k等价类，各行之内都按照数字从小到大排序，数字中间没有空格，行与行之间按照等价类中最小的数字从小到大排序。具体格式参考样例。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【样例输入1】<br>1 1<br>1 566</p>
<p>【样例输入2】<br>1 2<br>30 75</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【样例输出1】<br>123456<br>789</p>
<p>【样例输出2】<br>12<br>345<br>6<br>7<br>89</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>　　第一个样例中k = 1，只允许修改个位。对于1~559这些数，个位无论如何修改都在波段内。对于560~566这些数，个位修改为大于等于7的数字时（例如562的2修改为8），就不在波段内了。因此1~6和7~9属于不同的等价类。<br>　　第二个样例每一位上都可以修改。修改方法与上面一个样例类似。</p>
<p>　　对于25% 的数据，1≤n≤50，1≤a<sub>i</sub>≤b<sub>i</sub>≤600。<br>　　对于另25% 的数据，n = 1。<br>　　对于另30% 的数据，k = 1。<br>　　对于100% 的数据，1≤n≤10000，1≤k≤19，1≤a<sub>i</sub>≤b<sub>i</sub>≤10<sup>18</sup>。<br>　　在所有的数据中，均匀分布着25% 的随机数据。</p>
<p>来源：Nescafe 17</p>
</div>
</div>