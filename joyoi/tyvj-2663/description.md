# 

 
 # 题目描述 
<p>
GameZ为他们最新推出的游戏开通了一个网站。世界各地的玩家都可以将自己的游戏得分上传到网站上。这样就可以看到自己在世界上的排名。得分越高，排名就越靠前。当两个玩家的名次相同时，先上传记录者优先。由于新游戏的火爆，网站服务器已经难堪重负。为此GameZ雇用了你来帮他们重新开发一套新的核心。<br>排名系统通常要应付三种请求：上传一条新的得分记录、查询某个玩家的当前排名以及返回某个区段内的排名记录。当某个玩家上传自己最新的得分记录时，他原有的得分记录会被删除。为了减轻服务器负担，在返回某个区段内的排名记录时，最多返回10条记录。<br><br></p> 

 
 # 输入格式 
<p>
第一行是一个整数n（n>=10）表示请求总数目。接下来n行每行包含了一个请求。请求的具体格式如下：<br>+Name Score 上传最新得分记录。Name表示玩家名字，由大写英文字母组成，不超过10个字符。Score为最多8位的正整数。<br>?Name 查询玩家排名。该玩家的得分记录必定已经在前面上传。<br>?Index 返回自第Index名开始的最多10名玩家名字。Index必定合法，即不小于1，也不大于当前有记录的玩家总数。<br>输入文件总大小不超过2M。<br>NOTE：用C++的fstream读大规模数据的效率较低<br><br></p> 

 
 # 输出格式 
<p>
对于每条查询请求，输出相应结果。对于?Name格式的请求，应输出一个整数表示该玩家当前的排名。对于?Index格式的请求，应在一行中依次输出从第Index名开始的最多10名玩家姓名，用一个空格分隔。<br></p> 
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
<tr><td>20
+ADAM 1000000     加入ADAM的得分记录
+BOB 1000000       加入BOB的得分记录
+TOM 2000000       加入TOM的得分记录
+CATHY 10000000    加入CATHY的得分记录
?TOM               输出TOM目前排名
?1                  目前有记录的玩家总数为4，因此应输出第1名到第4名。
+DAM 100000        加入DAM的得分记录
+BOB 1200000       更新BOB的得分记录
+ADAM 900000      更新ADAM的得分记录（即使比原来的差）
+FRANK 12340000   加入FRANK的得分记录
+LEO 9000000       加入LEO的得分记录
+KAINE 9000000     加入KAINE的得分记录
+GRACE 8000000    加入GRACE的得分记录
+WALT 9000000      加入WALT的得分记录
+SANDY 8000000    加入SANDY的得分记录
+MICK 9000000      加入MICK的得分记录
+JACK 7320000      加入JACK的得分记录
?2                  目前有记录的玩家总数为12，因此应输出第2名到第11名。
?5                  输出第5名到第13名。
?KAINE             输出KAINE的排名

</td><td>2
CATHY TOM ADAM BOB
CATHY LEO KAINE WALT MICK GRACE SANDY JACK TOM BOB
WALT MICK GRACE SANDY JACK TOM BOB ADAM DAM</td></tr></table>
