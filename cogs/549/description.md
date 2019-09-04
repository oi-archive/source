# 题目描述


<p>
<br/>
</p>
<p>
<span>题目描述：</span> 
</p>
<p>
<span>给</span><span><span>n</span></span><span>个人安排座位，先给每个人一个</span><span><span>1~n</span></span><span>的编号，设第</span><span><span>i</span></span><span>个人的编号为</span><span><span>ai</span></span><span>（不同人的编号可以相同），接着从第一个人开始，大家依次入座，第</span><span><span>i</span></span><span>个人来了以后尝试坐到</span><span><span>ai</span></span><span>，如果</span><span><span>ai</span></span><span>被占据了，就尝试</span><span><span>ai+1</span></span><span>，</span><span><span>ai+1</span></span><span>也被占据了的话就尝试</span><span><span>ai+2</span></span><span>，……，如果一直尝试到第</span><span><span>n</span></span><span>个都不行，该安排方案就不合法。然而有</span><span><span>m</span></span><span>个人的编号已经确定</span><span><span>(</span></span><span>他们或许贿赂了你的上司</span><span><span>...)</span></span><span>，你只能安排剩下的人的编号，求有多少种合法的安排方案。由于答案可能很大，只需输出其除以</span><span><span>M</span></span><span>后的余数即可。</span> 
</p>
<p>
<br/>
</p>
<p>
<span>输入格式：</span> 
</p>
<p>
<span>第一行一个整数</span><span><span>T</span></span><span>，表示数据组数</span> 
</p>
<p>
<span>对于每组数据，第一行有三个整数，分别表示</span><span><span>n</span></span><span>、</span><span><span>m</span></span><span>、</span><span><span>M</span></span> 
</p>
<p>
<span>若</span><span><span>m</span></span><span>不为</span><span><span>0</span></span><span>，则接下来一行有</span><span><span>m</span></span><span>对整数，</span><span><span>p1</span></span><span>、</span><span><span>q1</span></span><span>，</span><span><span>p2</span></span><span>、</span><span><span>q2 ,…, pm</span></span><span>、</span><span><span>qm</span></span><span>，其中第</span><span><span>i</span></span><span>对整数</span><span><span>pi</span></span><span>、</span><span><span>qi</span></span><span>表示第</span><span><span>pi</span></span><span>个人的编号必须为</span><span><span>qi</span></span> 
</p>
<p>
<br/>
</p>
<p>
<span>输出格式：</span> 
</p>
<p>
<span>对于每组数据输出一行，若是有解则输出</span><span><span>YES</span></span><span>，后跟一个整数表示方案数</span><span><span>mod M</span></span><span>，注意，</span><span><span>YES</span></span><span>和数之间只有一个空格，否则输出</span><span><span>NO</span></span> 
</p>
<p>
<br/>
</p>
<p>
<span>样例输入：</span> 
</p>
<p>
<span><span>2</span></span> 
</p>
<p>
<span><span>4 3 10</span></span> 
</p>
<p>
<span><span>1 2 2 1 3 1</span></span> 
</p>
<p>
<span><span>10 3 8882</span></span> 
</p>
<p>
<span><span>7 9 2 9 5 10</span></span> 
</p>
<p>
<br/>
</p>
<p>
<span>样例输出：</span> 
</p>
<p>
<span><span>YES 4</span></span> 
</p>
<p>
<span><span>NO</span></span> 
</p>
<p>
<br/>
</p>
<p>
<span>数据范围：</span> 
</p>
<p>
<span><span>30%</span></span><span>的数据满足：</span><span><span>1≤n≤10</span></span> 
</p>
<p>
<span><span>100%</span></span><span>的数据满足：</span><span><span>1≤T≤10</span></span><span>，</span><span><span>1≤n≤300</span></span><span>，</span><span><span>0≤m≤n</span></span><span>，</span><span><span>2≤M≤10</span><sup><span>9</span></sup></span><span>，</span><span><span>1≤pi</span></span><span>、</span><span><span>qi≤n </span></span><span>且保证</span><span><span>pi</span></span><span>互不相同。</span> 
</p>
<p>
<br/>
</p>
