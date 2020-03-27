# 题目描述

<p>今天是世界水日，著名的水题资源专家蝈蝈大臣向世界展示了他的一道又裸又水又原的题 —— <strong>排序问题</strong>。</p>
<p>蝈蝈大臣只是个idea的搬运工，当然不愿意自己造测试数据啦！所以他委托他的助手欧姆来造。</p>
<p>欧姆当然会造数据啦！但是他想考考你。</p>
<p>欧姆写了一些貌似可以解决此题的代码。在给任务设计数据的时候，欧姆期望其中的一些源程序能够得到满分，而另外的一些则只能得到 $0$ 分或者少许的部分分。现在你将会获得这些源程序（C++ 以及 Pascal 版本）。对于每个子任务，你需要去产生一组数据 $X$ 使得它能将该任务给定的 $2$ 种程序 $A$ 和 $B$ 区分开来。更具体地说，生成的数据必须满足如下两个条件： </p>
<ol><li>输入 $X$ 一定不会使程序 $A$ 出现超出时间限制（TLE）的问题。</li>
<li>输入 $X$ 一定会导致程序 $B$ 产生超出时间限制的问题。 </li>
</ol><p>所有的程序内置了一个计数器变量 <samp>counter</samp>，程序运行完毕时 <samp>counter</samp> 的值定义为该程序的<strong>用时</strong>。如果程序一定不会结束或用时超过了 $2000000$ 即为超出时间限制。</p>
<p>在满足这两个条件的前提下，欧姆希望程序 $A$ 的<strong>用时要尽可能小</strong>。欧姆设定了一个参数 $T$，他希望程序 $A$ 的用时不要超过参数 $T$。（注：本题中只关心程序是否超出时间限制，不关心是否结果正确） </p>
<p>欧姆写的 C++和 Pascal 源程序放在了“输入数据及源程序下载”中。</p>

# 排序问题的题目描述


<p>给出 $n$ 个非负整数 $a_1, \dots, a_n$，将它们按从小到大排序。即排序后满足 $a_1 \leq a_2 \leq \dots \leq a_n$。</p>

# 排序问题的输入格式


<p>第一行是一个正整数 $n$。</p>
<p>接下来 $n$ 行，第 $i$ 行包含一个非负整数表示 $a_i$。</p>

# 排序问题的输出格式


<p>输出一行，包含 $n$ 个非负整数表示排序的结果，以空格隔开。</p>

# 排序问题的限制与约定


<p>$1 \leq n \leq 30000, 0 \leq a_i \leq 10000000$。</p>

# 子任务


