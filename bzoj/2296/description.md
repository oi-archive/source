
# Description

<div class="content"><p></p>
<p></p>
<p></p><dd>
<div>
<p>1tthinking除了随机算法，其他什么都不会。但是他还是可以ac很多题目，他用的是什么呢？他会选择一个好的随机种子，然后输出答案。往往他选择的一个好的种子可以有99%的概率ac题目。</p>
<p>他会按照下面的规则选择一个种子。首先1tthinking有自己喜欢的一个幸运数字 <em>x</em>。然后他会找一个数字 <em>a</em> 使得 (1)<em>a</em> is a 是 <em>x</em> 的倍数 (2) <em>a</em> 的十进制表示包含0到9。</p>
<p>举个例子, 如果 <em>x</em> = 1, 那么 9182736450 就是一个1tthinking需要的随机种子。</p>
<p>然而1tthinking有的时候花了很久也找不到这个数，他感到很失望。现在他把问题留给了你。</p>
<p><img alt="" src="/source/bzoj/2296/img/aHR0cDovL21lZGlhLm9wZW5qdWRnZS5jbi9pbWFnZXMvZzMyMDZfMS5qcGc=.jpg"/></p>
</div>
<p></p>
<p></p>
</dd>
<p></p></div>

# Input

<div class="content"><p></p>
<p></p>
<p></p><dt>  </dt>
<dd>
<div>
<p>第1行，一个整数 <em>T</em> (0 ≤ <em>T</em> ≤ 100), 幸运数字的数量。</p>
<p>第2到 <em>T</em> + 1行: <em>X<sub>i</sub></em> (0 ≤ <em>X<sub>i</sub></em> ≤ 10<sup>6</sup>), 1tthinking的幸运数字。</p>
</div>
<p></p>
<p></p>
</dd>
<p></p></div>

# Output

<div class="content"><p></p>
<p></p>
<p></p><dt>  </dt>
<dd>
<p>第1到 <em>T</em>: 一个整数 <em>Y<sub>i</sub></em> (0 ≤ <em>Y<sub>i</sub></em> ≤ 10<sup>16</sup>), 满足条件的随机种子. 如果不存在，输出-1。</p>
<p></p>
<p></p>
</dd>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
1<br/>
2<br/>
10<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">9876543210<br/>
9876543210<br/>
9876543210<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢 dnc1994提供spj程序">鸣谢 dnc1994提供spj程序</a></p></div>

