# 题目描述


<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【题目背景】</span>
</h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第二届『Citric』杯NOIP提高组模拟赛 第二题</span><br/>
<br/>
<br/>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【题目描述】</span>
</h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Lemon最近买了一台数码相机。某天Lemon很无聊，于是对着夜空拍了一张照片，然后把照片导入了电脑。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Lemon想依靠电脑的力量，完成他小时候经常做却从来没有成功过的事情：数天空中有多少颗星星。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Lemon已经把相片处理成了黑白的，也就是说，每个像素只可能是两个颜色之一，白或黑。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Lemon定义像素(x,y)处是一颗星星，当且仅当，像素(x,y),(x-1,y),(x+1,y),(x,y-1),(x,y+1)都是白色的。因此一个白色像素有可能属于多个星星，也有可能有的白色像素不属于任何一颗星星。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">借助电脑的力量，数出有多少颗星星对Lemon实在太容易了，他很快就完成了。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">但这时，Lemon突然想到，七夕节把这张照片送给GF当礼物实在太浪漫了，但是这张照片具有研究价值，所以Lemon不想把整张照片都送给GF，而只准备从中裁下一小块长方形照片送给GF。但为了保证浪漫的效果，Lemon认为，他送给GF的那一小块相片中至少应该有k颗星星。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">现在Lemon想知道，到底有多少种方法裁下这一小块长方形相片呢？</span><br/>
<br/>
<br/>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span></span>【输入格式】<span></span></span>
</h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入文件第一行包含三个正整数n,m,k，意义见题目所示。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">接下来n行，每行一个长度为m的字符串，字符串仅由&#39;.&#39;和&#39;*&#39;构成，&#39;.&#39;表示这个像素为黑色，&#39;*&#39;表示这个像素为白色。</span><br/>
<br/>
<br/>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出格式】</span>
</h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输出文件仅包含一个整数，表示Lemon有多少种满足题意的裁剪方法。</span><br/>
<br/>
<br/>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入样例】</span>
</h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">5 6 3</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">***...</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">****..</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">.**.*.</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">******</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">.*.***</span><br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"></span><br/>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出样例】</span>
</h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3</span><br/>
<br/>
<br/>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例解释】</span>
</h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">图中共有4颗星星，分别位于第2行第2列、第2行第3列、第4行第2列、第4行第5列。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">有3种符合题意的选择方法（以左上角行列 - 右下角行列方式给出）: (1,1)-(5,4) (1,1)-(5,5) (1,1)-(5,6)</span><br/>
<br/>
<br/>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【数据规模】</span>
</h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">时间限制为3秒</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于20%的数据，满足N,M&lt;=20.</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于40%的数据，满足N,M&lt;=100.</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于70%的数据，满足N,M&lt;=200.</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于100%的数据，满足N,M&lt;=500，0&lt;k&lt;N*M.</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">提醒：tyvj在评测时会开O2进行优化，因此建议选手在本机测试你的程序速度时也打开O2开关。</span><br/>
<br/>
<br/>
