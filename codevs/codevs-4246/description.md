<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>   奶牛们在FJ的养育下茁壮成长。这天,FJ给了奶牛Bessie一个任务,去看看每个奶牛场中若干只奶牛的身高,由于Bessie是只奶牛,无法直接看出第i只奶牛的身高,而只能看出第i只奶牛与第j只奶牛的身高差,其中第i 只奶牛与第j只奶牛的身高差为A(i&lt;=n)。当A大于0时表示这只奶牛比前一只奶牛高A cm,小于0时则是低。现在,FJ让Bessie总共去看了m次身高,当然也就传回给FJ m对奶牛的身高差,但是Bessie毕竟是奶牛,有时候眼睛可能会不好使……(大雾)你的任务是帮助FJ来判断是不是需要给Bessie看看眼睛了……</p><p>注:Hj-Hi=A 注意T1的样例 注意注意注意 重要的事情说三遍。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为一个正整数w,表示有w组数据,即w个奶牛场,需要你判断。每组数据的第一行为两个正整数n和m,分别表示对应的奶牛场中的奶牛只数以及看了多少个对奶牛身高差。接下来的m行表示Bessie看m次后传回给FJ的m条信息,每条信息占一行,有三个整数s,t和v,表示第s只奶牛与第t只奶牛的身高差为v。</p><p style=""><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>包含w行,每行是”Bessie’s&nbsp;eyes&nbsp;are&nbsp;good”或”Bessie&nbsp;is&nbsp;blind.”(不含双引号),其中第i行为”Bessie’s&nbsp;eyes&nbsp;are&nbsp;good”当且仅当第i组数据,即无法从第i个奶牛场传回的身高差判断Bessie视力好不好;第i行为”Bessie&nbsp;is&nbsp;blind.”当且仅当第i组数据,即从第i个奶牛场传回的身高差是有问题的。</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p><p>3 3</p><p>1 3 10</p><p>2 3 5</p><p>1 2 5</p><p>4 3</p><p>1 4 100</p><p>3 4 50</p><p>1 3 100</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Bessie’s eyes are good</p><p>Bessie is blind.</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据,保证n&lt;=100,m&lt;=1000;</p><p>对于100%的数据,保证w&lt;=100,n&lt;=1000,m&lt;=30000,|A|&lt;=30000.</p><p><br></p>
</div>
</div>