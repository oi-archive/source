# 题目描述


<div style="text-indent:21pt;">
设有字符串<span>X，我们称在X的头尾及中间插入任意多个空格后构成的新字符串为X的扩展串，如字符串X为“abcbcd”，则字符串“abcb□cd”，“□a□bcbcd□”和“abcb□cd□”都是X的扩展串，这里“□”代表空格字符。</span> 
</div>
<div style="text-indent:21pt;">
如果<span>A<sub>1</sub>是字符串A的扩展串，B<sub>1</sub>是字符串B的扩展串，A<sub>1</sub>与B<sub>1</sub>具有相同的长度，那么我们定义字符串A<sub>1</sub>与B<sub>1</sub>的距离为相应位置上的字符的距离总和，而两个非空格字符的距离定义为它们的ASCII码的差的绝对值，而空格字符与其它任意字符之间的距离为已知的定值K，空格字符与空格字符的距离为O。在字符串A、B的所有扩展串中，必定存在两个等长的扩展串A<sub>1</sub>、B<sub>1</sub>，使得A<sub>1</sub>与B<sub>1</sub>之间的距离达到最小，我们将这一距离定义为字符串A、B的距离。</span> 
</div>
<div style="text-indent:21pt;">
请你写一个程序，求出字符串<span>A、B的距离。</span> 
</div>
<div>
<b> </b> 
</div>
<div>
<b>输入</b> 
</div>
<div style="text-indent:21pt;">
输入文件第一行为字符串<span>A，第二行为字符串B，A、B均由小写字母组成且长度均不超过2000，第三行为一个整数K，1≤K≤100，表示空格与其它字符的距离。</span> 
</div>
<div>
<b> </b> 
</div>
<div>
<b>输出</b> 
</div>
<div style="text-indent:21pt;">
输出文件仅一行包含一个整数，表示要求的字符串<span>A、B的距离。</span> 
</div>
<div>
<b> </b> 
</div>
<div>
<b>输入样例</b> 
</div>
<div>
 
</div>
<div align="left">
<span style="font-size:10pt;">cmc</span> 
</div>
<div align="left">
<span style="font-size:10pt;">snmn</span> 
</div>
<div>
<span style="font-size:10pt;">2</span> 
</div>
<div>
 
</div>
<div>
<div>
<b>输出样例</b> 
</div>
</div>
<div>
<span style="font-size:10pt;">10</span> 
</div>
<div>
 
</div>
