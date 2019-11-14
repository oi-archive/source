
# Content

Paul Erdos$(1913-1996)$ is a legendary mathematician of the $20$th century. Famous for his eccentric living style, Erdos was one of the most prolific publishers of papers in mathematical history, having written around $1500$ mathematical articles, mostly with co-authors. Erdos spent most of his lifetime traveling between scientific conferences and visiting homes of colleagues all over the world, with most of his belongings in a suitcase. He would typically show up at a colleague's doorstep and announce `my brain is open`, staying long enough to collaborate on a few papers before moving on a few days later. In many cases, he would ask the current collaborator whom he should visit next.

Because of his prolific output, friends created the Erdos number as a humorous tribute, which has been a part of the folklore of mathematicians throughout the world for many years. Erdos himself is assigned the Erdos number of $0$. Those who have co-written a paper with Erdos have an Erdos number of $1$. In turn, authors who have collaborated with those whose Erdos number is $1$(but not with Erdos himself) have an Erdos number of $2$. In general, if the lowest Erdos number of the cowriters of an author is $S$, then his Erdos number is $S+1$. A person with no such coauthorship chain connecting to Erdos has an infinite Erdos number.

![.*](/source/lutece/erdos-number/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNzYvMjAxNDAxMTMwMjQxMjcyNjExLmdpZg==.gif)

For example, in the picture above, the lady collaborates with Erdos on one paper, and then with the man on the right on another, so this man is given an Erdos number of $2$(assuming he has never collaborated with Erdos himself).

The interesting thing with Erdos number is that about $90\%$ of the world's active mathematicians have an Erdos number smaller than $8$, and many mathematicians have an Erdos number surprisingly smaller than they expect. For example, Andrew Wiles, who have proved the Fermat's Last Theorem and whose research area is very different from that of Erdos, has an Erdos number of only $3$. All Fields prize winners have an Erdos number at most $5$ and all Wolf prize winners' Erdos numbers do not exceed $6$. In addition, a very large number of non-mathematicians also have finite Erdos numbers. For example, Albert Einstein has an Erdos number of $2$ and Bill Gates has an Erdos number of $4$.

Your task is, given a list of co-writing activities of authors, to answer a series of queries according to the list, which have the form: `What is the Erdos number of author A?`

# Standard Input

The first line of the input file is an integer $N$, number of co-authoring activities. The next $N$ lines each contain two names, separated with spaces, meaning these two authors have co-written a paper. On the next line is an integer $M$, number of queries. The next $M$ lines each contain the name of an author.

$N \leq 50000, M \leq 50000$

Notes

* Names contain letters(`A`-`Z`, `a`-`z`) and `.` only and don't contain white spaces. 

* Each name has at most $20$ characters.

* Names are case-sensitive, e.g. Erdos is not the same person as erdos. 

* Authors with the same name should be considered the same person. 

* Paul Erdos himself is represented with exactly the name `Erdos`. 

* The same co-authoring activity is listed at most once. 

* No author will be co-authoring with himself.

# Standard Output

For each query, output the corresponding author's Erdos number on a line. If the author doesn't have a finite Erdos number, output `infinity` instead(quotes for clarity only).

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
<tr><td>7
Erdos Andrew.Odlyzko
Andrew.Odlyzko Chris.M.Skinner
Chris.M.Skinner Andrew.Wiles
Erdos Pavol.Hell
Pavol.Hell Xiao.Tie.Deng
Xiao.Tie.Deng Chris.Papadimitriou
Chris.Papadimitriou Bill.Gates
3
Andrew.Wiles
Bill.Gates
Albert.Einstein</td><td>3
4
infinity</td></tr></table>


# Constraints



# Note

Although Albert Einstein’s Erdos number is $2$ in the real world, he doesn't have a finite Erdos number according to the list.

# Source


