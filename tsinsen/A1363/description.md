<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　有一个正方形的地区，该地区特点鲜明：如果把它等分为<i>N</i>×<i>N</i>个小正方形格子的话，在每个格子内的任意地点的地表高度是相同的，并且是一个0到<i>M</i>之间的整数。正方形地区的外部被无限高的边界包围。<br/>
　　该地区可能会有积水。经过多年的观察，人们发现了几个关于积水的重要规律：<br/>
　　1. 每个格子要么完全没有积水，要么它内部的任意地点的水面高度都是相同的。并且水面高度一定大于地表高度。<br/>
　　2. 每个格子的水面高度在0~<i>M</i>之间，并且一定是整数。<br/>
　　3. 对于相邻（必须为边相邻）的两个格子，一定不会出现水自动从一个格子流向另一个格子的情况。也就是说，一定不能出现这两个格子都有水且水面高度不同，或者有水格子的水面比无水格子的地表要高的情况。<br/>
　　例如，下面图中每个格子里有两个数a/b，说明该格子的地表高度是<i>a</i>，水面高度是<i>b</i>（均为海拔高度），而没有水的格子中<i>b</i>以“−”表示。则左边的情况是符合规律的，而右边的情况并不符合以上规律，因为水可以由2/4的格子流向3/−的格子。<br/>
<img width="517" height="228" src="source/tsinsen/A1363/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9VEFHMzg4QnQ=.do"/><br/>
　　(图1)<br/>
<br/>
<br/>
　　该地区水文站的工作人员小A想知道，该地区中有多少种不同的水位情况符合规律。你能回答他的这个问题吗？</div>
# 输入格式

<div class="pdcont">　　输入文件的第一行包含两个正整数<i>N</i>和<i>M</i>。<br/>
　　随后的<i>N</i>行，每行包含<i>N</i>个非负整数。其中第<i>i</i>+1行的第<i>j</i>个数表示该地区第<i>i</i>行第<i>j</i>列格子的地表高度。</div>
# 输出格式

<div class="pdcont">　　输出文件只包含一个整数，即该地区符合规律的水位情况种数。</div>
# 样例输入

<div class="pddata">4 3<br/>
1 1 1 1<br/>
1 2 2 2<br/>
1 2 3 3<br/>
1 2 3 2</div>
# 样例输出

<div class="pddata">6</div>
# 对样例的说明

<div class="pdcont">　　符合规律的水位情况有以下六种 ：<br/>
<img width="447" height="276" src="source/tsinsen/A1363/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9dDdBaExReUY=.do"/></div>
# 数据规模和约定

<div class="pdcont"><img width="564" height="163" src="source/tsinsen/A1363/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9ZmhIRUxBcTg=.do"/></div>

</div>