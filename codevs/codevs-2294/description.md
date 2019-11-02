<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<div>【Shadow 1】第四题</div>
<div>在2017年，帥芞の面包正负责为十九大布置庄重的会议室。</div>
<div>因为会议室被设计为招待来自世界各地记者的场所，它装备了一些电器插座以匹配各个国家使用的电器的不同插头形状和电压。当然，这些插座的规格是以这个会议室建成时世界各国的规格作为标准滚的。不幸的是，由于这座会议室年代久远，它建成时，记者还只是使用为数不多的电子设备，所以它对每种类型只配备了一个插座。今天，记者向其他人一样，需要很多的电子设备才能工作：掌上型计算器，手提电话，录音机，寻呼机，电咖啡壶，微波炉，电吹风，电熨斗，电动牙刷等等。</div>
<div>在会议开始前，帥芞の面包将记者所有可能使用的设备集中起来，尝试将它们接到插座上。帥芞の面包注意到有些设备的插头没有相应的插座。对某些插座，也有许多设备都使用对应的插头；而对另一些插座，也许没有任何设备使用对应的插头。</div>
<div>因为帥芞の面包整天不是刷题就是办比赛，为了解决这个问题，帥芞の面包叫无辜的Shadow去附近一家五金商店买转接头。转接头可以将一种接头转换成另一种接头。一个转接头还可以接到另一个转接头上。并非所有插座和插头的组合都有相应的转接头，但是对每种出售的转接头，商店都有足够的存货。至于钱的问题？？？都是花Shadow的啦=v=</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<div>第1行，1个整数n，表示会议室的插座数；</div>
<div>接下来n行，每行列出了能在会议室找到的插座的名称cz；</div>
<div>接下来是1个整数m，表示你要连接的插头数；</div>
<div>接下来m行，每行列出了设备的名称sb和它使用的插头的名称ct，两者用一个空格分开；</div>
<div>接着是1个整数k，表示可用的转接头的种类；</div>
<div>接下来k行，每行列出了转接头提供的插座zcz和插头的类型zct。</div>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>输出最少无法连接的设备数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<div>4</div>
<div>A</div>
<div>B</div>
<div>C</div>
<div>D</div>
<div>5</div>
<div>laptop B</div>
<div>phone C</div>
<div>pager B</div>
<div>clock B</div>
<div>comb X</div>
<div>3</div>
<div>B X</div>
<div>X A</div>
<div>X D</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<div>1≤n,m≤500,1≤k≤100；</div>
<div>cz、sb、ct、zcz、zct是由字母和数字组成的字符串，长度不超过24个字符。</div>
</div>
</div>