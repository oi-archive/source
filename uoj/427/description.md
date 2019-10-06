# 题目描述

<p>现有$n-1$种化学物质，他们全部溶于水。任取$n-1$种化学物质中的两种都可以在一定条件下发生化学反应（两种可以相同）。特别地，水和其他化学物质不会化学反应，但是我们为了统一考虑，我们认为水可以和任意一种化学物质$X$反应生成$X$。那么包含水我们一共有$n$种化学物质。</p>
<p>根据相关理论，由于产物不离开溶液反应体系，化学药品之间反应的产物与加入药品的顺序无关。另外，每种化学物质都有恰好一种对应的化学物质，它们两个反应生成水。</p>
<p>现在桌子上有一排药瓶，每一个药瓶中存放了一种化学物质，编号从左到右分别为$1,2,\cdots,m$。为了体现您的超强实验功底，您的第$i$次实验仅用编号在区间$[L_i,R_i]$中的药瓶。假设您能创造出任何可能的反应条件，请问第$i$次实验您总共能配出多少种不同的物质（包含一开始就有的物质）？</p>

# 输入格式


<p>第一行三个正整数$t,m,q$，分别表示第二行正整数个数、桌子上化学药品的数量、您做实验的次数；</p>
<p>第二行为用于描述这些化学药品性质的$t$个正整数；</p>
<p>接下来一行$m$个$[1,n]$内的正整数，第$i$个整数表示编号为$i$的药品是第几种化学物质；</p>
<p>接下来$q$行，每行两个正整数$L_i,R_i$，表示第$i$次实验中您能使用的药品编号区间。</p>

# 输出格式


<p>恰好$q$行，每行一个$[1,n]$内的正整数，表示第$i$次实验您在理论上能配出的不同的物质种类数。</p>

# 样例一


<h4>input</h4>
<pre>1 5 3
4
1 3 2 2 4
2 4
1 2
1 1

</pre>

<h4>output</h4>
<pre>4
2
1

</pre>


# 辅助代码


<p>推荐使用C++解决本题。</p>
<pre><code class="sh_cpp">namespace LIB{
    const int N=30;
    int dim[N],dimcnt;
    template&lt;class T&gt;void dfs(int dep,T g,int x,int y,int z,int n){
        if(dep&gt;dimcnt){
            g[x][y]=z;
            return;
        }
        int d=n/dim[dep];
        for(int i=0;i&lt;n;i+=d){
            for(int j=0;j&lt;n;j+=d){
                dfs(dep+1,g,x+i,y+j,z+(i+j)%n,d);
            }
        }
    }
    template&lt;class T1,class T2&gt;inline int put_reaction(int t,T1 a,T2 g){
        dimcnt=t;
        int n=1;
        for(int i=1;i&lt;=t;i++){
            n*=dim[i]=a[i];
        }
        dfs(1,g,1,1,1,n);
        return n;
    }
}</code></pre>
<p>将以上代码包含在您的源程序内之后，您可以调用这个时间复杂度为$\mathrm O(n^2)$的函数来处理输入数据的前两行：</p>
<pre><code class="sh_cpp">int LIB::put_reaction(t,a,g);</code></pre>
<ul><li>第一个参数是输入第一行的整数$t$；</li>
<li>第二个参数是一个<code>int</code>数组，里面从下标$1$开始存放着输入数据第二行的$t$个数；</li>
<li>第三个参数是一个<code>int</code>二维数组，函数执行完成之后，第i种物质和第j种物质反应的产物的是第<code>g[i][j]</code>种物质；</li>
<li>该函数返回一个<code>int</code>，表示【题目描述】中的$n$。</li>
</ul><p>程序能根据描述化学药品性质的$t$个正整数生成一个二维<code>int</code>数组<code>g</code>。根据【题目描述】，该数组满足：</p>
<ul><li>第i种化学物质和第j种化学物质反应生成第<code>g[i][j]</code>种化学物质；</li>
<li>产物与加入顺序无关，故<code>g[i][j]==g[j][i]</code>且<code>g[g[i][j]][k]==g[i][g[j][k]]</code>成立；</li>
<li>$n$种物质中恰有一种是水，保证其反应性质满足题目中的描述；</li>
<li>二维数组<code>g</code>的每一行、每一列都恰有一个是水。</li>
</ul><p>参考用法：</p>
<pre><code class="sh_cpp">#include &lt;cstdio&gt;
namespace LIB{ /* ... */ }
const int N=3010;
int a[N],b[N][N];
int main(){
    int t,m,q;
    scanf(&#34;%d%d%d&#34;,&amp;t,&amp;m,&amp;q);
    for(int i=1;i&lt;=t;i++){
        scanf(&#34;%d&#34;,a+i);
    }
    int n=LIB::put_reaction(t,a,b);
    /* ... */
    return 0;
}</code></pre>

# 限制与约定


<p>对于所有数据：</p>
<ul><li>$n\leq3000,m,q\leq10^6$；</li>
<li>$\forall i,1\leq L_i\leq R_i\leq m$；</li>
<li>$\forall i,a_i\neq 1$。</li>
</ul><div class="table-responsive"><table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th width="200">测试点编号</th><th>特殊约定</th>
    </tr></thead><tbody><tr><td>$1$</td><td>$n,m,q\leq100$</td></tr><tr><td>$2,3$</td><td>$m,q\leq4000$</td></tr><tr><td>$4,5$</td><td>$\min(m,q)\leq4000$</td></tr><tr><td>$6$</td><td>$n$为素数</td></tr><tr><td>$7$</td><td>$n$为若干不同质数乘积</td></tr><tr><td>$8$</td><td>$g[i][j]=((i-1) xor (j-1))+1$</td></tr><tr><td>$9,10,11,12,13,14,15,16,17,18,19,20$</td><td>无</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$\texttt{2s}$</p>
<p><strong>空间限制：</strong>$\texttt{512MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=427">样例数据下载</a></p>
