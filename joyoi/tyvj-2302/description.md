# 

 
 # 题目描述 
<p>
A civil engineer that has recently graduated from the Czech Technical University encountered an interesting problem and asked us for a help. The problem is more of economical than engineering nature. The engineer needs to connect several buildings with an infrastructure. Unfortunately, the investor is not the owner of all the land between these places. Therefore, some properties have to be bought first. <br>The land is divided into a regular ``grid" of hexagonal parcels, each of them forms an independent unit and has the same value. Some of the parcels belong to the investor. These parcels form four connected areas, each containing one building to be connected with the others. Your task is to find the minimal number of parcels that must be acquired to connect the four given areas. <br> <br>The whole land also has a hexagonal shape with six sides, each consisting of exactly H parcels. The above picture shows a land with H = 4 , parcels with letters represent the four areas to be connected. In this case, it is necessary to buy four additional parcels. One of the possible solutions is marked by crosses. <br>简单描述：给你一个六边形，这个六边形由很多个小六边形构成，如图．这个六边形中有4个连通区域(图中黑色区域)，现在你的任务是再选择最少个数的小六边形使得四块区域连通．<br><br></p> 

 
 # 输入格式 
<p>
The input contains several scenarios. Each scenario begins with an integer number H , which specifies the size of the land, 2 H 20 . Then there are 2*H - 1 lines representing individual ``rows" of the land (always oriented as in the picture). The lines contain one non-space character for each parcel. It means the first line will contain H characters, the second line H + 1 , and so on. The longest line will be the middle one, with 2*H - 1 characters. Then the ``length" descends and the last line contains H parcels, again. <br>The character representing a parcel will be either a dot (``.") for the land that is not owned by the investor, or one of the uppercase letters ``A", ``B", ``C", or ``D". The areas of parcels occupied by the same letter will always be connected. It means that between any two parcels in the same area, there exists a path leading only through that area. <br>Beside the characters representing parcels, the lines may contain any number of spaces at any positions to improve ``human readability" of the input. There is always at least one space between two letters (or the dots). After the land description, there will be one empty line and then the next scenario begins. The last scenario is followed by a line containing zero. <br></p> 

 
 # 输出格式 
<p>
For each scenario, output one line with the sentence ``You have to buy P parcels.", where P is the minimal number of parcels that must be acquired to make all four areas connected together. <br>Areas are considered connected, if it is possible to find a path between them that leads only through parcels that have been bought. <br></p> 

 
 # 提示 
<p>
<img border="0" src="/source/joyoi/tyvj-2302/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjMwMi9wcm9ibGVtc19pbWFnZXMvMjY3OC8xNDAxLmpwZw==.jpg"><br></p> 
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
    B . . C 
   . . . . C 
  . A . . C . 
 . A A . . . .
  . A . . . . 
   . . . D D 
    . . . . 
0
</td><td>You have to buy 4 parcels.</td></tr></table>
