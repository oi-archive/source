
# Description

<div class="content"><div style="background: white" align="left"><span style="font-size: medium"><span style="color: #200000">　　比特集合是一种抽象数据类型</span><span style="color: #200000">(Abstract Data Type) </span><span style="color: #200000">，其包含一个集合</span><span style="color: #200000">S</span><span style="color: #200000">，并支持如下几种操作：</span><span style="color: #200000"><br/>
</span><span style="color: #200000">　　</span><span style="color: #200000">INS M : </span><span style="color: #200000">将元素</span><span style="color: #200000"> M </span><span style="color: #200000">插入到集合</span><span style="color: #200000">S</span><span style="color: #200000">中；</span><span style="color: #200000"><br/>
</span><span style="color: #200000">　　</span><span style="color: #200000">DEL M : </span><span style="color: #200000">将集合</span><span style="color: #200000">S</span><span style="color: #200000">中所有等于</span><span style="color: #200000"> M </span><span style="color: #200000">的元素删除；</span><span style="color: #200000"><br/>
</span><span style="color: #200000">　　</span><span style="color: #200000">ADD M : </span><span style="color: #200000">将集合</span><span style="color: #200000">S</span><span style="color: #200000">中的所有元素都增加数值</span><span style="color: #200000">M </span><span style="color: #200000">；</span><span style="color: #200000"><br/>
</span><span style="color: #200000">　　</span><span style="color: #200000">QBIT k : </span><span style="color: #200000">查询集合中有多少个元素满足其二进制的第</span><span style="color: #200000"> k</span><span style="color: #200000">位为</span><span style="color: #200000"> 1 </span><span style="color: #200000">。</span><span style="color: #200000"><br/>
</span><span style="color: #200000">　　初始时，集合</span><span style="color: #200000">S</span><span style="color: #200000">为空集。请实现一个比特集合，并对于所有的</span><span style="color: #200000">QBIT</span><span style="color: #200000">操作输出相应的答案。</span></span></div></div>

# Input

<div class="content"><div style="background: white" align="left"><span style="font-size: medium"><span style="color: #200000">　　输入第一行包含一个正整数</span><span style="color: #200000">N</span><span style="color: #200000">，表示操作的数目。</span><span style="color: #200000"><br/>
</span><span style="color: #200000">　　接下来</span><span style="color: #200000">N</span><span style="color: #200000">行，每行为一个操作，格式见问题描述。</span></span></div></div>

# Output

<div class="content"><div style="background: white" align="left"><span style="font-size: medium"><span style="color: #200000">　　对于每一个</span><span style="color: #200000">QBIT</span><span style="color: #200000">操作，输出一行，表示相应的答案。</span></span></div></div>

# Sample Input

<div class="content"><span class="sampledata">8<br/>
INS 1<br/>
QBIT 0<br/>
ADD 1<br/>
QBIT 0<br/>
QBIT 1<br/>
DEL 2<br/>
INS 1<br/>
QBIT 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
0<br/>
1<br/>
0<br/>
</span></div>

# Hint

<div class="content"><p></p><p>数据规模和约定<br/><br/>
　　时间限制2s。<br/><br/>
　　对于30%的数据，1 ≤ N ≤ 10000。<br/><br/>
　　对于100%的数据，1 ≤ N ≤ 500000；QBIT操作中的k满足, 0 ≤ k &lt; 16。INS/DEL操作中，满足0 ≤ M ≤ 10^9；ADD操作中, 满足0 ≤ M ≤ 1000。<br/><br/>
注意<br/><br/>
　　注意集合S可以包含多个重复元素。<br/><br/>
 </p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2012国家集训队Round 1 day4">2012国家集训队Round 1 day4</a></p></div>

