<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    有n 位医生和m 位病人，其中某些医生需要给某些病人做手术，其中某些医生需要给某些病人做手术。<br>    为了避免医生的手直接接触到病人，医生在手术中必须佩带手套。然而，手套被使用后，内表面会沾染医生的汗液，外表面会沾染病人的血液。医生和病人都不愿意接触到其他人的汗液或血液。<br>    请你帮忙计算，最少使用多少副手套可以完成所有手术？<br>    值得注意的是：一副手套被当做一个整体，不可以拆成“两只”分别使用。<br>    此外，如果有必要，手套是可以“翻过来”使用的。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行包含一个正整数T，表示该文件中含有T 组测试数据。<br>    对于每组测试数据：第一行有三个正整数n、m、s。表示有n 位医生(编号0 至n-1)，有m 位病人(编号0 至m-1)，有s 场手术(编号0 至s-1)。<br>    随后s 行，按编号顺序描述每一场手术。每行有两个非负整数x、y，表示x 号医生和y 号病人需要做一场手术。数据保证不会出现两场相同的手术。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; 输出中应包含T 组测试数据的答案。<br />&nbsp; &nbsp; 对于每一组答案：第一行包含一个正整数p，表示你需要使用p 副手套(从字母a 开始顺序编号)。随后s 行，你需要按时间顺序描述每场手术安排，每场手术单独使用一行。对于一场手术，你需要先输出它的编号，随后输出它使用的手套数量k(必须是1 或2)，接下来以自内向外(从医生向病人) 的顺序输出所有使用的k 副手套的编号(字母)，并用空格分隔。特别地，若某副手套在该次手术中是以&ldquo;翻过来&rdquo;的状态使用的，则用对应的大写字母来表示，否则用小写字母表示，详见样例。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 <br>2 2 4<br>0 1<br>0 0<br>1 0<br>1 1<br>3 2 3<br>0 1<br>1 0<br>2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2 <br>1 2 a b<br>0 1 a<br>2 1 b<br>3 2 b a<br>3<br>0 2 a b<br>1 2 A B<br>2 1 c</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>s≤n*m,T≤10,n≤10,m≤10</p>
</div>
</div>