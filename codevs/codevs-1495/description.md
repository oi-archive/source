<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>N博士是一位著名的医学家，他以新颖的观点，高尚的医德以及甘于为科学事业奉献的敬业精神而享誉整个医学界。最近，他正着手研究多种危险药物共同对人体产生的作用。为了取得精确的第一手材料，N博士想亲身体验，即用自己的身体作为试验品进行一次人体试验。</p>
<p>由于是初次研究，N博士打算先试用A、B、C三种试剂。在整个试验过程中，N博士将每天注入自身<span style="font-family: 'Times New Roman';">1</span>JX的某种药剂（JX为体积单位，<span style="font-family: 'Times New Roman';">1</span>JX为人体每天能够承受的剂量）。这三种试剂的总剂量分别为VaJX、VbJX、VcJX（<span style="font-family: 'Times New Roman';">Va</span><span style="">、</span><span style="font-family: 'Times New Roman';">Vb</span><span style="">、</span><span style="font-family: 'Times New Roman';">Vc</span><span style="">为整数）。由于所有这些试剂都会对人体产生特殊效应，所以必须在上次用药后的一定时间内注入同种药剂，否则便会导致人体丧失某些正常的生理功能，这种药效的持续时间就叫做药效持续期，它是以天为单位的。</span></p>
<p>多种危险药物同时试用的一大危害就在于药物之间互相作用会产生负作用。由于复杂性，N博士仅考虑注入的药物与前一天注入的药物对人体产生的负影响，他的前期研究已经明确了前后两天的各种药物搭配对人体的危害，各种搭配都有一个危害值，值越大则说明危害越大。每次危害值的累加则为试验的总危害值。</p>
<p>N博士当然不希望由于未及时注入某种药物而使得自己丧失正常生理功能（所有药剂注射完后，N博士能够使用其他药物破坏先前药剂对人体产生特殊效应，不过在试验过程中却万万不可使用，否则便会前功尽弃），同时他也希望试验的总危害最小。现在就请你来帮助N博士设计一个合理的输药顺序。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>文件的第一行为Va，Vb，Vc三个数（0≤Va，Vb，Vc≤18），</p>
<p>第二行分别为三种药剂的药效持续期Pa，Pb，Pc（0≤Pa，Pb，Pc≤5），</p>
<p>余下的为一个3*3的表格： Gaa Gab Gac </p>
<p>                            Gba Gbb Gbc </p>
<p>                            Gca Gcb Gcc </p>
<p>  其中Gcb表示前后两天分别注入C、B两种试剂对人体所产生的危害值（是100以内的正整数）。</p>
<p>  相邻两项间用一个或多个空格隔开。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">文件仅两行，第一行为你所得到的合理输药顺序的最小危害值。若无合理顺序则仅输出&ldquo;No&nbsp;answer.&rdquo;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>          5 5 5</p>
<p>          3 4 4</p>
<p>          1 2 3</p>
<p>          2 4 1</p>
<p>          5 1 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>          21</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>