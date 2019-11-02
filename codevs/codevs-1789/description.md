<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>新的技术正冲击着手机通讯市场，对于各大运营商来说，这既是机遇，更是 挑战。THU 集团旗下的 CS&amp;T 通讯公司在新一代通讯技术血战的前夜，需要做 太多的准备工作，仅就站址选择一项，就需要完成前期市场研究、站址勘测、最 优化等项目。 在前期市场调查和站址勘测之后，公司得到了一共 N 个可以作为通讯信号中 转站的地址，而由于这些地址的地理位置差异，在不同的地方建造通讯中转站需 要投入的成本也是不一样的，所幸在前期调查之后这些都是已知数据：建立第 i 个通讯中转站需要的成本为 Pi（1≤i≤N）。 另外公司调查得出了所有期望中的用户群，一共 M 个。关于第 i 个用户群的 信息概括为 Ai, Bi和 Ci：这些用户会使用中转站 Ai和中转站 Bi进行通讯，公司 可以获益 Ci。（1≤i≤M, 1≤Ai, Bi≤N） THU 集团的 CS&amp;T 公司可以有选择的建立一些中转站（投入成本），为一些 用户提供服务并获得收益（获益之和）。那么如何选择最终建立的中转站才能让 公司的净获利最大呢？（净获利 = 获益之和 – 投入成本之和）</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件中第一行有两个正整数 N 和 M 。 第二行中有 N 个整数描述每一个通讯中转站的建立成本，依次为 P1, P2, …, PN 。 以下 M 行，第(i + 2)行的三个数 Ai, Bi和 Ci描述第 i 个用户群的信息。 所有变量的含义可以参见题目描述。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>你的程序只要向输出文件输出一个整数，表示公司可以得到的最大净获利。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 5</p>
<p>1 2 3 4 5</p>
<p>1 2 3</p>
<p>2 3 4</p>
<p>1 3 3</p>
<p>1 4 2</p>
<p>4 5 3 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>选择建立 1、2、3 号中转站，则需要投入成本 6，获利为 10，因此得到最大 收益 4。</p>
<p>80%的数据中：N≤200，M≤1 000。</p>
<p>100%的数据中：N≤5 000，M≤50 000，0≤Ci≤100，0≤Pi≤100。 </p>
</div>
</div>