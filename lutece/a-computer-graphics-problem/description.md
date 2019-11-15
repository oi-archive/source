
# Content

In this problem we talk about the study of Computer Graphics. Of course, this is very, very hard.

We have designed a new mobile phone, your task is to write a interface to display battery powers.

Here we use `.` as empty grids.

When the battery is empty, the interface will look like this:

```
*------------*
|............|
|............|
|............|
|............|
|............|
|............|
|............|
|............|
|............|
|............|
*------------*
```

When the battery is $60\%$ full, the interface will look like this:

```
*------------*
|............|
|............|
|............|
|............|
|------------|
|------------|
|------------|
|------------|
|------------|
|------------|
*------------*
```

Each line there are $14$ characters.

Given the battery power the mobile phone left, say $x\%$, your task is to output the corresponding interface. Here $x$ will always be a multiple of $10$, and never exceeds $100$.

# Standard Input

The first line has a number $T$ ($T\leq 10$) , indicating the number of test cases.

For each test case there is a single line with a number $x$. ($0 \leq x \leq 100$, $x$ is a multiple of $10$)

# Standard Output

For test case $X$, output `Case #X: ` at the first line. Then output the corresponding interface. See sample output for more details.

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
0
60</td><td>Case #1:
*------------*
|............|
|............|
|............|
|............|
|............|
|............|
|............|
|............|
|............|
|............|
*------------*
Case #2:
*------------*
|............|
|............|
|............|
|............|
|------------|
|------------|
|------------|
|------------|
|------------|
|------------|
*------------*</td></tr></table>


# Constraints



# Note



# Source


