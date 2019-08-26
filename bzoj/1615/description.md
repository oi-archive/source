
# Description

<div class="content"><p><span style="font-size: medium">Farmer John新买的干草打包机的内部结构大概算世界上最混乱的了，它不象普通的机器一样有明确的内部传动装置，而是，N (2 &lt;= N &lt;= 1050)个齿轮互相作用，每个齿轮都可能驱动着多个齿轮。 FJ记录了对于每个齿轮i，记录了它的3个参数：X_i，Y_i表示齿轮中心的位置坐标(-5000 &lt;= X_i &lt;= 5000; -5000 &lt;= Y_i &lt;= 5000)；R_i表示该齿轮的半径(3 &lt;= R_i &lt;= 800)。驱动齿轮的位置为0,0，并且FJ也知道最终的工作齿轮位于X_t,Y_t。 驱动齿轮顺时针转动，转速为10,000转/小时。你的任务是，确定传动序列中所有齿轮的转速。传动序列的定义为，能量由驱动齿轮传送到工作齿轮的过程中用到的所有齿轮的集合。对能量传送无意义的齿轮都应当被忽略。在一个半径为Rd，转速为S转/每小时的齿轮的带动下，与它相接的半径为Rx的齿轮的转速将为-S*Rd/Rx转/小时。S前的负号的意思是，一个齿轮带动的另一个齿轮的转向会与它的转向相反。 FJ只对整个传动序列中所有齿轮速度的绝对值之和感兴趣，你的任务也就相应转化成求这个值。机器中除了驱动齿轮以外的所有齿轮都被另外某个齿轮带动，并且不会出现2个不同的齿轮带动同一个齿轮的情况。 相信你能轻易地写个程序来完成这些计算:) </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* 第1行: 3个用空格隔开的整数：N，X_t，Y_t </span></p>
<p><span style="font-size: medium">* 第2..N+1行: 第i+1描述了齿轮i的位置及半径：X_i，Y_i，以及R_i</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* 第1行: 输出所有在传动中起到作用的齿轮转速的绝对值，包括驱动齿轮和 工作齿轮。只需要输出答案的整数部分 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 32 54<br/>
0 0 10<br/>
0 30 20<br/>
32 54 20<br/>
-40 30 20<br/>
<br/>
<br/>
    机器里一共有4个齿轮，位于0,0的是半径为10的驱动齿轮，它带动了位于<br/>
0,30的，半径为20的某个齿轮。这个齿轮又间接带动了位于32,54，半径为20的<br/>
工作齿轮，以及一个位于-40,30，半径同样为20的冗余的齿轮。<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">20000<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">输出说明:</span></p><br/>
<p><span style="font-size: medium">齿轮 位置  半径     转速<br/><br/>
1 (0,0)     10     10,000<br/><br/>
2 (0,30)    20     -5,000<br/><br/>
3 (32,54)   20      5,000<br/><br/>
                   ------<br/><br/>
齿轮转速绝对值之和:20,000<br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

