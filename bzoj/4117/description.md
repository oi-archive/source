
# Description

<div class="content"><p>我们假设每天只会出现四种天气：晴朗，多云，大雨，大雾，并已经预测了这四种天气每天出现的概率。现在我们要传输未来n天的天气状况。为了减轻传输压力，我们通过对n天所有4^n种可能的天气状况进行二进制编码来进行传输，并且不存在一个天气状况的编码是另外某一个编码的前缀。我们希望用某种编码方式来使将要传输的二进制位数的期望值最小。</p></div>

# Input

<div class="content"><p>第一行包含一个整数n(1≤n≤20)，表示将要传输未来n天的天气状况。<br/>
第二行包含四个和为1的实数，代表每天四种天气出现的概率。输入的每个实数最多精确到小数点后6位。</p></div>

# Output

<div class="content"><p>输出最小期望传输的二进制位数，绝对误差或相对误差不超过1e-4。</p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
0.9 0.049999 0.05 0.000001</span></div>

# Sample Output

<div class="content"><span class="sampledata">1.457510</span></div>

# Hint

<div class="content"><p></p><p>Sample input 2<br/><br/>
<br/><br/>
20<br/><br/>
0.25 0.25 0.25 0.25<br/><br/>
<br/><br/>
Sample output 2<br/><br/>
<br/><br/>
40.000000</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢phile提供译文">鸣谢phile提供译文</a></p></div>

