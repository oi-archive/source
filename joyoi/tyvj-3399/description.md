# 

 
 # 题目描述 
<p>
Exhibit（Exhibit.pas\c\cpp）<br><br>【题目描述】<br>　　博览馆正在展出由世上最佳的 M 位画家所画的图画。人们想到博览馆去看这几位大师的作品。<br>　　可是，那里的博览馆有一个很奇怪的规定，就是在购买门票时必须说明两个数字，a和b，代表要看展览中的第 a幅至第 b幅画(包含 a和 b)之间的所有图画，而门票的价钱就是一张图画一元。<br>　　人们希望入场后可以看到所有名师的图画(至少各一张)。可是又想节省金钱。。。<br>　　请你写一个程序决定购买门票时的 a 值和 b 值。<br></p> 

 
 # 输入格式 
<p>
　　输入文件Exhibit.in第一行是 N 和 M，分别代表博览馆内的图画总数及这些图画是由多少位名师的画所绘画的。<br>　　其后的一行包含 N 个数字，它们都介于 1 和 M 之间，代表该位名师的编号。<br></p> 

 
 # 输出格式 
<p>
　　输出文件Exhibit.outa和 b(a<=b)由一个空格符所隔开。<br>　　保证有解，如果多解，输出a最小的。<br></p> 

 
 # 提示 
<p>
【数据范围】<br>　　30%的数据N<=200 , M<=20<br>　　60%的数据N<=10000 , M<=1000<br>　　100%的数据N<=1000000 , M<=2000<br></p> 
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
<tr><td>12 5
2 5 3 1 3 2 4 1 1 5 4 3
</td><td>2 7</td></tr></table>
