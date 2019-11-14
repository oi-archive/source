
# Description

<div class="content"><div>上帝之手操纵着四维空间。假设四维空间中上帝关心的部分共N天，定义第i天结束时一个三维世界的混乱度为Xi。由于一些自然的原因，第i天该世界的混乱度会增加Di，即Xi=Xi-1+Di。但为了世界的平衡，每天该世界都有一个混乱度的上限值Li，即实际上Xi=min{Xi-1+Di , Li}。</div>
<div>上帝想对该四维空间作一系列测试，于是希望你帮忙建立一个模型。具体有以下三种测试：</div>
<div>（1）给定A、B和K，要求找到一个C（A&lt;=C&lt;=B），使得世界以LC-1的初始混乱度从第C天开始发展将得到第K大的XB­。你只需告诉上帝第K大的XB值即可。</div>
<div>（2）给定A、B和X0，要求找到一个C（A&lt;=C&lt;=B），使得世界以X0的初始混乱度从第C天开始发展将得到最大的XB。你只需告诉上帝最大的XB值即可（注意：X0可能大于LC-1）。</div>
<div>（3）给定A和B，要求对于所有满足A&lt;=C&lt;=B 的C，求出世界以LC-1的初始混乱度从第C天开始发展将得到的XB的不同值的种数­。</div>
<div>当然，上帝还会根据测试的结果修改某些位置的Li。你能成功帮助上帝完成测试吗？</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含两个正整数N和M，按序表示总天数和总操作（包含测试和修改）次数。</div>
<div>第二行为N个非负整数 D1-DN，第三行为N+1个非负整数L0-LN。含义见问题描述。</div>
<div>第四行起的M行，每行第一个整数type表示操作种类。</div>
<div>若type=0，则后面跟有两个整数u和x，表示将Lu改为x。</div>
<div>若type&gt;0，则type等于题目描述中对应的测试种类编号。type=1时后面跟有三个整数A、B和K；type=2时后面跟有三个整数A、B和X0；type=3时后面跟有两个整数A和B。具体含义见问题描述。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每个测试输出一行，包含一个整数表示测试结果。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 5<br/>
2 1 3<br/>
2 6 7 5<br/>
1 1 2 2<br/>
3 1 3<br/>
0 3 15<br/>
3 1 3<br/>
2 1 3 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
1<br/>
2<br/>
8<br/>
</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据，N&lt;=10^5，M&lt;=2×10^5，0&lt;=Di&lt;=10^4，0&lt;=Li, X0, x&lt;=10^9，0&lt;=u&lt;=N，1&lt;=A&lt;=B&lt;=N，1&lt;=K&lt;=B-A+1。</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2015年集训队互测">2015年集训队互测</a></p></div>

