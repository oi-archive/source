
# Description

<div class="content"><div>BX正在进行一个字符串游戏，他手上有一个字符串L，以及其他一些字符串的集合S，然后他可以进行以下操作：对</div>
<div>于一个在集合S中的字符串p,如果p在L中出现，BX就可以选择是否将其删除，如果删除，则将删除后L分裂成的左右</div>
<div>两部分合并。举个例子，L=&#39;abcdefg&#39; , S={&#39;de&#39;}，如果BX选择将&#39;de&#39;从L中删去，则删后的L=&#39;abcfg&#39;。现在BX可</div>
<div>以进行任意多次操作（删的次数，顺序都随意），他想知道最后L串的最短长度是多少。</div></div>

# Input

<div class="content"><div>输入的第一行包含一个字符串，表示L。</div>
<div>第二行包含一个数字n，表示集合S中元素个数。</div>
<div>以下n行，每行一个字符串，表示S中的一个元素。</div>
<div>输入字符串都只包含小写字母。</div></div>

# Output

<div class="content"><p>输出一个整数，表示L的最短长度。</p></div>

# Sample Input

<div class="content"><span class="sampledata">aaabccd<br/>
3<br/>
ac<br/>
abc<br/>
aaa<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
【样例说明】<br/>
aaabccd<br/>
aacd<br/>
ad<br/>
对于100%数据,满足|L|&lt;151,|S|&lt;31,S中的每个元素|p|&lt;21</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

