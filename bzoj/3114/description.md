
# Description

<div class="content"><p><span style="font-size: medium">给定一个数N，求所有满足最小公倍数为N的a,b的和对1000000007取模.</span></p>
<p><span style="font-size: medium">例如当N=6时，有如下对数</span><span style="font-size: medium">(1,6),(2,6),(2,3),(3,6),(6,6),其和为=(1+6)+(2+6)+(2+3)+(3+6)+(6+6)=7+8+5+9+12=41。</span></p>
<div style="text-indent: 21pt"><span style="font-size: medium">现在给你N的分解质因数式，请你求出相应的值。</span></div></div>

# Input

<div class="content"><div> </div>
<div style="text-indent: 21pt"><span style="font-size: medium">多组测试数据。第一行T表示数据组数。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">每组数据第一行为M，表示有M的质因子。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">下面M行，每行两个数，第一行为这个质因子，第二行为这个质因子在N中出现的次数。</span></div></div>

# Output

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">T行，每行一个整数表示f(N)的值。因为答案可能很大，所以只需输出答案 mod 1000000007。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
2<br/>
2 1<br/>
3 1<br/>
2<br/>
2 2<br/>
3 1<br/>
1<br/>
5 1<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case 1: 41<br/>
Case 2: 117<br/>
Case 3: 16<br/>
 <br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>100%保证t&lt;=500，m&lt;=15,每个质因数是2-1000内的质数,次数大于等于1小于等于50<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

