<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><strong>音乐家张老师被人发现倒毙在自己的卧室里昏迷不醒，家里的贵重东西被洗劫一空。名侦探柯南到现场破案发现张老师在昏迷前写的一张歌谱，这张歌谱上重复着同一段旋律。柯南研究了很久，终于找出这段歌谱的含义：原来每个音节的数字连接在一起就是一个八进制数，将所有的八进制数转成十进制数并连接起来就是一个电话号码。柯南根据这个电话号码很快找到了罪犯。请编写一个程序，将歌谱转换成电话号码。（请注意细节问题）</strong></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><strong>第一行是整数n，表示有n个音节。 第二行是歌谱上的数字，每个音节之间用一个‘！’分隔，音节最后没有‘！’。</strong></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><strong>按样例输出电话号码。</strong></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><strong>4 </strong></p><p><strong>5!673!10!727</strong></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><strong>54438471</strong><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><strong>100%的数据：3&lt;n&lt;20,答案不超过longint。</strong></p><p><strong><br></strong></p><p><strong>参考代码（程序填空）：</strong></p><p><strong>var</strong></p><p><strong>  a:array[1..20] of string;</strong></p><p><strong>  n,i,x,y,m,ans,j,k:longint;</strong></p><p><strong>  s:string;</strong></p><p><strong>begin</strong></p><p><strong>  readln(n);</strong></p><p><strong>  readln(s);</strong></p><p><strong>  if s=?<span style="text-decoration: none;"> </span>then</strong></p><p><strong>  begin</strong></p><p><strong>    write(0);</strong></p><p><strong>    ?</strong></p><p><strong>  end;</strong></p><p><strong>  s:=s+?;</strong></p><p><strong>  for i:=1 to n do</strong></p><p><strong>  begin</strong></p><p><strong>    a[i]:=?</strong></p><p><strong>    delete(s,1,pos('!',s));</strong></p><p><strong>  end;</strong></p><p><strong>  for i:=1 to n do</strong></p><p><strong>  begin</strong></p><p><strong>    x:=?</strong></p><p><strong>    for j:=1 to length(a[i]) do</strong></p><p><strong>    begin</strong></p><p><strong>      m:=1;</strong></p><p><strong>      dec(x);</strong></p><p><strong>      val(a[i][j],y);</strong></p><p><strong>      for k:=1 to x do</strong></p><p><strong>        m:=?</strong></p><p><strong>      ans:=ans+m*y;</strong></p><p><strong>    end;</strong></p><p><strong>    write(?);</strong></p><p><strong>    ans:=0;</strong></p><p><strong>  end;</strong></p><p><strong>end.</strong></p><p><strong><br></strong><br></p><p><br></p>
</div>
</div>