# 

 
 # 题目背景 
『谜题在丛林中散发芳香<BR>&nbsp;&nbsp;绿叶上露珠跳跃着歌唱<BR>&nbsp;&nbsp;火焰在隐暗的角落升腾飞起<BR>&nbsp;&nbsp;月华照射着神祇们忠诚的信徒。』<BR><BR>————《瓦尔基里福音书·第六乐章：幻想》———— 

 
 # 题目描述 
Tristan解决了英灵殿的守卫安排后，便到达了静谧的精灵领地——Alfheim。由于Midgard处在Alfheim和冥界Hel的中间，精灵族领地尚未受到冥界恶灵的侵入。族长Galanodel为了帮助米德加尔特抵御外敌，对邪恶亡灵军团使用了高等魔法，从而使得亡灵军团每个士兵的行进速度变得不一致，从而打乱冥王Hel安排的最佳阵型。由于这个军团离Midgard还很远，因此在抵达Midgard之前，对于A、B两个亡灵，若A的初始位置在B后面且A的速度比B快，A就会冲到B的前面去。现在Galanodel想知道，会有多少对亡灵之间出现反超现象？ 

 
 # 输入格式 
第一行一个整数n，表示排成一队的邪恶亡灵军团有多少人。<BR>第二行n个整数a[i]，表示邪恶亡灵们在数轴上的初始坐标。数据保证这些坐标全部不同。亡灵军团向数轴正方向前进。<BR>第三行n个整数v[i]，表示邪恶亡灵们的行进速度。 

 
 # 输出格式 
一行一个正整数k，表示「反超」的个数。 

 
 # 提示 
对于30%的数据，1&lt;=N&lt;=1000；<BR>对于100%的数据，1&lt;=N&lt;=10^5。<BR>所有数据的绝对值均不超过maxlongint。《末世神话：精灵族的急援》 
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
<tr><td>3
1 2 3
2 1 3</td><td>1</td></tr></table>
