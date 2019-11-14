<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: Arial;">《Journey to the West》(also 《Monkey》) is one of the Four Great Classical Novels of Chinese literature. It was written by Wu Cheng'en during the Ming Dynasty. In this novel, Monkey King Sun Wukong, pig Zhu Bajie and Sha Wujing, escorted Tang Monk to India to get sacred Buddhism texts. </span><br style="font-family: Arial;"><br style="font-family: Arial;"><span style="font-family: Arial;">During the journey, Tang Monk was often captured by demons. Most of demons wanted to eat Tang Monk to achieve immortality, but some female demons just wanted to marry him because he was handsome. So, fighting demons and saving Monk Tang is the major job for Sun Wukong to do.</span><br style="font-family: Arial;"><br style="font-family: Arial;"><span style="font-family: Arial;">Once, Tang Monk was captured by the demon White Bones. White Bones lived in a palace and she cuffed Tang Monk in a room. Sun Wukong managed to get into the palace. But to rescue Tang Monk, Sun Wukong might need to get some keys and kill some snakes in his way.</span><br style="font-family: Arial;"><br style="font-family: Arial;"><span style="font-family: Arial;">The palace can be described as a matrix of characters. Each character stands for a room. In the matrix, 'K' represents the original position of Sun Wukong, 'T' represents the location of Tang Monk and 'S' stands for a room with a snake in it. Please note that there are only one 'K' and one 'T', and at most five snakes in the palace. And, '.' means a clear room as well '#' means a deadly room which Sun Wukong couldn't get in.</span><br style="font-family: Arial;"><br style="font-family: Arial;"><span style="font-family: Arial;">There may be some keys of different kinds scattered in the rooms, but there is at most one key in one room. There are at most 9 kinds of keys. A room with a key in it is represented by a digit(from '1' to '9'). For example, '1' means a room with a first kind key, '2' means a room with a second kind key, '3' means a room with a third kind key... etc. To save Tang Monk, Sun Wukong must get ALL kinds of keys(in other words, at least one key for each kind).</span><br style="font-family: Arial;"><br style="font-family: Arial;"><span style="font-family: Arial;">For each step, Sun Wukong could move to the adjacent rooms(except deadly rooms) in 4 directions(north, west, south and east), and each step took him one minute. If he entered a room in which a living snake stayed, he must kill the snake. Killing a snake also took one minute. If Sun Wukong entered a room where there is a key of kind N, Sun would get that key if and only if he had already got keys of kind 1,kind 2 ... and kind N-1. In other words, Sun Wukong must get a key of kind N before he could get a key of kind N+1 (N&gt;=1). If Sun Wukong got all keys he needed and entered the room in which Tang Monk was cuffed, the rescue mission is completed. If Sun Wukong didn't get enough keys, he still could pass through Tang Monk's room. Since Sun Wukong was a impatient monkey, he wanted to save Tang Monk as quickly as possible. Please figure out the minimum time Sun Wukong needed to rescue Tang Monk.</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: Arial;">There are several test cases.</span></p><p><span style="font-family: Arial;">For each case, the first line includes two integers N and M(0 &lt; N &lt;= 100, 0&lt;=M&lt;=9), meaning that the palace is a N×N matrix and Sun Wukong needed M kinds of keys(kind 1, kind 2, ... kind M).</span><br style="font-family: Arial;"><span style="font-family: Arial;">Then the N × N matrix follows.</span><br style="font-family: Arial;"><span style="font-family: Arial;">The input ends with N = 0 and M = 0.</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: Arial; font-size: 14px; line-height: 26px; background-color: rgb(255, 255, 255);">For each test case, print the minimum time (in minutes) Sun Wukong needed to save Tang Monk. If it&#39;s impossible for Sun Wukong to complete the mission, print &quot;impossible&quot;(no quotes).</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Courier New', Courier, monospace;">3 1</span></p><p><span style="font-family: 'Courier New', Courier, monospace;">K.S</span></p><p><span style="font-family: 'Courier New', Courier, monospace;">##1</span></p><p><span style="font-family: 'Courier New', Courier, monospace;">1#T</span></p><p><span style="font-family: 'Courier New', Courier, monospace;">3 1</span></p><p><span style="font-family: 'Courier New', Courier, monospace;">K#T</span></p><p><span style="font-family: 'Courier New', Courier, monospace;">.S#</span></p><p><span style="font-family: 'Courier New', Courier, monospace;">1#.</span></p><p><span style="font-family: 'Courier New', Courier, monospace;">3 2</span></p><p><span style="font-family: 'Courier New', Courier, monospace;">K#T</span></p><p><span style="font-family: 'Courier New', Courier, monospace;">.S.</span></p><p><span style="font-family: 'Courier New', Courier, monospace;">21.</span></p><p><span style="font-family: 'Courier New', Courier, monospace;">0 0</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Courier New', Courier, monospace;">5</span></p><p><span style="font-family: 'Courier New', Courier, monospace;">impossible</span></p><p><span style="font-family: 'Courier New', Courier, monospace;">8</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>/</p>
</div>
</div>