
# Description

<div class="content"><p> 阿狸喜欢收藏各种稀奇古怪的东西，最近他淘到一台老式的打字机。打字机上只有28个按键，分别印有26个小写英文字母和&#39;B&#39;、&#39;P&#39;两个字母。<br/>
<br/>
经阿狸研究发现，这个打字机是这样工作的：<br/>
<br/>
l 输入小写字母，打字机的一个凹槽中会加入这个字母(这个字母加在凹槽的最后)。<br/>
<br/>
l 按一下印有&#39;B&#39;的按键，打字机凹槽中最后一个字母会消失。<br/>
<br/>
l 按一下印有&#39;P&#39;的按键，打字机会在纸上打印出凹槽中现有的所有字母并换行，但凹槽中的字母不会消失。<br/>
<br/>
例如，阿狸输入aPaPBbP，纸上被打印的字符如下：<br/>
<br/>
a<br/>
<br/>
aa<br/>
<br/>
ab<br/>
<br/>
我们把纸上打印出来的字符串从1开始顺序编号，一直到n。打字机有一个非常有趣的功能，在打字机中暗藏一个带数字的小键盘，在小键盘上输入两个数(x,y)（其中1≤x,y≤n），打字机会显示第x个打印的字符串在第y个打印的字符串中出现了多少次。<br/>
<br/>
阿狸发现了这个功能以后很兴奋，他想写个程序完成同样的功能，你能帮助他么？</p></div>

# Input

<div class="content"><p> 输入的第一行包含一个字符串，按阿狸的输入顺序给出所有阿狸输入的字符。<br/>
<br/>
第二行包含一个整数m，表示询问个数。<br/>
<br/>
接下来m行描述所有由小键盘输入的询问。其中第i行包含两个整数x, y，表示第i个询问为(x, y)。</p></div>

# Output

<div class="content"><p> 输出m行，其中第i行包含一个整数，表示第i个询问的答案。</p></div>

# Sample Input

<div class="content"><span class="sampledata">aPaPBbP<br/>
<br/>
3<br/>
<br/>
1 2<br/>
<br/>
1 3<br/>
<br/>
2 3<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
<br/>
1<br/>
<br/>
0</span></div>

# Hint

<div class="content"><p></p><p> 1&lt;=N&lt;=10^5</p><br/>
<div>1&lt;=M&lt;=10^5</div><br/>
<div>输入总长&lt;=10^5</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Trie">Trie</a></p></div>

