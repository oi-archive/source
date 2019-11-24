<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>WD 上了高中以后，发现化学方程式的记忆简直就是一个无底洞。</p><p>但是万幸的是，他发现李老师讲的化学方程式貌似有一个很牛的规律，这</p><p>个秘密可以节约大量的时间去记忆</p><p>首先讲一个最基本的方程式吧（注意:为了方便,所有数字都只有一位）</p><p>H2O+CO2=H2CO3  H2CO3+2NaOH=Na2CO3+2H2O</p><p>相加，于是我们可以得到一个总反应，即</p><p>CO2+2NaOH=Na2CO3+H2O</p><p>为了方便，我们可以这样来规定</p><p>1． 反应物和生成物同时相加，要将左右都有的物质抵掉相应的数（注</p><p>意：物质相同，当且仅当字符串相同）</p><p>2． 如果一个物质前面的化学剂量数为 1，那么就可以省掉不写</p><p>3． 输出中，不管是反应物还是生成物，相对分子质量大的先写</p><p>为了方便，此题中没有括号，不会有 Ca(NO3)2 这类的物质</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行：两个数 N（N&lt;=10），M（M&lt;=10）分别表示参与反应的元素个数，</p><p>以及化学反应的个数</p><p>第二到第 N+1 行：每行一个数，表示相对原子质量，后面空一个加一个或</p><p>两个字符，表示元素的符号（第一个是大写，如果有两位，第二位是小写）</p><p>第 N+2 到 N+M+1 行：每行一个反应方程式，用等号连接（不超过 80 个字</p><p>符）</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>只有一行，表示总的化学反应方程式（注意：不可以约分）</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 2</p><p>1 H</p><p>16 O</p><p>23 Na</p><p>12 C</p><p>H2O+CO2=H2CO3</p><p>H2CO3+2NaOH=Na2CO3+2H2O</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>CO2+2NaOH=Na2CO3+H2O</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>50%:N&lt;=10,M&lt;=10,方程式长度均小于50，反应物质系数均小于10</p><p>100%:N&lt;=233,M&lt;=2333,反应物个数&lt;666，生成物个数&lt;666，反应物系数可能大于10，数据是随机的<br></p>
</div>
</div>