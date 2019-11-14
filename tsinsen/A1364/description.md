<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　近日，社交网络研究的鼻祖Jon Kleinberg教授在清华大学给同学们带来了一个关于社交网络结构洞（Structural Hole）的主题演讲。对社交网络有着浓厚兴趣的小W也旁听了这次演讲。在演讲中Jon Kleinberg教授讲到社交网络结构洞是描述一个人在一个社交网络中重要程度的一个指标，那么如何定量地分析每一个人在社交网络的重要程度呢？<br/>
　　小W阅读很多参考文献，发现有一种通过计算社会关系跨度的方法。<br/>
<br/>
<br/>
　　【定义】社交网络用<img src="source/tsinsen/A1364/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9ZUI1WUR5Z0E=.do" width="80" height="20"/>表示一个社交网络，其中<img src="source/tsinsen/A1364/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9ZlE2RU5oYTk=.do" width="15" height="26"/>是网络中人的集合，<img width="82" height="17" src="source/tsinsen/A1364/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9WU1BbmZMUmE=.do"/>是人与人之间的关系集合。<br/>
　　【定义】社交网络距离<img src="source/tsinsen/A1364/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9VEVCZjdoOVk=.do" width="22" height="21"/>和<img src="source/tsinsen/A1364/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9N0ZhMjU2bTk=.do" width="17" height="24"/>两个人的社交网络距离<img src="source/tsinsen/A1364/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9SDhBdDRNRW4=.do" width="41" height="26"/>为<img src="source/tsinsen/A1364/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9VEVCZjdoOVk=.do" width="22" height="21"/>和<img src="source/tsinsen/A1364/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9N0ZhMjU2bTk=.do" width="17" height="24"/>之间的最短距离。<br/>
　　【定义】社会关系跨度用<img src="source/tsinsen/A1364/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9MmdURWpFTU4=.do" width="104" height="28"/>表示，是在社交网络中去掉所有与<img src="source/tsinsen/A1364/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9RVlGTEhtNkE=.do" width="20" height="26"/>相关的边（即边的一个端点为<img src="source/tsinsen/A1364/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9RVlGTEhtNkE=.do" width="20" height="26"/>）之后<img src="source/tsinsen/A1364/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9VEVCZjdoOVk=.do" width="22" height="21"/>和<img src="source/tsinsen/A1364/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9N0ZhMjU2bTk=.do" width="17" height="24"/>之间的最短距离。<br/>
　　那么描述每一个人的结构洞值<img src="source/tsinsen/A1364/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9TVJNSG41UWU=.do" width="38" height="33"/>表示其所有邻居节点之间社会关系跨度与社交网络距离差值的和。<br/>
<img src="source/tsinsen/A1364/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9Sm5MYjNmNTI=.do" width="476" height="91"/><br/>
　　(结构洞值的定义）<br/>
<br/>
<br/>
　　其中<img width="68" height="33" src="source/tsinsen/A1364/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9QWE0TDhMM0c=.do"/>表示<img src="source/tsinsen/A1364/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9VEVCZjdoOVk=.do" width="22" height="21"/>的邻居节点集合。<br/>
　　由于社交网络中人的数量十分庞大，计算每个人的结构洞值也变得十分困难。小W想请你帮助设计出一种好的计算方法，求出社交网络中所有人的结构洞值。</div>
# 输入格式

<div class="pdcont">　　输入的第一行包含两个整数n,m，表示社交网络中人的数量（人从1到n编号）和关系的数量。<br/>
　　接下来m行描述人们的关系情况，其中第i行包含两个整数<i>a<sub>i</sub></i>和<i>b<sub>i, </sub></i>1&lt;=<i>a</i><sub><i>i</i>,</sub><i>b<sub>i</sub></i>&lt;=n，表示<i>a</i><sub><i>i</i></sub>和<i>b<sub>i</sub></i>两个人之间在社交网络中有直接关系。</div>
# 输出格式

<div class="pdcont">　　输出一共n行，每行一个整数，表示每个人在社交网络中的结构洞值。</div>
# 样例输入

<div class="pddata">5 7<br/>
2 4<br/>
5 4<br/>
3 2<br/>
3 4<br/>
3 1<br/>
5 3<br/>
5 1</div>
# 样例输出

<div class="pddata">0<br/>
0<br/>
1<br/>
0<br/>
0</div>
# 对样例的说明

<div class="pdcont"><img src="source/tsinsen/A1364/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9ZTZhdG1uUUY=.do" width="935" height="328"/></div>
# 数据规模和约定

<div class="pdcont">　　所有测试数据的范围和特点如下表所示。<br/>
<img src="source/tsinsen/A1364/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9OHRuZmRhQUc=.do" width="904" height="659"/></div>

</div>