<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>相传，在远古时期，位于西方大陆的 Magic Land 上，人们已经掌握了用魔<br>法矿石炼制法杖的技术。那时人们就认识到，一个法杖的法力取决于使用的矿石。<br>一般地，矿石越多则法力越强，但物极必反：有时，人们为了获取更强的法力而<br>使用了很多矿石，却在炼制过程中发现魔法矿石全部消失了，从而无法炼制<br>出法杖，这个现象被称为“魔法抵消” 。特别地，如果在炼制过程中使用超过<br>一块同一种矿石，那么一定会发生“魔法抵消”。 <br> <br> 后来，随着人们认知水平的提高，这个现象得到了很好的解释。经过了大量<br>的实验后，著名法师 Dmitri 发现：如果给现在发现的每一种矿石进行合理的编<br>号（编号为正整数，称为该矿石的元素序号），那么，一个矿石组合会产生“魔<br>法抵消”当且仅当存在一个非空子集，那些矿石的元素序号按位异或起来<br>为零。 （如果你不清楚什么是异或，请参见下一页的名词解释。 ）例如，使用两<br>个同样的矿石必将发生“魔法抵消”，因为这两种矿石的元素序号相同，异或起<br>来为零。</p>
<p>并且人们有了测定魔力的有效途径，已经知道了：合成出来的法杖的魔力<br>等于每一种矿石的法力之和。人们已经测定了现今发现的所有矿石的法力值，<br>并且通过实验推算出每一种矿石的元素序号。 <br> <br> 现在，给定你以上的矿石信息，请你来计算一下当时可以炼制出的法杖最多<br>有多大的魔力。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含一个正整数N，表示矿石的种类数。 <br> 接下来 N行，每行两个正整数Numberi 和 Magici，表示这种矿石的元素序号<br>和魔力值。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅包一行，一个整数：最大的魔力值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 <br> 1 10 <br> 2 20 <br> 3 30</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>50 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 30%的数据：N ≤ 10； <br>另外有 40%的数据：Numberi 在二进制表示下恰好有两位是1，如样例 2； <br>对于全部的数据：N ≤ 1000，Numberi ≤ 10<sup>18</sup>，Magici ≤ 10<sup>4</sup>。</p>
</div>
</div>