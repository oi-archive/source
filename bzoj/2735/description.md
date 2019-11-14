
# Description

<div class="content"><div>四年一度的世博会又要举办了，Q国很荣幸成为了这次世博会的主办方。Q国主席QQ从全国各地收集了N件物品排成</div>
<div>一排，作为Q国馆的展出物。对于相邻摆放的一些物品，如果过于相似会让人觉得无聊，如果差别过大又会让人觉</div>
<div>得突兀。为了让人们对这次世博会的展出满意，QQ需要知道一些相邻物品的“差异度”。为了方便表示，QQ给每个</div>
<div>物品都定义了两个属性值A、B，两件物品之间的“绝对差异值”定义为它们对应属性的差的绝对值较大的一个。对</div>
<div>于一些物品的“差异度”，类似求方差的方法，QQ总会首先设想一个理想的“平均物品”，它的两个属性可以为任</div>
<div>意实数，且它与这些物品中的每个物品的“绝对差异值”之和最小。而这些物品的“差异度”就定义为这个最小的</div>
<div>和。QQ每次会询问：从第Li个到第Ri个物品的“差异度”是多少。现在，这个任务交给了神犇你。</div></div>

# Input

<div class="content"><div class="pdsec">
<div>第一行两个整数N和Q，表示物品数和QQ的询问数。第二行N个整数A1到An，表示每个物品的A属性。第三行N个整数B</div>
<div>1到Bn，表示每个物品的B属性。之后Q行每行两个整数Li Ri，表示QQ的询问。</div>
<div>1&lt;=N&lt;=100000, 1&lt;=Q&lt;=100000, |Ai|,|Bi|&lt;=1000000000,1&lt;=Li&lt;=Ri&lt;=N</div>
</div></div>

# Output

<div class="content"><div class="pdcont">共Q行，每行输出一个数，表示该次询问的物品的差异度，结果保留到小数点后两位。</div></div>

# Sample Input

<div class="content"><span class="sampledata">4 2<br/>
1 6 -3 2<br/>
2 7 -1 3<br/>
1 4<br/>
2 3<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">10.00<br/>
9.00<br/>
样例说明<br/>
对于第一个询问，平均物品的两个属性可以是1和2差异度为max(0,0)+max(5,5)+max(4,3)+max(1,1)=10对于第二个<br/>
询问，平均物品的两个属性可以是6和7差异度为max(0,0)+max(9,8)=9<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

