<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>LYp<span style="">无聊时经常出去找</span>MZ<span style="">，每一次会把那些妹纸的身高记录下来</span>(<span style="">由于</span>LYp<span style="">太懒了，所以编号都是上升的</span>)<span style="">，于是就构成了一个上升序列。</span></p><p><span style="">而且</span>LYP<span style="">为了让泥萌看不出</span>MZ<span style="">是谁，他又以特殊方法将</span>MZ<span style="">的名字记录了下来，但却让非常<span style="text-decoration: line-through;">善良</span>的</span>Zinc<span style="">将特殊方法偷了出来，现在</span>Zinc<span style="">会把特殊方法丢给你</span></p><p>LYP<span style="">有一天突然</span>**<span style="">了，所以随便翻了</span>n<span style="">个</span>MZ<span style="">的牌，他想知道其中</span>m<span style="">个</span>MZ<span style="">的身高在序列中的排名（但</span>Zinc<span style="">却十分<span style="text-decoration: line-through;">邪恶</span>地要你求出那个</span>MZ<span style="">的名字，以便让</span>LYP<span style="">尴尬），以便让</span>LYP<span style="">更好的<span style="text-decoration: line-through;">宠幸</span>疼爱他的</span>MZ<span style="">们</span>(LYp<span style="">需要快一点，如果你没有在</span>1s<span style="">内找到编号为</span>x<span style="">的那个</span>MZ<span style="">且那个</span>mz<span style="">的名字，他会就地取材，把</span>xxx<span style="">给</span>xxx<span style="">了</span>)<span style="">。</span></p><p><br></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第一行有两个数</span> n,m<span style="">分别表示有</span>n<span style="">个</span>mz,<span style="">随机抽取</span>m<span style="">个</span>MZ<br></p><p><span style="">第二行</span> 0-9<span style="">表示当前</span>MZ<span style="">的身高上各个位置上的数</span></p><p><span style="">第三行</span> <span style="">对应第二行的</span>10<span style="">个字母</span></p><p><span style="">第四行</span> n<span style="">个数，表示</span>n<span style="">个</span>MZ<span style="">的身高</span>ai<span style="">（保证上升）</span></p><p><span style="">第</span>5<span style="">到</span>5+m-1<span style="">行，每行一个整数</span>x<span style="">，表示</span>LYP<span style="">想知道身高为</span>x<span style="">的</span>MZ<span style="">在他的那</span>n<span style="">个</span>MZ<span style="">中的排名究竟是多少</span>(+Zinc<span style="">想要求你求的</span>MZ<span style="">的名字</span>)</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>m<span style="font-family:宋体">行</span> <span style="font-family:宋体">每行有两个东东，分别表示当前</span>MZ<span style="font-family:宋体">在</span>N<span style="font-family:宋体">个</span>MZ<span style="font-family:宋体">中身高的排名与</span>MZ<span style="font-family:宋体">的名字</span></p><p>不懂的话看数据</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3</p><p>0 1 2 3 4 5 6 7 8 9</p><p>ELTEWACREL</p><p>1 3 7           </p><p>3</p><p>1</p><p>7</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2 E</p><p>1 L</p><p>3 R</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>40% 0&lt;=N,M&lt;=10^6 </p><p>70%0&lt;=N,M&lt;=10^7 </p><p>100% 0&lt;=N,M=&lt;=10^8  </p><p>0&lt;=ai&lt;=100000000</p><p>妈的智障，大数据丢不上来，只有40%的</p><p>毛线啊，数据包不能大于50MB</p>
</div>
</div>