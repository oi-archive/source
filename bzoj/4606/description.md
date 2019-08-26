
# Description

<div class="content"><div>分析如DNA序列这样的生命科学数据是计算机的一个有趣应用。从生物学的角度上说,DNA 是一种由腺嘌呤、胞嘧啶</div>
<div>、鸟嘌呤和胸腺嘧啶这四种核苷酸组成的链式结构。这四种核苷酸分别用大写字母A、C、G、T表示。这样,一条DNA</div>
<div>单链可以被表示为一个只含以上四种字符的字符串。我们将这样的字符串称作一个DNA序列 。有时生物学家可能无</div>
<div>法确定一条DNA单链中的某些核苷酸。在这种情况下,字符N将被用来表示一个不确定的核苷酸。换句话说,N可以用</div>
<div>来表示A、C、G、T中的任何一个字符。我们称包含一个或者多个N的DNA序列为未完成序列;反之,就称作完成序列。</div>
<div>如果一个完成序列可以通过将一个未完成序列中的每个N任意替换成A、C、G、T得到的话,就称完成序列适合这个未</div>
<div>完成序列。举例来说,ACCCT适合ACNNT,但是AGGAT不适合。研究者们经常按照如下方式排序四种核苷酸:A优先于C,C</div>
<div>优先于G,G优先于T。如果一个DNA序列中的每个核苷酸都与其右边的相同或者优先,就将其归类为范式-1。举例来说</div>
<div>,AACCGT是范式-1,但是AACGTC不是。一般来说,一个DNA序列属于范式-j(j&gt;1),只要它属于范式-(j-1)或者是一个范</div>
<div>式-(j-1)和一个范式-1的连接。举例来说,AACCC、ACACC和ACACA都是范式-3,但GCACAC和ACACACA不是。同样,研究</div>
<div>者们按照字典序对 DNA 序列进行排序。按照这个定义,最小的属于范式-3的DNA序列是AAAAA,最大的是TTTTT。这里</div>
<div>是另外一个例子,考虑未完成序列 ACANNCNNG。那么前7个适合这个未完成序列的DNA序列是:</div>
<div>ACAAACAAG</div>
<div>ACAAACACG</div>
<div>ACAAACAGG</div>
<div>ACAAACCAG</div>
<div>ACAAACCCG</div>
<div>ACAAACCGG</div>
<div>ACAAACCTG</div>
<div>写一个程序,找到按字典序的第R个适合给定的长度为M的未完成序列的范式-K。</div>
<p></p></div>

# Input

<div class="content"><div>输入第一行包含三个由空格隔开的整数:M(1≤M≤50,000),K(1≤K≤10)和R(1≤R≤2×10^12)。</div>
<div>第二行包含一个长度为M的字符串,表示未完成序列。</div>
<div>保证适合该未完成序列的范式-K的总数不超过4×10^18 </div>
<div>因此该数可以用C和C++中的long long类型或者Pascal中的Int64类型表示。</div>
<div>同时,R不会超过适合给定未完成序列的范式-K的总数。</div>
<p></p></div>

# Output

<div class="content"><div>在第一行中输出第R个适合输入中的未完成序列的范式-K。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">9 3 5<br/>
ACANNCNNG<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">ACAAACCCG</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Yts1999上传">鸣谢Yts1999上传</a></p></div>

