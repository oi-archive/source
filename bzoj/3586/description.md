
# Description

<div class="content"><p><span style="font-size: medium">　　有一个字符串生成器，初始时生成的字符串为空串，它每次按照给定概率随机生成一个小写字母，加在当前已生成字符串的后面。<br/>
　　给定N个长度为L的字符串，每个字符串由小写字母组成。<br/>
　　如果在某个时候，发现每个给定字符串都在当前已生成的字符串中作为子串出现过，生成器就会停下来，将当前生成的字符串作为输出。<br/>
　　求输出字符串长度的期望值。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">　　第一行包含一个正整数C，表示有C组数据。<br/>
　　每组数据的第一行包含三个正整数N, L, T (L&lt;=6, T&lt;=10)。其中T表示生成器仅会生成前T个小写字母。<br/>
　　每组数据的第2~N+1行，每行包含一个长度为L的字符串，每个字符串由前T个小写英文字母组成。<br/>
　　每组数据的第N+2行包含T个不超过10000的正整数，设第i个正整数为x，那么字符串生成器生成第i个小写字母的概率为x/10000。输入保证这T个正整数之和为10000。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">　　包含C行，依次对应每组数据。每行包含一个实数，表示输出字符串长度的期望值。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
2 3 3<br/>
aac<br/>
abb<br/>
3333 3333 3334<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">40.5060771264</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium"><br/><br/>
数据规模和约定<br/><br/>
　　本题共10个测试点。<br/><br/>
　　对于30%的数据，N=1, C=1；<br/><br/>
　　对于60%的数据，N&lt;=4, C&lt;=2；<br/><br/>
　　对于100%的数据，N&lt;=8, C&lt;=20。<br/><br/>
　　其中N=1的数据中存在一个测试点，只有你的答案和我们的答案相差小于1才为正确，并且这个测试点中L=3, T=3；<br/><br/>
　　对于其他9个测试点，只有你的答案和我们的答案相差小于0.01才为正确。<br/><br/>
　　数据保证正确答案不会超过5*10^6。</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名提供">By 佚名提供</a></p></div>

