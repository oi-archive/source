<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小F的学校在城市的一个偏僻角落，所有学生都只好在学校吃饭。学校有一个食堂，虽然简陋，但食堂大厨总能做出让同学们满意的菜肴。当然，不同的人口味也不一定相同，但每个人的口味都可以用一个非负整数表示。</p>
<p>由于人手不够，食堂每次只能为一个人做菜。做每道菜所需的时间是和前一道菜有关的，若前一道菜的对应的口味是<em>a</em>，这一道为<em>b</em>，则做这道菜所需的时间为（<em>a</em> or <em>b</em>）-（<em>a</em> and <em>b</em>），而做第一道菜是不需要计算时间的。其中，or和and表示整数逐位或运算及逐位与运算，C语言中对应的运算符为”｜”和”＆”。</p>
<p>学生数目相对于这个学校还是比较多的，吃饭做菜往往就会花去不少时间。因此，学校食堂偶尔会不按照大家的排队顺序做菜，以缩短总的进餐时间。</p>
<p>虽然同学们能够理解学校食堂的这种做法，不过每个同学还是有一定容忍度的。也就是说，队伍中的第<em>i</em>个同学，最多允许紧跟他身后的<em>B<sub>i</sub></em>个人先拿到饭菜。一旦在此之后的任意同学比当前同学先拿到饭，当前同学将会十分愤怒。因此，食堂做菜还得照顾到同学们的情绪。</p>
<p>现在，小F想知道在满足所有人的容忍度这一前提下，自己的学校食堂做完所有菜最少需要多少时间。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行包含一个正整数<em>C</em>，表示测试点的数据组数。</p>
<p>每组数据的第一行包含一个正整数<em>N</em>，表示同学数。</p>
<p>每组数据的第二行起共<em>N</em>行，每行包含两个用空格分隔的非负整数<em>T<sub>i</sub></em>和<em>B<sub>i</sub></em>，表示按队伍顺序从前往后的每个同学所需的菜的口味和这个同学的忍受度。</p>
<p>每组数据之间没有多余空行。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出包含<em>C</em>行，每行一个整数，表示对应数据中食堂完成所有菜所需的最少时间。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>5</p>
<p>5 2</p>
<p>4 1</p>
<p>12 0</p>
<p>3 3</p>
<p>2 2</p>
<p>2</p>
<p>5 0</p>
<p>4 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>16</p>
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
<p>对于第一组数据：</p>
<p>同学1允许同学2或同学3在他之前拿到菜；同学2允许同学3在他之前拿到菜；同学3比较小气，他必须比他后面的同学先拿菜……</p>
<p>一种最优的方案是按同学3、同学2、同学1、同学4、同学5做菜，每道菜所需的时间分别是0、8、1、6及1。</p>
<p> <br><br></p>
<p>对于30%的数据，满足1 ≤ <em>N </em>≤ 20。</p>
<p>对于100%的数据，满足1 ≤ <em>N </em>≤ 1,000，0 ≤ <em>T<sub>i </sub></em>≤ 1,000，0 ≤ <em>B<sub>i </sub></em>≤ 7，1 ≤ <em>C </em>≤ 5。</p>
<p>存在30%的数据，满足0 ≤ <em>B<sub>i </sub></em>≤ 1。</p>
<p>存在65%的数据，满足0 ≤ <em>B<sub>i </sub></em>≤ 5。</p>
<p>存在45%的数据，满足0 ≤ <em>T<sub>i </sub></em>≤ 130。</p>
<p> </p>
</div>
</div>