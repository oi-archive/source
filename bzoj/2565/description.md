
# Description

<div class="content"><div style="background: white" align="left"><span style="font-size: 12pt; color: #200000">顺序和逆序读起来完全一样的串叫做回文串。比如</span><span style="font-size: 12pt; color: #200000">acbca</span><span style="font-size: 12pt; color: #200000">是回文串，而</span><span style="font-size: 12pt; color: #200000">abc</span><span style="font-size: 12pt; color: #200000">不是（</span><span style="font-size: 12pt; color: #200000">abc</span><span style="font-size: 12pt; color: #200000">的顺序为</span><span style="font-size: 12pt; color: #200000">“abc”</span><span style="font-size: 12pt; color: #200000">，逆序为</span><span style="font-size: 12pt; color: #200000">“cba”</span><span style="font-size: 12pt; color: #200000">，不相同）。</span><span style="font-size: 12pt; color: #200000"><br/>
</span><span style="font-size: 12pt; color: #200000">输入长度为</span><span style="font-size: 12pt; color: #200000">n</span><span style="font-size: 12pt; color: #200000">的串</span><span style="font-size: 12pt; color: #200000">S</span><span style="font-size: 12pt; color: #200000">，求</span><span style="font-size: 12pt; color: #200000">S</span><span style="font-size: 12pt; color: #200000">的最长双回文子串</span><span style="font-size: 12pt; color: #200000">T,</span><span style="font-size: 12pt; color: #200000">即可将</span><span style="font-size: 12pt; color: #200000">T</span><span style="font-size: 12pt; color: #200000">分为两部分</span><span style="font-size: 12pt; color: #200000">X</span><span style="font-size: 12pt; color: #200000">，</span><span style="font-size: 12pt; color: #200000">Y</span><span style="font-size: 12pt; color: #200000">，（</span><span style="font-size: 12pt; color: #200000">|X|,|Y|≥1</span><span style="font-size: 12pt; color: #200000">）且</span><span style="font-size: 12pt; color: #200000">X</span><span style="font-size: 12pt; color: #200000">和</span><span style="font-size: 12pt; color: #200000">Y</span><span style="font-size: 12pt; color: #200000">都是回文串。</span></div></div>

# Input

<div class="content"><p><font size="3"><font color="#200000">一行由小写英文字母组成的字符串<span style="font-size: 12pt; color: #200000">S</span></font></font><span style="font-size: 12pt; color: #200000">。</span></p></div>

# Output

<div class="content"><div style="background: white" align="left"><span style="font-size: 12pt; color: #200000">一行一个整数，表示最长双回文子串的长度。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">baacaabbacabb<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">12<br/>
</span></div>

# Hint

<div class="content"><p></p><p>样例说明<br/><br/>
从第二个字符开始的字符串aacaabbacabb可分为aacaa与bbacabb两部分，且两者都是回文串。<br/><br/>
对于100%的数据，2≤|S|≤10^5</p><br/>
<p>2015.4.25新加数据一组,2019.1.1新加数据一组。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2012国家集训队Round 1 day2">2012国家集训队Round 1 day2</a></p></div>

