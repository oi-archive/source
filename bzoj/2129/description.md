
# Description

<div class="content"><p>scp大老板最近喜事连连，决定到高一一班发放喜糖。scp大老板是个投掷高手，每次投掷的喜糖有个中心座位(x,y)，这个座位将会投掷到k颗喜糖，而所有与这个中心点的曼哈顿距离小于k的座位都会被投掷到(k-它与中心点的曼哈顿距离)颗喜糖(即他的投掷范围是个45度倾斜的正方形，数据保证这个投掷范围的边界均在座位表以内)。而每个人对于糖果有自己的喜悦值t，每得到一颗糖果，这个人就能收获t的喜悦值。现在scp大老板想知道，对于每次投掷喜糖，班级里的喜悦值总和是多少。 糖果的投掷范围如上图所示。</p></div>

# Input

<div class="content"><p>（由于数据要求小于5M，本题中输入的t矩阵和v矩阵都将由如下规则生成。对于某个矩阵f，f[i,j]=a[i mod pa +1]+b[i mod pb +1]+c[i mod pc +1]+a[j mod pa +1]+ b[j mod pb +1]+c[j mod pc +1]）输入的第一行的第一个正整数为pa，接下来pa个数为a[1..pa] 输入的第二行的第一个正整数为pb，接下来pb个数为b[1..pb] 输入的第三行的第一个正整数为pc，接下来pc个数为c[1..pc] 输入的第四行包含两个整数n,m,p表示v矩阵的大小为n*m。 v矩阵，表示座位在第i行第j列的同学对糖的喜悦值为v[i,j] mod p +1。接下来一行包含一个整数q表示t矩阵的大小为q*3。 t矩阵的每一行的三个数x,y,k,令nx= x mod n +1，ny= y mod m +1，表示询问以(nx,ny)为中心座位,以k mod min(nx,ny,n-nx+1,m-ny+1) +1为哈密顿距离的喜悦值总和。</p></div>

# Output

<div class="content"><p>输出一个整数，表示所有询问的答案的异或和。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 11 3 4<br/>
5 10 6 7 2 6<br/>
7 2 6 9 7 1 2 11<br/>
5 5 11<br/>
10<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
【数据规模】<br/>
对于100%以内的数据，n,m&lt;=600 q&lt;=360000 pa,pb,pc&lt;3000 输入数据中的所有数字小于等于100007。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

