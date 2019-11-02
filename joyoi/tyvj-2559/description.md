# 

 
 # 题目描述 
<p>
<br>Canmuu and his friends have recently acquired a large cache of<br>plutonium and have agreed to bury their newfound treasure at some<br>road intersection deep in the Canadian wilderness. Any sort of treasure<br>burial calls for a treasure map so they've decided to create one<br>of their own.<br><br>The road network consists of N (4 <= N <= 100,000) intersections<br>(conveniently numbered 1..N) with N roads connecting them. As busy<br>intersections confuse everybody, every intersection has at least<br>one road that leads to it, and no intersection has more than four<br>roads connected to it. Excellent maintenance has ensured that a<br>moose can always run either way between any pair of intersections.<br>Furthermore, Canmuu has decided the plutonium should not be buried<br>at any of the 4-way intersections since busy traffic decreases the<br>secrecy of the buried treasure.<br><br>The treasure map will contain all the roads and all the intersections.<br>But, to conceal the treasure's location, only one road intersection<br>on the treasure map is to be labeled: the intersection at which the<br>treasure is buried (which has a big red 'X', of course).<br><br>Ever the alert moose, Canmuu drew some trial maps to see what they<br>would look like depending on where the treasure was buried. Canmuu<br>noticed that the moose might draw similar maps even if they bury<br>their treasure in two different locations. Their curiosity piqued,<br>the herd began trying to figure out how many distinct maps they<br>could end up making.<br><br>Maps are indistinct if it is possible to assign a mapping such that:<br><br>  * the X-labeled intersections on both maps correspond,<br><br>  * a correspondence can be created for the other intersections,<br>    such that<br><br>  * when the well-chosen intersection correspondence is determined,<br>    the roads that connect the intersections also correspond.<br><br>By way of example, consider the maps below where N = 4; the treasure<br>might be buried at any of four intersections:<br><br>        +             +             X           +<br>       /|            /|            /|          /|<br>  X---+ |       +---X |       +---+ |     +---+ |<br>       \|            \|            \|          \|<br>        +             +             +           X<br><br>The final two maps, however, are not distinct since one can create<br>a correspondence for the vertices (consider the map upside down)<br>and then the roads correspond exactly. Thus, only three maps are<br>distinct.<br><br>How many distinct maps are possible for a given set of roads?<br><br></p> 

 
 # 输入格式 
<p>
* Line 1: A single integer: N<br><br>* Lines 2..N + 1: Two space-separated integers: A and B (1 <= A <= N;<br>        1 <= B <= N), indicating that there is a road connecting<br>        intersections A and B<br><br></p> 

 
 # 输出格式 
<p>
<br>* Line 1: A single integer that is the number of distinct treasure<br>        maps<br></p> 
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
<tr><td>
4
1 2
2 3
3 1
1 4

INPUT DETAILS:

Here is a drawing of the roads and the intersections.

                   4---1---2
                        \ /
                         3

</td><td>
3

OUTPUT DETAILS:

The treasure can be buried at any intersection. However, burying it at
intersections 2 and 3 yields maps that are identical to each other. So the
total number of distinct treasure maps is 3.
</td></tr></table>
