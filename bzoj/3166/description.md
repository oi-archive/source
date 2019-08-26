
# Description

<div class="content"><p><span style="font-size: medium">Welcome to ALO ( Arithmetic and Logistic Online)。这是一个VR MMORPG ，<br/>
如名字所见，到处充满了数学的谜题。<br/>
现在你拥有n颗宝石，每颗宝石有一个能量密度，记为ai，这些宝石的能量<br/>
密度两两不同。现在你可以选取连续的一些宝石（必须多于一个）进行融合，设为  ai, ai+1, …, a j，则融合而成的宝石的能量密度为这些宝石中能量密度的次大值<br/>
与其他任意一颗宝石的能量密度按位异或的值，即，设该段宝石能量密度次大值<br/>
为k，则生成的宝石的能量密度为max{k xor ap | ap ≠ k , i ≤ p ≤ j}。 <br/>
现在你需要知道你怎么选取需要融合的宝石，才能使生成的宝石能量密度最大。 <br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">第一行，一个整数 n，表示宝石个数。 <br/>
第二行， n个整数，分别表示a1至an，表示每颗宝石的能量密度，保证对于i ≠ j有 ai ≠ aj。 <br/>
 <br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">输出一行一个整数，表示最大能生成的宝石能量密度。 <br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 <br/>
9  2 1 4 7<br/>
 <br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">14 <br/>
 <br/>
 </span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
【样例解释】 <br/><br/>
选择区间[1,5]，最大值为 7 xor 9。 <br/><br/>
 <br/><br/>
 <br/><br/>
对于 100%的数据有 1 ≤ n ≤ 50000, 0 ≤ ai ≤ 10^9</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=加强型数据By Hta">加强型数据By Hta</a></p></div>

