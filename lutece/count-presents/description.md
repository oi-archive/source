
# Content

On the day of Xiao Ming's birthday, he received lots of presents from his uncles, aunts, brothers and sisters, a pencil from Uncle Wang, a box of sweets from Aunt Zhang, a lovely toy car from his big brother, and a toy pistol from his good friend Xiao Qiang. The numbers of the presents are too many to count, triggering that it is not available for Xiao Ming to remember from whom did he receive those presents. Fortunately, Xiao Ming still remembers the accurate time he received each gift. The sweets were received in the morning, his brother gave the gift to him at noon and the toy pistol was received in the afternoon when he went out to play games with Xiao Qiang while the box of Chinese chess were not on Xiao Ming’s bed until the night.

![.*](/source/lutece/count-presents/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTc0LzIwMTQwMjAyMjM0MjE2NzY2MzQucG5n.png)

Though lots of presents Xiao Ming has received, he finds that many of them are the same as others. Xiao Ming has found another $2$ boxes that contain the same pencils that Uncle Wang gave him, so as the sweets. The curious boy wants to know how many kinds of different presents are received **during a certain period of time**, can you help him?

# Standard Input

Firstly the inputs will tell you the name of the presents and the time when the presents are received, the followings are Xiao Ming’s questions. The first line of the inputs is $T$(no more than $10$), which stands for the number of test cases you need to solve, for each case you must solve it independently and print the answer as the requests.

After $T$, the inputs will be each test case. The first line of each case will be $N$, representing for the numbers of presents Xiao Ming has received. The form of the following $N$ lines is: name time, which stands for the name of the presents and the time it is received. The name is a string with a length no more than $10$. **To simplify the question, we use integers from $0$ to $86400$ to indicate the time ( $86400$ is excluded ). The data will guarantee that the receiving time for each gift will be different and the value of the receiving time for each gift in the input will be non-decreasing.**

$Q$ is given in the following line, which means that Xiao Ming has $Q$ questions to ask for you. Then the following $Q$ lines will be Xiao Ming’s questions, the maximum number of $Q$ will be $100000$. Every question contains $2$ elements: $s$, $t$, $0\leq s\leq t < 86400$, which stands for the start time and end time of the period Xiao Ming wants to ask you. Be careful that **the moment s and t are also contained in the time period**. For details please refer to the samples.

# Standard Output

Please output the answer for all test cases. **Print a blank line after each test case**.

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
<tr><td>2
5
candy 1538
pencil 3305
toycar 4437
pencil 7126
chess 12548
4
0 3304
1537 9000
0 10000
0 86399
10
chunge 3460
feimao 7571
feimao 8254
kaohongshu 15468
jichibang 17629
jichibang 19875
jichibang 27047
yangdaniu 28052
zengge 33854
yangdaniu 34494
7
7377 16406
22851 39403
32266 64046
27715 57687
17861 46069
20905 40493
0 31179</td><td>1
3
3
4

2
3
2
2
3
3
5</td></tr></table>


# Constraints



# Note



# Source


