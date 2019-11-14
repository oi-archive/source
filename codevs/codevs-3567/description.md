<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="font-family: simsun;"><span style="">从前有一个王国，这个王国的城堡是一个矩形，被分为</span><span style="">M</span><span style="">×</span><span style="">N</span><span style="">个方格。一些方格是墙，而另一些是空地。这个王国的国王在城堡里设了一些陷阱，每个陷阱占据一块空地。</span></p><p style="font-family: simsun;"><span style="">一天，国王决定在城堡里布置守卫，他希望安排尽量多的守卫。守卫们都是经过严格训练的，所以一旦他们发现同行或同列中有人的话，他们立即向那人射击。因此，国王希望能够合理地布置守卫，使他们互相之间不能看见，这样他们就不可能互相射击了。守卫们只能被布置在空地上，不能被布置在陷阱或墙上，且一块空地只能布置一个守卫。如果两个守卫在同一行或同一列，并且他们之间没有墙的话，他们就能互相看见。</span><span style="">(</span><span style="">守卫就像象棋里的车一样</span><span style="">)</span></p><p style="font-family: simsun;"><span style="">你的任务是写一个程序，根据给定的城堡，计算最多可布置多少个守卫，并设计出布置的方案。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="font-family: simsun;"><span style="">第一行两个整数</span><span style="">M</span><span style="">和</span><span style="">N</span><span style="">(</span><span style="">1</span><span style="">≤</span><span style="">M</span><span style="">，</span><span style="">N</span><span style="">≤</span><span style="">200</span><span style="">)</span><span style="">，表示城堡的规模。</span></p><p style="font-family: simsun;"><span style="">接下来</span><span style="">M</span><span style="">行</span><span style="">N</span><span style="">列的整数，描述的是城堡的地形。第</span><span style="">i</span><span style="">行</span><span style="">j</span><span style="">列的数用</span><span style="">a<sub>i,j</sub></span><span style="">表示。</span></p><p style="font-family: simsun;"><span style="">a<sub>i,j</sub>=0</span><span style="">，表示方格</span><span style="">[i,j]</span><span style="">是一块空地；</span></p><p style="font-family: simsun;"><span style="">a<sub>i,j</sub>=1</span><span style="">，表示方格</span><span style="">[i,j]</span><span style="">是一个陷阱；</span></p><p style="font-family: simsun;"><span style="">a<sub>i,j</sub>=2</span><span style="">，表示方格</span><span style="">[i,j]</span><span style="">是墙。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="margin-top: 0px;padding: 0px;border: 0px;list-style: none;word-wrap: normal;line-height: 21px;color: rgb(70, 70, 70);font-family: simsun;font-size: 14px;white-space: normal;background-color: rgb(255, 255, 255)"><span style="word-wrap: normal;font-family: 宋体">第一行一个整数</span><span xml:lang="EN-US" style="word-wrap: normal">K</span><span style="word-wrap: normal;font-family: 宋体">，表示最多可布置</span><span xml:lang="EN-US" style="word-wrap: normal">K</span><span style="word-wrap: normal;font-family: 宋体">个守卫。</span></p><p style="margin-top: 0px;padding: 0px;border: 0px;list-style: none;word-wrap: normal;line-height: 21px;color: rgb(70, 70, 70);font-family: simsun;font-size: 14px;white-space: normal;background-color: rgb(255, 255, 255)"><span style="word-wrap: normal; font-family: 宋体;">此后</span><span xml:lang="EN-US" style="word-wrap: normal;">K</span><span style="word-wrap: normal; font-family: 宋体;">行，每行两个整数</span><span xml:lang="EN-US" style="word-wrap: normal;">x<sub>i</sub></span><span style="word-wrap: normal; font-family: 宋体;">和</span><span xml:lang="EN-US" style="word-wrap: normal;">y<sub>i</sub></span><span style="word-wrap: normal; font-family: 宋体;">，描述一个守卫的位置。</span></p><p style="margin-top: 0px;padding: 0px;border: 0px;list-style: none;word-wrap: normal;line-height: 21px;color: rgb(70, 70, 70);font-family: simsun;font-size: 14px;white-space: normal;background-color: rgb(255, 255, 255)"><span style="word-wrap: normal; font-family: 宋体;"><br/></span></p><p style="margin-top: 0px;padding: 0px;border: 0px;list-style: none;word-wrap: normal;line-height: 21px;color: rgb(70, 70, 70);font-family: simsun;font-size: 14px;white-space: normal;background-color: rgb(255, 255, 255)"><span style="word-wrap: normal; font-family: 宋体;"><span style="color: rgb(70, 70, 70); font-family: 宋体; font-size: 14px; line-height: 21px; background-color: rgb(255, 255, 255);">（若有多解，请输出字典序最小的那一种）</span></span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style="font-family: simsun;"><span style="">3 4</span></p><p style="font-family: simsun;"><span style="">2 0 0 0</span></p><p style="font-family: simsun;"><span style="">2 2 2 1</span></p><p style="font-family: simsun;"><span style="">0 1 0 2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style="font-family: simsun;"><span style="">2</span></p><p style="font-family: simsun;"><span style="">1 2</span></p><p style="font-family: simsun;"><span style="">3 1</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见描述。</p>
</div>
</div>