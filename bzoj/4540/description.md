
# Description

<div class="content"><p>　　给定长度为n的序列：a1,a2,…,an，记为a[1:n]。类似地，a[l:r]（1≤l≤r≤N）是指序列：a<sub>l</sub>,a<sub>l+1</sub>,…,a<sub>r-<br/>
1</sub>,a<sub>r</sub>。若1≤l≤s≤t≤r≤n，则称a[s:t]是a[l:r]的子序列。现在有q个询问，每个询问给定两个数l和r，1≤l≤r<br/>
≤n，求a[l:r]的不同子序列的最小值之和。例如，给定序列5,2,4,1,3，询问给定的两个数为1和3，那么a[1:3]有<br/>
6个子序列a[1:1],a[2:2],a[3:3],a[1:2],a[2:3],a[1:3]，这6个子序列的最小值之和为5+2+4+2+2+2=17。</p></div>

# Input

<div class="content"><p>　　输入文件的第一行包含两个整数n和q，分别代表序列长度和询问数。接下来一行，包含n个整数，以空格隔开<br/>
,第i个整数为ai，即序列第i个元素的值。接下来q行，每行包含两个整数l和r，代表一次询问。</p></div>

# Output

<div class="content"><p>　　对于每次询问，输出一行，代表询问的答案。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 5 <br/>
5 2 4 1 3 <br/>
1 5 <br/>
1 3 <br/>
2 4 <br/>
3 5 <br/>
2 5 </span></div>

# Sample Output

<div class="content"><span class="sampledata">28 <br/>
17 <br/>
11 <br/>
11 <br/>
17 </span></div>

# Hint

<div class="content"><p></p><p>1 ≤N,Q ≤ 100000,|Ai| ≤ 10^9</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

