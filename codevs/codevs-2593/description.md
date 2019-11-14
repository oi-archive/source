<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Agri-Net</p>
<p>Farmer John has been elected mayor of his town! One of his campaignpromises was to bring internet connectivity to all farms in the area.He needs your help, of course. </p>
<p>Farmer John ordered a high speed connection for his farm and is goingto share his connectivity with the other farmers. To minimize cost, hewants to lay the minimum amount of optical fiber to connect his farm toall the other farms. </p>
<p>Given a list of how much fiber it takes to connect each pair of farms,you must find the minimum amount of fiber needed to connect them alltogether. Each farm must connect to some other farm such that a packetcan flow from any one farm to any other farm. </p>
<p>The distance between any two farms will not exceed 100,000. </p>
<p>PROGRAM NAME: agrinet<br><br><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>INPUT FORMAT<br>Line 1: The number of farms, N (3 &lt;= N &lt;= 100). <br>Line 2..end: The subsequent lines contain the N x N connectivitymatrix, where each element shows the distance from on farm to another.Logically, they are N lines of N space-separated integers. Physically,they are limited in length to 80 characters, so some lines continueonto others. Of course, the diagonal will be 0, since the distance fromfarm i to itself is not interesting for this problem. <br><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>OUTPUT FORMAT<br />The single output contains the integer length that is the sum of theminimum length of fiber required to connect the entire set of farms.</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4<br>0 4 9 21<br>4 0 8 17<br>9 8 0 16<br>21 17 16 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>28</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>The number of farms, N (3 &lt;= N &lt;= 100).</p>
</div>
</div>