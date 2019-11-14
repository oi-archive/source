
# Content

The most mysterious organization in Chani is “Related Department”. It is related to almost everything, and has branches almost everywhere. Events always have relation with it. Whenever disasters happen, “Related Department” would stand out to commit its responsibility. The members of “Related Department” are called “Related person”. However, ordinary people have no idea about who is “Related person” since their information is national secret.

Xiaoming is the top typist in Chani. The legend is that he could type $400$ words per minute. Today he accepted an order from a man who said that he is a “Related person”. That “Related person” asked Xiaoming to turn many paper documents into electronic files. For reasons of security, Xiaoming has to use a special device which has limited functions. With the special device, Xiaoming can only perform such operations:
1. Creating a new file. It takes a quite short time that we ignore the time for it.
2. Replacing current file with some file finished before. A file is allowed to be used to replace another one only after it is finished and won’t be edited later.
3. Deleting any letter(s) in current file.
4. Inserting letter(s) at arbitrary position in current file.

Note that, the keyboard for this device is so strange that the time for typing different letter may be different.

Xiaoming is somewhat afraid of dealing with “Related person”, so he wants to accomplish this order as soon as possible. Knowing time needed for each operation, Xiaoming is trying to make the best plan which spends the minimum time.

# Standard Input

The first line of the input is $T$ (no more than $50$), which stands for the number of test cases you need to solve.

Each case begins with two integers, repCost and delCost ($1 \leq repCost, delCost \leq 50$), time needed to replace current file, time for deleting one letter. On the second line, there are $26$ numbers representing the time for typing each letter from `a` to `z`, each number is between $1$ and $50$.

Then a line with an integer $N$ ($1 \leq N \leq 50$) is given indicating the number of files.

$N$ lines followed. Each line gives a string only consisting of letters `a`-`z` to represent a file. The maximum length of the strings is not greater than $50$.

# Standard Output

For every test case, you should output `"Case #k: c` in a line, where $k$ indicates the case number and counts from $1$, $c$ is the minimum time needed.

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
<tr><td>2
1 1
1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1
2
aaab
aaaa
10 10
1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1
2
aaab
aaaa</td><td>Case #1: 7
Case #2: 8</td></tr></table>


# Constraints



# Note

* Case #$1$, we can type $4$ `a`'s in one file, it takes $4$ unit time. Then creating a new file and replace it with file containing `aaaa`, it takes $1$ unit time. Finally delete a letter `a` and insert a letter `b` which takes $2$ unit time. The total time needed is $4 + 1 + 2 = 7$ unit time.
* Case #$2$, it would be more efficient to type the letters directly in two files, because replacing and deleting operation are costly.

# Source


