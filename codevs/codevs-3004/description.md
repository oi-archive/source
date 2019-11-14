<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Cause we're going to America！Jack赢得了去往美国的船票，一路狂奔上船。这里是泰坦尼克号，空前奢华、永不沉没的泰坦尼克号。1912年4月10日，这艘曾是人类史上建造过的最大最豪华的的两万吨巨轮开始了她的处女航。目的地：美国。270米的庞大身躯在无际的海洋上驰骋，她是当之无愧的时代的骄子。</p>
<p>Jack拿着船票登上泰坦尼克号，却不知这将是一次通向死亡的旅途。因为是三等舱，船票上只标注了房间的英文编号，却没有标注具体位置。同Jack一块的其他三等舱旅客也不知所措。索性船员意识到了这点，将房间编号及其对应的位置张贴了出来。房间的引文编号仅由A、B、C、D四个字母组成，长度从2个到12个字母不等。Jack和其他乘客都想快点知道自己的房间在什么地方。</p>
<p>得知位置后，Jack飞快地放好行李，然后奔向船头。"I can see the Statue of Liberty already（自由女神像）."Jack已经按耐不出自己的心情，仿佛美国就在前方。他爬上桅杆，眺望着远方，"I'm the king of the world! I'm the king of the world!"</p>
<p>而就在此时，一个叫Rose年轻女子的身影定格在了Jack的脑海中。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第一行有两个整数<span>N</span>、<span>M</span>。<span>N</span>表示旅客的数量，<span>M</span>表示房间的数量。接下来<span>M</span>行，每行为一个字符串和一个整数，分别表示房间的英文编号和房间的具体位置。在接下来<span>N</span>行每行有一个字符串，表示这<span>N</span>位乘客的房间的英文编号。数据保证编号仅由<span>A</span>、<span>B</span>、<span>C</span>、<span>D</span>四个大写字母组成。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<div class="WordSection1">
<p align="left">输出文件总共包含N行，按照输入顺序依次输出每位乘客的房间位置。如果此房间不存在，则输出incorrect number。</p>
</div>
<p>&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 6</p>
<p>CA 2</p>
<p>BC 3</p>
<p>ADD 1</p>
<p>BAD 5</p>
<p>CC 4</p>
<p>CA</p>
<p>DA</p>
<p>BAD</p>
<p>BC</p>
<p>CA</p>
<p>ADD</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>incorrect number</p>
<p>5</p>
<p>3</p>
<p>2</p>
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
<p><span style="">N</span><span style="">，<span>M<span style="">&lt;=500000</span></span></span></p>
<p><span style=""><span><span style="">字符串<span style="">由<span>A</span>、<span>B</span>、<span>C</span>、<span>D</span>四个大写字母组成，长度在<span>2</span>到<span>12</span>位之间。由于输入文件较大，建议使用<span>scanf</span>输入。</span></span></span></span></p>
</div>
</div>