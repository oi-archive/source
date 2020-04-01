
# Description

<div class="content"><div>Your fancy debugger will not help you in this matter. There are many ways in which code can produce different behavior between debug and release builds, and when this happens, one may have to resort to more primitive forms of debugging.</div>
<div>So you and your printf are now on your own in the search for a line of code that causes the release build to crash. Still you are lucky: adding printf statements to this program affects neither the bug (it still crashes at the same original code line) nor the execution time (at least not notably). So even the naive approach of putting a printf statement before each line, running the program until it crashes, and checking the last printed line, would work.</div>
<div></div>
<div>However, it takes some time to add each printf statement to the code, and the program may have a lot of lines. So perhaps a better plan would involve putting a printf statement in the middle of the program, letting it run, seeing whether it crashes before the added line, and then continuing the search in either the first or second half of the code.</div>
<div></div>
<div>But then again, running the program may take a lot of time, so the most time-efficient strategy might be something in between. Write a program that computes the minimum worst-case time to find the crashing line (no matter where it is), assuming you choose an optimal strategy for placing your printf statements.</div>
<div></div>
<div>We&#39;re releasing the new version in five hours, so this issue is escalated and needs to be fixed ASAP.</div>
<div></div>
<div>Input</div>
<div>The input consists of one line with three integers:</div>
<div></div>
<div>n ( 1≤n≤106 ), the number of code lines;</div>
<div>r ( 1≤r≤109 ), the amount of time it takes to compile and run the program until it crashes;</div>
<div>p ( 1≤p≤109 ), the time it takes to add a single printf line.</div>
<div>You have already run the program once and therefore already know that it does crash somewhere.</div>
<div></div>
<div>Output</div>
<div>Output the worst-case time to find the crashing line when using an optimal strategy.</div>
<div></div>
<div>你看中的调试器将不会在这件事上帮助你。有代码可以通过多种方式在调试与正式发布的间隙发生不同的行为，当出现这种情况，我们可能不得不求助于更原始的调试方式。</div>
<div>所以，你和你的printf现在在寻求一行导致该发布版本崩溃的代码。幸运的是：增加printf语句到程序里，既不会制造bug（仍然崩溃在同一原始的代码行），也没有影响执行时间（至少不显著）。 因此，即使在每行前加一个printf语句，运行程序，直到它崩溃，并检查最后打印行。</div>
<div>然而，它需要一些时间来添加每个printf语句到代码，并且该程序可以具有很多行。</div>
<div>因此，把一个printf语句在程序的中间或许是一个更好的计划，让它运行，观察它是否在加入行前崩溃，然后继续在代码的前一或后一半寻找。</div>
<div>不过话又说回来，运行程序可能需要很多时间，所以时效最优的策略可能是介于两者之间。</div>
<div>编写计算最坏情况下的最小时间来寻找崩溃行（无论它在哪里），认为你选择最优的加printf语句策略。</div>
<div>我们在5小时内发布新的版本，所以这个问题十分严重，需要尽快解决。</div>
<p></p></div>

# Input

<div class="content"><div>输入包括一行三个整数：</div>
<div>n（1≤n≤10^6），代码行的数目;</div>
<div>r（1≤r≤10^9），编译和运行程序直到它崩溃的时间量;</div>
<div>p（1≤p≤10^9），增加单个的printf行所花费的时间。</div>
<div>您已经运行一次程序，因此已经知道它崩溃的地方。</div>
<p></p></div>

# Output

<div class="content"><div>输出的最坏情况使用最优策略找到崩溃行的时间。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">Sample Input 1	<br/>
1 100 20 <br/>
Sample Input 2	<br/>
10 10 1 <br/>
Sample Input 3	<br/>
16 1 10</span></div>

# Sample Output

<div class="content"><span class="sampledata">Sample Output 1<br/>
0<br/>
Sample Output 2<br/>
19<br/>
Sample Output 3<br/>
44<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

