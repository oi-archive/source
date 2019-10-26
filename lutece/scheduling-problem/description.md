
# Content

Recently,wangkun is focused on the scheduling,proposing a method which can meet the scheduling demand.However,the principle is a little sophisticated.He wants to know how much time it takes to complete all the tasks.So,you are asked for help.

Followings are the principles:

First there exist $N$ tasks,numbered from $1$ to $N$.Each task i is assigned a
priority $P\_i$. Additionally,each task is divided into $S$ subtasks. $T\_j$ time is needed to spend on each subtask $j$. Now, $M$ machines are available. Every machine can only take a single subtask a time.

At the beginning,all the $M$ machines are available.we assume that,if a machine is available,it can take a subtask.Pay attention that,every time among the uncompleted subtasks,the subtask with the highest priority is taken out.For two subtasks with equal priority,we rank them according to their rank number.For instance,there is a subtask $3$ in task $1$ and a subtask $2$ in task $2$,and task $1$ and task $2$ are having the same priority.We define that subtask $3$ is prior to subtask $2$.Besides,for two subtasks in the same task,such as subtask $2$ in task $1$ and subtask $3$ in task $1$,subtask $2$ is prior to subtask $3$.

# Standard Input

First line is a integer $T$,representing the number of test cases

In each test cases,first line contains two integers $N$(number of tasks $0 < N \leq 100$),M(number of machines $0 < M \leq 100$)

Following are $N$ tasks.

In each task,first line contains two integers $S$(number of subtasks in the task $0 < S \leq 100$), $P$(the priority of the task $0 \leq p \leq 100$)

Following $S$ lines indicate the executing time for each subtask.

# Standard Output

One line,the time needed to complete all the tasks.

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
<tr><td>1
2 3
2 2
1
2
2 5
3
4</td><td>4</td></tr></table>


# Constraints



# Note



# Source


