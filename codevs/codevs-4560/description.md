<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有两个仅包含小写英文字母的字符串A和B。现在要从字符串A中取出k个互不重叠的非空子串，然后把这k个子串按照其在字符串A中出现的顺序依次连接起来得到一个新的字符串，请问有多少种方案可以使得这个新串与字符串B相等？注意：子串取出的位置不同也认为是不同的方案。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是三个正整数n，m，k，分别表示字符串A的长度，字符串B的长度，以及问题描述中所提到的k，每两个整数之间用一个空格隔开。 </p><p>第二行包含一个长度为n的字符串，表示字符串A。 第三行包含一个长度为m的字符串，表示字符串B。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出共一行，包含一个整数，表示所求方案数。由于答案可能很大，所以这里要求输出答案对1,000,000,007取模的结果。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【Input1】</p><p>6 3 1 </p><p>aabaab </p><p>aab</p><p>【Input2】</p><p style="">6 3 2 </p><p style="">aabaab </p><p style="">aab</p><p>【Input3】</p><p style="">6 3 3 </p><p style="">aabaab </p><p style="">aab</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【Output1】</p><p>2</p><p>【Output2】</p><p>7</p><p>【Output3】</p><p>7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于第1组数据：1≤n≤500，1≤m≤50，k=1； </p><p>对于第2组至第3组数据：1≤n≤500，1≤m≤50，k=2； </p><p>对于第4组至第5组数据：1≤n≤500，1≤m≤50，k=m； </p><p>对于第1组至第7组数据：1≤n≤500，1≤m≤50，1≤k≤m； </p><p>对于第1组至第9组数据：1≤n≤1000，1≤m≤100，1≤k≤m； </p><p>对于所有10组数据：1≤n≤1000，1≤m≤200，1≤k≤m。</p><p><br></p>
</div>
</div>