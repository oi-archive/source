
# Description

<div class="content"><div>小R最近遇上了大麻烦，他的程序设计挂科了。于是他只好找程设老师求情。善良的程设老师答应不挂他，但是要</div>
<div>求小R帮助他一起解决一个难题。问题是这样的，程设老师最近要进行一项邪恶的实验来证明P=NP，这个实验一共</div>
<div>持续n天，第i天需要a[i]个研究生来给他搬砖。研究生毕竟也是人，所以雇佣研究生是需要钱的，机智的程设老师</div>
<div>已经联系好了m所大学，第j所大学共有l[j]个研究生，同时雇佣这所大学的一个研究生需要p[j]元钱。本来程设老</div>
<div>师满心欢喜的以为，这样捡最便宜的max{a[i]}个研究生雇来，就可以完成实验；结果没想到，由于他要求硕士生</div>
<div>们每天工作25个小时不许吃饭睡觉上厕所喝水说话咳嗽打喷嚏呼吸空气，因此一天下来给他搬砖的所有研究生都会</div>
<div>进入濒死状态。濒死状态的研究生，毫无疑问，就不能再进行工作了。但是机智的老师早早联系好了k家医院，第i</div>
<div>家医院医治一个濒死的研究生需要d[i]天,并且需要q[i]元钱。现在，程设老师想要知道，最少花多少钱，能够在</div>
<div>这n天中满足每天的需要呢？若无法满足，则请输出”impossible”。注意，由于程设老师良心大大的坏，所以他</div>
<div>是可以不把濒死的研究生送去医院的！。</div></div>

# Input

<div class="content"><div>本题包含多组数据；第一行是一个数T(T&lt;=11)，表示数据组数，以下T组数据。</div>
<div>对于每一组数据，第一行三个数，n,m,k;</div>
<div>以下一行n个数，表示a[1]…a[n]</div>
<div>接着一行2m个数，表示l[1],p[1]…l[n],p[n]</div>
<div>接着一行2k个数，表示d[1],q[1]…d[n],q[n]</div>
<div>n,m,k&lt;=50,其余数均小于等于100.</div></div>

# Output

<div class="content"><p>对于每组数据以样例的格式输出一行，两个数分别表示第几组数据和最少钱数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
3 2 1<br/>
10 20 30<br/>
40 90 15 100<br/>
1 5<br/>
3 2 1<br/>
10 20 30<br/>
40 90 15 100<br/>
2 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case 1: 4650<br/>
Case 2: impossible<br/>
样例解释：<br/>
买下90块钱的那40个研究生，另外再买10个100块钱的。这样，第一天用完的10个人全部送到医院，那么他们在第<br/>
三天可以继续使用；同时，第二天和第三天都用新的研究生来弥补，这样一共需要花费40*90 + 10*100 + 5*10 = <br/>
4650元。</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium"><br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

