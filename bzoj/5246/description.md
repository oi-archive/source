
# Description

<div class="content"><div>
<div>Adam带了一堆扣在钥匙环上的钥匙，有些钥匙环可能会和其它钥匙环串在一起。钥匙可以从钥匙环上取下，或者挂</div>
<div>到钥匙环上。同理，串在一起的钥匙环可以人为地拆分开，不在一起的钥匙环也可以人为地串在一起。Adam想将其</div>
<div>中的一些钥匙交给Brenda。因为摆弄钥匙和钥匙环是很麻烦的事情，所以Adam想找到最佳的方案，使得摆弄钥匙和</div>
<div>钥匙环的次数最小。每次将某个钥匙从钥匙环上取下，每次将某个钥匙挂到某个钥匙环上，都算一次摆弄钥匙。每</div>
<div>次将两个钥匙环串在一起，每次将两个串在一起的钥匙环拆分开，都算一次摆弄钥匙环。显然，摆弄钥匙比摆弄钥</div>
<div>匙环要麻烦得多，所以Adam希望首先最小化摆弄钥匙的次数，在这个基础上再去最小化摆弄钥匙环的次数。你需要</div>
<div>帮助他找到最佳的方案。当所有操作完成之后，Adam和Brenda必须一人拿走恰好一组串在一起的钥匙环。当然，如</div>
<div>果某个人并没有想拿的钥匙的话，他会什么也不拿走。每把钥匙必须恰好挂在一个钥匙环上，钥匙环可以不挂任何</div>
<div>钥匙，这些钥匙环将被遗弃。</div>
<div><img src="/source/bzoj/5246/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwNC9waWMucG5n.png" width="604" height="212" alt=""/></div>
<div>如上图，一共有4把钥匙、3个钥匙环，其中Adam希望给Brenda两把钥匙(N和R)，自己拿走剩下两把(A和B)。从左图</div>
<div>摆弄两次钥匙和一次钥匙环就得到了右图。</div>
</div>
<p></p></div>

# Input

<div class="content"><div>每组数据包含若干行，每行一个长度为2的字母构成的字符串。</div>
<div>小写字母a到z表示钥匙环，而大写字母A到Z表示钥匙。</div>
<div>每一行要么是两个小写字母，要么是一个小写字母和一个大写字母，表示这两个事物连接在一起。</div>
<div>每组数据最后会有一个0表示结束。</div>
<div>A到M表示Adam希望拿走的钥匙，N到Z表示Brenda希望拿走的钥匙。</div>
<div>输入保证不会重复描述同一个连接关系，保证输入中出现的每个钥匙恰好属于一个环，环与环之间的连接不存在环路。</div>
<div>你不需要考虑输入中未出现的那些字母。</div>
<p></p></div>

# Output

<div class="content"><div>对于每组数据，输出一行</div>
<div>包含数据编号，之后两个数，分别表示摆弄钥匙次数的最小值以及在这个基础上摆弄钥匙环次数的最小值。</div>
<div>若无解，请输出impossible。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">ab<br/>
bc<br/>
aA<br/>
aN<br/>
Rb<br/>
cB<br/>
0<br/>
aA<br/>
bB<br/>
Cc<br/>
0<br/>
aA<br/>
aZ<br/>
0<br/>
aA<br/>
bB<br/>
cC<br/>
xX<br/>
yY<br/>
ax<br/>
xb<br/>
by<br/>
yc<br/>
0</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case 1: 2 1<br/>
Case 2: 0 2<br/>
Case 3: impossible<br/>
Case 4: 0 7<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris提供试题">鸣谢Claris提供试题</a></p></div>

