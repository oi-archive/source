<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>申奥成功后，布布经过不懈努力，终于成为奥组委下属公司人力资源部门的 主管。布布刚上任就遇到了一个难题：为即将启动的奥运新项目招募一批短期志 愿者。经过估算，这个项目需要 N 天才能完成，其中第 i 天至少需要 Ai个人。 布布通过了解得知，一共有 M 类志愿者可以招募。其中第 i 类可以从第 Si天工 作到第 Ti 天，招募费用是每人 Ci元。新官上任三把火，为了出色地完成自己的 工作，布布希望用尽量少的费用招募足够的志愿者，但这并不是他的特长！于是 布布找到了你，希望你帮他设计一种最优的招募方案。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件 employee.in 的第一行包含两个整数 N, M，表示完成项目的天数和 可以招募的志愿者的种类。 接下来的一行中包含 N 个非负整数，表示每天至少需要的志愿者人数。  接下来的 M 行中每行包含三个整数 Si, Ti, Ci，含义如上文所述。为了方便起 见，我们可以认为每类志愿者的数量都是无限多的。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输入文件 employee.out 中仅包含一个整数，表示你所设计的最优方案的总费用。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3</p>
<p>2 3 4</p>
<p>1 2 2</p>
<p>2 3 5</p>
<p>3 3 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>14 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例说明】</p>
<p>招募 3 名第一类志愿者和 4 名第三类志愿者。</p>
<p>30%的数据中，1 ≤ N, M ≤ 10，1 ≤ Ai ≤ 10；</p>
<p>100%的数据中，1 ≤ N ≤ 1000，1 ≤ M ≤ 10000，题目中其他所涉及的数据均不超过 231-1。 </p>
</div>
</div>