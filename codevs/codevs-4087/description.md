<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>凳子猫跟我们一样，也是一只上学猫，由于他每天喜欢睡在凳子上，故美名其曰“凳子猫”，他的假期就要到了，然而他也像我们一样，喜欢先玩一段时间再写作业，但是他却是一只小心谨慎的猫，他怕的是，如果他不能及时开始写作业，如果不能在假期结束前完成，猫老师可是会怒了的！他不敢惹猫老师，但他的数学不太好，算不出来要留下几天的写作业时间，于是他去查度娘，度娘也不能告诉他留几天写作业（废话），于是他找到了你这个oier，想让你帮他算算要留多少写作业时间。</p><p><br></p><p>当然他也有一项强大的技能，就是在假期的最后一天作业效率是普通效率的10倍，但他可不想这样做，这毕竟是很累的，所以他打算最后一天也用普通效率，但是如果从第一天一直写到倒数第二天还没写完，且余下的作业一天也做不完，他是可以使用该技能的。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行输入n，m，表示凳子猫假期天数和作业数量；</p><p>第二行输入k，表示凳子猫的普通效率；（可以理解成每天能完成的单位数量）</p><p>第3~m+2行，表示凳子猫每项作业的数量a[i]。（可以理解成每科作业单位数量）</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出共两行<br/></p><p>第一行：输出凳子猫该留下多少天来足以写完作业；如果写不完就输出‘Its teacher is angry!’</p><p>第二行：输出凳子猫是否需要在最后一天用十倍的效率来完成作业才能写完，用了输出‘Yes’，没用输出‘No’，如果尽管用了也没能完成作业，就输出‘It is tired and sad.’（注意标点符号！！！）</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例输入1：</p><p>10 7</p><p>5</p><p>4</p><p>6</p><p>9</p><p>8</p><p>6</p><p>4</p><p>2</p><p><br></p><p>样例输入2：</p><p>4 3</p><p>5</p><p>50</p><p>4</p><p>11</p><p><br></p><p>样例输入3：</p><p>5 9</p><p>4</p><p>1</p><p>2</p><p>3</p><p>4</p><p>5</p><p>6</p><p>7</p><p>8</p><p>39</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例输出1：<br></p><p>8</p><p>No</p><p><br></p><p>样例输出2：</p><p>4</p><p>Yes</p><p><br></p><p>样例输出3：</p><p>Its teacher is angry!</p><p>It is tired and sad.<br></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=n,m&lt;=100000<br></p><p>1&lt;=k&lt;=100</p><p>1&lt;=a[i]&lt;=10^9<br></p><p>然而我不保证累加会爆longint</p><p><br></p><p>顺便附带样例2解释：</p><p>4天3项作业，普通效率每天5个数量单位；</p><p>第一个作业有50个作业单位；</p><p>第二个作业有4个作业单位；</p><p>第三个作业有11个作业单位；</p><p>由于凳子猫如果每天都用普通效率写作业，最终是写不完的，所以他在最后一天用了10倍的效率，最后写完了作业。表示为5*(4-1)+5*10&gt;=sum(a[1]:a[m])，在此题中sum(a[1]:a[m])=65，因此作业总单位数量与提高效率后的15+50=65个总完成单位数量相等，因此能完成作业。其他输出不解释。</p>
</div>
</div>