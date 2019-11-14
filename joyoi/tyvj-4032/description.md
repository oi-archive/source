# 

 
 # 题目背景 
<hr />
<p><span style="line-height: 1.6em;">在一个夜黑风高，伸手不见五指的深夜，睡梦中的林月如突然听到房外一阵躁动。她出去一看，发现一个女飞贼抢了一个古董商的包袱。</span></p>

<p>&quot;站住！&quot;<br />
&quot;那你为什么不来追我？&quot;<br />
&quot;因为程序设计，在李大哥来之前，我不能追你。&quot;<br />
&quot;那李逍遥为什么不来呢？&quot;<br />
&quot;大概程序出bug了吧&quot;<br />
&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;<br />
终于，在登了一个又一个时辰后，林月如终于忍不住了，开始向女飞贼发起进攻。</p>

<p>&quot;喂！你为什么可以动？？？&quot;<br />
&quot;这大概也是一个bug吧！&quot;<br />
&quot;不公平啊！&quot;<br />
&quot;废话少说。&quot;</p> 

 
 # 题目描述 
<p>&nbsp;&nbsp;已知林月如和女飞贼站在一个矩阵中，矩阵中有某些障碍物不可穿越。月如使出的铜钱镖可攻击8个方向，但不可穿越障碍物（可视为不能穿墙的重狙）。每个单位时间，月如可向上下左右4个方向移动一格，攻击不浪费时间。当然，月如想尽快结束这场无聊的战斗，所以她想在最短的时间内消灭女飞贼。</p> 

 
 # 输入格式 
<p>采用文件输入输出，输入文件&#39;input.txt&#39;,输出文件&#39;output.txt&#39;。</p>

<p>第一行为2个数N,M表示矩阵的规模(N为高,M为宽)。</p>

<p>接下来是N*M的矩阵,O表示空地,X表示障碍物。</p>

<p>下面是若干行数据，每行为一对数据，分别是女飞贼的位置和林月如的位置，显然她们都不可能在障碍物上。</p>

<p>以&quot;0&nbsp;0&nbsp;0&nbsp;0&quot;为输入结束标志。</p> 

 
 # 输出格式 
<p>每一组数据输出一行，仅一个整数，表示能消灭掉女飞贼的最短时间。</p>

<p>显然若能直接打到女飞贼，则时间为0。</p>

<p>若无法消灭，则输出&quot;Impossible!&quot;。（不含引号）</p> 
