# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
FJ喜欢尽可能的收集许多不同类型的牛。
</p>
<p>
事实上，他已收集了几乎所有类型的牛，除了极少数的几个，这些牛写在一个名单上，这个名单有N行（1&lt;= n &lt;= 100）。名单看起来是这样的：
</p>
<p>
<br/>
</p>
<p>
Farmer John has no large brown noisy cow.
</p>
<p>
Farmer John has no small white silent cow.
</p>
<p>
Farmer John has no large spotted noisy cow.
</p>
<p>
<br/>
</p>
<p>
(FJ没有大的、棕色的、吵闹的牛。
</p>
<p>
FJ没有小的、白色的、安静的牛。
</p>
<p>
FJ没有大的、带斑点的、吵闹的牛。)
</p>
<p>
<br/>
</p>
<p>
名单中的每一行描述的是一个农场上缺少的牛的形容词，每行包含相同数量的形容词（在本例中为3）。每行的形容词的数量可以在2到30之间。
</p>
<p>
<br/>
</p>
<p>
除了名单上的牛，FJ有符合其他所有的形容词组合的牛。在这个例子中，第一个形容词可以是大的、小的，第二个形容词可以是棕色的，白色的，或有斑点的，第三个形容词可以是吵闹的或安静的。
</p>
<p>
<br/>
</p>
<p>
这给出了2×3×2＝12种不同的组合，除了那些他的名单上提到的，FJ有满足其他组合的所有类型牛。
</p>
<p>
<br/>
</p>
<p>
在这个例子中，a large, white, noisy(一个大的，白色的，吵闹的)牛是他的9头牛中的一只。可以确定的是，FJ最多有1,000,000,000头牛。
</p>
<p>
<br/>
</p>
<p>
如果FJ的名单是按字典序排列的，农场中的第k头牛是什么样的？
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
第1行：两个整数，N和K。
</p>
<p>
第2..1 + N：每行的这样一句话：&#34;Farmer John has no large spotted noisy cow.&#34;。句子中的每个词，将是一个至多10个小写字母的字符串。看到字符串&#34;cow.&#34;，表示句子结束；
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
1行：农场上第k牛的描述。
</p>
<h3>
【样例输入】
</h3>
<pre><p>
3 7
Farmer John has no large brown noisy cow.
Farmer John has no small white silent cow.
Farmer John has no large spotted noisy cow.
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre>small spotted noisy</pre>
<h3>
【提示】
</h3>
<p>
输入样例就是上面的问题描述的样例。当列表按字典序排列。FJ想知道他农场上第7头牛是什么样子的
</p>
<p>
<br/>
</p>
<p>
输出是农场上第k头牛的描述。
</p>
<p>
<br/>
</p>
<h3>
【数据规模】
</h3>
<p>
<br/>
</p>
<p>
40%的数据在名单中最多有两个形容词。
</p>
<p>
60%的数据，每一个形容词，有两个可能的情况。
</p>
<p>
100%的数据，每一个形容词有1..N种可能）。
</p>
<p>
<br/>
</p>
