# 

 
 # 题目描述 
<p>
Farmer John suffered a terrible loss when giant Australian cockroaches<br>ate the entirety of his hay inventory, leaving him with nothing to<br>feed the cows. He hitched up his wagon with capacity C (1 <= C <=<br>50,000) cubic units and sauntered over to Farmer Don's to get some<br>hay before the cows miss a meal.<br><br>Farmer Don had a wide variety of H (1 <= H <= 5,000) hay bales for<br>sale, each with its own volume (1 <= V_i <= C). Bales of hay, you<br>know, are somewhat flexible and can be jammed into the oddest of<br>spaces in a wagon.<br><br>FJ carefully evaluates the volumes so that he can figure out the<br>largest amount of hay he can purchase for his cows.<br><br>Given the volume constraint and a list of bales to buy, what is the<br>greatest volume of hay FJ can purchase?  He can't purchase partial<br>bales, of course. Each input line (after the first) lists a single<br>bale FJ can buy.<br><br></p> 

 
 # 输入格式 
<p>
* Line 1: Two space-separated integers: C and H<br><br>* Lines 2..H+1: Each line describes the volume of a single bale: V_i<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: A single integer which is the greatest volume of hay FJ can<br>        purchase given the list of bales for sale and constraints.<br><br></p> 

 
 # 提示 
<p>
<br>Buying the two smaller bales fills the wagon.<br></p> 
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
<tr><td>7 3  //总体积为7,用3个物品来背包
2
6
5


The wagon holds 7 volumetric units; three bales are offered for sale with
volumes of 2, 6, and 5 units, respectively.

</td><td>7  //最大可以背出来的体积
</td></tr></table>
