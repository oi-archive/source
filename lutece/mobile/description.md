
# Content

You've probably seen mobiles suspended from the ceilings of museums or airports. We'll restrict our-selves to the type suspended from the ceiling by a single wire that is attached to a pivot point on an arm (also made of wire). At each end of the arm is either another wire suspending yet another arm, or a weight (usually in the form of some design). Below is one example, made by Alexander Calder, the best-known mobile artist.

Some mobiles are simple and some are quite complex. Be-sides the artistry, these must balance. Recall that from a pivot point distance $d\_L$ from the left and $d\_R$ from the right,an arm will balance if the product of the weight at the left end and $d\_L$ is equal to the product of the weight at the right end and $d\_R$. (We ignore the weight of the arm and the wires suspending the arms.)

For example, consider the mobile drawn below. If weight $1$ weighs $8$ units, then weights $2, 3, 4$, and $5$ must weigh $2, 6, 4$, and $4$ units respectively. In fact, if you know the structure of the mobile,that is, the arrangement of arms and where the pivot points are on each arm, and the value of one weight, you can determine the values of all the weights. That is your problem here { almost. It seems you only have weights that are integer valued. So, you'll be given the desired minimum value of one weight and determine the value of the other weights, so that those values will also be integers. Thus, it's possible that the specified minimum valued weight must be raised a little bit to accomplish this.

![title](/source/lutece/mobile/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNzMyLzIwMTQwOTAyMTM0NzEzNDI4MzkucG5n.png)

# Standard Input

Input for each test case will start with a line containing the positive integer $n$, indicating the number of arms in the mobile. These arms are numbered $1$ through $n$. The next $n$ lines will describe the arms,in order $1,2 \cdots n$, and will be in the form $d\_L$ $d\_R$ $type\_L$ $type\_R$ $n\_L$ $n\_R$ where $d\_L$ and $d\_R$ are integers $\le 20$ giving the distances from the pivot point to the left end and right end of the arm, $type\_L$ and $type\_R$ are each either $W$ or $A$, indicating that a weight or arm hangs from the left or right ends, and $n\_L$ and $n\_R$ are the index numbers of the weight or arm on the left and right.The indices for the weights will start at $1$ and be consecutive. The mobile will not have an arm that is hanging further down than $6$ arms from the top. In our example above the lowest arm is $3$ arms from the top.
 
Following the description of the arms is a line of the form $m$ $w$, indicating that weight $m$ weighs at least $w$, where $1 \le w \le 20$.

A line containing a $0$ follows the last test case

# Standard Output

For each test case output one line giving the minimum total weight of the mobile if weight $m$ is at least $w$. Use the format given in the Sample Output. You may assume all output values will be less than $10^9$.

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
<tr><td>4
3 1 W W 2 3
4 2 W A 1 3
2 2 A A 1 4
1 1 W W 4 5
1 8
4
2 2 A W 2 5
3 1 W A 4 3
4 1 W A 3 4
2 1 W W 1 2
3 20
0</td><td>Case 1: 24
Case 2: 280</td></tr></table>


# Constraints



# Note



# Source


