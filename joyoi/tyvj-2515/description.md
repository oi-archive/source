# 

 
 # 题目描述 
<p><span style="line-height: 20.7999992370605px;">涵涵有两盒火柴，每盒装有&nbsp;n&nbsp;根火柴，每根火柴都有一个高度。现在将每盒中的火柴各自排成一列，同一列火柴的高度互不相同，两列火柴之间的距离定义为：</span><img alt="" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAFQAAAAPCAIAAAD1QH+iAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAVHSURBVEhL5ZdrLNZtHMdvL/JCa9Y0hdWwZGviRWKTzbzhRTqIGq1E5VzZGGrmoQOdKDmMVlGmWiuHLYfNsNZmPDMhJYrJalFEDil6cj+f/tfV3e2O1COvns8L+/2u//X/39f1O3yvi0r9f+LNmzfJyck3btw4e/bss2fPVIODg4GBgYcOHUpKSvrrG8HBwUFBQQ0NDZ8+fYqPj79169aVK1ciIyP7+vrkZ36Nt2/fvnv3TjoLwIsXLx4/fjzbql6+fPnx40fpKDx9+vTChQtfvny5fv36xo0bVZ8/f3Z3d1epVLdv3+YZ33ry5MnVq1cZyczM5AVfX19HR8empiYXF5cjR46Ir/wKWVlZu3fvbmtrk/4CwIKXLFly/vx56U/n3r17Xl5eVVVV0tfi+PHjYWFhX8u+v79/2bJlTk5O4oHA1dWVWsDYv3//4cOHMc6cOYOtPJwb3t20adPw8LD0F4YPHz6sWLGivr5e+j9ALtetW1dZWSl9hbKyMk9Pz/Hxcdnzd+7cIdUnT54ULty/f//BgwcYBw4coCkwTp8+HRoaqjycA8rE1NR0YGBA+t949eoVpYgxMTEhRuZJTU2NhYUFBs1FMYtBHUpLS9euXaup/5aWFpFL+C5427dvZ//Nzc3SV2CVJHDHjh28TNo9PDx0umhG/P39d+3aJR0FwoyO7N27lzhu2bLl2LFj8sH8SExMZNkImJ2dnb29/WzNv2bNmps3b2IgeNbW1ojXxYsXt23b9n3zPFi6dClfGRkZkUNq9eTkJH3V0dGB8vEXOZgzaWTAysoK1ZC+Ar9E+01NTWEvWrQoLS1NjM8TPktWi4qKenp6Fi9ePFvz79y5c8+ePRisPyQkZN++fYgRjTntqMvNzSX57e3t0v9PjI6OGhsbU2zSVzqIlQ0NDWFzuJiYmDx8+FA86uzsJLjCFtAsyM2GmUCi5SQFpHr58uWxsbHCtbW1TUhIwOju7qbVxaAgJibG2dlZOlpM2zzJoSSk842MjIycnBzpzI7YGyByOpvnmxo1zc/PZ/Oa8snLy7t8+bKwBdRaY2Pj3zPx+vVrOUmB7jUyMurt7cWmrQwNDZF3bLqAqlamSAgKsZOOFt83j5ivX79eRzaILlqqE0htmFBXV7d161auA2IEUWB7xcXFwgUkA+HA4Ni3tLT09vbGZpP0EcvFUGb9NhylNLOwL126tGrVKn66q6uLuOsIE6Xu5uYmHS3k5tkA6eJN4QL6+fz5c9Lo5+eXnZ3NCDaKgjQIOCDp4ffv37OBiIgIcSIIHBwcTpw4IR21mvuCnp4e4ed2tXnzZiJVUFBAtbe2thImGkHO+03oZAMDAyqCO9jq1atRfga5VqxcuZJjRcwRcEOJjo6WjhZfN8+uOAwrKirEkIA+OXjwIAab57TD4Dg8evQoGYa4uLhz586hgspcNdERkwUpKSlor3SU6kBdCBD9TEPSpeIQ5ReJhZjzuxD3wsLCkpISVgIa4aitrdVJMsElr5y+0tdCRZ2jmUSLGx6CB+hKamqqvr7+qVOnmMEJFx4ejkE4yRWCCTQCd2NNj6Snp2sOT0DzbGxsWJz0ZyEqKkr7ZvFH4PDTuYZS89SIdKajQl3Mzc1pHjMzM4oQuJ+gogyKvg0ICBB3m7t37xJjqhdIPgHSZB6b3xC24NGjRwgs5f2TewHXLOSgurpa+n8CipTPcqWjNGhMLhTIjUaMdVAhvEjOPzPB+2NjYz4+PlQ+cirf+IHy8nLmUMCct7wlRxXVoCJ+cnDybwnval8r5g/lyTdRImxCcO3aNTE+A2r1v9tuk7UN2VDGAAAAAElFTkSuQmCC" style="line-height: 20.7999992370605px; width: 84px; height: 15px;" /><span style="line-height: 20.7999992370605px;">，其中&nbsp;ai&nbsp;表示第一列火柴中第&nbsp;i&nbsp;个火柴的高度，bi&nbsp;表示第二列火柴中第&nbsp;i&nbsp;个火柴的高度。</span><br style="line-height: 20.7999992370605px;" />
<span style="line-height: 20.7999992370605px;">每列火柴中相邻两根火柴的位置都可以交换，请你通过交换使得两列火柴之间的距离最小。请问得到这个最小的距离，最少需要交换多少次？如果这个数字太大，请输出这个最小交换次数对&nbsp;99,999,997&nbsp;取模的结果。</span></p> 

 
 # 输入格式 
