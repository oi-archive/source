
# Description

<div class="content"><p> Allison有非常多的电子设备，比如iMac,iPod,iPhone和iPad。所以她准备购买插线板来给电子设备充电。在做了大量的网络调研后，</p>
<div>Allison拔线了一款美丽精巧的天翼牌排插（如左下图所示）。在见到这个插线板的第一眼，Allison就被它的境美造型所吸引，</div>
<div>于是她一次性购买了n个这种型号的插线板。 </div>
<div> 可是问题也随之而来，Allison的家中只有一个插座，她需要通过插线板的连接将电一层一层地导出（如右上图所示）。 </div>
<div>插线板的连接方式是树形结构的：每个插线板的插头插在另一个插线板的插空中（除了根节点），插线板的连接不允许构成环。 </div>
<div>每个插线板有火线，零线，地线三根导线，随着插线板数量的增加、倒显得磨损，电路中导线与导线之间接触产生的电阻已经到了</div>
<div>不能被忽视的地步。 </div>
<div>如何来描述插线板的树形结构以及导线之间的电阻关系呢？Allison思考出来一个数学模型：用ai代表第i个插线板的编号，fi代表</div>
<div>第i个插线板的插头所差的插线板（即ai在树中的父亲），1代表火线，2代表零线，3代表地线，则整个网络的电阻可以用</div>
<div>R(ai,fi,x,y)(x,y∈{1,2,3})来描述，它代表ai的x线与fi的y线之间的电阻值（在这个数学模型中，Allison认为火线和领先也是</div>
<div>可能连接并且产生电阻的）下面是一个例子： </div>
<div> <img src="source/bzoj/3556/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNS8xMTExLmpwZw==.jpg" width="450" height="411" alt=""/></div>
<div>由于时间的推移，导线与导线之间的电阻还可能发生变化。现在，Allison想知道在插线板树形电路中，当前时刻ai插线板的x线和</div>
<div>aj插线板的y线之间的电阻式多少。规定插线板的树根节点不再插向其他插线板，且编号为1。 </div></div>

# Input

<div class="content"><p> 第一行包含一个正整数n，表示插线板的个数。 </p>
<div>接下来4(n-1)行，每4行为一个块。 </div>
<div>第i块的第一行为一个整数fi【注：原题如此。实际应该是fi+1，下同】，表示编号为i+1的插线板的父亲为fi【注：同上】插线板。 </div>
<div>接下来一个3*3的矩阵gxy，第x行第y个数表示编号为i+1的插线板的x线和fi【注：同上】的y线之间的电阻的倒数。 </div>
<div>接下来一个整数q，表示q个操作数。 </div>
<div>第一个整数位k，若k=1则接下来包含四个整数ai,xi,xj,g，表示将ai插线板的xi线与ai插线板的父亲fi</div>
<div>【注：原题如此。实际应该是fai】的xj线之间的电阻值改为g的倒数。保证2&lt;=ai&lt;=n。 </div>
<div>若k=2，则接下来包含四个整数ai,xi,aj,xj，表示询问ai插线板的xi线与aj插线板的xj线之间的电阻大小。保证ai≠aj。 </div></div>

# Output

<div class="content"><p>对每个询问，输出一行实数，表示两条线之间的电阻。 </p>
<div>若|(选手输出-标准输出)/标准输出|&lt;=10^-3，则被认为该电阻值正确，若所有电阻值皆正确，则可获得该测试点的得分。 </div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
1<br/>
6 7 1 <br/>
4 1 8 <br/>
8 3 3 <br/>
2<br/>
7 5 8 <br/>
10 5 7 <br/>
10 5 5 <br/>
10<br/>
1 3 1 2 2<br/>
1 2 2 3 5<br/>
2 3 2 2 2<br/>
1 2 3 2 5<br/>
1 3 1 2 3<br/>
2 1 2 2 3<br/>
1 3 2 1 2<br/>
2 2 1 1 1<br/>
1 2 1 2 5<br/>
2 3 1 1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.083836<br/>
0.095256<br/>
0.078828<br/>
0.146900</span></div>

# Hint

<div class="content"><p></p><p> 对于所有测试数据，输入保证是一棵树。0&lt;输入中电阻的倒数&lt;=10。 </p><br/>
<div>测试点编号            特点</div><br/>
<div>   1-6          n&lt;=100,q&lt;=1000，保证输入中只有查询没有修改</div><br/>
<div>   7-10         n&lt;=1000,q&lt;=1000，保证数据是一条链</div><br/>
<div>   11-16        n&lt;=10000,q&lt;=10000，保证数的高度不超过30</div><br/>
<div>   17-20        n&lt;=10000,q&lt;=10000</div><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Vfleaking提供Spj">鸣谢Vfleaking提供Spj</a></p></div>

