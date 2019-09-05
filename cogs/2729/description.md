# 题目描述


<p>
<img alt="" src="/upload/image/20170711/20170711213632_31593.png"/> 
</p>
<p>
<img alt="" src="/upload/image/20170711/20170711213717_70151.png"/> 
</p>
<p>
<img alt="" src="/upload/image/20170711/20170711213802_79179.png"/> 
</p>
<p>
<img alt="" src="/upload/image/20170711/20170711213843_54573.png"/> 
</p>
<p>
以及，由于数据的问题，各位同学在提交的时候需要加上数据生成器，详情请参照以下模板
</p>
<p>
<br/>
</p>
<pre class="prettyprint lang-cpp">#include &lt;iostream&gt;
#include &lt;algorithm&gt;
// DATA_GEN --- BEGIN ---// 你可以直接将这个数据生成器嵌入到你的代码中
// 或者，你也可以根据自己程序的需要，自己改写这个数据生成器
// 使用方法：从输入文件读入 N 和随机数种子之后，调用 gen_data 方法，可以将获得的排列 {A}, {B}, {C} 分别存放在对应 3 个数组中
const int MAXN = 2e6 + 10;
int lastInt, seed;
inline int nextInt() {
	static const int mod = 1e9 + 7;
	lastInt = lastInt ^ (((long long) lastInt * lastInt + seed) % mod);
	return lastInt;
}
void getPerm(int P[], int n, int x0, int c) {
	for (int i = 1; i &lt;= n; ++i) P[i] = i;
	lastInt = x0;
	seed = c;
	for (int i = n; i &gt;= 1; --i) std::swap(P[i], P[nextInt() % i + 1]);
}
int n, A[MAXN], B[MAXN], C[MAXN];  // 生成的排列将存储在这三个数组中
void gen_data(int n, int a0, int seed_a, int b0, int seed_b, int c0, int seed_c) {
	getPerm(A, n, a0, seed_a);
	getPerm(B, n, b0, seed_b);
	getPerm(C, n, c0, seed_c);
}
// DATA_GEN --- END ---
int main()
{
	int n;
	int a0, s_a;
	int b0, s_b;
	int c0, s_c;
	std::cin &gt;&gt; n;
	std::cin &gt;&gt; a0 &gt;&gt; s_a;
	std::cin &gt;&gt; b0 &gt;&gt; s_b;
	std::cin &gt;&gt; c0 &gt;&gt; s_c;
	gen_data(n, a0, s_a, b0, s_b, c0, s_c);
	/*
	在这里填写你的程序
	*/
	return 0;
}</pre>
<p>
<br/>
</p>
<p>
<br/>
</p>