<p><span style="line-height: 20.7999992370605px;">共三行，第一行包含一个整数&nbsp;n，表示每盒中火柴的数目。&nbsp;</span><br style="line-height: 20.7999992370605px;" />
<span style="line-height: 20.7999992370605px;">第二行有&nbsp;n&nbsp;个整数，每两个整数之间用一个空格隔开，表示第一列火柴的高度。第三行有&nbsp;n&nbsp;个整数，每两个整数之间用一个空格隔开，表示第二列火柴的高度。&nbsp;</span></p> 

 
 # 输出格式 
<p><span style="color: rgb(68, 68, 68); font-family: 'Microsoft YaHei', 微软雅黑, Tahoma, Helvetica, Arial, sans-serif; font-size: 12px; line-height: 21.6000003814697px; background-color: rgba(255, 255, 255, 0.65098);">输出共一行，包含一个整数，表示最少交换次数对&nbsp;99,999,997&nbsp;取模的结果。</span></p> 

 
 # 提示 
<p>【输入输出样例1说明】<br />
最小距离是&nbsp;0，最少需要交换&nbsp;1&nbsp;次，比如：交换第&nbsp;1&nbsp;列的前&nbsp;2&nbsp;根火柴或者交换第&nbsp;2&nbsp;列的前&nbsp;2&nbsp;根火柴。<br />
【输入输出样例2说明】<br />
最小距离是&nbsp;10，最少需要交换&nbsp;2&nbsp;次，比如：交换第&nbsp;1&nbsp;列的中间&nbsp;2&nbsp;根火柴的位置，再交换第&nbsp;2&nbsp;列中后&nbsp;2&nbsp;根火柴的位置。<br />
【数据范围】</p>

<p>对于&nbsp;10%的数据，&nbsp;1&nbsp;&le;&nbsp;n&nbsp;&le;&nbsp;10；</p>

<p>对于&nbsp;30%的数据，1&nbsp;&le;&nbsp;n&nbsp;&le;&nbsp;100；</p>

<p>对于&nbsp;60%的数据，1&nbsp;&le;&nbsp;n&nbsp;&le;&nbsp;1,000；<br />
对于&nbsp;100%的数据，1&nbsp;&le;&nbsp;n&nbsp;&le;&nbsp;100,000，0&nbsp;&le;火柴高度&le;&nbsp;2<sup>31</sup>&nbsp;&minus;&nbsp;1。</p> 
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
<tr><td>4 
2 3 1 4 
3 2 1 4</td><td>1</td></tr><tr><td>4 
1 3 4 2 
1 7 2 4 </td><td>2</td></tr></table>
