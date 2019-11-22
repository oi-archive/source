# 

 
 # 题目描述 
<p>
　　在如今的信息社会中，时间-就是生命，对于记者们来说，如何以最快的速度传递消息就显得十分重要了，而为了尽快记录消息内容，速记也是必不可少的。速记就是用一些简单且特殊的符号表示一定的含义，具体如何对应依个人习惯而定，没有一种固定的表示方法。 　　<br>　　Tom是一名报社的新闻记者，常常马不停蹄的跟着新闻跑，有时只能随手记下采访的内容，让人送回报社，而自己又奔赴下一个现场。不过Tom是一个糊涂的记者，有时忙中出错，把用自己的速记符号写的内容直接传回报社。因为一时联系不上Tom，但这条新闻又十分重要，要赶着在当天的报纸排版前整理出来，于是Tom的同事们只好来猜测Tom的速记符号的意思。幸运的是Tom的同事们与他共事的时间也不短了，对于Tom的一些用词情况有一定的了解，经过讨论，他们列出了一张可能性表来表示每一个速记符号可能与哪些单词相对应，并列出了对应的可能性有多大。 　　<br>　　你的任务是：根据Tom的同事们提供的可能性表，找出一种可能性最大的速记符号与单词的对应方法（可能性应该相乘来计算）。 　　注意：每一个速记符号有且只有一个单词与其对应，每一个单词有不超过一个速记符号与其对应（可能没有速记符号与之对应）。 <br></p> 

 
 # 输入格式 
<p>
　　文件的第一行有两个整数，分别为速记符号的个数n(1 <= n <= 100)和单词总m (1 <= m <= 500)。 　　<br>　　从第1行到第n+1行为每个速记符号可能对应的单词及其可能性。 <br>　　第i+1(1 <= i <= n)行的第一个数Ci表示第i个速记符号可能与Ci个单词相对应，后面有Ci个数对(Nik，Rik)(1<=k<=Ci)，表示第i个速记符号与第Nik个单词相对应的可能性为Rik（Rik为大于0小于1的实数）。 <br></p> 

 
 # 输出格式 
<p>
　　输出文件仅包含一行，若有解则输出一个实数即最大的可能性，保留四位有效数字（四舍五入），若无解则输出"NO ANSWER"。 <br>　　（当可能性大于1e-12时才被视为有解） <br></p> 

 
 # 提示 
<p>
　　注意: 由于实数的精度误差，使用PASCAL的选手请采用Borland Pascal编译，使用C++的选手请采用djgpp编译。</p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td><br><img src="/source/joyoi/tyvj-3132/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzEzMi9wcm9ibGVtc19pbWFnZXMvMTQxNi8xLmJtcA==.bmp"></img>  </td><td><br><img src="/source/joyoi/tyvj-3132/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzEzMi9wcm9ibGVtc19pbWFnZXMvMTQxNi8yLmJtcA==.bmp"></img>  </td></tr></table>
