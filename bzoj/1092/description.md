
# Description

<div class="content"><p><span style="font-size: medium;">有一堆管道，还有一个蜘蛛Willy，如下图所示。所有管道的是上端开口，下端封底，直径都是1cm，连接两个管道的连接容量无限，但体积可以忽略不计。</span></p>
<p><span style="font-size: medium;"> <img alt="" border="0" src="/source/bzoj/1092/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzEwOTIvMi5qcGc=.jpg"/> </span></p>
<p><span style="font-size: medium;">在第一个管道上方有一个水源，从中有水不断往下流，速度为每秒0.25 cm3。由于管道横截面积为0.25 cm3，所以单给一个管道注水时水面每秒上升1cm。根据物理知识，在前2秒中，水注如左边的管道底部，第3~5秒时注入右边的管道，第6~9秒同时注入两个管道（虽然流量不变，但是由于同时给两个管道注水，因此水面上升的速度仅为每秒0.5cm），接触到蜘蛛。 给出管道和管道之间连接的位置，以及蜘蛛Willy的位置，求水面接触到Willy的时间。假设蜘蛛的实际位置比给出的略高一点，因此如果蜘蛛在左边管道的n=4的位置，答案应该是5秒。因为前两秒后水面虽然看起来接触到了Willy，但实际上比Willy略低一点。</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium;">所有位置都用有序数对(x, y)表示，其中y坐标从上到下逐渐增大；x坐标从左到右逐渐增大，因此左上角的坐标为(0,0)，其他所有坐标值为0到100之间的整数。输入第一行为一个整数p(1&lt;=p&lt;=20)，表示管道的数目；以下p行，每行用x, y, h三个整数描述一根管道。(x,y)为管道左上角坐标；h为管道高度(1&lt;=h&lt;=20)。以下一行为一个整数L(0&lt;=L&lt;=50)，为连接的个数。以下L行每行用三个整数x, y, d描述一个连接，(x,y)为左端点的坐标，d为连接的长度(1&lt;=d&lt;=20)。最后一行为两个整数a, b，表示Willy在管道a的y坐标为b的位置。管道按照在文件中出现的顺序编号为1,2,3…p 以下为一些假设： 水源总是在第一根管道的正上方 连接不会穿越管道 任意两个连接的y坐标都不相同 任意两个管道的左上角的x坐标都不相同 任意连接的两个端点都在管道上（不会出现悬空的情形）</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium;">仅一个整数，为水面接触到Willy的时间。如果水面无法接触到Willy，输出-1。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
2 0 6<br/>
5 1 6<br/>
1<br/>
3 4 2<br/>
2 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">9</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium;">该样例对应题目中的例子。</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

