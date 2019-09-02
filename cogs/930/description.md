# 题目描述


<p>
<span>题目描述</span> 
</p>
<p>
<span>看到很短的题目会让人心情愉悦，所以</span><span>给出一个长度为N的序列A1,A2,A3,...,AN，</span> 
</p>
<p>
<span>现在有M个询问，每个询问都是Ai...Aj中第k小的数等</span><span>于多少。</span> 
</p>
<span></span><br/>
<span>输入格式</span><br/>
<span></span><br/>
<span>第一行两个正整数N，M。</span><br/>
<span>第二行N个数，表示序列A1,A2,...,AN。</span><br/>
<span>紧着的M行，每行三个正整数i,j,k(k≤j-i+1)，表示</span><br/>
<p>
<span>询问Ai...Aj中第k小的数等于多少。</span> 
</p>
<p>
<span><br/>
</span> 
</p>
<span>输出格式</span><br/>
<p>
<span>共输出M行，第i行输出第i个询问的答案。</span> 
</p>
<p>
<span><br/>
</span> 
</p>
<span>样例输入1：</span><br/>
<p>
<span>4 3</span> 
</p>
<p>
4 1 2 3
</p>
<p>
<span>1 3 1</span> 
</p>
<p>
<span>2 4 3</span> 
</p>
<p>
1 4 4
</p>
<p>
<br/>
</p>
<span>样例输出1：</span><br/>
<span>1</span><br/>
<span>3</span><br/>
<span>4</span><br/>
<span></span><br/>
<span>样例输入2：</span><br/>
<span>5 5</span><br/>
<span>4 2 9 9 10</span><br/>
<span>1 3 1</span><br/>
<span>2 4 3</span><br/>
<span>1 4 4</span><br/>
<span>3 5 2</span><br/>
<span>2 5 2</span><br/>
<br/>
<span>样例输出2：</span><br/>
<span>2</span><br/>
<span>9</span><br/>
<span>9</span><br/>
<span>9</span><br/>
<span>9</span><br/>
<span></span><br/>
<span>注释：</span><br/>
<span>询问区间的第k小值并非严格第k小，例如样例2中第4个询问，询问3到5中第2小的数，</span><br/>
<span>答案输出9，并不是严格第2小的10。</span><br/>
<span></span><span></span><br/>
<span>数据范围：</span><br/>
<span>在50%的数据中，1&lt;=N&lt;=10000，1&lt;=M&lt;=10000，A[i]&lt;=100000;</span><br/>
<span>在100%的数据中，1&lt;=N&lt;=100000,1&lt;=M&lt;=100000,A[i]&lt;=1000000;</span><br/>
