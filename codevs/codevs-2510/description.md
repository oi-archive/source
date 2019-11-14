<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Our recycling company is about to process waste that comes in railway wagons. There are N wagons waiting on <br>the incoming railway track, and each wagon contains exactly one type of waste. Waste is processed according to one <br>of a fixed number of settings. For each setting we are given the set of waste types that can be processed with this <br>setting. Sadly, changing the setting is a very time-consuming operation, therefore the company uses one setting a day. <br>The wagons are to be processed in the order they arrive on the incoming railway track. To speed up recycling, the <br>company has built an auxiliary track as shown on the <br>figure below. This way, if the next wagon contains waste that cannot be processed with the current <br>setting, then it can be moved to the auxiliary track, preceding the wagons that are already there. The next wagon to be processed is the first in row from either the incoming track or the auxiliary track. Mind that <br>no wagon can be moved back from the auxiliary to the incoming track. The company wants to recycle as <br>many wagons of waste as possible within the next three days. At the end of the third day the auxiliary <br>track must be empty.</p>
<p>Task <br>You are to write a program that computes settings for the three days, that allows the processing of the highest <br>number of wagons with leaving the auxiliary track empty. If all the wagons can be processed in fewer than three days, <br>then your program must give a solution with the smallest number of days.</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>The first line of the input contains three integers, N (1 ≤ N ≤ 20 000) is the number of wagons, K (1 ≤ K ≤ 1000) is <br>the number of waste types, and S (1 ≤ S ≤ 1000) is the number of settings. Wagons are numbered from 1 to N, waste <br>types are numbered from 1 to K and settings are numbered from 1 to S. The next S lines contain the description of the <br>settings. The (i+1)th line of the input contains a space-separated list of integers terminated by a 0, the set of waste <br>types that can be processed with setting i,. The last line is a list of N integers describing the wagons: the ith number is <br>the identifier of the type of the waste contained in wagon i. For each type x there is at least one and at most 10 settings <br>that contain waste of that type.</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>The first line of the output contains one integer, the maximum number of wagons that can be processed. The <br />second line of the output contains three integers separated by space, the setting for the first, the second and the third <br />day. If two days are enough for processing all wagons then the third number must be 0. Similarly, if one day is enough <br />then the second number must also be 0. If there are multiple solutions, your program should output only one; it does <br />not matter which one.</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>13 5 4 <br>1 0 <br>4 5 0 <br>5 3 0 <br>2 5 0 <br>4 5 2 5 5 4 1 1 5 4 5 3 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>11 <br>2 1 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>In 50% of the test cases N is at most 10 000 and S is at most 300. <br>If only the first line is correct then 40% of the points are awarded.</p>
</div>
</div>