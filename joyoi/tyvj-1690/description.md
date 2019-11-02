# 

 
 # 题目背景 
全国信息学奥林匹克联赛（NOIP2011）复赛普及组第三题<BR>在双人对决的竞技性比赛，如乒乓球、羽毛球、国际象棋中，最常见的赛制是淘汰赛和循环赛。前者的特点是比赛场数少，每场都紧张刺激，但偶然性较高。后者的特点是较为公平，偶然性较低，但比赛过程往往十分冗长。<BR>本题中介绍的瑞士轮赛制，因最早使用于&nbsp;1895&nbsp;年在瑞士举办的国际象棋比赛而得名。它可以看作是淘汰赛与循环赛的折衷，既保证了比赛的稳定性，又能使赛程不至于过长。<BR> 

 
 # 题目描述 
2*N&nbsp;名编号为1~2N&nbsp;的选手共进行R&nbsp;轮比赛。每轮比赛开始前，以及所有比赛结束后，都会按照总分从高到低对选手进行一次排名。选手的总分为第一轮开始前的初始分数加上已参加过的所有比赛的得分和。总分相同的，约定编号较小的选手排名靠前。<BR>每轮比赛的对阵安排与该轮比赛开始前的排名有关：第&nbsp;1&nbsp;名和第2&nbsp;名、第3&nbsp;名和第4名、……、第2K&nbsp;–&nbsp;1&nbsp;名和第2K&nbsp;名、……&nbsp;、第&nbsp;2N&nbsp;–&nbsp;1&nbsp;名和第2N&nbsp;名，各进行一场比赛。每场比赛胜者得1&nbsp;分，负者得0&nbsp;分。也就是说除了首轮以外，其它轮比赛的安排均不能事先确定，而是要取决于选手在之前比赛中的表现。<BR>现给定每个选手的初始分数及其实力值，试计算在&nbsp;R&nbsp;轮比赛过后，排名第Q&nbsp;的选手编号是多少。我们假设选手的实力值两两不同，且每场比赛中实力值较高的总能获胜。<BR> 

 
 # 输入格式 
输入文件名为&nbsp;swiss.in。<BR>输入的第一行是三个正整数&nbsp;N、R、Q，每两个数之间用一个空格隔开，表示有2*N&nbsp;名选手、R&nbsp;轮比赛，以及我们关心的名次Q。<BR>第二行是&nbsp;2*N&nbsp;个非负整数s1,&nbsp;s2,&nbsp;…,&nbsp;s2N，每两个数之间用一个空格隔开，其中si&nbsp;表示编号为i&nbsp;的选手的初始分数。<BR>第三行是&nbsp;2*N&nbsp;个正整数w1,&nbsp;w2,&nbsp;…,&nbsp;w2N，每两个数之间用一个空格隔开，其中wi&nbsp;表示编号为i&nbsp;的选手的实力值。<BR> 

 
 # 输出格式 
输出文件名为&nbsp;swiss.out。<BR>输出只有一行，包含一个整数，即&nbsp;R&nbsp;轮比赛结束后，排名第Q&nbsp;的选手的编号。<BR> 

 
 # 提示 
【输入输出样例说明】<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;本轮对阵&nbsp;&nbsp;&nbsp;&nbsp;本轮结束后的得分<BR>选手编号&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;/&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;①&nbsp;②&nbsp;③&nbsp;④<BR>初始&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;/&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7&nbsp;&nbsp;6&nbsp;&nbsp;6&nbsp;&nbsp;7<BR>第1&nbsp;轮&nbsp;&nbsp;&nbsp;&nbsp;①—④&nbsp;②—③&nbsp;&nbsp;7&nbsp;&nbsp;6&nbsp;&nbsp;7&nbsp;&nbsp;8<BR>第2&nbsp;轮&nbsp;&nbsp;&nbsp;&nbsp;④—①&nbsp;③—②&nbsp;&nbsp;7&nbsp;&nbsp;6&nbsp;&nbsp;8&nbsp;&nbsp;9<BR>第3&nbsp;轮&nbsp;&nbsp;&nbsp;&nbsp;④—③&nbsp;①—②&nbsp;&nbsp;8&nbsp;&nbsp;6&nbsp;&nbsp;9&nbsp;&nbsp;9<BR>第4&nbsp;轮&nbsp;&nbsp;&nbsp;&nbsp;③—④&nbsp;①—②&nbsp;&nbsp;9&nbsp;&nbsp;6&nbsp;&nbsp;10&nbsp;&nbsp;9<BR>【数据范围】<BR>对于&nbsp;30%的数据，1&nbsp;≤&nbsp;N≤&nbsp;100；<BR>对于&nbsp;50%的数据，1&nbsp;≤&nbsp;N≤&nbsp;10,000；<BR>对于&nbsp;100%的数据，1&nbsp;≤&nbsp;N≤&nbsp;100,000，1&nbsp;≤&nbsp;R≤&nbsp;50，1&nbsp;≤&nbsp;Q≤&nbsp;2N，0&nbsp;≤&nbsp;s1,&nbsp;s2,&nbsp;…,&nbsp;s2N&nbsp;≤&nbsp;10^8，1&nbsp;≤&nbsp;w1,w2,&nbsp;…,&nbsp;w2N&nbsp;≤&nbsp;10^8。<BR>By&nbsp;wjy 
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
<tr><td>2 4 2
7 6 6 7
10 5 20 15
</td><td>1</td></tr></table>
