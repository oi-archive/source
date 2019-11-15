
# Content

Gigel has a strange `balance` and he wants to poise it. Actually, the device is different from any other ordinary balance. 

It orders two arms of negligible weight and each arm's length is $15$. Some hooks are attached to these arms and Gigel wants to hang up some weights from his collection of $G$ weights $(1 \leq G \leq 20)$ knowing that these weights have distinct values in the range $1 \cdots 25$. Gigel may droop any weight of any hook but he is forced to use all the weights. 

Finally, Gigel managed to balance the device using the experience he gained at the National Olympiad in Informatics. Now he would like to know in how many ways the device can be balanced. 

Knowing the repartition of the hooks and the set of the weights write a program that calculates the number of possibilities to balance the device.

# Standard Input

The input has the following structure: 

the first line contains the number $C (2 \leq C \leq 20)$ and the number $G (2 \leq G \leq 20)$; 

the next line contains $C$ integer numbers (these numbers are also distinct and sorted in ascending order) in the range $-15 \cdots 15$ representing the repartition of the hooks; each number represents the position relative to the center of the balance on the $X$ axis (when no weights are attached the device is balanced and lined up to the $X$ axis; the absolute value of the distances represents the distance between the hook and the balance center and the sign of the numbers determines the arm of the balance to which the hook is attached: `-` for the left arm and `+` for the right arm); on the next line there are $G$ natural, distinct and sorted in ascending order numbers in the range $1 \cdots 25$ representing the weights' values.

The input contains multi-cases, process to the EOF.

# Standard Output

The output contains the number $M$ representing the number of possibilities to poise the balance.

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
<tr><td>2 4
-2 3
3 4 5 8</td><td>2</td></tr></table>


# Constraints



# Note

1 :  数据保证结果不会使用到大数类。

2：尽量使用scanf printf,不然可能导致TLE。

The data used in this problem is unofficial data prepared by silentsky. So any mistake here does not imply mistake in the offcial judge data.

# Source


