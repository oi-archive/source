
# Content

Hongshu is so poor that his boss assigned him a boring work: managing the super-computer named YY. What Hongshu should do is to start YY when he comes to work at $10$ o'clock each weekday (Monday to Friday), and close it when he leaves at $18$ o'clock. **Hongshu never go to work on weekends**.

Users of YY send their tasks to Hongshu. Because YY can only deal with at most one problem at any time, tasks coming when YY is busy or closed would be put into a queue. The tasks in the queue are ordered by their coming time. Whenever YY is free and the queue is not empty, it would take the earliest task from the task queue.

Customers always make things difficult. After submitting their tasks, some of them even want to know when their tasks would be finished by YY. Hongshu is so smart that he can figure out how many hours YY needs to complete each task. However, he is busy playing Karting now. So he asks you, his best friend, to help him solve this problem. Could you help him?

In this problem, we do not consider holidays.

# Standard Input

The first line of the input will be an integer $N$ ($N \leq 10000$) indicating the number of tasks Hongshu has received.

The following $N$ lines list the $N$ tasks in time order. The format for each line is `YYYY/MM/DD HH T`, representing that this task is received at `HH` o'clock on day `YYYY/MM/DD`, and it is supposed to occupy YY for `T` ($1 \leq T\leq 10000$) hours. Please refer to sample input for more details.

We guarantee that the first task comes not earlier than year $2001$, and the last task would be completed before year $10000$.

# Standard Output

For each task, print `Case #t: YYYY/MM/DD HH` in a single line, in which t is the number of this task starting from $1$, and `YYYY/MM/DD HH` shows the completion time for each task.

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
2001/01/01 00 8
2001/02/28 17 2
2001/02/28 23 10</td><td>Case #1: 2001/01/01 18
Case #2: 2001/03/01 11
Case #3: 2001/03/02 13</td></tr></table>


# Constraints



# Note

`2001/1/1` is Monday.

The first task comes at $0$ am. YY would deal with it since $10$ am because Hongshu starts it at that time.

The first task and third task would be put into the queue.

# Source