<p>我们一共有 6 个程序，分别都提供了 C++ 和 Pascal 两个版本的源代码。（什么？你是C语言选手？直接看C++程序就可以啦！）</p>
<ul><li>bogo_sort: Bogo排序。每次把数列胡乱地打乱，判定是否有序，直到有序为止。<a href="//zh.wikipedia.org/wiki/Bogo%E6%8E%92%E5%BA%8F">维基介绍</a></li>
<li>bubble_sort: 冒泡排序。重复地走访过要排序的数列，每次比较相邻两个元素，如果它们的顺序错误就把他们交换过来。<a href="//zh.wikipedia.org/wiki/%E5%86%92%E6%B3%A1%E6%8E%92%E5%BA%8F">维基介绍</a></li>
<li>selection_sort：选择排序。每次在未排序的部分找到最小的元素放到已排序数列的末尾。<a href="//zh.wikipedia.org/wiki/%E9%80%89%E6%8B%A9%E6%8E%92%E5%BA%8F">维基介绍</a></li>
<li>counting_sort：计数排序。使用一个额外的数组 $C$，其中第 $i$ 个元素是待排序数组 $A$ 中值等于 $i$ 的元素的个数，然后将 $A$ 中的元素排到正确的位置。<a href="//zh.wikipedia.org/wiki/%E8%AE%A1%E6%95%B0%E6%8E%92%E5%BA%8F">维基介绍</a></li>
<li>merge_sort：归并排序。把数列分成左右两部分递归进行排序，然后利用归并操作合并两个有序数组。<a href="//zh.wikipedia.org/wiki/%E5%BD%92%E5%B9%B6%E6%8E%92%E5%BA%8F">维基介绍</a></li>
<li>quick_sort：快速排序。从数列中挑出一个元素作为基准，接着把比基准小的数放在基准左边，大的放右边，递归左右两边进行排序。<a href="//zh.wikipedia.org/wiki/%E5%BF%AB%E9%80%9F%E6%8E%92%E5%BA%8F">维基介绍</a></li>
</ul><p>不保证给出的程序总能在人类可接受的时限运行完毕。</p>
<p>不要尝试用自然溢出等方式把 <samp>counter</samp> 设定为一个负数，在OJ上进行评测时将会在 <samp>counter</samp> 大于 $9999999$ 时自动结束程序。</p>
<p>表中每一行描述了一个子任务。每个任务所占分数见下表。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th>
<th>分值</th>
<th>$T$</th>
<th>源程序 $A$</th>
<th>源程序 $B$</th>
</tr></thead><tbody><tr><td>1</td><td>5</td><td>$7$</td><td>归并排序 merge_sort</td><td>计数排序 counting_sort</td></tr><tr><td>2</td><td>8</td><td>$1986591$</td><td>冒泡排序 bubble_sort</td><td>选择排序 selection_sort</td></tr><tr><td>3</td><td>18</td><td>$116792$</td><td>归并排序 merge_sort</td><td>快速排序 quick_sort</td></tr><tr><td>4</td><td>19</td><td>$4117$</td><td>计数排序 counting_sort</td><td>冒泡排序 bubble_sort</td></tr><tr><td>5</td><td>20</td><td>$536443$</td><td>选择排序 selection_sort</td><td>冒泡排序 bubble_sort</td></tr><tr><td>6</td><td>30</td><td>$43026$</td><td>Bogo排序 bogo_sort</td><td>快速排序 quick_sort</td></tr></tbody></table></div>

<p>番外篇：对于 5 号点，如果比赛期间你玩出了用时不超过 $535274$ 的解，送 UOJ 抱枕一个（或者给你价值为抱枕价格的奖金）！如果多个人玩出来了只送给用时最少的同学，如果有多个用时最少的同学只送给提交记录编号最小的同学。</p>
<p><strong>番外篇++：目前的最优解是wangyisong1996的523056，提交于2015-03-23 19:56:51。如果你跑出了更优的解快去UOJ群里喊一嗓子→_→</strong></p>

# 输入格式


<p>该题为提交答案型试题，所有输入数据 tasksauthor1.in ~ tasksauthor6.in 见“输入数据及源程序下载”。</p>
<p>一行一个整数 $k$，$1 \leq k \leq 6$，表示你需要解决的子任务编号。</p>

# 输出格式


<p>针对给定的 6 个输入文件 tasksauthor1.in ~ tasksauthor6.in，你需要分别提交你的输出文件 tasksauthor1.out ~ tasksauthor6.out。</p>
<p>输出文件内容为一个排序问题的输入 $X$，表示你的答案。格式见“排序问题的输入格式”一节。</p>

# 评分方式


<p>对于每个子任务，你给出的输入 $X$ 需要能够将源程序 $A$ 和 $B$ 区分开来，只有这样你才能够得到相应的分数。</p>
<p>具体说来，如果程序 $A$ 超时或者程序 $B$ 通过，则此子任务不得分。</p>
<p>否则，你的分数将由程序 $A$ 的用时 $S$ 决定。如果 $S \leq T$ 则此测试点得满分，否则若此测试点满分为 $P$，则此测试点的得分为 $\max(P \cdot (1 - \frac{S - T}{2000}), 1)$，如果得分不是整数则向下取整到整数。</p>
<p>对于每个子任务，保证存在某个输入 $X$，使得它能够使程序 $B$ 超时，并且使程序 $A$ 的用时为 $T$。</p>
<p><strong>注意比赛时提交此题显示的成绩就是最终成绩。</strong></p>

# 下载


<p><a href="/download.php?type=problem&amp;id=83">输入数据及源程序下载</a></p>
