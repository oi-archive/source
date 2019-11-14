
# Content

下课时间到了，`zh`一下子冲出了教室，赶向南门的卖汉堡的食品商店去恰饭。  
可是在抵达汉堡店之前，`zh`会在一些食物商店买零食，不然会在半路饿晕以至于赶不到汉堡店就倒下了。道路是单向的，并且`zh`对不同食物商店的零食都会有一个喜爱度，每当`zh`路过一个食物商店，他可以得到一个零食喜爱度，`zh`可以重复路过一家食物商店，但是不能重复获得这个商店的喜爱度。现在给你每个商店的位置和零食喜爱度，请你设计一个方案使得在`zh`到达卖汉堡的食物商店时能得到尽可能多的零食喜爱度。

# Standard Input

第一行包含两个整数N、M。N表示食物商店的个数，M表示道路条数，n,m<=3000 。  
接下来M行，每行两个整数，这两个整数都在1到N之间，第i+1行的两个整数表示第i条道路的起点和终点食物商店编号。  
接下来N行，每行一个整数，按顺序表示zh对每个食物商店处的零食喜爱度value，value<=1000。  
接下来一行包含两个整数S、P，S表示学校的编号，也就是出发地点。P表示卖汉堡的食物商店数目（即`zh`可能最终到达的终点数目）。接下来的一行中有P个整数，表示P个卖汉堡的食物商店的编号。

# Standard Output

输出一个整数，表示`zh`到达汉堡店时能得到的最多的干食喜爱度

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>6 7  
1 2  
2 3  
3 5  
2 4  
4 1  
2 6  
6 5  
10  
12  
8  
16  
1  
5  
1 4  
4 3 5 6 </td><td>47</td></tr></table>


# Constraints



# Note

样例解释：`zh`可以按照1->2->4->1->2->3->5的路线走，获得的零食喜爱度为47且最大

# Source


