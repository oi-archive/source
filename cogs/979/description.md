# 题目描述


<p>
<b><span style="font-family:Microsoft YaHei;font-size:18px;">Problem 1 : leader</span></b> 
</p>
<p>
<b><span style="font-family:Microsoft YaHei;font-size:18px;">谁是卧底</span></b><b><span style="font-family:;" "=""></span></b> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;"> </span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">问题描述</span><span style="font-family:;" "=""></span> 
</p>
<p>
<span style="font-family:;" "=""><span style="font-family:Microsoft YaHei;font-size:18px;">    </span><span style="font-family:Microsoft YaHei;font-size:18px;">八中信息组需要选一个组长。信息组一共有</span><span style="font-family:Microsoft YaHei;font-size:18px;">n</span><span style="font-family:Microsoft YaHei;font-size:18px;">个人，分别用</span><span style="font-family:Microsoft YaHei;font-size:18px;">1</span><span style="font-family:Microsoft YaHei;font-size:18px;">到</span><span style="font-family:Microsoft YaHei;font-size:18px;">n</span><span style="font-family:Microsoft YaHei;font-size:18px;">编号，其中</span><span style="font-family:Microsoft YaHei;font-size:18px;">m</span><span style="font-family:Microsoft YaHei;font-size:18px;">个人参与了投票。得票数过半（票数大于</span><span style="font-family:Microsoft YaHei;font-size:18px;">m div 2</span><span style="font-family:Microsoft YaHei;font-size:18px;">）的人将被选为组长。</span></span> 
</p>
<p>
<span style="font-family:;" "=""><span style="font-family:Microsoft YaHei;font-size:18px;">    </span><span style="font-family:Microsoft YaHei;font-size:18px;">输入数据将告知这</span><span style="font-family:Microsoft YaHei;font-size:18px;">m</span><span style="font-family:Microsoft YaHei;font-size:18px;">个人分别将票投给了谁，请统计出谁将担任八中信息组的组长。</span></span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;"> </span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">输入数据</span><span style="font-family:;" "=""></span> 
</p>
<p>
<span style="font-family:;" "=""><span style="font-family:Microsoft YaHei;font-size:18px;">    </span><span style="font-family:Microsoft YaHei;font-size:18px;">第一行两个数</span><span style="font-family:Microsoft YaHei;font-size:18px;">n</span><span style="font-family:Microsoft YaHei;font-size:18px;">和</span><span style="font-family:Microsoft YaHei;font-size:18px;">m</span><span style="font-family:Microsoft YaHei;font-size:18px;">。</span></span> 
</p>
<p>
<span style="font-family:;" "=""><span style="font-family:Microsoft YaHei;font-size:18px;">    </span><span style="font-family:Microsoft YaHei;font-size:18px;">第二行有</span><span style="font-family:Microsoft YaHei;font-size:18px;">m</span><span style="font-family:Microsoft YaHei;font-size:18px;">个数，这些数都是不超过</span><span style="font-family:Microsoft YaHei;font-size:18px;">n</span><span style="font-family:Microsoft YaHei;font-size:18px;">的正整数，表明这</span><span style="font-family:Microsoft YaHei;font-size:18px;">m</span><span style="font-family:Microsoft YaHei;font-size:18px;">个人的选择。</span></span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;"> </span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">输出数据</span><span style="font-family:;" "=""></span> 
</p>
<p>
<span style="font-family:;" "=""><span style="font-family:Microsoft YaHei;font-size:18px;">    </span><span style="font-family:Microsoft YaHei;font-size:18px;">输出将被选为组长的人。如果没有人的票数过半，请输出</span><span style="font-family:Microsoft YaHei;font-size:18px;">-1</span><span style="font-family:Microsoft YaHei;font-size:18px;">。</span></span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;"> </span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">输入样例</span><span style="font-family:;" "=""></span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">7
4</span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">7
7 2 7</span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;"> </span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">输出样例</span><span style="font-family:;" "=""></span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">7</span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;"> </span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">时间限制</span><span style="font-family:;" "=""></span> 
</p>
<p>
<span style="font-family:;" "=""><span style="font-family:Microsoft YaHei;font-size:18px;">    </span><span style="font-family:Microsoft YaHei;font-size:18px;">各测试点</span><span style="font-family:Microsoft YaHei;font-size:18px;">1</span><span style="font-family:Microsoft YaHei;font-size:18px;">秒</span></span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;"> </span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">内存限制</span><span style="font-family:;" "=""></span> 
</p>
<p>
<span style="font-family:;" "=""><span style="font-family:Microsoft YaHei;font-size:18px;">    </span><span style="font-family:Microsoft YaHei;font-size:18px;">你的程序将被分配</span><span style="font-family:Microsoft YaHei;font-size:18px;">10MB</span><span style="font-family:Microsoft YaHei;font-size:18px;">的运行空间</span></span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;"> </span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">数据规模</span><span style="font-family:;" "=""></span> 
</p>
<p>
<span style="font-family:;" "=""><span style="font-family:Microsoft YaHei;font-size:18px;">    </span><span style="font-family:Microsoft YaHei;font-size:18px;">1&lt;=n&lt;=maxlongint</span></span> 
</p>
<p>
<span style="font-family:;" "=""><span style="font-family:Microsoft YaHei;font-size:18px;">    </span><span style="font-family:Microsoft YaHei;font-size:18px;">1&lt;=m&lt;=10000</span></span> 
</p>
