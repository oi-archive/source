<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>追逐影子的人，自己就是影子 ——荷马  </p><p>Allison最近迷上了文学。她喜欢在一个慵懒的午后，细细地品上一杯卡布奇诺，静静地阅读她爱不释手的《荷马史诗》。但是由《奥德赛》和《伊利亚特》组成的鸿篇巨制《荷马史诗》实在是太长了，Allison想通过一种编码方式使得它变得短一些。  </p><p>一部《荷马史诗》中有 n 种不同的单词，从 1 到 n 进行编号。其中第 i 种单词出现的总次数为 w[i] 。Allison想要用 k 进制串 s[i] 来替换第 i 种单词，使得其满足如下要求：  </p><p>对于任意的 1&lt;=i,j&lt;=n ， i&lt;&gt;j ，都有： s[i] 不是 s[j] 的前缀。  </p><p>现在Allison想要知道，如何选择 s[i] ，才能使替换以后得到的新的《荷马史诗》长度最小。在确保总长度最小的情况下，Allison还想知道最长的 s[i] 的最短长度是多少？  </p><p>一个字符串被称为 k 进制字符串，当且仅当它的每个字符是 0 到 k-1 之间（包括 0 和 k−1 ）的整数。  </p><p>字符串 Str1 被称为字符串 Str2 的前缀，当且仅当：存在 1&lt;=t&lt;=m ，使得 Str1 = Str2[1..t] 。其中， m 是字符串 str2 的长度， str2[1..t] 表示 str2 的前 t 个字符组成的字符串。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件的第 1 行包含 2 个正整数 n,k ，中间用单个空格隔开，表示共有 n 种单词，需要使用 k 进制字符串进行替换。 </p><p>接下来 n 行，第 i+1 行包含 1 个非负整数 w[i] ，表示第 i 种单词的出现次数。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件包括 2 行。 &nbsp;第 1 行输出 1 个整数，为《荷马史诗》经过重新编码以后的最短长度。 第 2 行输出 1 个整数，为保证最短总长度的情况下，最长字符串 s[i] 的最短长度。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例输入1:</p><p>4 2<br></p><p>1</p><p>1</p><p>2</p><p>2</p><p><br></p><p>样例输入2:</p><p>6 3 </p><p>1 </p><p>1 </p><p>3 </p><p>3 </p><p>9 </p><p>9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例输出1:</p><p>12<br></p><p>2</p><p><br></p><p>样例输出2:</p><p>36</p><p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><br></p><p><br></p><p><img src="/source/codevs/codevs-5501/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy01NTAxL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvcHJvYmxlbS81NTAxLmpwZw==.jpg" width="500"></p><p>19&amp;20: n=100,000      k=9</p><p>提示:选手请注意使用 64 位整数进行输入输出、存储和计算。</p>
</div>
</div>