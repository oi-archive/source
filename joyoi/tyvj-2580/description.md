# 

 
 # 题目描述 
<p>
<br>FJ's cows really hate getting wet so much that the mere thought of<br>getting caught in the rain makes them shake in their hooves.  They<br>have decided to put a rain siren on the farm to let them know when<br>rain is approaching. They intend to create a rain evacuation plan<br>so that all the cows can get to shelter before the rain begins.<br>Weather forecasting is not always correct, though. In order to<br>minimize false alarms, they want to sound the siren as late as<br>possible while still giving enough time for all the cows to get to<br>some shelter.<br><br>The farm has F (1 <= F <= 200) fields on which the cows graze.  A<br>set of P (1 <= P <= 1500) paths connects them. The paths are wide,<br>so that any number of cows can traverse a path in either direction.<br><br>Some of the farm's fields have rain shelters under which the cows<br>can shield themselves. These shelters are of limited size, so a<br>single shelter might not be able to hold all the cows.  Fields are<br>small compared to the paths and require no time for cows to traverse.<br><br>Compute the minimum amount of time before rain starts that the siren<br>must be sounded so that every cow can get to some shelter.<br><br></p> 

 
 # 输入格式 
<p>
<br>* Line 1: Two space-separated integers: F and P<br><br>* Lines 2..F+1: Two space-separated integers that describe a field. <br>        The first integer (range: 0..1000) is the number of cows in<br>        that field.  The second integer (range: 0..1000) is the number<br>        of cows the shelter in that field can hold.  Line i+1<br>        describes field i.<br><br>* Lines F+2..F+P+1: Three space-separated integers that describe a<br>        path. The first and second integers (both range 1..F) tell the<br>        fields connected by the path. The third integer (range:<br>        1..1,000,000,000) is how long any cow takes to traverse it.<br><br></p> 

 
 # 输出格式 
<p>
<br>* Line 1: The minimum amount of time required for all cows to get<br>        under a shelter, presuming they plan their routes optimally. <br>        If it not possible for the all the cows to get under a<br>        shelter, output "-1".<br><br></p> 
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
3 4
7 2
0 4
2 6
1 2 40
3 2 70
2 3 90
1 3 120

</td><td>
110

OUTPUT DETAILS:

In 110 time units, two cows from field 1 can get under the shelter in that
field, four cows from field 1 can get under the shelter in field 2, and one
cow can get to field 3 and join the cows from that field under the
shelter in field 3.  Although there are other plans that will get all the
cows under a shelter, none will do it in fewer than 110 time units.</td></tr></table>
