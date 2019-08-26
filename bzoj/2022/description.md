
# Description

<div class="content">Gigel has a strange &#34;balance&#34; and he wants to poise it. Actually, the device is different from any other ordinary balance. It orders two arms of negligible weight and each arm&#39;s length is 15. Some hooks are attached to these arms and Gigel wants to hang up some weights from his collection of G weights (1 &lt;= G &lt;= 20) knowing that these weights have distinct values in the range 1..25. Gigel may droop any weight of any hook but he is forced to use all the weights. Finally, Gigel managed to balance the device using the experience he gained at the National Olympiad in Informatics. Now he would like to know in how many ways the device can be balanced. Knowing the repartition of the hooks and the set of the weights write a program that calculates the number of possibilities to balance the device. It is guaranteed that will exist at least one solution for each test case at the evaluation. 
输入一个天平若干（&lt;=20）挂钩的位置，将若干（&lt;=20）砝码挂到天平上，问有多少种使天平挂平衡的方法。
</div>

# Input

<div class="content">The input has the following structure: 
• the first line contains the number C (2 &lt;= C &lt;= 20) and the number G (2 &lt;= G &lt;= 20); 
• the next line contains C integer numbers (these numbers are also distinct and sorted in ascending order) in the range -15..15 representing the repartition of the hooks; each number represents the position relative to the center of the balance on the X axis (when no weights are attached the device is balanced and lined up to the X axis; the absolute value of the distances represents the distance between the hook and the balance center and the sign of the numbers determines the arm of the balance to which the hook is attached: &#39;-&#39; for the left arm and &#39;+&#39; for the right arm); 
• on the next line there are G natural, distinct and sorted in ascending order numbers in the range 1..25 representing the weights&#39; values. 
</div>

# Output

<div class="content">The output contains the number M representing the number of possibilities to poise the balance. 
</div>

# Sample Input

<div class="content"><span class="sampledata">2 4	<br/>
-2 3 <br/>
3 4 5 8<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
</span></div>

# Hint

<div class="content"><p>第一种放法把(4,8)放左边,(3,5)放右边<br/>
第二种放法把((3,4,5)放左边，8单独放右边<br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

