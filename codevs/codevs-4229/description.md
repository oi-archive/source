<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">为了随时与</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">rainbow</span></span><span style="">快速交流，</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">Freda</span></span><span style="">制造了两部传呼机。</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">Freda</span></span><span style="">和</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">rainbow</span></span><span style="">所在的地方有</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">N</span></span><span style="">座房屋、</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">M</span></span><span style="">条双向光缆。每条光缆连接两座房屋，传呼机发出的信号只能沿着光缆传递，并且传呼机的信号从光缆的其中一端传递到另一端需要花费</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">t</span></span><span style="">单位时间。现在</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">Freda</span></span><span style="">要进行</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">Q</span></span><span style="">次试验，每次选取两座房屋，并想知道传呼机的信号在这两座房屋之间传递至少需要多长时间。</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">Freda</span></span><span style="">和</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">rainbow</span></span><span style="">简直弱爆了有木有</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">T_T</span></span><span style="">，请你帮帮他们吧……</span></p><p><span style=""></span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;"></span></span></p><p><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">N</span></span><span style="">座房屋通过光缆一定是连通的，并且这</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">M</span></span><span style="">条光缆有以下三类连接情况：</span></p><p><span style=""></span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;"></span></span></p><p><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">A</span></span><span style="">：光缆不形成环，也就是光缆仅有</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">N-1</span></span><span style="">条。</span></p><p><span style=""></span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;"></span></span></p><p><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">B</span></span><span style="">：光缆只形成一个环，也就是光缆仅有</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">N</span></span><span style="">条。</span></p><p><span style=""></span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;"></span></span></p><p><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">C</span></span><span style="">：每条光缆仅在一个环中。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第一行包含三个用空格隔开的整数，</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">N</span></span><span style="">、</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">M</span></span><span style="">和</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">Q</span></span><span style="">。</span></p><p><span style=""></span></p><p><span style="">接下来</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">M</span></span><span style="">行每行三个整数</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">x</span></span><span style="">、</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">y</span></span><span style="">、</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">t</span></span><span style="">，表示房屋</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">x</span></span><span style="">和</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">y</span></span><span style="">之间有一条传递时间为</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">t</span></span><span style="">的光缆。</span></p><p><span style=""></span></p><p><span style="">最后</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">Q</span></span><span style="">行每行两个整数</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">x</span></span><span style="">、</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">y</span></span><span style="">，表示</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">Freda</span></span><span style="">想知道在</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">x</span></span><span style="">和</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">y</span></span><span style="">之间传呼最少需要多长时间。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size:16px">输出</span><span style="font-family:Times New Roman,Times New Roman;font-size:16px"><span style="font-family:Times New Roman,Times New Roman;font-size:16px">Q</span></span><span style="font-size:16px">行，每行一个整数，表示</span><span style="font-family:Times New Roman,Times New Roman;font-size:16px"><span style="font-family:Times New Roman,Times New Roman;font-size:16px">Freda</span></span><span style="font-size:16px">每次试验的结果。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style=""></span></p><p>例1</p><p>5 4 2</p><p>1 2 1</p><p>1 3 1</p><p>2 4 1</p><p>2 5 1</p><p>3 5</p><p>2 1</p><p>例2</p><p><span style=""></span></p><p>5 5 2</p><p></p><p><span style="">1 2 1</span></p><p><span style="font-family: Colonna MT,Colonna;"><span style="font-family: Colonna MT,Colonna;"></span></span><span style=""></span></p><p>2 1 1</p><p>1 3 1</p><p>2 4 1</p><p>2 5 1</p><p>3 5</p><p>2 1</p><p>例3</p><p></p><p><span style=""></span></p><p>9 10 2</p><p>1 2 1</p><p>1 4 1</p><p>3 4 1</p><p>2 3 1</p><p>3 7 1</p><p>7 8 2</p><p>7 9 2</p><p>1 5 3</p><p>1 6 4</p><p>5 6 1</p><p>1 9</p><p>5 7</p><p></p><p></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>例1<span style=""></span></p><p>3</p><p>1</p><p>例2</p><span style=""><p>3</p><p></p><p>1</p><p></p></span><p>例3</p><p><span style=""></span></p><p>5</p><p>6</p><p></p><span style=""><span style=""><p><br></p></span></span><p></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">颂芬数据占</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">10%</span></span><span style="">，</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">2&lt;=N&lt;=1000</span></span><span style="">，</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">N-1&lt;=M&lt;=1200</span></span><span style="">。</span></p><p><span style=""></span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;"></span></span></p><p><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">A</span></span><span style="">类数据占</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">30%</span></span><span style="">，</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">M=N-1</span></span><span style="">。</span></p><p><span style=""></span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;"></span></span></p><p><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">B</span></span><span style="">类数据占</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">50%</span></span><span style="">，</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">M=N</span></span><span style="">。</span></p><p><span style=""></span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;"></span></span></p><p><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">C</span></span><span style="">类数据占</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">10%</span></span><span style="">，</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">M&gt;N</span></span><span style="">。</span></p><p><span style=""></span></p><p><span style="">对于</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">100%</span></span><span style="">的数据，</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">2&lt;=N&lt;=10000</span></span><span style="">，</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">N-1&lt;=M&lt;=12000</span></span><span style="">，</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">Q=10000</span></span><span style="">，</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">1&lt;=x,y&lt;=N</span></span><span style="">，</span><span style="font-family: Times New Roman,Times New Roman;"><span style="font-family: Times New Roman,Times New Roman;">1&lt;=t&lt;32768</span></span><span style="">。</span></p><p><br></p>
</div>
</div>