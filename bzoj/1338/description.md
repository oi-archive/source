
# Description

<div class="content">You are given N points in the xy-plane. You have a circle of radius one and move it on the xy-plane, so as to enclose as many of the points as possible. Find how many points can be simultaneously enclosed at the maximum. A point is considered enclosed by a circle when it is inside or on the circle. 


Fig 1. Circle and Points 


平面上N个点，用一个半径R的圆去覆盖，最多能覆盖多少个点？ 

</div>

# Input

<div class="content">The input consists of a series of data sets, followed by a single line only containing a single character &#39;0&#39;, which indicates the end of the input. Each data set begins with a line containing an integer N, which indicates the number of points in the data set. It is followed by N lines describing the coordinates of the points. Each of the N lines has two decimal fractions X and Y, describing the x- and y-coordinates of a point, respectively. They are given with five digits after the decimal point. 

You may assume 1 &lt;= N &lt;= 300, 0.0 &lt;= X &lt;= 10.0, and 0.0 &lt;= Y &lt;= 10.0. No two points are closer than 0.0001. No two points in a data set are approximately at a distance of 2.0. More precisely, for any two points in a data set, the distance d between the two never satisfies 1.9999 &lt;= d &lt;= 2.0001. Finally, no three points in a data set are simultaneously very close to a single circle of radius one. More precisely, let P1, P2, and P3 be any three points in a data set, and d1, d2, and d3 the distances from an arbitrarily selected point in the xy-plane to each of them respectively. Then it never simultaneously holds that 0.9999 &lt;= di &lt;= 1.0001 (i = 1, 2, 3). 



</div>

# Output

<div class="content">For each data set, print a single line containing the maximum number of points in the data set that can be simultaneously enclosed by a circle of radius one. No other characters including leading and trailing spaces should be printed. 
</div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
6.47634 7.69628<br/>
5.16828 4.79915<br/>
6.69533 6.20378<br/>
6<br/>
7.15296 4.08328<br/>
6.50827 2.69466<br/>
5.91219 3.86661<br/>
5.29853 4.16097<br/>
6.10838 3.46039<br/>
6.34060 2.41599<br/>
8<br/>
7.90650 4.01746<br/>
4.10998 4.18354<br/>
4.67289 4.01887<br/>
6.33885 4.28388<br/>
4.98106 3.82728<br/>
5.12379 5.16473<br/>
7.84664 4.67693<br/>
4.02776 3.87990<br/>
20<br/>
6.65128 5.47490<br/>
6.42743 6.26189<br/>
6.35864 4.61611<br/>
6.59020 4.54228<br/>
4.43967 5.70059<br/>
4.38226 5.70536<br/>
5.50755 6.18163<br/>
7.41971 6.13668<br/>
6.71936 3.04496<br/>
5.61832 4.23857<br/>
5.99424 4.29328<br/>
5.60961 4.32998<br/>
6.82242 5.79683<br/>
5.44693 3.82724<br/>
6.70906 3.65736<br/>
7.89087 5.68000<br/>
6.23300 4.59530<br/>
5.92401 4.92329<br/>
6.24168 3.81389<br/>
6.22671 3.62210<br/>
0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
5<br/>
5<br/>
11<br/>
<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

