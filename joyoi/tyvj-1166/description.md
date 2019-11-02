# 

 
 # 题目背景 
在纽约中央公园里。。。<BR>纽约中央公园里有很多的动物，其中呢，以四只企鹅Skipper/Kowalski/Private/Rico和三只狐猴Julien/Maurice/Mort为主角，<BR>他们每天都有开心、悲伤、忧愁、激动、烦恼的时刻，<BR>让我们去看看吧！！！ 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;众所周知，企鹅帮中的Kowalski在这个帮派中起到了智囊的作用，关键时刻总能帮助老大Skipper解决一些困难的问题（虽然有时也会出些馊主意，且过分依赖科学和数据）。<BR>&nbsp;&nbsp;&nbsp;&nbsp;Kowalski也经常玩他的算盘！！！（他对算盘的迷恋程度相当于Rico对刀的迷恋程度！！！）不过，他可不是像一些弱智儿童一样算一些1+1=2，1+2=3，2+2=？的问题（。。。），而是经常“遨游在神秘的科学世界里探索新的发现”，这不，今天他又发现了一个东西：由于是他的发明，所以他暂且将该项发现的专利名称定为：科沃斯基数。。。<BR>&nbsp;&nbsp;&nbsp;&nbsp;科沃斯基数是这样的啊：首先呢，会给你N个数，然后呢，需要你求出，这N个数里，最多能找到多少个数，能构成严格的递减序列（可以不相邻哦！！！），然后将最多个数赋为K，然后呢，再输入一个2000位以内的数L，将L和K相加得到一个高精度数，将这个高精度数去掉指定的O位以后最大与最小的两种情况分别输在在两行。<BR>&nbsp;&nbsp;&nbsp;&nbsp;Kowalski想让你编个程序，算出这最大和最小的两个数！！！别忘了，事成之后，Kowalski会给你10000000000000000000000000000000000000000000000000&nbsp;mod&nbsp;10-100000元。。。<BR> 

 
 # 输入格式 
第一行一个整数N，表示有N个数；<BR>第二行N个正整数，表示这N个数；<BR>第三行一个高精度数L；<BR>第四行一个数O； 

 
 # 输出格式 
两行。<BR>第一行为K+L这个高精度数去掉O位后尽可能大的数；<BR>第二行为K+L这个高精度数去掉O位后尽可能小的数； 

 
 # 提示 
30%的数据&nbsp;1≤N≤100,N个正整数不超过32767，O不超过1500，L的位数不超过2000，<BR>此题比较水。。。<BR>不过还是要细心啊！！！！！！！！！！<BR>^_^来自Skipper、Kowalski&nbsp;&nbsp;&nbsp;&nbsp;and&nbsp;&nbsp;&nbsp;Julien... 
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
<tr><td>2
2 1
9999999997
5</td><td>99999
99999</td></tr></table>
