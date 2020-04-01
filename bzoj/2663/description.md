
# Description

<div class="content"><p><span style="font-size: medium">【问题描述】 <br/>
“作为你们本体的灵魂，为了能够更好的运用魔法，被赋予了既小巧又安全<br/>
的外形，„„” <br/>
 <br/>
  我们知道，魔法少女的生命被存放于一个称为灵魂宝石（Soul Gem）的装置<br/>
内。而有时，当灵魂宝石与躯体的距离较远时，魔法少女就无法控制自己的躯体<br/>
了。 <br/>
   <br/>
  在传说中，魔法少女 Abel仅通过推理就得到了这个现象的一般法则，被称为<br/>
Abel定理：   <br/>
  存在宇宙常量 R（是一个非负实数，或正无穷） ，被称为灵魂宝石常量，量<br/>
纲为空间度量（即：长度） 。如果某个魔法少女的灵魂宝石与她的躯体的距离严<br/>
格超过 R，则她一定无法控制自己的躯体；如果这个距离严格小于 R，则她一定<br/>
可以控制自己的躯体。 （这里的距离指平面的 Euclid距离。） <br/>
  注意：该定理不能预言距离刚好为 R 的情形。可能存在魔法少女 A 和 B，她<br/>
们离自己的灵魂宝石的距离都恰好为 R，但是 A可以控制自己的躯体，而 B 不可<br/>
以。 <br/>
   现在这个世界上再也没有魔法少女了，但是我们却对这个宇宙常量感兴趣。<br/>
我们只能通过之前的世界遗留下来的数据来确定这个常量的范围了。 <br/>
  每一组数据包含以下信息： <br/>
    ·一共有N 个魔法少女及她们的灵魂宝石，分别编号为 1~N。 <br/>
    ·这 N个魔法少女所在的位置是（Xi, Yi）。 <br/>
    ·这 N个灵魂宝石所在的位置是（xi, yi）。 <br/>
    ·此时恰好有 K个魔法少女能够控制自己的躯体。 <br/>
  需要注意的是： <br/>
1. 我们认为这个世界是二维的 Euclid 空间。 <br/>
    2. 魔法少女与灵魂宝石之间的对应关系是未知的。 <br/>
    3. 我们不知道是具体是哪 K个魔法少女能够控制自己的躯体。 <br/>
     <br/>
  根据以上信息，你需要确定灵魂宝石常量 R可能的最小值 Rmin 和最大值<br/>
Rmax。 </span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行包两个整数：N、K。 <br/>
接下来 N行，每行包含两个整数：Xi , Yi ，由空格隔开。 <br/>
再接下来N 行，每行包含两个整数：xi , yi ，由空格隔开。 <br/>
 </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">输出两个量：Rmin、Rmax，中间用空格隔开。 <br/>
Rmin 一定是一个非负实数，四舍五入到小数点后两位。 <br/>
Rmax 可能是非负实数，或者是正无穷： <br/>
  如果是非负实数，四舍五入到小数点后两位； <br/>
  如果是正无穷，输出“+INF”（不包含引号）。 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 1 <br/>
1 0 <br/>
4 0 <br/>
0 0 <br/>
4 4 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1.00 5.00 <br/>
<br/>
 </span></div>

# Hint

<div class="content"><p></p><p></p><br/>
<p>对于100%的数据： <br/><br/>
1 ≤  N  ≤  50， <br/><br/>
0 ≤  K  ≤  N， <br/><br/>
-1000 ≤  xi, yi , Xi , Yi  ≤  1000。 <br/><br/>
 <br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

