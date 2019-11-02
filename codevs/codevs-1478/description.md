<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>杜伊通过自杀激活了身上的魂魄驱动器,使优莱卡的某力量约束装置失效.优莱卡彻底 变为珊瑚形态,被囚禁在生命之树内,人类和珊瑚开始走向灭亡. 然而此时此刻的兰顿,出于对优莱卡的爱,出于对世界的爱,依然不放弃最后的希望. 在 得知优莱卡的生命信号还存在后,兰顿立马驾驶着零式机尼尔瓦修前去拯救优莱卡.然而命 运多舛,在这紧要关头,兰顿遇到了大量的抗体科达利安,尼尔瓦修因为长期战斗已经难以硬 … 扛住这些阻碍者了 于是兰顿开始分析自己的处境, … 准备要巧妙的击败眼前的阻碍 具体来说,兰顿面临这 样一个情况: 在一个n*n的区域中散布着许多抗体科达利安,兰顿拥有的武器可以一次打击一行或者 一列的敌人,使得这一行(列)的每个子区域敌人数量减少1,如果一个区域敌人已经被消灭光 了,那自然也不会减少了.然而因为不同科达利安的强度不同,打击不同行与不同列的能量不 同,我们用Ai表示打击一次第i 行需要的能量,用Bi表示打击一次第i 列 … 需要的能量 自然而然的,若想安全的通过此区域,必然要消灭所有的 … 抗体科达利安 由于未来充满 了未知的挑战,兰顿并不想消耗太多的能量来消灭敌人,所以他只使用了最少的能量来打击 敌人, … 最终成功的拯救了优莱卡 这一事迹将被载入史书,作为史书的编辑人你得计算出这 个最小值以及方案…</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含一个正整数n…<br>第二行有n个正整数,表示A … 数组<br>第三行有n个正整数,表示B数组.A,B … 数组含义见题面红字部分<br>接下来n行,每行n个正整数,用ai,j来表示在这个n*n的区域中每个小格点的抗体科<br>达利安的个数…</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第一行一个数, &hellip; 表示最少使用的能量<br />第二行有n个数,表示对第i &hellip; 行进行了多少次打击<br />第三行有n个数,表示对第i &hellip; 列进行了多少次打击</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4<br>12 23 26 14 <br>18 20 18 16 <br>0 2 2 2 <br>0 2 0 2 <br>0 2 1 0 <br>2 2 0 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>130<br>1 0 0 2 <br>0 2 1 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>