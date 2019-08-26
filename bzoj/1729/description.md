
# Description

<div class="content"><div><span style="font-size: medium">    约翰的N(1≤N≤100000)只奶牛中出现了K(1≤K≤25000)只爱惹麻烦的坏蛋．奶牛们按一定的顺序排队的时候，这些坏蛋总会站在一起．为了找出这些坏蛋，约翰让他的奶牛排好队进入牛棚，同时需要你的慧眼来识别坏蛋,为了区分，约翰给所有奶牛都发了号牌，上面写着一个1．．S(1≤S≤25)之间的数字．虽然这不是一个完美的方法，但也能起一点作用．现在，约翰已经不记得坏蛋们的具体号码．但是凭他的记忆，他给出一个“模式串”．原坏蛋的号码如果相同，模式串中他们的号码依然相同．模式串中坏蛋们之间号码的大小关系也与原号码相同的．比如，对于这样一个模式串：<span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">1,4,4,3,,2,1 。</span>原来的6只坏蛋，排最前面的与排最后的号码相同（尽管不一定是1），而且他们的号码在团伙中是最小的．第2，3位置的坏蛋，他们的号码也相同（不一定是4），且是坏蛋团伙中最大的．    现在所有奶牛排成队列，号码依次是这样：    5，6，2，10，10，7，3，2，9存在子串2，10，10，7，3，2，满足模式串的相同关系和大小关系，所以这就是坏蛋团伙, 请找出K个坏蛋的困伙的所有可能性．</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">    第1行输入三个整数N，K，S．接下来N行每行输入一只牛的号码．接下来K行每行输入一个模式串的号码．</span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">    第1行输出一个整数B.接下来B行，每行一个整数，表示一种可能下的坏蛋团伙的起始位置．</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">9 6 10<br/>
5<br/>
6<br/>
2<br/>
10<br/>
10<br/>
7<br/>
3<br/>
2<br/>
9<br/>
1<br/>
4<br/>
4<br/>
3<br/>
2<br/>
1<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
The sample input corresponds to the example given in the problem statement.<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
3<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
There is only one match, at position 3 within FJ&#39;s sequence of N cows.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

