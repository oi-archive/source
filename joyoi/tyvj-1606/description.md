# 

 
 # 题目描述 
小迈克尔住在一个小镇上，他喜欢看每周日下午发布的音乐电视评比。它每周都根据选票介绍相同的歌曲，列出这些歌曲的流行排行榜。<BR>有一个星期日迈克尔和他的朋友在一起玩得太久了以致于未能看到新的流行榜。他非常失望，但是不久他就发现下周至少可以部分地建立出流行榜。除了每首歌曲的位置，排行榜还根据这些歌曲上周的排行列出了它们排行变动的信息，更精确地说，从这周起，不管那首歌是继续排在原位，还是排名上升或排名下降，都会给出一点说明。<BR>编写程序，根据给定的流行榜帮助迈克尔推断出上周可能的排行榜。<BR> 

 
 # 输入格式 
输入的第一行是一个整数N，1≤N≤100，表示排行榜上歌曲的总数。<BR>接下来的N块列出了排行信息。每块有两行组成，第i块第一行是第i首歌曲的名称，歌名包括最多不超过100个英文大写字母，第二行包含下列三个单词中的一个：UP(歌曲在排行榜上的位置上升)，DOWN(歌曲在排行榜上的位置下滑)或SAME(排行不变)，表示与上周排行榜相比，排行榜所发生的变动。<BR> 

 
 # 输出格式 
输出应该用N行输出一个上周可能的排行榜。<BR>每一行包含一首歌名，即第i行包含排行榜上第i首歌的歌名。<BR>注意：解不必是唯一的，但对于每一个测试数据都至少有一个解。<BR> 
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
<tr><td>5
HIGHHOPES
UP
LOWFEELINGS
UP
UPANDDOWN
DOWN
IAMSTILLSTANDING
DOWN
FOOLINGAROUND
DOWN

</td><td>UPANDDOWN
IAMSTILLSTANDING
FOOLINGAROUND
HGHHOPES
LOWFEELINGS
</td></tr></table>
