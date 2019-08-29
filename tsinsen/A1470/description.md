<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　现在有一个的字符串，都是有小写字母构成。再给你很多个集合。对于每个集合，求以下子串s[a,b]的数量：<br/>
　　1.子串中出现的字母必须出现在集合中。<br/>
　　2.集合中的字母必须在子串中找得到<br/>
　　3.不存在比这个子串更长的子串s[x,y],使得s[x,y]满足1,2，且(x&lt;=a&lt;=b&lt;=y,y-x+1&gt;b-a+1)</div>
# 输入格式

<div class="pdcont">　　第一行字符串s<br/>
　　第2行包含一个正整数m。表示给你m个集合。<br/>
　　接下来有m行，每行会给你一个集合ci，保证集合中每个元素各不相同，且都是小写字母。</div>
# 输出格式

<div class="pdcont">　　输出m行，每行一个整数，第i行表示对于第i个集合，字符串中满足题意的子串的数量</div>
# 样例输入

<div class="pddata">abacaba<br/>
3<br/>
ac<br/>
ba<br/>
a</div>
# 样例输出

<div class="pddata">1<br/>
2<br/>
4</div>
# 数据规模和约定

<div class="pdcont">　　1 ≤ |<i>s</i>| ≤ 10<sup>6</sup><br/>
　　1 ≤ <i>m</i> ≤ 10<sup>4</sup></div>

</div>