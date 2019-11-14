
# Description

<div class="content"><div>Lweb 面对如山的英语单词，陷入了深深的沉思，“我怎么样才能快点学完，然后去玩三国杀呢？”。这时候睿智</div>
<div>的凤老师从远处飘来，他送给了 Lweb 一本计划册和一大缸泡椒，他的计划册是长这样的：</div>
<div>—————</div>
<div>序号  单词</div>
<div>—————</div>
<div> 1</div>
<div> 2</div>
<div>……</div>
<div>n-2</div>
<div>n-1</div>
<div> n</div>
<div>—————</div>
<div></div>
<div>然后凤老师告诉 Lweb ，我知道你要学习的单词总共有 n 个，现在我们从上往下完成计划表，对于一个序号为 x </div>
<div>的单词（序号 1...x-1 都已经被填入）：</div>
<div>1) 如果存在一个单词是它的后缀，并且当前没有被填入表内，那他需要吃 n×n 颗泡椒才能学会；</div>
<div>2) 当它的所有后缀都被填入表内的情况下，如果在 1...x-1 的位置上的单词都不是它的后缀，那么你吃 x 颗泡</div>
<div>椒就能记住它；</div>
<div>3) 当它的所有后缀都被填入表内的情况下，如果 1...x-1的位置上存在是它后缀的单词，所有是它后缀的单词中</div>
<div>，序号最大为 y ，那么你只要吃 x-y 颗泡椒就能把它记住。</div>
<div>Lweb 是一个吃到辣辣的东西会暴走的奇怪小朋友，所以请你帮助 Lweb ，寻找一种最优的填写单词方案，使得他</div>
<div>记住这 n 个单词的情况下，吃最少的泡椒。</div>
<div></div></div>

# Input

<div class="content"><div>输入一个整数 n ，表示 Lweb 要学习的单词数。接下来 n 行，每行有一个单词（由小写字母构成，且保证任意单</div>
<div>词两两互不相同）1≤n≤100000, 所有字符的长度总和 1≤|len|≤510000</div>
<div></div></div>

# Output

<div class="content"><p> Lweb 吃的最少泡椒数</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">2 <br/>
a <br/>
ba</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

