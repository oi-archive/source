# 题目描述


<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【问题描述】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">出于最高安全性考虑，司令部采用了特殊的安全操作系统，该系统采用一个特殊的文件系统。在这个文件系统中所有磁盘空间都被分成了相同尺寸的<span>N</span><span>块，用整数</span><span>1</span><span>到</span><span>N</span><span>标识。每个文件占用磁盘上任意区域的一块或多块存储区，未被文件占用的存储块被认为是可是用的。如果文件存储在磁盘上自然连续的存储块中，则能被以最快的速度读出。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">因为磁盘是匀速转动的，所以存取上面不同的存储块需要的时间也不同。读取磁盘开头处的存储块比读取磁盘尾处的存储块快。根据以上现象，我们事先将文件按其存取频率的大小用整数<span>1</span><span>到</span><span>K</span><span>标识。按文件在磁盘上的最佳存储方法，</span><span>1</span><span>号文件将占用</span><span>1, 2, </span><span>…</span><span>, S</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">的存储块，<span>2</span><span>号文件将占用</span><span>S</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">+1, S</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">+2, <span>…， </span><span>S</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">+S</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">的存储块，以此类推（<span>S</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">i</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">是被第<span>i</span><span>个文件占用的存储块的个数）。为了将文件以最佳形式存储在磁盘上，需要执行存储块移动操作。一个存储块移动操作包括从磁盘上读取一个被占用的存储块至内存并将它写入其他空的存储块，然后宣称前一个存储块被释放，后一个存储块被占用。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">本程序的目的是通过执行最少次数的存储块移动操作，将文件安最佳方式存储到磁盘上，注意同一个文件的存储块在移动之后其相对次序不可改变。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    每个磁盘说明的第一行包含两个用空格隔开的整数<span>N</span><span>和</span><span>K</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1<span>≤</span><span>K</span><span>≤</span><span>N</span><span>≤</span><span>100000</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，接下来的<span>K</span><span>行每行说明一个文件，对第</span><span>i</span><span>个文件的说明是这样的：首先以整数</span><span>S</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">i</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">开头，表示第<span>i</span><span>个文件的存储块数量，</span><span>1</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">&lt;</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">=S</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">i</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">&lt;</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">=N</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">-</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">K<span>，然后跟</span><span>S</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">i</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">个整数，每个整数之间用空格隔开，表示该文件按自然顺序在磁盘上占用的存储块的标识。所有这些数都介于<span>1</span><span>和</span><span>N</span><span>之间，包括</span><span>1</span><span>和</span><span>N</span><span>。一个磁盘说明中所有存储块的标识都是不同的，并且该盘至少有一个空的存储块。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输出】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    对于每一个磁盘说明，只需输出一行句子“<span>We need M move operations</span><span>”，</span><span>M</span><span>表示将文件按最佳方式存储到磁盘上所需进行的最少存储块移动操作次数。如果文件已按最佳方式存储，仅需输出“</span><span>No optimization needed.</span><span>”。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【样例】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">defrag.in                           </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">defrag.out</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">20 3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">                                 </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">We need 9 move operations</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">4 2 3 11 12</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1 7</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3 18 5 10</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<br/>
</p>
