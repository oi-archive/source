
# Description

<div class="content"><div>一共n×m个硬币，摆成n×m的长方形。dongdong和xixi玩一个游戏，每次可以选择一个连通块，并把其中的硬币全</div>
<div>部翻转，但是需要满足存在一个硬币属于这个连通块并且所有其他硬币都在它的左上方(可以正左方也可以正上方)</div>
<div>，并且这个硬币是从反面向上翻成正面向上。dongdong和xixi轮流操作。如果某一方无法操作，那么他(她)就输了</div>
<div>。dongdong先进行第一步操作，假设双方都采用最优策略。问dongdong是否有必胜策略。</div></div>

# Input

<div class="content"><div>第一行一个数T，表示他们一共玩T局游戏。</div>
<div>接下来是T组游戏描述。每组游戏第一行两个数n;m，</div>
<div>接下来n行每行m个字符，第i行第j个字符如果是“H”表示第i行第j列的硬币是正面向上，</div>
<div>否则是反面向上。第i行j列的左上方是指行不超过i并且列不超过j的区域。</div>
<div>1≤n;m≤100，1≤T≤50。</div></div>

# Output

<div class="content"><div>对于每局游戏，输出一行。</div>
<div>如果dongdong 存在必胜策略则输出“- -”(不含 引号) 否则输出“= =”(不含引号)。</div>
<div>(注意输出的都是半角符号，即三个符号 ASCII 码分别为45,61,95)</div></div>

# Sample Input

<div class="content"><span class="sampledata">32<br/>
3<br/>
HHH<br/>
HHH<br/>
2 3<br/>
HHH<br/>
TTH<br/>
2 1<br/>
T<br/>
H<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">= =<br/>
- -<br/>
- -<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

