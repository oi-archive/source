
# 题目描述

**译自 POI 2011 Round 3. Day 2. C「[Programming Contest](https://szkopul.edu.pl/problemset/problem/VwDLJhYqi1z_sZrb2NyfvQ5e/site/?key=statement)」**

Bartie and his friends compete in the Team Programming Contest. There are $ n $ contestants on each team, and each team has access to $ n $ computers. The contest lasts $ t $ minutes, during which the contestants are to solve $ m $ programming problems. Furthermore, penalties are imposed on the teams: solving a problem $ s $ minutes since the beginning of the contest amounts to $ s $ penal points. The team that solved the most problems wins the contest, with ties broken in favour of the team with smaller penalty.

On the contest day Bartie quickly glances over the problem statements and distributes them among his teammates. He knows his team so well that he can exactly assess who is able to solve which problem. Solving any problem takes any contestant that is able to solve it exactly $ r $ minutes of using the computer.

Bartie's team did not fare well in this year's contest. Bartie is obsessed with the thought that it might be his fault, due to wrong decisions regarding the distribution of problems. He asks you to write a program that, given what Bartie knew at the beginning of the contest, determines the best possible result of Bytie's team, together with the assignment of problems to team members that attains the result.

# 输入格式

Five integers $ n, m, r, t $ and $ k $ ($ 1 \le n, m \le 500 $, $ 1 \le r, t \le 1000000 $) are given in the first line of the standard input, separated by single spaces. These denote, respectively: the number of contestants on a team, the number of problems, the time it takes a contestant to solve a problem, the duration of the contest, and the number of contestant-problem pairs given on the input. Each of the following $ k $ lines holds two integers $ a $ and $ b $ ($ 1 \le a \le n $, $ 1 \le b \le m$), separated by a single space, denoting that the contestant $ a $ is able to solve the problem $ b $. Each such pair appears at most once in the input.

In tests worth at least $ 30\% $ of the points it additionally holds that $ n, m \le 100 $.


# 输出格式

In the first line of the standard output the best possible result of Bytie's team should be printed as two numbers separated by a single space: the number of solved problems $ z $ and the total penal points. An exemplary assignment of problems that attains this result should be given in the following $ z $ lines. Each of those should hold three integers $ a $, $ b $ and $ c $ ($ 1 \le a \le n $, $ 1 \le b \le m $, $ 0 \le c \le t-r $), separated by single spaces, signifying that the contestant $ a $ should start solving the problem $ b $ at time $ c $ (the contest starts at time $ 0 $). No contestant should be assigned a problem that they cannot solve. If more that one optimal assignment exists, your program can output any of them.


# 样例

For the input data:
```plain
2 4 3 15 4
1 1
2 3
1 4
1 3
```
the correct result is:
```plain
3 12
1 4 0
2 3 0
1 1 3
```

# 数据范围与提示

Task author: Tomasz Idziaszek.  
SPJ: ceba

