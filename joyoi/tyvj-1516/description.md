# 

 
 # 题目描述 
<p>　　春华秋实，在这个金秋的季节，Life带着他的宠物&mdash;&mdash;PFT到了他的试验田，当他看见自己的辛勤成果时，心里是那个高兴啊！<br />
　　这时Life对他的宠物PFT说：&ldquo;你想不想吃桃啊？&rdquo;<br />
　　PFT兴奋地说：&ldquo;好啊！&rdquo;<br />
　　Life说：&ldquo;好吧，但是我只给你一定的时间，你必须在规定的时间内回到我面前，否则你摘的桃都要归我吃！&rdquo;<br />
&nbsp;&nbsp;&nbsp;&nbsp;PFT思考了一会儿，最终答应了。<br />
　　由于PFT的数学不好，它并不知道怎样才能在规定时间获得最大的价值，但你是一个好心人，如果你帮助它，你的RP一定会暴涨的！<br />
　　对于这个可以RP暴涨的机会，你一定不会错过的是不是？<br />
　　由于PFT不是机器人，所以它的体力并不是无限的，他不想摘很多的桃以至体力为0，而白白把桃让给Life。同时PFT每次只能摘一棵桃树，每颗桃树都可以摘K次（对于同一棵桃每次摘的桃数相同）。每次摘完后都要返回出发点（PFT一次拿不了很多）即Life的所在地（0，0）{试验田左上角的桃坐标是（1,1）}<br />
　　PFT每秒只能移动一个单位，每移动一个单位耗费体力1（摘取不花费时间和体力，但只限上下左右移动）。</p> 

 
 # 输入格式 
<p>输入文件Manor.in&nbsp;共2N+1行<br />
第一行共四个数，为N,M,TI,A分别表示试验田的长和宽，Life给PFT的时间，和PFT的体力。<br />
下面一个N行M列的矩阵桃田。表示每次每棵桃树上能摘的桃数。<br />
接下来N行M列的矩阵，表示每棵桃最多可以采摘的次数K</p> 

 
 # 输出格式 
<p>一个数：PFT可以获得的最大的桃个数。</p> 

 
 # 提示 
<p>对于M,N,TI,A<br />
10&lt;=30%&lt;=50<br />
10&lt;=100%&lt;=100<br />
对于K<br />
10&lt;=100%&lt;=100<br />
保证结果在longint范围内Tgotmacp</p> 
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
<tr><td>4 4 13 20
10 0 0 0
0 0 10 0
0 0 10 0
0 0 0 0
1 0 0 0
0 0 2 0
0 0 4 0
0 0 0 0</td><td>10</td></tr></table>
