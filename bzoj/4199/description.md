
# Description

<div class="content"><p> 一年一度的“幻影阁夏日品酒大会”隆重开幕了。大会包含品尝和趣味挑战两个环节，分别向优胜者颁发“首席品</p>
<div>酒家”和“首席猎手”两个奖项，吸引了众多品酒师参加。在大会的晚餐上，调酒师Rainbow调制了 n 杯鸡尾酒。</div>
<div>这 n 杯鸡尾酒排成一行，其中第 i 杯酒 (1≤i≤n) 被贴上了一个标签 s_i ，每个标签都是 26 个小写英文字母</div>
<div>之一。设 Str(l,r) 表示第 l 杯酒到第 r 杯酒的 r-l+1 个标签顺次连接构成的字符串。若 Str(p,po)=Str(q,qo</div>
<div>) ，其中 1≤p≤po≤n,1≤q≤qo≤n,p≠q,po-p+1=qo-q+1=r ，则称第 p 杯酒与第 q 杯酒是“ r 相似”的。当</div>
<div>然两杯“ r 相似”(r&gt;1)的酒同时也是“ 1 相似”、“ 2 相似”、……、“ (r-1) 相似”的。在品尝环节上，</div>
<div>品酒师Freda轻松地评定了每一杯酒的美味度，凭借其专业的水准和经验成功夺取了“首席品酒家”的称号，其中</div>
<div>第 i 杯酒 (1≤i≤n) 的美味度为 a_i 。现在Rainbow公布了挑战环节的问题：本次大会调制的鸡尾酒有一个特点</div>
<div>，如果把第 p 杯酒与第 q 杯酒调兑在一起，将得到一杯美味度为 a_p a_q 的酒。现在请各位品酒师分别对于 r=</div>
<div>0,1,2,?,n-1 ，统计出有多少种方法可以选出 2 杯“ r 相似”的酒，并回答选择 2 杯“ r 相似”的酒调兑可以</div>
<div>得到的美味度的最大值。</div>
<div></div></div>

# Input

<div class="content"><div>输入文件的第1行包含1个正整数 n ，表示鸡尾酒的杯数。</div>
<div>第 2 行包含一个长度为 n 的字符串 S ，其中第 i 个字符表示第 i 杯酒的标签。</div>
<div>第 3 行包含 n 个整数，相邻整数之间用单个空格隔开，其中第 i 个整数表示第 i 杯酒的美味度 a_i 。</div>
<div>n=300,000<span class="Apple-tab-span" style="white-space: pre;">	</span>|a_i |≤1,000,000,000<span class="Apple-tab-span" style="white-space: pre;">	</span></div>
<div></div></div>

# Output

<div class="content"><p>输出文件包括 n 行。第 i 行输出 2 个整数，中间用单个空格隔开。</p>
<div>
<div>第 1 个整数表示选出两杯“ (i-1)&#34; &#34; 相似”的酒的方案数，</div>
<div>第 2 个整数表示选出两杯“ (i-1) 相似”的酒调兑可以得到的最大美味度。</div>
<div>若不存在两杯“ (i-1) 相似”的酒，这两个数均为 0 。</div>
<div></div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
ponoiiipoi<br/>
2 1 4 7 4 8 3 6 4 7</span></div>

# Sample Output

<div class="content"><span class="sampledata">45 56<br/>
10 56<br/>
3 32<br/>
0 0<br/>
0 0<br/>
0 0<br/>
0 0<br/>
0 0<br/>
0 0<br/>
0 0<br/>
【样例说明1】<br/>
用二元组 (p,q) 表示第 p 杯酒与第 q 杯酒。<br/>
0 相似：所有 45 对二元组都是 0 相似的，美味度最大的是 8×7=56 。<br/>
1 相似： (1,8) (2,4) (2,9) (4,9) (5,6) (5,7) (5,10) (6,7) (6,10) (7,10) ，最大的 8×7=56 。<br/>
2 相似： (1,8) (4,9) (5,6) ，最大的 4×8=32 。<br/>
没有 3,4,5,?,9 相似的两杯酒，故均输出 0 。</span></div>

# Hint

<div class="content"><p></p><p></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

