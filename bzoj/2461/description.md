
# Description

<div class="content"><p><span style="font-size: medium">  在可以炼制魔力强大的法杖的同时，Magic Land 上的人们渐渐意识到，魔力<br/>
强大并不一定能给人们带来好处——反而，由此产生的破坏性的高魔力释放，给<br/>
整个大陆蒙上了恐怖的阴影。 <br/>
 <br/>
  可控的魔力释放，成为了人们新的追求。这种控制魔力释放的技术，也就是<br/>
被现在的我们熟知的“魔法”。在远古时期，“魔法”由法师们口口相传，但也因<br/>
为这样，很多“古代魔法”已经成为传说——因为那时没有良好的记录魔法的方<br/>
法。 <br/>
 <br/>
  后来，天才法师Ferdinand 发现了一种记录魔法的方法：将一种特殊材料做<br/>
成的正反面均有 1行 N列格子的带子的一端扭转 180度之后与另一端粘贴，<br/>
这样就得到了一个仅有一面的环，被称为“符环” （Spell Ring） 。 <br/>
   符环上的某一个格子为“起始位”，并标有起始方向，这样，我们就可以给<br/>
这个环上的每一个格子进行编号： 起始位编号是 0，向起始方向移动一格为 1，<br/>
这样，一共有 2N 个格子，并且第 i 个格子的背面（虽然带子是一面的，但<br/>
是仍然有“背面”这个概念）是第(i+N) mod N 格。 <br/>
 <br/>
  法师们将魔法用一个由魔法标记“（”和“）”组成的串表示。人们发现，<br/>
所有魔法对应的串都为合法的括号序列，并且任何一个合法的括号序列都<br/>
对应一个魔法。可以发现，合法的括号序列长度均为偶数，这样就可以把一个<br/>
魔法写在符环之中：从起始格开始，向起始方向，依次写入魔法标记。 <br/>
 <br/>
  这种特殊的材料使得符环带有美丽的色彩：假如一个格子的两面写有相同<br/>
的魔法标记（即：假设这个带子是透明的，两个魔法标记重合），那么这<br/>
个格子会变为绯红色（Scarlet） ；反之，若两面的魔法标记不同，会变为深<br/>
蓝色（Deep blue）。 <br/>
   现在，你得到了一些古代的符环，由于年代久远，魔法标记已经变得模糊不<br/>
清，但是颜色依然保持完好。你希望知道：给定的颜色信息，对应了多少种<br/>
不同的魔法？ </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium"><br/>
第一行包含一个正整数T，表示符环的数量。 <br/>
  接下来的 T 行，每一行包含一个符环的颜色信息： <br/>
一个长度为 N的由大写字母“S”和“D”组成的字符串。 <br/>
“S”表示绯红色（Scarlet），“D”表示深蓝色（Deep blue）。 <br/>
从左到右依次为第 0、1、……、N-1 个格子的颜色。 </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">包含T 行： <br/>
每行一个正整数，表示该符环对应的不同魔法的数量。</span></p>
<p><span style="font-size: medium"><br/>
</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 <br/>
D <br/>
SSD <br/>
SDSDSDSDSDSDSDSDSDSDSDSDSDSDSDSDSDSDSDSDSDSDSDSDSD </span></div>

# Sample Output

<div class="content"><span class="sampledata">  1 <br/>
  1 <br/>
  0 </span></div>

# Hint

<div class="content"><p></p><p>第一张符环对应了唯一的魔法“（）”。 <br/><br/>
第二张符环对应了唯一的魔法“（）（（））”。 <br/><br/>
对于第三张符环，它的长度为50，颜色是交替的。可以证明，它不能对应任<br/><br/>
何魔法。</p><br/>
<p></p><br/>
<p> 对于全部的数据：N ≤ 50，T ≤ 10。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day2">Day2</a></p></div>

