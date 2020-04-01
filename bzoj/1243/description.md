
# Description

<div class="content">我们可以用三个正整数x y z来描述一个等差数列：x，x+z，x+2z，…，x+kz(x+kz≤y，x+(k+1)z&gt;y)。
给定n个这种形式的等差数列，并且告诉你，在所有的正整数中，最多只有一个数字出现在奇数个等差数列中。你需要算出这个数字是多少，或者不存在,如果存在请输出这个数字是多少及它出现的次数
</div>

# Input

<div class="content">Input file consists from multiple data sets separated by one or more empty lines.
Each data set represents a sequence of 32-bit (positive) integers (references) which are stored in compressed way.
Each line of input set consists from three single space separated 32-bit (positive) integers X Y Z and they represent following sequence of references: X, X+Z, X+2*Z, X+3*Z, …, X+K*Z, …(while (X+K*Z)&lt;=Y).
Your task is to data-mine input data and for each set determine weather data were corrupted, which reference is occurring odd number of times, and count that reference.</div>

# Output

<div class="content">For each input data set you should print to standard output new line of text with either “no corruption” (low case) or two integers separated by single space (first one is reference that occurs odd number of times and second one is count of that reference).</div>

# Sample Input

<div class="content"><span class="sampledata">1 10 1<br/>
2 10 1<br/>
<br/>
1 10 1<br/>
1 10 1<br/>
<br/>
1 10 1<br/>
4 4 1<br/>
1 5 1<br/>
6 10 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 1<br/>
no corruption<br/>
4 3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

