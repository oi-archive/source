
# Content

Kufeng is fond of circles. He builds a big machine which deal with circles and points.

There are m points on a `XOY` plane. 
The points' position may coincide. 
Kufeng also has n circles, the position of each circle's center, as long as the initial radius of each circle are given to you.

Each point and each circle has a unique id, the id will also given.

Each time, Kufeng can operate the machine, and he can add or delete a circle or point on the plane. 
If he adds a new circle or point, he gives that circle or point a new id, which will be different from all ids before, or he can delete a circle or point, in that case he just delete it forever.

The points give energy to the circles, the total energy for a circle is the number of points that strictly lie inside that circle. A point might serve energy to more than one circle.

At some time, Kufeng wants to know the total energy of a certain circle.

Because Kufeng's special sense of beauty, it is guaranteed that the circumference of all the circles given in the input(including the original ones and the added ones) will not intersect with each other, not even touch with each other.

# Standard Input

The first line of the input contains two numbers $n$ and $m$, 
the number of circles and the number of points that is originally on the plane. ($1\leq n\leq 10000$, $1\leq m\leq 10000$)

The next $n$ lines each with four numbers $id_i,x_i,y_i,r_i$, 
which means there is a circle on the plane with id as $id_i$, 
with center located at $(x_i,y_i)$, and with radius length $r_i$. ($-10000\leq x_i,y_i\leq 10000, 1\leq r_i\leq 10000$)

The next $m$ lines each with three numbers $id_i, px_i,py_i$, which means there is point on the plane with id as $id_i$, 
and located at $(px\_i,py\_i)$. ($-10000\leq px\_i,py\_i\leq 10000$)

The next lines contain a number $q$, the number of operations Kufeng will do. ($1\leq q\leq 100000$)
The next $q$ lines each can be given in the following two types:

* `1 id x y r`: Kufeng will add a new circle on the plane, with id as $id$, the centre located at $(x, y)$, with radius as $r$.
* `2 id x y`: Kufeng will add a new point on the plane, with id as $id$, the centre located at $(x, y)$.
* `3 id`: Kufeng will delete the circle or point with id as $id$.
* `4 id`: Kufeng has a question for you. If the $id$ correspond to a circle, output its total energy, otherwise output the number of circles the point serve energy to.

No circles or points will share a same id. All the numbers given in input are integers.

All the ids will be postive and will not exceed 150000.

# Standard Output

For each type of $4$ id, output the answer on a single line.

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
<tr><td>1 1
1 1 1 2
2 0 1
6
4 1
4 2
2 3 2 1
4 1
3 3
4 1</td><td>1
1
2
1</td></tr></table>


# Constraints



# Note



# Source


