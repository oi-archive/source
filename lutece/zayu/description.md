
# Content

BUPT is a poor university, with poor campus area, poor dormitories, and also poor educational facilities.

Most disciplines of the BUPT are about telecommunications and informatics, and one of them is called Microcomputer Theory. This discipline generally talks about the microcomputer system, the microprocessor with memory, the assembly language and the bus transferring system.

In fact, most universities of engineering offer this discipline, and take Intel8086 as the microprocessor for experiments. However, so poor is BUPT that the university do not have enough money to buy Intel8086, they use another microprocessor called ZAYU instead.

This kind of microprocessor is quite simple. It works with integers only, and has no storage beside a stack memory for arithmetic operations and a queue memory for storing instructions from the user.(It has no registers!) The arithmetic unit of the microprocessor operates the numbers on the stack with the instructions stored in the queue. The ZAYU can only take instructions as follows:
1. `PSH x`, where $x$ is a non-negative integer($0\le x\le 2^{31}$). This instruction pushes $x$ to the top of the stack.
2. `POP`, pop out the top number from the stack.
3. `NEG`, change the sign of the top number.(e.g. $7\rightarrow−7$)
4. `DUP`, duplicate the top number on the stack.
5. `SWP`, swap the top two numbers.
6. `ADD`, pop the top two numbers on the stack, and push the sum of them into the stack.
7. `SUB`, pop the top two numbers on the stack, and push the difference(the second one minus the top one) of them to the stack.
8. `MUL`, pop the top two numbers on the stack, and push the product of them to the stack.
9. `DIV`, pop the top two numbers on the stack, and push the quotient of division of them(the second one divides the top one) to the stack. Note that it is an integer division(e.g. $\frac{14}{3}=4$)
10. `MOD`, pop the top two numbers on the stack, and push the remainder of division of them(the second one modulo the top one) to the stack.
11. `END`. This instruction ends the arithmetic process pops the top number on the stack and output it to the output device, LED etc.

To avoid ambiguities while working with negative divisors and remainders, if any operand of a division operation is negative, the absolute value of the result should always be computed with absolute values of operands, and the sign is determined as follows: the quotient is negative if and only if exactly one of the operands is negative. The remainder has the same sign as the dividend. Thus, $13\ div\ -4 = -3$, $-13\ mod\ 4 = 3$, $-13\ mod\ -4 = -1$, etc.

All binary operations take the top number as the right operand, and the second as the left operand. All of them remove both operands from the stack and push the result on the top.

If there is an illegal instructions, the ZAYU just throws an error signal to the output device and halts. Error occurs when:
1. There is not enough numbers on the stack for the instruction(`POP`, `NEG` and `DUP` need at least one number while `SWP`, `ADD`, `SUB`, `MUL`, `DIV` and `MOD` need at least two).
2. The divisor is $0$(for `DIV` or `MOD`).
3. The absolute value of the result for any operation$\ge 2^{31}$.
4. The size of the stack $> 64$(for `PSH` and `DUP`).

What's more, the size of the instruction memory are also limited, which cannot store more than $64$ instructions.

Quite a poor, simple and boring chip, right? So is the homework of the discipline. The teachers always ask students to write instructions, that when some combinations of buttons pressed, the microprocessor processes the instructions and output something to light some other combinations of LEDs. What a boring task!

You are tired of doing such boring homework, drawing Karnaugh maps endlessly. As a skilled programmer, Don't Repeat Yourself is your principle. You decide to write a "universal" program, which would be able to write programs for homework, so that you may get more time with your girlfriend. You know that the combinations of buttons and LEDs can be expressed as integers using binary notation. So your task is to write a program, that when given $N$ pairs of integers , it is able to generates a program of the above instructions, that when executed with the stack initially containing only the input $X\_i$, after its successful execution, the microprocessor outputs $Y\_i$ with the stack empty.

# Standard Input

The first line contains an integer $T$ ($T\le 1000$), the number of test cases.

For each case, the first line contains an integer $N$ ($1\le N\le 8$), the number of inputs and outputs of homework. Each of the next $N$ lines contains two integers $X\_i$ and $Y\_i$($0\le X\_i,Y\_i<64$), the $i\_{th}$ input and output. All $X\_i$ are distinct.

There is a blank line after each case.

# Standard Output

Foreach case, the first line contains an integer $M$ ($1\le M\le 64$), the number of instructions.The next $M$ lines are made up of all the instructions that have been described above, one in a line. 

You should be careful that the last instruction should always be `END`, which pops the last number on the stack and output it.

Print a newline AFTER each test case.

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
3
2 6
1 3
3 11
2
10 1
23 3</td><td>5
DUP
MUL
PSH 2
ADD
END

5
PSH 2
DIV
PSH 4
MOD
END</td></tr></table>


# Constraints



# Note



# Source


