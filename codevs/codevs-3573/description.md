<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: SimSun;">Alice 和 Marisa 都住在一个巨大的由 N 个路口与 M 条单向小道构成的森林中。 Marisa<br><span style="">非常喜欢到 Alice 家里去玩，但是 Alice 并不喜欢这位鲁莽的来客。 Alice 非常擅长观察，<br><span style="">因此每当她发现 Marisa 走了一条与之前完全相同的路径来到她家时， 她就会装作不在家，<br><span style="">Marisa 就只好败兴而归。 Marisa 发现了这个秘密， 因此她决定每次走不同的路径到 Alice<br><span style="">家。<br><span style="">Marisa 体力有限，她不想走超过 K 条边到达 Alice 家， 并且， 每当她走 t（ t≤K）条边<br><span style="">到达 Alice 家时，她需要付出 t^<span style="">2<span style="">的体力。 Marisa 想知道，在 Alice 无论如何都不想接见她<br><span style="">之前（即 Marisa 无法走一条长度不超过 K 的与之前不同的路径）， 她会消耗多少体力。<br><span style="">现在 Marisa 拿到了一张森林的地图， 但因为 Marisa 非常笨， 她并不知道自己的家和<br><span style="">Alice 的家在哪一个路口，因此她会给询问你 Q 次， 每次询问假如 Marisa 的家的位置在 S<br><span style="">而 Alice 的家的位置在 T 时的答案。<br><span style="">一条路径 A 的定义是指一个长度为 P（ P 可以 为任意正整数或零） 的边的序列<br><span style="">Am<span style="">0<span style="">, Am<span style="">1<span style="">, Am<span style="">2<span style="">, …,Am<span style="">T-1<span style="">， 其中对于任意 1≤i＜P， 有 Am<span style="">i-1<span style="">的结束节点是 Am<span style="">i<span style="">的起始节点。<br><span style="">两条路径 A 和 B 完全相同是指两条路径的长度均为 T 并且对任意 0≤i＜P， 有 Am<span style="">i<span style="">=Bm<span style="">i<span style="">。</span></span></span></span></span></span></span></span></span></span></span></span></span><br style=""></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: SimSun;">输入数据第一行包含四个整数 <span style="font-family: Calibri;">N,M,K,Q<span style="font-family: SimSun;">， 含义如题所述。<br><span style="">接下来 <span style="font-family: Calibri;">M <span style="font-family: SimSun;">行，每行两个整数 <span style="font-family: Calibri;">X,Y<span style="font-family: SimSun;">， 表示从第 <span style="font-family: Calibri;">X <span style="font-family: SimSun;">个路口到第 <span style="font-family: Calibri;">Y <span style="font-family: SimSun;">个路口有一条单向小道。路<br><span style="">口的标号为 <span style="font-family: Calibri;">1,2,3,…,N<span style="font-family: SimSun;">，在输入数据第 <span style="font-family: Calibri;">i+1 <span style="font-family: SimSun;">行的边的标号为 <span style="font-family: Calibri;">i<span style="font-family: SimSun;">。<br><span style="">接下来 <span style="font-family: Calibri;">Q <span style="font-family: SimSun;">行，每行两个整数 <span style="font-family: Calibri;">S <span style="font-family: SimSun;">和 <span style="font-family: Calibri;">T<span style="font-family: SimSun;">，含义如题所述。</span></span></span><br style=""></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: SimSun; font-size: 11pt;">对于每个询问， 输出一行，表示这次询问的答案。由于 <span style="font-family: Calibri; font-size: 11pt;">Marisa <span style="font-family: SimSun; font-size: 11pt;">接受不了非常大的数，<br/><span style="font-size: 11pt;">你只需要输出答案模 <span style="font-family: Calibri; font-size: 11pt;">1,000,000,007 <span style="font-family: SimSun; font-size: 11pt;">的值。</span><br style="orphans: 2; text-align: -webkit-auto; white-space: normal; widows: 2;"/></span></span></span></span></span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: Calibri;">2 0 1 1<br><span style="">1 2</span><br style=""></span></p><p><span style="font-family: Calibri;"><span style=""><br></span></span></p><p><span style="font-family: Calibri;">2 22 1<br><span style="">1 2<br><span style="">2 1<br><span style="">1 1</span></span></span><br style=""></span></p><p><span style="font-family: Calibri;"><span style=""><span style=""><span style=""><br></span></span></span></span></p><p><span style="font-family: Calibri;"><span style=""><span style=""><span style=""><span style="font-family: Calibri;">2 2 100 1<br><span style="">1 2<br><span style="">2 1<br><span style="">1 2</span></span></span><br style=""></span></span></span></span></span></p><p><span style="font-family: Calibri;"><span style=""><span style=""><span style=""><span style="font-family: Calibri;"><span style=""><span style=""><span style=""><br></span></span></span></span></span></span></span></span></p><p><span style="font-family: Calibri;"><span style=""><span style=""><span style=""><span style="font-family: Calibri;"><span style=""><span style=""><span style=""><span style="font-family: Calibri;">2 3 100 2<br><span style="">1 2<br><span style="">1 2<br><span style="">2 1<br><span style="">2 2<br><span style="">2 1</span></span></span></span></span><br style=""></span></span></span></span></span></span></span></span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: Calibri;">0<br style=""></span></p><p><span style="font-family: Calibri;"><br></span></p><p><span style="font-family: Calibri;"><span style="font-family: Calibri;">4<br style=""></span></span></p><p><span style="font-family: Calibri;"><span style="font-family: Calibri;"><br></span></span></p><p><span style="font-family: Calibri;"><span style="font-family: Calibri;"><span style="font-family: Calibri;">166650<br style=""></span></span></span></p><p><br></p><p><span style="font-family: Calibri;">632506153<br><span style="">518794755</span><br style=""></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: SimSun;">对于 <span style="font-family: Calibri;">20%<span style="font-family: SimSun;">的数据， <span style="font-family: Calibri;">N<span style="font-family: SimSun;">≤<span style="font-family: Calibri;">5<span style="font-family: SimSun;">， <span style="font-family: Calibri;">M<span style="font-family: SimSun;">≤<span style="font-family: Calibri;">10<span style="font-family: SimSun;">， <span style="font-family: Calibri;">K<span style="font-family: SimSun;">≤<span style="font-family: Calibri;">3<span style="font-family: SimSun;">， <span style="font-family: Calibri;">Q<span style="font-family: SimSun;">≤<span style="font-family: Calibri;">10<br><span style="font-family: SimSun;">对于 <span style="font-family: Calibri;">40%<span style="font-family: SimSun;">的数据， <span style="font-family: Calibri;">N<span style="font-family: SimSun;">≤<span style="font-family: Calibri;">30<span style="font-family: SimSun;">， <span style="font-family: Calibri;">M<span style="font-family: SimSun;">≤<span style="font-family: Calibri;">900<span style="font-family: SimSun;">， <span style="font-family: Calibri;">K<span style="font-family: SimSun;">≤<span style="font-family: Calibri;">100<span style="font-family: SimSun;">， <span style="font-family: Calibri;">Q<span style="font-family: SimSun;">≤<span style="font-family: Calibri;">100<br><span style="font-family: SimSun;">对于 <span style="font-family: Calibri;">60%<span style="font-family: SimSun;">的数据， <span style="font-family: Calibri;">N<span style="font-family: SimSun;">≤<span style="font-family: Calibri;">50<span style="font-family: SimSun;">， <span style="font-family: Calibri;">M<span style="font-family: SimSun;">≤<span style="font-family: Calibri;">2,500<span style="font-family: SimSun;">， <span style="font-family: Calibri;">K<span style="font-family: SimSun;">≤<span style="font-family: Calibri;">10,000,000<span style="font-family: SimSun;">， <span style="font-family: Calibri;">Q<span style="font-family: SimSun;">≤<span style="font-family: Calibri;">1,000<br><span style="font-family: SimSun;">对于 <span style="font-family: Calibri;">100%<span style="font-family: SimSun;">的数据， <span style="font-family: Calibri;">2<span style="font-family: SimSun;">≤<span style="font-family: Calibri;">N<span style="font-family: SimSun;">≤<span style="font-family: Calibri;">100<span style="font-family: SimSun;">， <span style="font-family: Calibri;">0<span style="font-family: SimSun;">≤<span style="font-family: Calibri;">M<span style="font-family: SimSun;">≤<span style="font-family: Calibri;">100,000<span style="font-family: SimSun;">， <span style="font-family: Calibri;">0<span style="font-family: SimSun;">≤<span style="font-family: Calibri;">K<span style="font-family: SimSun;">≤<span style="font-family: Calibri;">1,000,000,000<span style="font-family: SimSun;">， <span style="font-family: Calibri;">0<span style="font-family: SimSun;">≤<span style="font-family: Calibri;">Q<span style="font-family: SimSun;">≤<span style="font-family: Calibri;">10,000<span style="font-family: SimSun;">，<br><span style="font-family: Calibri;">1<span style="font-family: SimSun;">≤<span style="font-family: Calibri;">X<span style="font-family: SimSun;">， <span style="font-family: Calibri;">Y<span style="font-family: SimSun;">， <span style="font-family: Calibri;">S<span style="font-family: SimSun;">， <span style="font-family: Calibri;">T<span style="font-family: SimSun;">≤<span style="font-family: Calibri;">N</span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></p><p><span style="font-family: Calibri;"><span style=""><br></span></span><span style="font-family: Calibri;"><span style=""><br></span></span><span style="font-family: SimSun;">样例一解释<br><span style="">从 <span style="font-family: Calibri;">S <span style="font-family: SimSun;">到 <span style="font-family: Calibri;">T <span style="font-family: SimSun;">不存在路径<br><span style="">样例二解释<br><span style="font-family: Calibri;">Marisa <span style="font-family: SimSun;">可以重复经过一个路口，即使这个路口就是 <span style="font-family: Calibri;">Alice <span style="font-family: SimSun;">的家或 <span style="font-family: Calibri;">Marisa <span style="font-family: SimSun;">的家</span></span></span><br style=""></span></span></span></span></span></span></span></span></span></span></p>
</div>
</div>