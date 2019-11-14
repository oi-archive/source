
# Description

<div class="content"><p style="text-align: left"><font face="Times New Roman" size="3"><span id="1323849459956S" style="display: none"> </span>项链 <br/>
著名珠宝商Byteman的迷人项链使得Byteland声名在外。这些项链由宝石串织而成。宝石有26个不同的种类 <br/>
我们用小写的拉丁字母a – z来表示（同一类型的宝石是不可区分的）。不生产俩条完全一样的项链是 <br/>
Byteman的一份荣誉，因而他保留有以前制造的所有项链的描述。由于有些项链确实很长，这就使得我们 <br/>
必须用简短的形式来描述它。每个描述都由下列形式的fragments构成：一个字符串（我们称之为pattern） <br/>
后面跟一整数，整数表示此pattern在项链中重复的次数。所有描述都是这样的fragments的连续。 <br/>
例如，描述： <br/>
abc 2 xyz 1 axc 3 <br/>
表示项链abcabcxyzaxcaxcaxc（这一字符串可由写“abc”两次，“xyz”一次和“axc”3次而得到）。 <br/>
然而，由于不能决定项链的开始（即项链能任意被转动），这个问题变得更加复杂化。一些项链可能 <br/>
有多于一种的描述形式。例如，我们上面提到的项链也可以描述为如下形式： <br/>
cabcxyzaxcaxcaxcab或者xcaxcaxcabcabcxyza。 <br/>
要求 <br/>
写一程序： <br/>
1、 从文件NAS.IN中读入俩条项链的描述； <br/>
2、证明这俩个描述是否表示同一项链； <br/>
3、结果写入文件NAS.OUT中。 <br/>
</font></p>
<p style="text-align: left"></p></div>

# Input

<div class="content"><p style="text-align: left"><font face="Times New Roman" size="3">输入俩行。每行都为某一项链的描述，由小写的拉丁字母和整数组成 <br/>
用单个空格隔开。每行开始为一整数n，它表示此描述中所含pattern的数量 <br/>
1&lt;=n&lt;=1 000。后面跟着是n个重复pattern的描述。第i个重复pattern由以下几部分组成： <br/>
整数li ，表示pattern的长度；由li 个小写拉丁字母构成的字符串si ； <br/>
以及整数ki表示pattern在描述中重复的次数，1&lt;=ki&lt;=100 000。整数li (for i=1,...,n)的总和不超过10 000。 <br/>
</font></p>
<p style="text-align: left"></p></div>

# Output

<div class="content"><p style="text-align: left"><font face="Times New Roman" size="3">如果这俩个描述表示的是同一条项链，程序应在输出文件的第一行写入一单词&#34;TAK&#34;，否则，写入单词&#34;NIE&#34;。 <br/>
</font></p>
<p><font face="Times New Roman" size="3">
</font></p><pre><font face="Times New Roman" size="3">		</font></pre><font face="Times New Roman" size="3">
</font><p></p>
<pre></pre></div>

# Sample Input

<div class="content"><span class="sampledata">3 3 abc 2 3 xyz 1 3 axc 3<br/>
4 4 cabc 1 4 xyza 1 3 xca 3 1 b 1<br/>
<br/>
<br/>
 </span></div>

# Sample Output

<div class="content"><span class="sampledata">TAK<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

