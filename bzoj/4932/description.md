
# Description

<div class="content"><div>给定一个长度为n的字符串s，有q组询问，每个询问给定L,r，询问s[L..r]中有多少本质不同的回文子串。</div>
<p></p></div>

# Input

<div class="content"><div>第一行一个整数type，若type=0，表示这个数据没有进行加密，若</div>
<div>type=1，表示这个数据进行了加密。</div>
<div>第二行两个整数n,q。</div>
<div>第三行一个字符串s。</div>
<div>接下来q行，每行两个整数L′,r′。记Lastans为上一次询问的答案，</div>
<div>若这是第一次询问，Lastans=0，则这次猜测的L,r为，L=L′⊕(type×</div>
<div>Lastans),r=r′⊕(type×Lastans)。</div>
<div>N&lt;=100000</div>
<div>q ≤ 2n, 且解密后的 L, r 满足 1 ≤ L ≤ r ≤ n。字符串的字符集为小写字母</div>
<p></p></div>

# Output

<div class="content"><div>输出共q行，代表每个询问的答案。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1 <br/>
8 4 <br/>
abbabbba <br/>
1 7 <br/>
3 2<br/>
6 10<br/>
1 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">7<br/>
2<br/>
5<br/>
2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

