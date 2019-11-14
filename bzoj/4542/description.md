
# Description

<div class="content"><p>　　小 B 有一个很大的数 S，长度达到了 N 位；这个数可以看成是一个串，它可能有前导 0，例如00009312345<br/>
。小B还有一个素数P。现在，小 B 提出了 M 个询问，每个询问求 S 的一个子串中有多少子串是 P 的倍数（0 也<br/>
是P 的倍数）。例如 S为0077时，其子串 007有6个子串：0,0,7,00,07,007；显然0077的子串007有6个子串都是素<br/>
数7的倍数。</p></div>

# Input

<div class="content"><p>　　第一行一个整数：P。第二行一个串：S。第三行一个整数：M。接下来M行，每行两个整数 fr,to，表示对S 的<br/>
子串S[fr…to]的一次询问。注意：S的最左端的数字的位置序号为 1；例如S为213567，则S[1]为 2，S[1…3]为 2<br/>
13。N,M&lt;=100000，P为素数</p></div>

# Output

<div class="content"><p>　　输出M行，每行一个整数，第 i行是第 i个询问的答案。</p></div>

# Sample Input

<div class="content"><span class="sampledata">11 <br/>
121121 <br/>
3 <br/>
1 6 <br/>
1 5 <br/>
1 4 </span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
3<br/>
2<br/>
//第一个询问问的是整个串，满足条件的子串分别有：121121,2112,11,121,121。</span></div>

# Hint

<div class="content"><p></p><p> 2016.4.19新加数据一组</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

