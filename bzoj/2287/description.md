
# Description

<div class="content"><p></p><dd>
<div>
<p>ftiasch 有 <em>N</em> 个物品, 体积分别是 <em>W<sub>1</sub></em>, <em>W<sub>2</sub></em>, ..., <em>W<sub>N</sub></em>。 由于她的疏忽, 第 <em>i</em> 个物品丢失了。 “要使用剩下的 <em>N</em> - 1 物品装满容积为 <em>x</em> 的背包，有几种方法呢？” -- 这是经典的问题了。她把答案记为 <em>Count(i, x)</em> ，想要得到所有1 &lt;= i &lt;= N, 1 &lt;= x &lt;= M的 <em>Count(i, x)</em> 表格。</p>
<p><img src="/source/bzoj/2287/img/aHR0cDovL21lZGlhLm9wZW5qdWRnZS5jbi9pbWFnZXMvZzMxOTdfMS5wbmc=.png" alt=""/></p>
</div>
</dd>
<p></p></div>

# Input

<div class="content"><p></p><dt>  </dt>
<dd>
<div>
<p>第1行：两个整数 <em>N</em> (1 ≤ <em>N</em> ≤ 2 × 10<sup>3</sup>) 和 <em>M</em> (1 ≤ <em>M</em> ≤ 2 × 10<sup>3</sup>)，物品的数量和最大的容积。</p>
<p>第2行： <em>N</em> 个整数 <em>W<sub>1</sub></em>, <em>W<sub>2</sub></em>, ..., <em>W<sub>N</sub></em>, 物品的体积。</p>
</div>
</dd>
<p></p></div>

# Output

<div class="content"><p></p><dt>  </dt>
<dd>
<div>
<p>一个 <em>N</em> × <em>M</em> 的矩阵， <em>Count(i, x)</em>的末位数字。</p>
</div>
</dd>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 2<br/>
1 1 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">11<br/>
11<br/>
21<br/>
</span></div>

# Hint

<div class="content"><p></p><p>如果物品3丢失的话，只有一种方法装满容量是2的背包，即选择物品1和物品2。<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

