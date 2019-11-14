
# Description

<div class="content"><p><span style="font-size: medium">The widget factory produces several different kinds of widgets. Each widget is carefully built by a skilled widgeteer. The time required to build a widget depends on its type: the simple widgets need only 3 days, but the most complex ones may need as many as 9 days. The factory is currently in a state of complete chaos: recently, the factory has been bought by a new owner, and the new director has fired almost everyone. The new staff know almost nothing about building widgets, and it seems that no one remembers how many days are required to build each diofferent type of widget. This is very embarrassing when a client orders widgets and the factory cannot tell the client how many days are needed to produce the required goods. Fortunately, there are records that say for each widgeteer the date when he started working at the factory, the date when he was fired and what types of widgets he built. The problem is that the record does not say the exact date of starting and leaving the job, only the day of the week. Nevertheless, even this information might be helpful in certain cases: for example, if a widgeteer started working on a Tuesday, built a Type 41 widget, and was fired on a Friday,then we know that it takes 4 days to build a Type 41 widget. Your task is to figure out from these records (if possible) the number of days that are required to build the different types of widgets. </span></p>
<p></p>
<p><span style="font-size: medium">  </span></p>
<div v:shape="_x0000_s1026"><span style="font-size: medium">制作n种小玩具需要3-9天的时间，现在有m批由不同的玩具组成的任务的历史记录，记录里是开始和结束分别是星期几。求出每个玩具的制作时间。</span></div></div>

# Input

<div class="content"><p>The input contains several blocks of test cases. Each case begins with a line containing two integers: the number 1 ≤ n ≤ 300 of the different types, and the number 1 ≤ m ≤ 300 of the records. This line is followed by a description of the m records. Each record is described by two lines. The first line contains the total number 1 ≤ k ≤ 10000 of widgets built by this widgeteer, followed by the day of week when he/she started working and the day of the week he/she was fired. The days of the week are given bythe strings `MON&#39;, `TUE&#39;, `WED&#39;, `THU&#39;, `FRI&#39;, `SAT&#39; and `SUN&#39;. The second line contains k integers separated by spaces. These numbers are between 1 and n , and they describe the diofferent types of widgets that the widgeteer built. For example, the following two lines mean that the widgeteer started working on a Wednesday, built a Type 13 widget, a Type 18 widget, a Type 1 widget, again a Type 13 widget,and was fired on a Sunday. 4 WED SUN 13 18 1 13 Note that the widgeteers work 7 days a week, and they were working on every day between their first and last day at the factory (if you like weekends and holidays, then do not become a widgeteer!). The input is terminated by a test case with n = m = 0 . 制作n种小玩具需要3-9天的时间，现在有m批由不同的玩具组成的任务的历史记录，记录里是开始和结束分别是星期几。求出每个玩具的制作时间。</p></div>

# Output

<div class="content"><p>For each test case, you have to output a single line containing n integers separated by spaces: the number of days required to build the different types of widgets. There should be no space before the first number or after the last number, and there should be exactly one space between two numbers. If there is more than one possible solution for the problem, then write `Multiple solutions.&#39; (without the quotes). If you are sure that there is no solution consistent with the input, then write `Inconsistent data.&#39;(without the quotes).</p></div>

# Sample Input

<div class="content"><span class="sampledata">2 3<br/>
2 MON THU<br/>
1 2<br/>
3 MON FRI<br/>
1 1 2<br/>
3 MON SUN<br/>
1 2 2<br/>
10 2<br/>
1 MON TUE <br/>
3<br/>
1 MON WED<br/>
3<br/>
0 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">8 3<br/>
Inconsistent data.<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>Huge input file, &#39;scanf&#39; recommended to avoid TLE.</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Cerc2005">Cerc2005</a></p></div>

