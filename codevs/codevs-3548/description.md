<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>转眼就要到Karin的生日了！Yuuna她们想为她准备生日礼物！现在有许多礼物被排列成</p><p>了一个一维序列，每个礼物都有一个价值。Yuuna对这个序列十分感兴趣。因此，你需要</p><p>多次回答：在某个区间内出现次数第k1少的价值是多少，可能多个不同的价值出现</p><p>次数均为第k1少，输出其中第k2小的，保证输入合法。注意内存限制。</p><p>例如：对于一个区间而言(当然不一定是有序的):</p><p>1,2,3,4,5,5,6,6,7,7,7,7,8,8,8,8,9,9,9,9,10,10,10,10,11,11,11,11,11,11,12,12,12,12,12,12,</p><p>12,12,12,12</p><p>权值 出现次数</p><p>1 1 出现次数第1少 第1小</p><p>2 1 第2小</p><p>3 1 第3小</p><p>4 1 第4小</p><p>5 2 出现次数第2少 第1小</p><p>6 2 第2小</p><p>7 4 出现次数第3少 第1小</p><p>8 4 第2小</p><p>9 4 第3小</p><p>10 4 第4小</p><p>11 6 出现次数第4少 第1小</p><p>12 10 出现次数第5少 第1小</p><p>若k1=3，k2=2，代表询问这个区间里出现次数第3少的权值中第2小的，则应该输出8。</p><p>若k1=5，k2=1，代表询问这个区间里出现次数第5少的权值中第1小的，则应该输出</p><p>12。</p><p>若k1=1，k2=3，代表询问这个区间里出现次数第1少的权值中第3小的，则应该输出3。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包括一个整数n，代表序列的长度。</p><p>第二行包括n个整数a1...an，代表该序列。</p><p>第三行包括一个整数m，代表询问的次数。</p><p>接下来m行，每行包括4个整数l，r，k1，k2，询问al...ar中出现次数第k1少的权值中</p><p>第k2小的。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每个询问，仅输出一行，包括一个整数，代表你的回答。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【输入样例1】<br></p><p>10</p><p>3 6 6 8 3 10 1 6 5 6</p><p>10</p><p>4 7 1 2</p><p>5 7 1 1</p><p>5 6 1 2</p><p>2 6 2 1</p><p>8 9 1 1</p><p>6 9 1 2</p><p>1 2 1 1</p><p>1 4 2 1</p><p>5 7 1 3</p><p>2 6 1 3</p><p><br></p><p>【输入样例2】</p><p>20</p><p>14 18 19 11 15 13 9 10 5 13 3 14 14 12 12 8 4 17 8 8</p><p>20</p><p>8 9 1 2</p><p>6 19 2 2</p><p>7 11 1 1</p><p>8 12 1 4</p><p>9 13 2 1</p><p>14 15 1 1</p><p>6 11 1 4</p><p>5 7 1 3</p><p>8 18 2 1</p><p>2 4 1 3</p><p>4 16 1 1</p><p>5 14 1 5</p><p>13 14 1 2</p><p>15 15 1 1</p><p>12 17 1 1</p><p>3 12 2 1</p><p>14 17 1 1</p><p>6 13 1 4</p><p>11 11 1 1</p><p>2 4 1 3</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【输出样例1】</p><p>3</p><p>1</p><p>10</p><p>6</p><p>5</p><p>5</p><p>3</p><p>6</p><p>10</p><p>10</p><p><br></p><p>【输出样例2】</p><p>10</p><p>12</p><p>3</p><p>13</p><p>14</p><p>12</p><p>10</p><p>15</p><p>12</p><p>19</p><p>3</p><p>12</p><p>14</p><p>12</p><p>4</p><p>13</p><p>4</p><p>10</p><p>3</p><p>19</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【数据范围】</p><p>1&lt;=n&lt;=40000，</p><p>1&lt;=ai&lt;=n (1&lt;=i&lt;=n)，</p><p>1&lt;=m&lt;=40000，</p><p>1&lt;=l&lt;=r&lt;=n，</p><p>保证k1,k2合法。</p><p>特殊数据:</p><p>测试点 n m 备注</p><p>0 &lt;=1000 &lt;=1000</p><p>1 &lt;=1000 &lt;=1000</p><p>2 &lt;=30000 &lt;=30000 k1 是区间内出现次数最多的权值出现次数的排名,k2=1</p><p>(即询问该区间内最小的众数)</p><p>3 &lt;=30000 &lt;=30000 同上</p><p>4 &lt;=16000 &lt;=16000</p><p>5 &lt;=16000 &lt;=16000</p><p>6 &lt;=40000 &lt;=40000</p><p>7 &lt;=40000 &lt;=40000</p><p>8 &lt;=40000 &lt;=40000</p><p>9 &lt;=40000 &lt;=40000</p>
</div>
</div>