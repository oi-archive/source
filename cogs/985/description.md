# 题目描述


<span style="font-family:Microsoft YaHei;">【题目描述】</span><br/>
<br/>
<br/>
<span style="font-family:Microsoft YaHei;"> 学校里有一个水房，水房里一共装有m 个龙头可供同学们打开水，每个龙头每秒钟的供水量相等，均为1。</span><br/>
<span style="font-family:Microsoft YaHei;"> 现在有n 名同学准备接水，他们的初始接水顺序已经确定。将这些同学按接水顺序从1到n 编号，i 号同学的接水量为wi。接水开始时，1 到m 号同学各占一个水龙头，并同时打开水龙头接水。当其中某名同学j 完成其接水量要求wj 后，下一名排队等候接水的同学k马上接替j 同学的位置开始接水。这个换人的过程是瞬间完成的，且没有任何水的浪费。即j 同学第x 秒结束时完成接水，则k 同学第x+1 秒立刻开始接水。若当前接水人数n&#39;不足m，则只有n&#39;个龙头供水，其它m-n&#39;个龙头关闭。</span><br/>
<span style="font-family:Microsoft YaHei;"> 现在给出n 名同学的接水量，按照上述接水规则，问所有同学都接完水需要多少秒。</span><br/>
<br/>
<br/>
<span style="font-family:Microsoft YaHei;"> 【输入格式】</span><br/>
<br/>
<br/>
<span style="font-family:Microsoft YaHei;"> 第1 行2 个整数n 和m，用一个空格隔开，分别表示接水人数和龙头个数。</span><br/>
<span style="font-family:Microsoft YaHei;"> 第2 行n 个整数w1、w2、……、wn，每两个整数之间用一个空格隔开，wi 表示i 号同</span><br/>
<span style="font-family:Microsoft YaHei;"> 学的接水量。</span><br/>
<br/>
<br/>
<span style="font-family:Microsoft YaHei;"> 【输出格式】</span><br/>
<br/>
<br/>
<span style="font-family:Microsoft YaHei;"> 输出只有一行，1 个整数，表示接水所需的总时间</span><br/>
<br/>
<br/>
<span style="font-family:Microsoft YaHei;"> 【输入样例1】</span><br/>
<span style="font-family:Microsoft YaHei;"> 5 3</span><br/>
<span style="font-family:Microsoft YaHei;"> 4 4 1 2 1</span><br/>
<br/>
<br/>
<span style="font-family:Microsoft YaHei;"> 【输出样例1】</span><br/>
<span style="font-family:Microsoft YaHei;"> 4</span><br/>
<br/>
<br/>
<span style="font-family:Microsoft YaHei;"> 【输入输出样例 1 说明】</span><br/>
<span style="font-family:Microsoft YaHei;"> 第1 秒，3 人接水。第1 秒结束时，1、2、3 号同学每人的已接水量为1，3 号同学接完</span><br/>
<span style="font-family:Microsoft YaHei;"> 水，4 号同学接替3 号同学开始接水。</span><br/>
<span style="font-family:Microsoft YaHei;"> 第2 秒，3 人接水。第2 秒结束时，1、2 号同学每人的已接水量为2，4 号同学的已接</span><br/>
<span style="font-family:Microsoft YaHei;"> 水量为1。</span><br/>
<span style="font-family:Microsoft YaHei;"> 第3 秒，3 人接水。第3 秒结束时，1、2 号同学每人的已接水量为3，4 号同学的已接</span><br/>
<span style="font-family:Microsoft YaHei;"> 水量为2。4 号同学接完水，5 号同学接替4 号同学开始接水。</span><br/>
<span style="font-family:Microsoft YaHei;"> 第4 秒，3 人接水。第4 秒结束时，1、2 号同学每人的已接水量为4，5 号同学的已接</span><br/>
<span style="font-family:Microsoft YaHei;"> 水量为1。1、2、5 号同学接完水，即所有人完成接水。</span><br/>
<span style="font-family:Microsoft YaHei;"> 总接水时间为4 秒。</span><br/>
<br/>
<br/>
<span style="font-family:Microsoft YaHei;"> 【输入样例2】</span><br/>
<span style="font-family:Microsoft YaHei;"> 8 4</span><br/>
<span style="font-family:Microsoft YaHei;"> 23 71 87 32 70 93 80 76</span><br/>
<br/>
<br/>
<span style="font-family:Microsoft YaHei;"> 【输出样例2】</span><br/>
<span style="font-family:Microsoft YaHei;"> 163</span><br/>
<br/>
<br/>
<span style="font-family:Microsoft YaHei;"> 【数据范围】</span><br/>
<span style="font-family:Microsoft YaHei;"> 1 ≤ n ≤ 10000，1 ≤m≤ 100 且m≤ n；</span><br/>
<span style="font-family:Microsoft YaHei;"> 1 ≤ wi ≤ 100。</span><br/>
<div>
<br/>
</div>
