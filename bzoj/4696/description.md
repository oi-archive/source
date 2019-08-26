
# Description

<div class="content"><div>
<div>红学姐和黄学长是好朋友。</div>
<div>红学姐有一只宠物，叫魔法猪。黄学长也有一只宠物，叫小奇。有一天，小奇来到了一个古老的文明的遗址上。这</div>
<div>个文明曾经的统治者被称作“战狂”，他生前有一千万士兵。这片土地被划分成 n×m 个正方形方块，初始时小奇</div>
<div>在(1,1)这个方块中。而在(n,m)这个方块中有一个远古遗迹。当小奇在(i,j)时，它分别有Pi,j,1 ,Pi,j,2 ,Pi,j,</div>
<div>3 ,Pi,j,4 的概率移动到(i-1,j),(i,j+1),(i+1,j),(i,j-1)。此外，在一些格子中存在“蛮子”，如果小奇走到</div>
<div>蛮子所在的格子里，它会被蛮子生吃掉。当小奇得到远古遗迹时，它就会停止移动，并让魔法猪把它传送走（当然</div>
<div>如果它被蛮子吃了也会停止移动）。小奇想知道它得到远古遗迹的概率，被蛮子吃掉的概率以及再也停不下来的概</div>
<div>率。</div>
<div></div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行包含两个整数 n，m，其值均小于等于40</div>
<div>接下来 n*m 行按上题的编号顺序依次表示每个格子。每行 5 个数，第一个数为 0 表示没有蛮子，为 1 表示有蛮</div>
<div>子，后面 4 个数（至多小数点后 1 位）表示 Pi,j,1 ,Pi,j,2 ,Pi,j,3 ,Pi,j,4 。保证(1,1)和(n,m)没有蛮子。</div>
<div></div>
</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>
<div>输出三行，每行一个实数，分别表示小奇得到远古遗迹的概率，被蛮子吃掉的概率以及再也停不下来的概率。保留</div>
<div> 4 位小数。</div>
<div></div>
</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 3<br/>
0 0 0.2 0.8 0<br/>
0 0 0.3 0.7 0<br/>
0 0 0 0.5 0.5<br/>
0 0 0.2 0.8 0<br/>
0 0.2 0.8 0 0<br/>
0 1 0 0 0<br/>
0 0 1 0 0<br/>
0 0.3 0.4 0.3 0<br/>
0 0 0 1 0<br/>
1 0 1 0 0<br/>
0 0 0.7 0 0.3<br/>
0 1 0 0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.3904<br/>
0.0576<br/>
0.5520</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

