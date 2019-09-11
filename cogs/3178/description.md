# 题目描述


<h3>
【题目描述】
</h3>
<p>
<strong> </strong> 
</p>
<p>
<strong>小 D 擅长搞操作。</strong> 
</p>
<p>
<strong>对于一个序列 A（下标从 0 编号），小 D 可以做如下操作获得序列 B：</strong> 
</p>
<p>
<strong>• B 是一个空序列。</strong> 
</p>
<p>
<strong>• 从 0 至 length(A) - 1 枚举 i，从 0 至 length(A) - i - 1 枚举 j。</strong> 
</p>
<p>
<strong>• 对于枚举的每一个 (i, j)，依次将 max$ A_k$ (<strong>k=j-i+j)</strong>加入 B 的末尾。</strong> 
</p>
<p>
<strong>小 D 太喜欢操作了，于是按照同样的方法由 B 操作出了序列 C。</strong> 
</p>
<p>
<strong>小 D 想知道 ∑$C_i$<strong><strong>(i=0-</strong>length(C)-1)</strong>，对 $10^9$ + $7 $取模。</strong> 
</p>
<h3>
【输入格式】
</h3>
<p>
第一行，正整数 n，代表 A 的长度。
</p>
<p>
第二行， n 个正整数，代表序列 A。
</p>
<h3>
【输出格式】
</h3>
<p>
输出一行，一个整数，代表取模后的答案。
</p>
<h3>
【样例输入】
</h3>
<pre>3
3 2 1
</pre>
<h3>
【样例输出】
</h3>
<pre>58
</pre>
<h3>
【提示】
</h3>
<p>
保证$ n$ ≤ $2 $∗ $10^5$， $1$ ≤ $A_i$ ≤$ 10^6$。
</p>
