# 

 
 # 题目描述 
<p>
在二维网格平面上有许多机器人在移动。每个机器人的状态由它所在的位置和面向的方位确定。每个机器人按照各自固定的指令执行移动。位置由一对整数(x, y)表示。机器人的方向有4个，用角度表示，分别是0，90，180，270。命令有两种，转身和移动。转身命令有一个参数D，是90，180或270，机器人当前的方向改变D个度数，C度将变为(C&nbsp;+&nbsp;D)&nbsp;mod&nbsp;360。移动指令没有参数，机器人将按它的方向前进一个单位。0方向的移动，位置改变（1，0），方向90改变（0，1），方向180改变（-1，0），方向270改变（0，-1）。<br>一个机器人依次完成它自己的指令序列。序列执行完后机器人将停在最终的位置上。<br>两个机器人之间的行动不互相影响，同一个位置可以有多个机器人。<br>在机器人开始移动前，可以去掉一些指令，所以控制中心可以改变机器人的行动路线和最终位置。控制中心希望使所有的机器人最后到达同一个位置以进行检查。同时希望能够在去掉最少的指令情况下完成这个目标。<br>任务：<br>共有R(2&nbsp;<=&nbsp;R&nbsp;<=&nbsp;10)个机器人。每个机器人有它的初始位置，初始方向和命令序列。命令序列长度不超过50。计算需要去掉的最少的命令数<br></p> 

 
 # 输入格式 
<p>
Input data should be read from the file robots.in. The first line of the file contains <br>integer R (2 ≤ R ≤ 10) – the number of robots. Then R sections of lines follow. Each <br>section describes one robot. The first line of the section contains four integers, <br>separated by single spaces: x, y – initial robot position (x, y), initial robot direction C <br>(C = 0, 90, 180, or 270) and  the  length of  robot’s command  sequence n  (1 ≤ n ≤ 50). <br>Then the section contains n lines describing the sequence of commands, one <br>command per line. The line of the step command contains single character S in the <br>first position and the line of the turn command contains character  T in the first <br>position that is followed by turn parameter – integer D (D = 90, 180 or 270) and is <br>separated by a single space</p> 

 
 # 输出格式 
<p>
需要去掉的最少的命令数<br></p> 

 
 # 提示 
<p>
There are 2 moving robots. The first robot has initial position (2, 0), direction 270 and a <br>sequence of 5 commands. The second one has initial position (1, -1), direction 0 and a <br>sequence of 8 commands. The minimum total number of commands to be removed that <br>makes robots share final position is 2: for example, remove the 3-rd command of the <br>first robot and the 5-th command of the second robot. The common final position in <br>that case is (2, 1). </p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>2 
2 0 270 5 
S 
T 180 
S 
S 
S 
1 -1 0 8 
S 
S 
T 90 
S 
T 270 
S 
T 90 
S </td><td>2</td></tr></table>
