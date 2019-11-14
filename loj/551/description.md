
# 题目描述

Alex 在和 Ball 玩游戏，他们面前有一个 $n \times n$ 的空白矩阵 $M$，Alex 和 Ball 轮流往上放标记，**Ball 先手**。  
矩阵中的一个格子被放置标记后就不能再放置标记，同时我们记 Alex 放的标记为 $A$ 标记，Ball 放的标记为 $B$ 标记。  
在某一轮游戏结束后（一轮游戏指的是 Ball 先操作，然后 Alex 操作），若存在一个排列 $p[1..n]$ 使得对任意 $i \in [1,n]$，满足 $M[i][p[i]]=A$，则Alex立即获胜。  
在 $\lfloor n^2 /2 \rfloor$ 轮后，若 Alex 没有获胜，则 Ball 获胜。  
若 Alex 或 Ball 在某个时刻做了非法的操作（由于遗忘在放过标记的地方重复放），他会直接输掉游戏。  
狡猾的 Ball 想了一个办法来恶心 Alex ，他每隔很久很久才给出下一个操作，这样 Alex 可能会忘掉双方之前的操作。  
现在你得到了这个信息，对于一个给定的 $n$，你想知道两件事：

* Alex 在自己每次操作前记得双方之前所有操作的情况下是否有必胜策略。
* Alex 在自己每次操作前忘掉双方之前所有操作，仅知道 Ball 最后一次操作的情况下是否有必胜策略。

Ball 永远记得双方的所有操作。

<div class="lang-divider"> </div>

Alex is playing a game with Ball. There is a blank matrix $M$ with $n$ lines and $n$ columns. Alex and Ball take turns to mark one of the matrix elements with his own sign (Alex’s sign is called $A$ and Ball’s sign is called $B$). **Ball goes first**.  
After a round of game (a round means that Ball and Alex operates once each in order), if there exists a permutation $p[1..n]$ satisfies that for each $ i \in [1,n]$,$M[i][p[i]]=A$, Alex wins immediately.  
After $\lfloor n^2 /2 \rfloor$ rounds, if Alex hasn’t won, Ball wins instead.  
Notice that whenever anyone tries to mark a marked matrix element(because of forgetting), he will lose the game immediately.  
Sly Ball thinks of a way to interfere Alex. He decides to operate long time after the Alex’s last operation so that Alex may forget about the previous operations.  
Now you get this message and want to know two things for a given $n$: 

* whether Alex has winning strategy if he remembers all the previous operations
* whether Alex has winning strategy if he forgets all the previous operations, and only knows Ball's last operation each time.  

Ball always knows all their previous operations.

# 输入格式

从标准输入中读取数据。  
第一行，一个整数 $T$，表示数据组数。  
接下来 $T$ 行，每行一个整数$n$，表示矩阵的大小。  

<div class="lang-divider"> </div>

Read from the standard input.   
This first line contains a single integer $T$ which means the number of the test cases.   
The following $T$ lines, each line contains one integer $n$ which means the size of the matrix.   

# 输出格式

输出到标准输出中。   
输出共 $T$ 行，对于每一组数据，输出两行"Yes"或者"No"。   
第一行表示Alex在操作前**记得**双方之前操作的情况下他是否一定能获胜。   
第二行表示Alex在操作前**忘掉**双方之前操作，仅知道 Ball 最后一次操作的情况下他是否一定能获胜。   

<div class="lang-divider"> </div>

Write to the standard output.  
For each test case, output two lines of `Yes` or `No`.   
The first line means whether Alex can win for sure If he **remembers** the previous operations.  
The second line means whether Alex can win for sure If he **forgets** the previous operations.  


# 样例

#### 样例输入  
```plain
2
1
2
```

#### 样例输出  
```plain
No
No
No
No
```

<div class="lang-divider"> </div>

#### Sample Input  
```plain
2
1
2
```

#### Sample Output  
```plain
No
No
No
No
```

# 数据范围与提示

对于所有数据， $1\leq n \leq 10^{18}$,$1 \leq T \leq 100$。

详细的数据限制及约定如下（留空表示和上述所有数据的约定相同）：  

|	子任务编号	|	分值	(百分比) |	$n$			         	|
|:----------------------:|:----------------:|:------------------------------------:|
|	$1$			|	10		|	$\leq 3$			        |
|	$2$			|	40		|	$\leq 100$			|
|	$3$			|	20		|	$\leq 10^6$			|
|	$4$			|	30		|	$\leq 10^{18}$		|

<div class="lang-divider"> </div>

For all test cases,  $1\leq n \leq 10^{18}$,$1 \leq T \leq 100$ .

Detailed constraints and hints are as follows (blank grids denote the same constraints as mentioned above):    

|	Subtask	|	Score (percentage)	|	$n$			         	|
|:----------------------:|:----------------:|:------------------------------------:|
|	$1$			|	10		|	$\leq 3$			        |
|	$2$			|	40		|	$\leq 100$			|
|	$3$			|	20		|	$\leq 10^6$			|
|	$4$			|	30		|	$\leq 10^{18}$		|

