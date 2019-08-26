
# Description

<div class="content"><div id="ptit" class="probtitle" style="text-align: center; padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; font-family: 微软雅黑, 黑体, &#39;Times New Roman&#39;; font-size: 24pt; font-weight: bold; padding-top: 0px"></div>
<div id="pres" style="text-align: center; padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; font-family: 宋体, &#39;Times New Roman&#39;; font-size: 14px; vertical-align: middle; font-weight: bold; padding-top: 0px"></div>
<div id="pcont1" style="text-align: left; padding-bottom: 0px; margin: 20px 0px 0px; padding-left: 0px; padding-right: 0px; font-family: 宋体, &#39;Times New Roman&#39;; padding-top: 0px">
<div class="pdcont" style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; font-family: &#39;Times New Roman&#39;, 宋体; color: rgb(32,0,0); font-size: 14px; padding-top: 0px">　　Answer在看过碟中谍后，对“X中X”很感兴趣，于是想探究“图中图”。<br style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px"/>
“图中图”的外图是一张由M个大节点组成的有K条边(无重边和自环)的无向无权图(不一定连通)，外图中的每个大节点的内部又是一张由若干条边组成的无向有权图。<br style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px"/>
Answer想要构一张“图中图”，对大节点之间的边可以随便连K条，对每个大节点内部的无向图，Answer有一种生成方法：<br style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px"/>
1. 先确定一个长度为N的序列A<br style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px"/>
2. 对于每个大节点，确定一个在A中的区间[l<sub style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px">i </sub>, r<sub style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px">i</sub>]<br style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px"/>
3. 那么在第i个大节点中，<br style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px"/>
边数=sigma(sum<sub style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px">x</sub>+num<sub style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px">x</sub><sup style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px">3</sup>) 区间[l<sub style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px">i </sub>, r<sub style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px">i</sub>]中存在x<br style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px"/>
其中sum<sub style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px">x</sub>为在区间[l<sub style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px">i </sub>, r<sub style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px">i</sub>]中比x小的数字个数，num<sub style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px">x</sub>为区间[l<sub style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px">i </sub>, r<sub style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px">i</sub>]中等于x的数字个数。<br style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px"/>
设t为在区间[l<sub style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px">i </sub>, r<sub style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px">i </sub>]中出现的不重复的数字个数，那么每条边上的权值可以取1~t的任意正整数。<br style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px"/>
现在，Answer想要求出在给M,K,序列A和每个大节点的区间[l<sub style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px">i </sub>, r<sub style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px">i </sub>]的情况下，有多少张不同的“图中图”，由于方案数可能很大，你只需要输出方案数模P后的答案。<br style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px"/>
*对于大节点，Answer只关心边的情况，而不关心点的情况，每个大节点中的边是有标号的，两个方案不同当且仅当，M个大节点的连接状况不同或者至少其中有一个大节点的其中一条边的权值不同。</div>
<div class="pdsec" style="border-bottom: rgb(187,187,187) 1px solid; padding-bottom: 4px; background-color: rgb(248,248,255); margin: 8px 0px 4px; padding-left: 6px; padding-right: 0px; font-family: 微软雅黑, 黑体, 华文细黑; font-size: 16px; font-weight: bold; padding-top: 4px; border-top-left-radius: 4px; border-top-right-radius: 4px; border-bottom-right-radius: 0px; border-bottom-left-radius: 0px"></div>
<div class="pdcont" style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; font-family: &#39;Times New Roman&#39;, 宋体; color: rgb(32,0,0); font-size: 14px; padding-top: 0px"></div>
</div>
<p></p></div>

# Input

<div class="content"><div class="pdsec" style="border-bottom: rgb(187,187,187) 1px solid; text-align: left; padding-bottom: 4px; background-color: rgb(248,248,255); margin: 8px 0px 4px; padding-left: 6px; padding-right: 0px; font-family: 微软雅黑, 黑体, 华文细黑; font-size: 16px; font-weight: bold; padding-top: 4px; border-top-left-radius: 4px; border-top-right-radius: 4px; border-bottom-right-radius: 0px; border-bottom-left-radius: 0px"></div>
<div class="pdcont" style="text-align: left; padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; font-family: &#39;Times New Roman&#39;, 宋体; color: rgb(32,0,0); font-size: 14px; padding-top: 0px">　　输入的第一行包含四个正整数N,M,P,K。<br style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px"/>
第二行包含N个正整数A<sub style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px">i</sub>。<br style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px"/>
以下M行，每行包含两个正整数l<sub style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px">i</sub>,r<sub style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px">i</sub>。<br style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px"/>
意义如上。</div>
<div class="pdsec" style="border-bottom: rgb(187,187,187) 1px solid; text-align: left; padding-bottom: 4px; background-color: rgb(248,248,255); margin: 8px 0px 4px; padding-left: 6px; padding-right: 0px; font-family: 微软雅黑, 黑体, 华文细黑; font-size: 16px; font-weight: bold; padding-top: 4px; border-top-left-radius: 4px; border-top-right-radius: 4px; border-bottom-right-radius: 0px; border-bottom-left-radius: 0px"></div>
<div class="pdcont" style="text-align: left; padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; font-family: &#39;Times New Roman&#39;, 宋体; color: rgb(32,0,0); font-size: 14px; padding-top: 0px"></div>
<p></p></div>

# Output

<div class="content"><p></p>
<div></div>
<div>
<div class="pdcont" style="text-align: left; padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; font-family: &#39;Times New Roman&#39;, 宋体; color: rgb(32,0,0); font-size: 14px; padding-top: 0px">　　输出一个整数，表示方案数模P后的值。</div>
<div class="pdsec" style="border-bottom: rgb(187,187,187) 1px solid; text-align: left; padding-bottom: 4px; background-color: rgb(248,248,255); margin: 8px 0px 4px; padding-left: 6px; padding-right: 0px; font-family: 微软雅黑, 黑体, 华文细黑; font-size: 16px; font-weight: bold; padding-top: 4px; border-top-left-radius: 4px; border-top-right-radius: 4px; border-bottom-right-radius: 0px; border-bottom-left-radius: 0px"></div>
<div class="pdcont" style="text-align: left; padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; font-family: &#39;Times New Roman&#39;, 宋体; color: rgb(32,0,0); font-size: 14px; padding-top: 0px"></div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">5 3 22 2<br/>
1 2 1 3 1<br/>
1 3<br/>
2 4<br/>
3 5<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">14<br/>
</span></div>

# Hint

<div class="content"><p></p><div>样例说明</div><br/>
<div>　　外图中有3个大节点，那么连2条边，有3种连法</div><br/>
<div>　　第一个大节点中有11条边，每条边可以取值1~2</div><br/>
<div>　　第二个大节点中有6条边，每条边可以取值1~3</div><br/>
<div>　　第三个大节点中有11条边，每条边可以取值1~2</div><br/>
<div>　　所以总方案数模22得14</div><br/>
<div>数据规模和约定</div><br/>
<div>　　设P=p1 c1 *p2c2 *…*ptct ，pi为质数。</div><br/>
<div>　　对于30%的数据，满足N,M≤1000,M2&lt;P&lt;10^9且P是质数</div><br/>
<div>　　另有20%的数据，满足N,M≤1000</div><br/>
<div>　　对于100%的数据,满足N,M≤50000 , K≤M*(M-1)/2 , 0≤ai≤10^9</div><br/>
<div>pi^ci ≤100000 , P≤10^9</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

