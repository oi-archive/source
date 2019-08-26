
# Description

<div class="content"><div>
<div>一个长度为n的序列a，设其排过序之后为b，其中位数定义为b[n/2]，其中a,b从0开始标号,除法取下整。给你一个</div>
<div>长度为n的序列s。回答Q个这样的询问：s的左端点在[a,b]之间,右端点在[c,d]之间的子序列中，最大的中位数。</div>
<div>其中a&lt;b&lt;c&lt;d。位置也从0开始标号。我会使用一些方式强制你在线。</div>
</div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行序列长度n。接下来n行按顺序给出a中的数。</div>
<div>接下来一行Q。然后Q行每行a,b,c,d，我们令上个询问的答案是</div>
<div>x(如果这是第一个询问则x=0)。</div>
<div>令数组q={(a+x)%n,(b+x)%n,(c+x)%n,(d+x)%n}。</div>
<div>将q从小到大排序之后，令真正的</div>
<div>要询问的a=q[0],b=q[1],c=q[2],d=q[3]。　　</div>
<div>输入保证满足条件。</div>
<div>第一行所谓“排过序”指的是从小到大排序！</div>
<div>n&lt;=20000,Q&lt;=25000</div>
</div>
<div></div>
<p></p></div>

# Output

<div class="content"><p>Q行依次给出询问的答案。</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
170337785<br/>
271451044<br/>
22430280<br/>
969056313<br/>
206452321<br/>
3<br/>
3 1 0 2<br/>
2 3 1 4<br/>
3 1 4 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">271451044<br/>
271451044<br/>
969056313</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

