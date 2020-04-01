<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　In 2200 A.D., the Earth is invaded by some alien intelligent beings from Mars. We call these creatures Martians. To fight back, some scientists have invented a new weapon called super bomb.<br/>
　　Super bombs can be classified into many types. Intuitively, it costs more to produce a more powerful bomb. A super bomb that can destroy <i>K</i> city (cities) simultaneously exactly costs <i>K</i><sup>2</sup> dollars.<br/>
　　Now the commander plans to use the super bombs to devastate all <i>N</i> cities, numbered from 1 to <i>N</i>, on Mars. However, there are some one-way channels between some pairs of the cities on Mars. If there is a channel from city <i>A</i> to city <i>B</i>, then city <i>A</i> must be destroyed no later than city <i>B</i>.<br/>
　　In order to launch the attack, a plan must be prepared first. <i>A</i> plan of attack is actually a list of cities sorted by the order they will be destroyed. The cities that are destroyed simultaneously should appear consecutively in the list, while the order among them can be arbitrary.<br/>
　　For example, if we use a bomb to destroy city 1 and 2, and then another bomb to destroy city 3, 4 and 5, then the following 12 arrangements are all legal:<br/>
　　12345  12354  12435  12453  12534  12543<br/>
　　21345  21354  21435  21453  21534  21543<br/>
　　Now given the map of Mars, please find out the minimal cost needed to destroy all the cities. Besides, with the minimal cost, please find out a plan in which the number of cities between two given cities <i>A</i> and <i>B</i> is minimized.</div>
# 输入格式

<div class="pdcont">　　The first line of the input consists of four integers <i>n</i>, <i>m</i>, <i>A</i>, <i>B</i>, indicating the number of cities, the number of channels, and the cities needed in finding out the proper plan.<br/>
　　Each of the following <i>m</i> lines consists of two integers <i>a</i> and <i>b</i>, which shows that there is a channel from city <i>a</i> to city <i>b</i>.</div>
# 输出格式

<div class="pdcont">　　The output should contain one line for each case, consisting of two integers indicating the minimal cost and the minimal number of cities between the two given ones, respectively.</div>
# Sample Input One

<div class="pdcont">　　5 6 1 3<br/>
　　1 2<br/>
　　2 1<br/>
　　3 4<br/>
　　4 5<br/>
　　5 3<br/>
　　2 3</div>
# Sample Output One

<div class="pdcont">　　13 0</div>
# Sample Input Two

<div class="pdcont">　　6 8 1 5<br/>
　　1 2<br/>
　　2 1<br/>
　　3 4<br/>
　　4 3<br/>
　　5 6<br/>
　　6 5<br/>
　　2 3<br/>
　　4 5</div>
# Sample Output Two

<div class="pdcont">　　12 2</div>
# Explanations

<div class="pdcont">　　For the first sample, we destroy city 1 and 2 first, then city 3, 4 and 5. This costs us 4+9=13 dollars in total. Note that city 1 and city 3 can be adjacent in plans like 21345.<br/>
　　For the second sample, we destroy city 1 and 2 first, followed by city 3 and 4, and finally city 5 and 6. This costs us 4+4+4=12 dollars in total. There are two cities between city 1 and 5 in the plan 213456.</div>
# Constraints

<div class="pdcont">　　For all test cases, 1 ≤ <i>n</i> ≤ 20000, 1 ≤ <i>m</i> ≤ 200000.</div>

</div>