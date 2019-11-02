# 

 
 # 题目描述 
<p>
水王争霸（water.pas\c\cpp） <br><br>【题目描述】 <br>　　众所周知，IOIForum有很多水王，他们的发贴数是如此之多，以至于必须要用高精度数才能保存。<br>　　为了迎接国庆，IOIForum决定举行一次水王争霸赛，比赛的规则是将这些水王截止到2003年9月30日23时59分59秒这一刻所发的总贴数从大到小进行排序。每个水王当然都想取得尽量靠前的名次，所以他们竭尽全力，不择手段地进行灌水。<br>　　终于，激动人心的一刻到来了，2003年10月1日0时0分0秒，你作为裁判得到了每个水王的发贴数，现在，你的任务是公正地把这些水王按照发贴数从大到小进行排序。<br><br></p> 

 
 # 输入格式 
<p>
　　输入文件water.in的第一行是一个1到1000的整数N，表示总共有N位水王参加了争霸赛。<br>　　以下依次给出每位水王的描述，一位水王的描述占据两行，第一行为一个仅由字母和数字组成的长度不超过20的字符串，代表这个水王的ID，第二行一个高精度的整数(非负数)，代表这个水王的发贴数。注意，这个整数的首位没有不必要的0。<br>　　考虑到IOIForum的数据库是有限的，所有水王发贴数的总长度（注意，是总长度而不是总和）不会超过10000。<br>　　除了子母、数字和必要的换行，输入中不会出现空格等字符。<br></p> 

 
 # 输出格式 
<p>
　　输出文件water.out依次输出按照发贴数从大到小排好序的各位水王的ID，每个ID占据单独的一行。不能有任何多余的字符。若几个ID的发贴数相同，则按照ID的字典顺序先后排列。</p> 
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
<tr><td>6
lowai
1534534124561243453
zhouyuan
23453265344
Maolaoda
23442353452342
BuTaoCaiGuai
7568784573464
ArthurKing
97534892734723947
hyyylr
623893451
</td><td>lowai
ArthurKing
Maolaoda
BuTaoCaiGuai
zhouyuan
hyyylr</td></tr></table>
