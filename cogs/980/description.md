# 题目描述


<p>
<b><span style="font-family:Microsoft YaHei;font-size:18px;">Problem 2 : money</span></b> 
</p>
<p>
<b><span style="font-family:Microsoft YaHei;font-size:18px;">最小花费</span></b><b><span style="font-family:&#34;"></span></b> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;"> </span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">问题描述</span><span style="font-family:&#34;"></span> 
</p>
<p>
<span style="font-family:&#34;"><span style="font-family:Microsoft YaHei;font-size:18px;">    </span><span style="font-family:Microsoft YaHei;font-size:18px;">在</span><span style="font-family:Microsoft YaHei;font-size:18px;">n</span><span style="font-family:Microsoft YaHei;font-size:18px;">个人中，某些人的银行账号之间可以互相转账。这些人之间转账的手续费各不相同。给定这些人之间转账时需要从转账金额里扣除百分之几的手续费，请问</span><span style="font-family:Microsoft YaHei;font-size:18px;">A</span><span style="font-family:Microsoft YaHei;font-size:18px;">最少需要多少钱使得转账后</span><span style="font-family:Microsoft YaHei;font-size:18px;">B</span><span style="font-family:Microsoft YaHei;font-size:18px;">收到</span><span style="font-family:Microsoft YaHei;font-size:18px;">100</span><span style="font-family:Microsoft YaHei;font-size:18px;">元。</span></span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;"> </span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">输入数据</span><span style="font-family:&#34;"></span> 
</p>
<p>
<span style="font-family:&#34;"><span style="font-family:Microsoft YaHei;font-size:18px;">    </span><span style="font-family:Microsoft YaHei;font-size:18px;">第一行输入两个正整数</span><span style="font-family:Microsoft YaHei;font-size:18px;">n,m</span><span style="font-family:Microsoft YaHei;font-size:18px;">，分别表示总人数和可以互相转账的人的对数。</span></span> 
</p>
<p>
<span style="font-family:&#34;"><span style="font-family:Microsoft YaHei;font-size:18px;">    </span><span style="font-family:Microsoft YaHei;font-size:18px;">以下</span><span style="font-family:Microsoft YaHei;font-size:18px;">m</span><span style="font-family:Microsoft YaHei;font-size:18px;">行每行输入三个正整数</span><span style="font-family:Microsoft YaHei;font-size:18px;">x,y,z</span><span style="font-family:Microsoft YaHei;font-size:18px;">，表示标号为</span><span style="font-family:Microsoft YaHei;font-size:18px;">x</span><span style="font-family:Microsoft YaHei;font-size:18px;">的人和标号为</span><span style="font-family:Microsoft YaHei;font-size:18px;">y</span><span style="font-family:Microsoft YaHei;font-size:18px;">的人之间互相转账需要扣除</span><span style="font-family:Microsoft YaHei;font-size:18px;">z%</span><span style="font-family:Microsoft YaHei;font-size:18px;">的手续费</span><span style="font-family:Microsoft YaHei;font-size:18px;"> (z&lt;100)</span><span style="font-family:Microsoft YaHei;font-size:18px;">。</span></span> 
</p>
<p>
<span style="font-family:&#34;"><span style="font-family:Microsoft YaHei;font-size:18px;">    </span><span style="font-family:Microsoft YaHei;font-size:18px;">最后一行输入两个正整数</span><span style="font-family:Microsoft YaHei;font-size:18px;">A,B</span><span style="font-family:Microsoft YaHei;font-size:18px;">。数据保证</span><span style="font-family:Microsoft YaHei;font-size:18px;">A</span><span style="font-family:Microsoft YaHei;font-size:18px;">与</span><span style="font-family:Microsoft YaHei;font-size:18px;">B</span><span style="font-family:Microsoft YaHei;font-size:18px;">之间可以直接或间接地转账。</span></span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;"> </span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">输出数据</span><span style="font-family:&#34;"></span> 
</p>
<p>
<span style="font-family:&#34;"><span style="font-family:Microsoft YaHei;font-size:18px;">    </span><span style="font-family:Microsoft YaHei;font-size:18px;">输出</span><span style="font-family:Microsoft YaHei;font-size:18px;">A</span><span style="font-family:Microsoft YaHei;font-size:18px;">使得</span><span style="font-family:Microsoft YaHei;font-size:18px;">B</span><span style="font-family:Microsoft YaHei;font-size:18px;">到账</span><span style="font-family:Microsoft YaHei;font-size:18px;">100</span><span style="font-family:Microsoft YaHei;font-size:18px;">元最少需要的总费用。精确到小数点后</span><span style="font-family:Microsoft YaHei;font-size:18px;">8</span><span style="font-family:Microsoft YaHei;font-size:18px;">位。</span></span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;"> </span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">输入样例</span><span style="font-family:&#34;"></span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">3
3</span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">1
2 1</span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">2
3 2</span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">1
3 3</span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">1
3</span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;"> </span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">输出样例</span><span style="font-family:&#34;"></span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">103.07153164</span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;"> </span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">时间限制</span><span style="font-family:&#34;"></span> 
</p>
<p>
<span style="font-family:&#34;"><span style="font-family:Microsoft YaHei;font-size:18px;">    </span><span style="font-family:Microsoft YaHei;font-size:18px;">各测试点</span><span style="font-family:Microsoft YaHei;font-size:18px;">1</span><span style="font-family:Microsoft YaHei;font-size:18px;">秒</span></span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;"> </span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">内存限制</span><span style="font-family:&#34;"></span> 
</p>
<p>
<span style="font-family:&#34;"><span style="font-family:Microsoft YaHei;font-size:18px;">    </span><span style="font-family:Microsoft YaHei;font-size:18px;">你的程序将被分配</span><span style="font-family:Microsoft YaHei;font-size:18px;">40MB</span><span style="font-family:Microsoft YaHei;font-size:18px;">的运行空间</span></span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;"> </span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">数据规模</span><span style="font-family:&#34;"></span> 
</p>
<p>
<span style="font-family:&#34;"><span style="font-family:Microsoft YaHei;font-size:18px;">    </span><span style="font-family:Microsoft YaHei;font-size:18px;">1&lt;=n&lt;=2000</span></span> 
</p>
