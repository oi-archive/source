<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　比特集合是一种抽象数据类型(Abstract Data Type) ，其包含一个集合S，并支持如下几种操作：<br/>
　　INS M : 将元素 M 插入到集合S中；<br/>
　　DEL M : 将集合S中所有等于 M 的元素删除；<br/>
　　ADD M : 将集合S中的所有元素都增加数值M ；<br/>
　　QBIT k : 查询集合中有多少个元素满足其二进制的第 k位为 1 。<br/>
<br/>
　　初始时，集合S为空集。请实现一个比特集合，并对于所有的QBIT操作输出相应的答案。</div>
# 输入格式

<div class="pdcont">　　输入第一行包含一个正整数<i>N</i>，表示操作的数目。<br/>
　　接下来<i>N</i>行，每行为一个操作，格式见问题描述。</div>
# 输出格式

<div class="pdcont">　　对于每一个QBIT操作，输出一行，表示相应的答案。</div>
# 样例输入

<div class="pddata">8<br/>
INS 1<br/>
QBIT 0<br/>
ADD 1<br/>
QBIT 0<br/>
QBIT 1<br/>
DEL 2<br/>
INS 1<br/>
QBIT 1</div>
# 样例输出

<div class="pddata">1<br/>
0<br/>
1<br/>
0</div>
# 数据规模和约定

<div class="pdcont">　　时间限制2s。<br/>
<br/>
　　对于30%的数据，1 ≤ <i>N </i>≤ 10000。<br/>
　　对于100%的数据，1 ≤ <i>N</i> ≤ 500000；QBIT操作中的k满足, 0 ≤ k &lt; 16。INS/DEL操作中，满足0 ≤ M ≤ 10^9；ADD操作中, 满足0 ≤ M ≤ 1000。</div>
# 注意

<div class="pdcont">　　注意集合S可以包含多个重复元素。</div>

</div>