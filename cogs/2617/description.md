# 题目描述


<h3>
这是一道简单而又正常的题面丢失题，请先读懂给出的代码，然后写一个能够完成相同任务的代码在规定时间内得出结果。<br/>
</h3>
<h3>
【题目描述】
</h3>
<p>
新人求助,本机AC提交又WA又TLE。。。
</p>
<p>
下面是我的代码：
</p>
<pre class="prettyprint lang-cpp">#include&lt;cstdio&gt;
const int maxn=1005,maxm=50005,INF=0x3f3f3f3f;
struct tree{int to,next,num;}e[maxm];
int n,m,len,head[maxn],Dis[maxm],S,cnt;bool vis[maxn];
void set(int prt,int son,int num){
    e[++len].to=son,e[len].next=head[prt],head[prt]=len,e[len].num=num;
}
void dfs(int rt){
    vis[rt]=true,cnt++;
    for(int i=head[rt];i;i=e[i].next)
	if((S&amp;(1&lt;&lt;e[i].num))&amp;&amp;!vis[e[i].to])dfs(e[i].to);
}
int main(){
    freopen(&#34;newworld.in&#34;,&#34;r&#34;,stdin);
    freopen(&#34;newworld.out&#34;,&#34;w&#34;,stdout);
    scanf(&#34;%d%d&#34;,&amp;n,&amp;m);int i,j,x,y,N=1&lt;&lt;m,ans=INF,tmp;
    for(i=0;i&lt;m;i++)scanf(&#34;%d%d%d&#34;,&amp;x,&amp;y,&amp;Dis[i]),set(x,y,i);
    for(i=0;i&lt;N;i++){
	S=i;cnt=0;for(j=1;j&lt;=n;j++)vis[j]=false;
	dfs(1);if(cnt&lt;n)continue;
	tmp=0;
	for(j=0;j&lt;m;j++)if(S&amp;(1&lt;&lt;j))tmp+=Dis[j];
	if(tmp&lt;ans)ans=tmp;
    }
    printf(&#34;%d\n&#34;,ans);
    return 0;
}</pre>
<h3>
【样例输入】
</h3>
<pre><p>
5 10
</p>

<p>
1 4 2
</p>

<p>
4 3 6
</p>

<p>
3 5 1
</p>

<p>
5 2 0
</p>

<p>
1 1 3
</p>

<p>
2 3 8
</p>

<p>
1 4 2
</p>

<p>
2 1 0
</p>

<p>
5 1 8
</p>

<p>
5 5 5
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre>9</pre>
<h3>
【提示】
</h3>
<p>
数据范围
</p>
<p>
对于10%的数据n&lt;=20,m&lt;=20
</p>
<p>
对于30%的数据n&lt;=100,m&lt;=2000
</p>
<p>
另有20%的数据m&lt;=n
</p>
<p>
另有20%的数据输入的Dis[]的值&lt;=100
</p>
<p>
对于100%的数据n&lt;=1000,m&lt;=50000,所有读入的数字&lt;=1000000;
</p>
<h3>
【来源】
</h3>
<p>
一只名字很长的蒟蒻
</p>
