<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>HYY经过你的帮助，进了JCH的家，等待他的是一个巨大的迷宫~~</p><p><br></p><p>进了门，放眼望去，是一望无际碧绿的树丛掩映下的小路。</p><p>这是一个巨大的迷宫，HYY（H）和JCH（J）在其中，有一个出口（E），请输出谁先到，HYY先到输出H，JCH先到输出J，同时输出L，如果两人都到达不了出口输出-1（因为本人提交题目达到上限，所以暂时停更）<span style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">（此题我在洛谷上发了比赛）</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>两个整数n和m</p><p>以下n行，每行m个字符（无空格），为0或1或H或J或E</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个字符，为H或J或L或-1</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 4</p><p>E001</p><p>10H0</p><p>J010</p><p>1010</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>H</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1≤n,m≤1000</p><p>in文件随机：</p><p>var</p><p> x,y,hx,hy,jx,jy,fx,fy,c,i,j:longint;</p><p> n,m:longint;</p><p>begin</p><p> readln(n,m);</p><p> randomize;</p><p> writeln(n,' ',m);</p><p> x:=random(n)+1;y:=random(m)+1;</p><p> hx:=x;hy:=y;</p><p> repeat</p><p>  x:=random(n)+1;y:=random(m)+1;</p><p> until (x&lt;&gt;hx)or(y&lt;&gt;hy);</p><p> jx:=x;jy:=y;</p><p> repeat</p><p>  x:=random(n)+1;y:=random(m)+1;</p><p> until ((x&lt;&gt;hx)or(y&lt;&gt;hy))and((x&lt;&gt;jx)or(y&lt;&gt;jy));</p><p> fx:=x;fy:=y;</p><p> for i:=1 to n do</p><p>  begin</p><p>   for j:=1 to m do</p><p>    begin</p><p>     if (i=hx)and(j=hy) then write('H')</p><p>     else if (i=jx)and(j=jy) then write('J')</p><p>     else if (i=fx)and(j=fy) then write('E')</p><p>     else</p><p>      begin</p><p>       c:=random(3);</p><p>       if c=0 then write('1') else write('0');</p><p>      end;</p><p>    end;</p><p>   writeln;</p><p>  end;</p><p>end.</p>
</div>
</div>