
# Description

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt"><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;">幼儿园里有<font face="Times New Roman">N</font><font face="宋体">个小朋友，</font><font face="Times New Roman">lxhgww</font><font face="宋体">老师现在想要给这些小朋友们分配糖果，要求每个小朋友都要分到糖果。但是小朋友们也有嫉妒心，总是会提出一些要求，比如小明不希望小红分到的糖果比他的多，于是在分配糖果的时候，</font><font face="Times New Roman">lxhgww</font><font face="宋体">需要满足小朋友们的</font><font face="Times New Roman">K</font><font face="宋体">个要求。幼儿园的糖果总是有限的，</font><font face="Times New Roman">lxhgww</font><font face="宋体">想知道他至少需要准备多少个糖果，才能使得每个小朋友都能够分到糖果，并且满足小朋友们所有的要求。</font></span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 20.25pt"><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<!--EndFragment--></div>

# Input

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 20.25pt"><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;">输入的第一行是两个整数<font face="Times New Roman">N</font><font face="宋体">，</font><font face="Times New Roman">K</font><font face="宋体">。</font></span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 20.25pt"><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;">接下来<font face="Times New Roman">K</font><font face="宋体">行，表示这些点需要满足的关系，每行</font><font face="Times New Roman">3</font><font face="宋体">个数字，</font><font face="Times New Roman">X</font><font face="宋体">，</font><font face="Times New Roman">A</font><font face="宋体">，</font><font face="Times New Roman">B</font><font face="宋体">。</font></span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 20.25pt"><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;">如果<font face="Times New Roman">X=1</font><font face="宋体">， 表示第</font><font face="Times New Roman">A</font><font face="宋体">个小朋友分到的糖果必须和第</font><font face="Times New Roman">B</font><font face="宋体">个小朋友</font>分到的糖果一样多；</span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 20.25pt"><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;">如果<font face="Times New Roman">X=2</font><font face="宋体">， </font></span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;">表示第<font face="Times New Roman">A</font><font face="宋体">个小朋友分到的糖果必须少于第</font><font face="Times New Roman">B</font><font face="宋体">个小朋友</font></span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;">分到的糖果</span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;">；</span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 20.25pt"><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;">如果<font face="Times New Roman">X=3</font><font face="宋体">， </font></span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;">表示第<font face="Times New Roman">A</font><font face="宋体">个小朋友分到的糖果必须不少于第</font><font face="Times New Roman">B</font><font face="宋体">个小朋友</font></span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;">分到的糖果</span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;">；</span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 20.25pt"><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;">如果<font face="Times New Roman">X=4</font><font face="宋体">， </font></span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;">表示第<font face="Times New Roman">A</font><font face="宋体">个小朋友分到的糖果必须多于第</font><font face="Times New Roman">B</font><font face="宋体">个小朋友</font></span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;">分到的糖果</span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;">；</span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 20.25pt"><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;">如果<font face="Times New Roman">X=5</font><font face="宋体">， </font></span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;">表示第<font face="Times New Roman">A</font><font face="宋体">个小朋友分到的糖果必须不多于第</font><font face="Times New Roman">B</font><font face="宋体">个小朋友</font></span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;">分到的糖果；</span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 20.25pt"><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p></div>

# Output

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 20.25pt"><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;">输出一行，表示<font face="Times New Roman">lxhgww</font><font face="宋体">老师至少需要准备的糖果数，如果不能满足小朋友们的所有要求，就输出</font><font face="Times New Roman">-1</font><font face="宋体">。</font></span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 20.25pt"><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 7<br/>
<br/>
1 1 2<br/>
<br/>
2 3 2<br/>
<br/>
4 4 1<br/>
<br/>
3 4 5<br/>
<br/>
5 4 5<br/>
<br/>
2 3 5<br/>
<br/>
4 5 1<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
11<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>【数据范围】</p><br/>
<p>    对于30%的数据，保证 N&lt;=100</p><br/>
<p>    对于100%的数据，保证 N&lt;=100000</p><br/>
<p>对于所有的数据，保证 K&lt;=100000，1&lt;=X&lt;=5，1&lt;=A, B&lt;=N<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day1">Day1</a></p></div>

