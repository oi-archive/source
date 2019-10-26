
# Content

XiaoA is a lovely boy who likes designing some digital product.One day, he met XiaoB who is XiaoA's little girl friend and told her that his new product had came out.It's a calculator which can do `add`($+$) opeartion and `sub`($-$) operation between nonnegative numbers.

Actually, XiaoA's calculator is very low-grade.However, XiaoB is not willing to make XiaoA disappoint, and praised XiaoA's talent all the same.

The calculator has three $K$-digit register, named Ra, Rb and Rc.You can input a nonnegative decimal number to the register Ra and Rb, which will be stored in the binary base.For example, if $K$ is $8$ then $99$ stored as `01100011`, and $147$ stored as `10010011`.Now a problem is that the value will change after storing in the register for a large decimal number. For instance, $523$ will be stored as `00001011` for $K=8$. Yes! Because $523$ is overflow for this $8$-digit register.

The operation of the calculator is $R\_a + R\_b = R\_c$ and $R\_a - R\_b = R\_c$. In the `sub` operation , it should be guaranteed that the number stored in $R\_a$ is not smaller in decimal base than that in $R\_b$ , otherwise XiaoA will roar, `it's too hard!`. 

Since XiaoA can do it, how about you?

# Standard Input

In the first line is $N$ ($N\leq 100$), which is the number of test cases.

For each of the next $N$ lines, the first is a number $K$($1\leq K\leq 16$), then there is a operation either $A + B$ or $A - B$, where $A$(stored in $R\_a$) and $B$(stored in $R\_b$) are nonnegtive decimal integers ($0\leq A, B\leq 10^7$).

# Standard Output

For each case, you should output one line.

First, output `Case #C: `, where $C$ is the number of the test case, from $1$ to $T$.

Then, if it is a `sub` operation and the number stored in $R\_a$ is smaller in decimal base than that in $R\_b$, you should output `Maybe , it is really too hard, hha!`, else you should output the number which is stored in $R\_c$ in decimal base.

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
<tr><td>3
8 5 + 3
8 4 - 9
8 523 + 1</td><td>Case #1: 8
Case #2: Maybe , it is really too hard, hha!
Case #3: 12</td></tr></table>


# Constraints



# Note



# Source


