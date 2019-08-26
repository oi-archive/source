
# Description

<div class="content"><div>身为特工，Star的任务除了获取敌人的情报外，当然还包括传递己方的情报。考虑到利用数字进行运算的加密方式</div>
<div>容易被破译，他想到了一个借助字母的加密法。现在有一个包含N个小写字母的字符串S，其下标从0开始。Star用</div>
<div>下列方式得到它对应的密码：</div>
<div>1、光标初始位于下标0处；</div>
<div>2、当光标位于i时，找到一个最长的子串S[j ... j + len - 1]，满足j &lt; i，使得S[i ... i + len - 1] = S[j </div>
<div>... j + len - 1]。然后在密文中追加len、j两个整数，并将光标往后移动len个位置。若对于最大的len，有多个</div>
<div>合法的j与之对应，Star会选择最小者；</div>
<div>3、若不存在合法的len、j，则在密文中依次追加-1和S[i]对应的ASCII码，并将光标往后移动一位；</div>
<div>4、当光标位于下标N时，加密完成，最终得到的密文会是一行偶数个用空格隔开的整数。</div>
<div>现给定某个字符串S，请你输出对应的密文。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>一行一个字符串S。</div>
<div>N ≤ 500000</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>一行若干个整数，如题目描述。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">tttqqttt </span></div>

# Sample Output

<div class="content"><span class="sampledata">-1 116 2 0 -1 113 1 3 3 0</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

