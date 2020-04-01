<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给出无向图G，边(Ai,Bi) 的权是Ci，判断下列性质是否成立</p><p>对于任意圈C，其边权的异或和是0</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style='font-family: Georgia, "Times New Roman", "Bitstream Charter", Times, serif;'>第1 行，1 个整数T，表示数据的组数。</span><br style='font-family: Georgia, "Times New Roman", "Bitstream Charter", Times, serif;'><span style='font-family: Georgia, "Times New Roman", "Bitstream Charter", Times, serif;'>每组数据第1 行，2 个整数N,M，表示图G 点和边的数量。</span><br style='font-family: Georgia, "Times New Roman", "Bitstream Charter", Times, serif;'><span style='font-family: Georgia, "Times New Roman", "Bitstream Charter", Times, serif;'>M 行，每行3 个整数Ai,Bi,Ci</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(51, 51, 51); font-family: Georgia, &quot;Times New Roman&quot;, &quot;Bitstream Charter&quot;, Times, serif; background-color: rgb(255, 255, 255);">对每个数据输出一行，“Yes” 或者“No”</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style="">2<br></p><p style="">3 3</p><p style="">1 2 1</p><p style="">2 3 2</p><p style="">3 1 3</p><p style="">1 1</p><p style="">1 1 1</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Yes</p><p>No</p><p></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>• 对于50% 的数据，N,M &lt;= 20</p><p>• 对于100% 的数据，1 &lt;= N,M &lt;= 50; 1 &lt;= Ai,Bi &lt;= N; 0 &lt; =Ci &lt; 2^16</p><p><br></p>
</div>
</div>