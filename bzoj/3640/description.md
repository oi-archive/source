
# Description

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 14pt; font-family: 宋体"><span style="mso-tab-count: 1">   </span></span><span style="font-size: 12pt; font-family: 宋体">让我们继续<span lang="EN-US">JC</span>和<span lang="EN-US">DZY</span>的故事。<span lang="EN-US"><o:p></o:p></span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt; font-family: 宋体"><span style="mso-tab-count: 1">    </span></span><span style="font-size: 12pt; font-family: 宋体">“你是我的小丫小苹果，怎么爱你都不嫌多！”<span lang="EN-US"><o:p></o:p></span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt; font-family: 宋体"><span style="mso-tab-count: 1">    </span></span><span style="font-size: 12pt; font-family: 宋体">“点亮我生命的火，火火火火火！”<span lang="EN-US"><o:p></o:p></span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt; font-family: 宋体"><span style="mso-tab-count: 1">    </span></span><span style="font-size: 12pt; font-family: 宋体">话说<span lang="EN-US">JC</span>历经艰辛来到了城市<span lang="EN-US">B</span>，但是由于他的疏忽<span lang="EN-US">DZY</span>偷走了他的小苹果！没有小苹果怎么听歌！他发现邪恶的<span lang="EN-US">DZY</span>把他的小苹果藏在了一个迷宫里。<span lang="EN-US">JC</span>在经历了之前的战斗后他还剩下<span lang="EN-US">hp</span>点血。开始<span lang="EN-US">JC</span>在<span lang="EN-US">1</span>号点，他的小苹果在<span lang="EN-US">N</span>号点。<span lang="EN-US">DZY</span>在一些点里放了怪兽。当<span lang="EN-US">JC</span>每次遇到位置在<span lang="EN-US">i</span>的怪兽时他会损失<span lang="EN-US">Ai</span>点血。当<span lang="EN-US">JC</span>的血小于等于<span lang="EN-US">0</span>时他就会被自动弹出迷宫并且再也无法进入。<span lang="EN-US"><o:p></o:p></span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt; font-family: 宋体"><span style="mso-tab-count: 1">    </span></span><span style="font-size: 12pt; font-family: 宋体">但是<span lang="EN-US">JC</span>迷路了，他每次只能从当前所在点出发等概率的选择一条道路走。所有道路都是双向的，一共有<span lang="EN-US">m</span>条，怪兽无法被杀死。现在<span lang="EN-US">JC</span>想知道他找到他的小苹果的概率。<span lang="EN-US"><o:p></o:p></span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt; font-family: 宋体"><span style="mso-tab-count: 1">    </span>P.S.</span><span style="font-size: 12pt; font-family: 宋体">大家都知道这个系列是提高组模拟赛，所以这是一道送分题<span lang="EN-US">balabala<o:p></o:p></span></span></p>
<p></p></div>

# Input

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><span style="font-size: 12pt; font-family: 宋体">第一行三个整数表示<span lang="EN-US">n</span>，<span lang="EN-US">m</span>，<span lang="EN-US">hp</span>。接下来一行整数，第<span lang="EN-US">i</span>个表示<span lang="EN-US">jc</span>到第<span lang="EN-US">i</span>个点要损失的血量。保证第<span lang="EN-US">1</span>个和<span lang="EN-US">n</span>个数为<span lang="EN-US">0</span>。接下来<span lang="EN-US">m</span>行每行两个整数<span lang="EN-US">a</span>，<span lang="EN-US">b</span>表示<span lang="EN-US">ab</span>间有一条无向边。<span lang="EN-US"><o:p></o:p></span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体"><span lang="EN-US"><o:p></o:p></span></span></p></div>

# Output

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt; font-family: 宋体"><span style="mso-tab-count: 1">    </span></span><span style="font-size: 12pt; font-family: 宋体">仅一行，表示<span lang="EN-US">JC</span>找到他的小苹果的期望概率，保留八位小数。<span lang="EN-US"><o:p></o:p></span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体"><span lang="EN-US"><o:p></o:p></span></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">    3 3 2<br/>
    0 1 0<br/>
    1 2<br/>
    1 3<br/>
    2 3<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">    0.87500000<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据 2&lt;=n&lt;=150，hp&lt;=10000，m&lt;=5000，保证图联通。<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By JRY">By JRY</a></p></div>

