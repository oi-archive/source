
# Description

<div class="content"><p><span style="font-size: medium">Bessie is in Camelot and has encountered a sticky situation: she needs to pass through the forest that is guarded by the Knights of Ni. In order to pass through safely, the Knights have demanded that she bring them a single shrubbery. Time is of the essence, and Bessie must find and bring them a shrubbery as quickly as possible. Bessie has a map of of the forest, which is partitioned into a square grid arrayed in the usual manner, with axes parallel to the X and Y axes. The map is W x H units in size (1 &lt;= W &lt;= 1000; 1 &lt;= H &lt;= 1000). The map shows where Bessie starts her quest, the single square where the Knights of Ni are, and the locations of all the shrubberies of the land. It also shows which areas of the map can be traverse (some grid blocks are impassable because of swamps, cliffs, and killer rabbits). Bessie can not pass through the Knights of Ni square without a shrubbery. In order to make sure that she follows the map correctly, Bessie can only move in four directions: North, East, South, or West (i.e., NOT diagonally). She requires one day to complete a traversal from one grid block to a neighboring grid block. It is guaranteed that Bessie will be able to obtain a shrubbery and then deliver it to the Knights of Ni. Determine the quickest way for her to do so. </span></p>
<div><span style="font-size: medium"> 贝茜遇到了一件很麻烦的事：她无意中闯入了森林里的一座城堡，如果她想回家，就必须穿过这片由骑士们守护着的森林．为了能安全地离开，贝茜不得不按照骑士们的要求，在森林寻找一种特殊的灌木并带一棵给他们．当然，贝茜想早点离开这可怕的森林，于是她必须尽快完成骑士们给的任务，贝茜随身带着这片森林的地图，地图上的森林被放入了直角坐标系，并按x,y轴上的单位长度划分成了W×H(1≤W,H≤1000)块，贝茜在地图上查出了她自己以及骑士们所在的位置，当然地图上也标注了她所需要的灌木生长的区域．某些区域是不能通过的（比如说沼泽地，悬崖，以及食人兔的聚居地）．在没有找到灌木之前，贝茜不能通过骑士们所在的那个区域，为了确保她自己不会迷路，贝茜只向正北、正东、正南、正西四个方向移动（注意，她不会走对角线）．她要走整整一天，才能从某块区域走到与它相邻的那块区域．    输入数据保证贝茜一定能完成骑士的任务．贝茜希望你能帮她计算一下，她最少需要多少天才可脱离这可怕的地方？</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">    第1行输入2个用空格隔开的整数，即题目中提到的W、H.</span></div>
<div><span style="font-size: medium">    接下来输入贝茜持有的地图，每一行用若干个数字代表地图上对应行的地形．第1行描述了地图最北的那一排土地；最后一行描述的则是最南面的．相邻的数字所对应的区域是相邻的．如果地图的宽小于或等于40，那每一行数字恰好对应了地图上的一排土地．如果地图的宽大于40，那每行只会给出40个数字，并且保证除了最后一行的每一行都包含恰好40个数字．没有哪一行描述的区域分布在两个不同的行里．</span></div>
<div><span style="font-size: medium">    地图上的数字所对应的地形：</span></div>
<div><span style="font-size: medium">    0：贝茜可以通过的空地</span></div>
<div><span style="font-size: medium">    1：由于各种原因而不可通行的区域</span></div>
<div><span style="font-size: medium">    2：贝茜现在所在的位置</span></div>
<div><span style="font-size: medium">    3：骑士们的位置</span></div>
<div><span style="font-size: medium">    4：长着贝茜需要的灌木的土地</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">    输出一个正整数D，即贝茜最少要花多少天才能完成骑士们给的任务．</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">8 4<br/>
4 1 0 0 0 0 1 0<br/>
0 0 0 1 0 1 0 0<br/>
0 2 1 1 3 0 4 0<br/>
0 0 0 4 1 1 1 0<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
Width=8, height=4. Bessie starts on the third row, only a few squares away<br/>
from the Knights.<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">11<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman"> </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">这片森林的长为</span><span lang="EN-US"><font face="Times New Roman">8</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，宽为</span><span lang="EN-US"><font face="Times New Roman">4</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">．贝茜的起始位置在第</span><span lang="EN-US"><font face="Times New Roman">3</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行，离骑士们不远．</span></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">    </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">贝茜可以按这样的路线完成骑士的任务：北，西，北，南，东，东，北，东，东，南，南．她在森林的西北角</span></span><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">得到一株她需要的灌木，然后绕过障碍把它交给在东南方的骑士．</span></span></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

