# 题目描述


<span style="font-family:宋体;font-size:14px;line-height:24px;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;line-height:24px;">试题四:贪婪大陆 </span><br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;line-height:24px;">【题目描述】 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;line-height:24px;">面对蚂蚁们的疯狂进攻，小FF的Tower defense宣告失败……人类被蚂蚁们逼到了Greed Island上的一个海湾。现在，小FF的后方是一望无际的大海，前方是变异了的超级蚂蚁。 小FF还有大好前程，他可不想命丧于此， 于是他派遣手下最后一批改造SCV布置地雷以阻挡蚂蚁们的进攻。 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;line-height:24px;">小FF最后一道防线是一条长度为N的战壕， 小FF拥有无数多种地雷，而SCV每次可以在[ L , R ]区间埋放同一种不同于之前已经埋放的地雷。 由于情况已经十万火急，小FF在某些时候可能会询问你在[ L&#39; , R&#39;] 区间内有多少种不同的地雷， 他希望你能尽快的给予答复。 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;line-height:24px;">【输入格式】 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;line-height:24px;">第一行为两个整数n和m； n表示防线长度， m表示SCV布雷次数及小FF询问的次数总和。 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;line-height:24px;">接下来有m行， 每行三个整数Q，L , R； 若Q=1 则表示SCV在[ L , R ]这段区间布上一种地雷， 若Q=2则表示小FF询问当前[ L , R ]区间总共有多少种地雷。 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;line-height:24px;">【输出格式】 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;line-height:24px;">对于小FF的每次询问，输出一个答案（单独一行），表示当前区间地雷总数。 </span><br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;line-height:24px;">【输入样例】 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;line-height:24px;">5 4 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;line-height:24px;">1 1 3 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;line-height:24px;">2 2 5 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;line-height:24px;">1 2 4 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;line-height:24px;">2 3 5 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;line-height:24px;">【输出样例】 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;line-height:24px;">1 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;line-height:24px;">2 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;line-height:24px;">【数据范围】 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;line-height:24px;">对于30%的数据： 0&lt;=n, m&lt;=1000; </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;line-height:24px;">对于100%的数据： 0&lt;=n, m&lt;=10^5.</span></span> 
<div>
<span style="font-family:宋体;font-size:14px;line-height:24px;"><br/>
</span> 
</div>
