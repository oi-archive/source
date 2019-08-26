
# Description

<div class="content"><div>学校组织了一次新生舞会，Cathy作为经验丰富的老学姐，负责为同学们安排舞伴。有n个男生和n个女生参加舞会</div>
<div>买一个男生和一个女生一起跳舞，互为舞伴。Cathy收集了这些同学之间的关系，比如两个人之前认识没计算得出 </div>
<div>a[i][j] ，表示第i个男生和第j个女生一起跳舞时他们的喜悦程度。Cathy还需要考虑两个人一起跳舞是否方便，</div>
<div>比如身高体重差别会不会太大，计算得出 b[i][j]，表示第i个男生和第j个女生一起跳舞时的不协调程度。当然，</div>
<div>还需要考虑很多其他问题。Cathy想先用一个程序通过a[i][j]和b[i][j]求出一种方案，再手动对方案进行微调。C</div>
<div>athy找到你，希望你帮她写那个程序。一个方案中有n对舞伴，假设没对舞伴的喜悦程度分别是a&#39;1,a&#39;2,...,a&#39;n，</div>
<div>假设每对舞伴的不协调程度分别是b&#39;1,b&#39;2,...,b&#39;n。令</div>
<div>C=(a&#39;1+a&#39;2+...+a&#39;n)/(b&#39;1+b&#39;2+...+b&#39;n),Cathy希望C值最大。</div>
<div></div></div>

# Input

<div class="content"><div>第一行一个整数n。</div>
<div>接下来n行，每行n个整数，第i行第j个数表示a[i][j]。</div>
<div>接下来n行，每行n个整数，第i行第j个数表示b[i][j]。</div>
<div>1&lt;=n&lt;=100,1&lt;=a[i][j],b[i][j]&lt;=10^4</div>
<div></div></div>

# Output

<div class="content"><div>一行一个数，表示C的最大值。四舍五入保留6位小数，选手输出的小数需要与标准输出相等</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
19 17 16<br/>
25 24 23<br/>
35 36 31<br/>
9 5 6<br/>
3 4 2<br/>
7 8 9</span></div>

# Sample Output

<div class="content"><span class="sampledata">5.357143</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢infinityedge上传">鸣谢infinityedge上传</a></p></div>

