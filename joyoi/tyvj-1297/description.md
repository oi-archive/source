# 

 
 # 题目描述 
其实你们都不知道，小B是很小气的。一天小B带着他的弟弟小B'一起去摘果子，走着走着，他们忽然发现了一颗长满了果子的树。由于弟弟长得太矮了，弟弟只有让哥哥小B帮他摘一些果子下来。哥哥小B说:"弟弟啊，不是我不想给你摘多，我只是一次拿不了那么多，昨天晚上又没睡好，只能上一次树。所以哥哥只能给你摘一个哈。"没办法，弟弟只有答应了这个要求。<BR>于是几下小B就上了树，树上的果子还真多，有N个呢！！但是小B很快发现这些果子大小不一。抠门的小B就想给自己拿个最大的，给弟弟拿个最小的果子。但是由于树上有些果子太高，小B不一定可以够着，所以他给你选了P个可以够着的果子区间，让你在这些区间里面找一个最大的果子和一个最小的果子。<BR><BR> 

 
 # 输入格式 
共p+2行，<BR>&nbsp;&nbsp;第一行为n和p，<BR>&nbsp;&nbsp;第二行为区间[1,n]的果子大小（用正整数表示）<BR>&nbsp;&nbsp;后面p行形如a&nbsp;b，意为每次询问的区间的左界和右界<BR><BR> 

 
 # 输出格式 
共p行，第i行为第i次询问时得到的最大值以及最小值（一个询问用空格空开max和min）<BR><BR>【注意】在输入数据中果子的大小是无序的。<BR><BR> 

 
 # 提示 
【数据范围】<BR>&nbsp;&nbsp;保证果子大小不超过maxlongint<BR>&nbsp;&nbsp;40%的数据：1&lt;=n,p&lt;=1,000<BR>&nbsp;&nbsp;100%的数据：1&lt;=n&lt;=50,000<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1&lt;=p&lt;=20,000<BR><BR> 
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
<tr><td>5 2
1 3 2 4 5
1 4
2 5

</td><td>4 1
5 2

</td></tr></table>
