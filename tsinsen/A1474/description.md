<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　您找了一份有趣的新工作，那就是做一位船长。您的第一个任务就是用最少的支出，完成从甲地到乙地的航行任务。<br/>
　　众所周知，两点间的最短距离，是它们之间线段的长度。但是残念的是，一座岛屿正坐落于海洋中。因此，您可能无法直线航行到目的地。<br/>
　　您<b>只</b>打算在安全位置上航行。一个点在安全位置当且仅当它在甲乙两地之间的线段或者岛屿的边界上。<br/>
　　还好，您有一些能干的手下来帮您完成这个任务。具体来说，他们可以帮助您在海上操纵船只，费用为 <img width="8" height="21" src="source/tsinsen/A1474/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9Z0g2RHlMNWg=.do"/> 埃及镑/单位距离。当然了，他们还可以在陆上搬运船只（那是，他们特厉害的说），费用为 <img width="8" height="21" src="source/tsinsen/A1474/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9M0RnUTZZZlI=.do"/> 埃及镑/单位距离。因为支出会被您的手下平分，所以手下的数量与您的支出无关。<br/>
　　您的船可以在岛屿的边界上行驶，其等价于在海面上行驶。<br/>
　　现在，您有一张该海域的地图。您需要计算出完成该任务的最小开支。<br/>
　　您从甲地 <img width="84" height="21" src="source/tsinsen/A1474/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9ZWcySjJ0Rk4=.do"/> 出发，目的地位于乙地 <img width="72" height="21" src="source/tsinsen/A1474/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9MkVoUkpqeXE=.do"/>，保证两点不同。同时数据还保证岛屿是一个凸多边形，其边界上任意三个顶点不共线，且甲乙两地不会位于其内部或边界。多边形的顶点将会按照逆时针的顺序给出。</div>
# 输入格式

<div class="pdcont">　　第一行包括四个整数，<img width="34" height="21" src="source/tsinsen/A1474/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9QnFMbjdUUUE=.do"/> <img width="34" height="21" src="source/tsinsen/A1474/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9amJleU1leXQ=.do"/> <img width="27" height="21" src="source/tsinsen/A1474/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9M0c0R1RueXE=.do"/> 和 <img width="28" height="21" src="source/tsinsen/A1474/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9eVRtWWRiSkU=.do"/> <img width="243" height="21" src="source/tsinsen/A1474/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9blQ4MnFhQkY=.do"/>，表示出发地和目的地的坐标。<br/>
　　第二行包括一个整数 <img width="8" height="21" src="source/tsinsen/A1474/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9R2p5SmpiOTI=.do"/> <img src="source/tsinsen/A1474/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9bW5HODd5RGE=.do" width="87" height="21"/>  ，表示多边形的顶点数。<br/>
　　随后第三行包括 <img width="8" height="21" src="source/tsinsen/A1474/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9eW5KSERHTEg=.do"/> 对整数 <img width="8" height="21" src="source/tsinsen/A1474/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9ckQyZURtTUg=.do"/> 和 <img width="8" height="21" src="source/tsinsen/A1474/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9UkpCRHk1NEY=.do"/> <img width="126" height="21" src="source/tsinsen/A1474/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9OGdkajZkbUw=.do"/> ，描述多边形的顶点坐标。保证其两两不同。</div>
# 输出格式

<div class="pdcont">　　单独一行输出最小的开支。答案的相对误差或绝对误差不超过 <img width="29" height="21" src="source/tsinsen/A1474/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9QkpZcTVydFQ=.do"/> 。</div>
# 样例输入

<div class="pddata">1 7 6 7<br/>
4<br/>
4 2 4 12 3 12 3 2</div>
# 样例输出

<div class="pddata">6.000000000</div>
# 样例输入

<div class="pddata">-1 0 2 0<br/>
4<br/>
0 0 1 0 1 1 0 1</div>
# 样例输出

<div class="pddata">3.000000000</div>
# 数据规模和约定

<div class="pdcont"><table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">#</td><td style="border:solid 1.0pt"><img width="8" height="21" src="source/tsinsen/A1474/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9R2p5SmpiOTI=.do"/> 的值</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">1</td><td align="right" style="border:solid 1.0pt">3</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">2</td><td align="right" style="border:solid 1.0pt">3</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">3</td><td align="right" style="border:solid 1.0pt">3</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">4</td><td align="right" style="border:solid 1.0pt">3</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">5</td><td align="right" style="border:solid 1.0pt">3</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">6</td><td align="right" style="border:solid 1.0pt">4</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">7</td><td align="right" style="border:solid 1.0pt">4</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">8</td><td align="right" style="border:solid 1.0pt">4</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">9</td><td align="right" style="border:solid 1.0pt">5</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">10</td><td align="right" style="border:solid 1.0pt">7</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">11</td><td align="right" style="border:solid 1.0pt">7</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">12</td><td align="right" style="border:solid 1.0pt">9</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">13</td><td align="right" style="border:solid 1.0pt">9</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">14</td><td align="right" style="border:solid 1.0pt">9</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">15</td><td align="right" style="border:solid 1.0pt">9</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">16</td><td align="right" style="border:solid 1.0pt">9</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">17</td><td align="right" style="border:solid 1.0pt">9</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">18</td><td align="right" style="border:solid 1.0pt">10</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">19</td><td align="right" style="border:solid 1.0pt">11</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">20</td><td align="right" style="border:solid 1.0pt">12</td></tr></tbody></table></div>

</div>