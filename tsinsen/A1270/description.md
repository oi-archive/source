<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　BX正在进行一个字符串游戏，他手上有一个字符串<i>L</i>，以及其他一些字符串的集合<i>S</i>，然后他可以进行以下操作：对于一个在集合<i>S</i>中的字符串<i>p</i>,如果<i>p</i>在<i>L</i>中出现，BX就可以选择是否将其删除，如果删除，则将删除后<i>L</i>分裂成的左右两部分合并。<br/>
　　举个例子，<i>L</i>=&#39;abcdefg&#39; , <i>S</i>={&#39;de&#39;}，如果BX选择将&#39;de&#39;从<i>L</i>中删去，则删后的<i>L</i>=&#39;abcfg&#39;。<br/>
　　现在BX可以进行任意多次操作（删的次数，顺序都随意），他想知道最后<i>L</i>串的最短长度是多少。</div>
# 输入格式

<div class="pdcont">　　输入的第一行包含一个字符串，表示<i>L</i>。<br/>
　　第二行包含一个数字<i>n</i>，表示集合<i>S</i>中元素个数。<br/>
　　以下<i>n</i>行，每行一个字符串，表示<i>S</i>中的一个元素。<br/>
　　输入字符串都只包含小写字母。</div>
# 输出格式

<div class="pdcont">　　输出一个整数，表示L的最短长度。</div>
# 样例输入

<div class="pddata">aaabccd<br/>
3<br/>
ac<br/>
abc<br/>
aaa</div>
# 样例输出

<div class="pddata">2</div>
# 样例说明

<div class="pdcont">　　aaabccd<br/>
　　aacd<br/>
　　ad</div>
# 数据规模和约定

<div class="pdcont">　　对于40%数据，满足|<i>L</i>|&lt;9<br/>
　　对于100%数据,满足|<i>L</i>|&lt;151,|<i>S</i>|&lt;31,S中的每个元素|<i>p</i>|&lt;21</div>

</div>