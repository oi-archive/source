
# Description

<div class="content"><p>A telecom company is developing a GSM network in the city of Vrsar. Their contract with the city specifies the minimum number of households that need to be covered by the signal. Due to budget constraints they can only build one antenna with a certain range. Since the cost is proportional to the range of the antenna, they would like to place the antenna so that the range required to meet the terms of the contract is minimized. There are N households in Vrsar, each represented by a pair of integer coordinates. The antenna can be placed at any point in the plane (not necessarily with integer coordinates) and the range of the antenna can be any positive real number. If the range of the antenna is R, then a household is covered by the signal if the distance between the antenna and the household is at most R. Write a program that, given the locations of the households and an integer K, finds the minimum range required and one possible location for the antenna so that at last K households are covered by the signal. 题目分析题目大意是给出N个点的坐标，要求能够覆盖其中至少K个点的圆的最小半径及圆心位置。</p></div>

# Input

<div class="content"><p>The first line of input contains two integers N and K (2≤K≤N≤500) – the total number of households and the minimum number of households that need to be covered by the signal. Each of the following N lines contains two integers X and Y (0≤X,Y≤10 000) – the coordinates of one household. No two households will be located at the same coordinates.</p></div>

# Output

<div class="content"><p>The first line of output should contain the minimum required range R for the antenna – a real number. The second line of output should contain the coordinates of the antenna - two real numbers X and Y. Note: If there are multiple solutions, you should output any one of them. All three numbers should be output either in standard decimal form or scientific notation. Grading Your solution will be marked correct if and only if the following two conditions ar satisfied:  The absolute difference between R and the minimum required range as determined by the jury is less than or equal to 0.0001.  The antenna with range R+0.0002 placed at coordinates (X,Y) covers at least K households.</p></div>

# Sample Input

<div class="content"><span class="sampledata">10 5 <br/>
1 8 <br/>
2 6 <br/>
4 8 <br/>
2 2 <br/>
9 7 <br/>
8 5 <br/>
5 3 <br/>
3 3 <br/>
4 6 <br/>
4 1 </span></div>

# Sample Output

<div class="content"><span class="sampledata">2.236068 <br/>
3 4 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

