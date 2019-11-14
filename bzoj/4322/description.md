
# Description

<div class="content"><div>聪明的小C想到了一个很棒的压缩规则，一次压缩，就是把这个无限长的大数从左往右选择连续的相同的数字（比如说这段区间是X（这个数不能有前导0）个相同的Y（这个数只能是一个字符）），那么这段区间在压缩后的数中就用XY代替。比若说“1122”经过一次压缩就变成了“2122”，但是不能是“11111212”（把连续的相同的不在一起压缩，这是不合法的）。悲剧的是小C实在是太萝莉了，这个数字在压缩了一次之后还是特别大，不过幸运的是这个数字只要报一年就可以报完了，但是小C还是觉得报这个数字太浪费他的青春了，所以他压缩了两次。但是大家知道，这种压缩并不是一一对应的，现在我们已知了小C报出的这个数字（呵呵！只有最多500位了），现在我们想知道最开始的那个大数的值有多少种不同的可能。</div>
<p></p></div>

# Input

<div class="content"><div>第一行一个不超过500个字符的字符串st，表示压缩过两次的字符串。</div>
<p></p></div>

# Output

<div class="content"><div>一个数，表示最开始的大数的值的可能方案数 mod 1000000009.<span class="Apple-tab-span" style="white-space: pre;">	</span></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">22</span></div>

# Sample Output

<div class="content"><span class="sampledata">1</span></div>

# Hint

<div class="content"><p></p><div>样例解释：</div><br/>
<div>原大数只能是22.</div><br/>
<div>经过一次压缩变成22;</div><br/>
<div>再一次压缩变成22。</div><br/>
<div>原大数只能是22.</div><br/>
<div>字符串长度&lt;=50000</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

