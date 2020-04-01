
# Description

<div class="content"><div>小克里斯现今遇上了可怕的事情，甚至他在梦中也总是想着数学。</div>
<div>克里斯梦到了m个从1到m编号的长度为n的二进制串。最使人震惊的</div>
<div>是，每个二进制串的各个位均按照不下降或者不上升顺序排列。例如，克里斯能</div>
<div>梦到接下来这四个长度为五的二进制串：</div>
<div>00011</div>
<div>00000</div>
<div>11110</div>
<div>11111</div>
<div>两个长度为n的串a和b之间的汉明距离H(a，b)为对应符号不相同的位</div>
<div>数。克里斯认为每三个有不同编号的二进制串组成一个三角；并且他有一种错觉，</div>
<div>只要他能计算出在所有用梦到的二进制串构成的三角a，b，c中，和H(a，</div>
<div>b)+H(b，c)+H(c，a)为最大值的三角数，就能醒来。</div>
<div>请帮助困于噩梦中的克里斯</div>
<p></p></div>

# Input

<div class="content"><div>输入第一行包含两个整数n和m（1&lt;=n&lt;=10^9;3&lt;=m&lt;=10^5），二进制串的长度及数量。</div>
<div>接下来m行描述这些二进制串。第i行包含两个整数si及fi（0&lt;=si&lt;=1;1&lt;=fi&lt;=n），</div>
<div>描述编号为i的二进制串：第i个二进制串的前fi位等于si，</div>
<div>然后剩下n-fi位等于1-si。注意在克里斯梦中可以有多个相同的二进制串。</div>
<p></p></div>

# Output

<div class="content"><div>输出单独一个整数，这些个汉明距离和为最大值的二进制串三角的个数</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 4<br/>
0 3<br/>
0 5<br/>
1 4<br/>
1 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

