
# Description

<div class="content"><p>采油区域 Siruseri政府决定将石油资源丰富的Navalur省的土地拍卖给私人承包商以建立油井。被拍卖的整块土地为一个矩形区域，被划分为M×N个小块。 Siruseri地质调查局有关于Navalur土地石油储量的估测数据。这些数据表示为M×N个非负整数，即对每一小块土地石油储量的估计值。 为了避免出现垄断，政府规定每一个承包商只能承包一个由K×K块相连的土地构成的正方形区域。 AoE石油联合公司由三个承包商组成，他们想选择三块互不相交的K×K的区域使得总的收益最大。 例如，假设石油储量的估计值如下： 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 8 8 8 8 8 1 1 1 1 8 8 8 8 8 1 1 1 1 8 8 8 8 8 1 1 1 1 1 1 1 8 8 8 1 1 1 1 1 1 1 1 8 8 8 1 1 1 1 1 1 9 9 9 1 1 1 1 1 1 9 9 9 如果K = 2, AoE公司可以承包的区域的石油储量总和为100, 如果K = 3, AoE公司可以承包的区域的石油储量总和为208。 AoE公司雇佣你来写一个程序，帮助计算出他们可以承包的区域的石油储量之和的最大值。</p></div>

# Input

<div class="content"><p>输入第一行包含三个整数M, N, K，其中M和N是矩形区域的行数和列数，K是每一个承包商承包的正方形的大小（边长的块数）。接下来M行，每行有N个非负整数表示这一行每一小块土地的石油储量的估计值</p></div>

# Output

<div class="content"><p>输出只包含一个整数，表示AoE公司可以承包的区域的石油储量之和的最大值。</p></div>

# Sample Input

<div class="content"><span class="sampledata">9 9 3 <br/>
1 1 1 1 1 1 1 1 1 <br/>
1 1 1 1 1 1 1 1 1 <br/>
1 8 8 8 8 8 1 1 1 <br/>
1 8 8 8 8 8 1 1 1 <br/>
1 8 8 8 8 8 1 1 1 <br/>
1 1 1 1 8 8 8 1 1 <br/>
1 1 1 1 1 1 8 8 8 <br/>
1 1 1 1 1 1 9 9 9 <br/>
1 1 1 1 1 1 9 9 9 </span></div>

# Sample Output

<div class="content"><span class="sampledata">208</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

