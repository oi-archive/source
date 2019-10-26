
# Content

In order to get from one of the $F (1 \leq F \leq 5,000)$ grazing fields (which are numbered $1 \cdots F$) to another field, Bessie and the rest of the herd are forced to cross near the Tree of Rotten Apples. The cows are now tired of often being forced to take a particular path and want to build some new paths so that they will always have a choice of at least two separate routes between any pair of fields. They currently have at least one route between each pair of fields and want to have at least two. Of course, they can only travel on Official Paths when they move from one field to another. 

Given a description of the current set of $R (F-1 \leq R \leq 10,000)$ paths that each connect exactly two different fields, determine the minimum number of new paths (each of which connects exactly two fields) that must be built so that there are at least two separate routes between any pair of fields. Routes are considered separate if they use none of the same paths, even if they visit the same intermediate field along the way. 

There might already be more than one paths between the same pair of fields, and you may also build a new path that connects the same fields as some other path.

# Standard Input

Line $1$: Two space-separated integers: $F$ and $R$ 

Lines $2 \cdots R+1$: Each line contains two space-separated integers which are the fields at the endpoints of some path.

# Standard Output

Line $1$: A single integer that is the number of new paths that must be built.

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
<tr><td>7 7
1 2
2 3
3 4
2 5
4 5
5 6
5 7</td><td>2</td></tr></table>


# Constraints



# Note

#####Explanation of the sample: 

One visualization of the paths is: 

![title](/source/lutece/redundant-paths/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMjYxLzIwMTQwMzE4MjAxNzI2NTA5MjAucG5n.png)

Building new paths from $1$ to $6$ and from $4$ to $7$ satisfies the conditions.

![title](/source/lutece/redundant-paths/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMjYxLzIwMTQwMzE4MjAxNzQ2ODg2MjEucG5n.png)

Check some of the routes: 
1. $1 – 2: 1 –> 2$ and $1 –> 6 –> 5 –> 2$ 
2. $1 – 4: 1 –> 2 –> 3 –> 4$ and $1 –> 6 –> 5 –> 4 $
3. $3 – 7: 3 –> 4 –> 7$ and $3 –> 2 –> 5 –> 7 $
Every pair of fields is, in fact, connected by two routes. 

It's possible that adding some other path will also solve the problem (like one from $6$ to $7$). Adding two paths, however, is the minimum

# Source


