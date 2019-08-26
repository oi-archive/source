
# Description

<div class="content"><div>考古学家发现了一堵写有未知语言的白色墙壁，上面有一个n行m列的格子，其中有些格子内被填入了某个A至Z的大</div>
<div>写字母，还有些格子是空白的。一直横着或竖着的连续若干个字母会形成一个单词，且每一行的阅读顺序可能是从</div>
<div>左向右或从右向左，每一列的阅读顺序可能是从下往上或从上往下。也就是说对于每一行来说，从左向右可以被看</div>
<div>做是若干个单词形成的句子，相邻两个单词被一个或多个空白格子分割开来；也有可能是从右向左被看成是一个句</div>
<div>子，竖直方向类似。遗憾的是，我们并不完全知道每一行每一列的阅读顺序是怎样的。但可以猜测，有些单词会满</div>
<div>足反转过来也是一个单词。例如单词BOY，翻转过来的YOB也是一个英文单词。此外观察者发现，对每一行（列）来</div>
<div>说，按照确定后的阅读顺序读出的所有单词同时满足“自己的字典序不小于翻转后的字典序”，或同时满足“自己</div>
<div>的字典序不大于翻转后的字典序”。在确定了所有行列的阅读顺序之后，我们可以构造出关于这种未知语言的字典</div>
<div>。请问字典中出现的“翻转过来也是一个单词”的单词最少有多少种请注意，如果一个单词翻转后是不同的另外一</div>
<div>个单词，它们需要被分别计入；而对于本身是回文的单词则不需要重复计入</div>
<div></div></div>

# Input

<div class="content"><div>第一行一个整数T，表示T组测试数据。</div>
<div>对于每一组数据来说：第一行输入两个整数n,m。</div>
<div>第二行给出了n个数字，对应n行，其中若第i个数字为1，则表示第i行的阅读顺序从左往右；若为-1则为从右向左</div>
<div>；若为0则表示无法确定</div>
<div>第三行给出了m个数字，对应n行，其中若第i个数字为1，则表示第i列的阅读顺序从上往下；若为-1则为从下向上</div>
<div>；若为0则表示无法确定</div>
<div>之后n行，每行给出了长度为m的字符串，由A~Z和下划线组成，对应了每个格子的符号，其中下划线表示格子为空</div></div>

# Output

<div class="content"><div>输出T行。每一组数据输出一行一个整数，表示最少有多少个单词，满足翻转后依然是单词。</div>
<div>注意，如果一个单词是回文，那么它一定满足“翻转后依旧是单词”</div></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
2 10<br/>
0 0<br/>
0 0 0 0 0 0 0 0 0 0 <br/>
ADA_JARVIS<br/>
ADA_SIVRAJ</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
对于100%的数据，1&lt;=n,m&lt;=72,T&lt;=64</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By AHdoc命题 鸣谢Loi_DQS上传，xiaoyimi提供题面">By AHdoc命题 鸣谢Loi_DQS上传，xiaoyimi提供题面</a></p></div>

