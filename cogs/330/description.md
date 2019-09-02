

# 问题描述



# 32, 126



# 输入文件



# 32, 126


<ul>
<li>
MOVE操作不超过50000个，INSERT和DELETE操作的总个数不超过4000，PREV和NEXT操作的总个数不超过200000。
</li>
<li>
所有INSERT插入的字符数之和不超过2M（1M=1024*1024），正确的输出文件长度不超过3M字节。
</li>
<li>
DELETE操作和GET操作执行时光标后必然有足够的字符。MOVE、PREV、NEXT操作不会把光标移动到非法位置。
</li>
<li>
输入文件没有错误。
</li>
</ul>

# 输出文件



# 样例输入


<pre>15
Insert 26
abcdefghijklmnop
qrstuv wxy
Move 15
Delete 11
Move 5
Insert 1
^
Next
Insert 1
_
Next
Next
Insert 4
.\/.
Get 4
Prev
Insert 1
^
Move 0
Get 22
</pre>

# 样例输出


<pre>.\/. </pre>
<pre>abcde^_^f.\/.ghijklmno</pre>
<p>
<br/>
</p>
