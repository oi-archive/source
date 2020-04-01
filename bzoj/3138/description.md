
# Description

<div class="content"><p><span style="font-size: medium">Victor正在使用vim编辑他的文章，他的文章只有包含<code>abcdefghij</code>这<code>10</code>个字母，他想把他文章中所有的<code>e</code>都删除。Victor并不是很熟悉vim，它只懂得下面几个操作：</span></p>
<ul>
    <li><span style="font-size: medium"><code>x</code>：删除光标所在的字母，光标位置不变。 </span></li>
    <li><span style="font-size: medium"><code>h</code>：光标向左移。如果已经是行首就不会移。 </span></li>
    <li><span style="font-size: medium"><code>f</code>：后面还会跟一个字母<code>c</code>，表示跳到下一个字母<code>c</code>的位置。如果不存在那么就不会跳。 </span></li>
</ul>
<p><span style="font-size: medium">悲剧的是Victor的键盘上<code>e</code>按键突然坏掉了……</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行：文章长度<code>N</code> (<code>N &lt;= 70 000</code>）第二行：文章，只包含小写<code>abcdefghij</code>。第一个字母和最后一个字母保证不是<code>e</code></span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">Victor最少需要按多少个键才能把所有的<code>e</code>删除。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">35<br/>
chefeddiefedjeffeachbigagedegghehad<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">36<br/>
<br/>
样例说明<br/>
fdhxhhxffhxfahxhhhxhhhxfdhxfghxfahhx<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=abcdabcd987提供">abcdabcd987提供</a></p></div>

