
# Description

<div class="content"><div>现有一个传动系统，包含了N个组合齿轮和M个链条。每一个链条连接了两个组合齿轮u和v，并提供了一个传动比x </div>
<div>: y。即如果只考虑这两个组合齿轮，编号为u的齿轮转动x圈，编号为v的齿轮会转动y圈。传动比为正表示若编号</div>
<div>为u的齿轮顺时针转动，则编号为v的齿轮也顺时针转动。传动比为负表示若编号为u的齿轮顺时针转动，则编号为v</div>
<div>的齿轮会逆时针转动。若不同链条的传动比不相容，则有些齿轮无法转动。我们希望知道，系统中的这Ｎ个组合齿</div>
<div>轮能否同时转动。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>有多组数据，第一行给定整数Ｔ，表示总的数据组数，之后依次给出Ｔ组数据。每一组数据的第一行给定整数Ｎ和</div>
<div>Ｍ，表示齿轮总数和链条总数。之后有Ｍ行，依次描述了每一个链条，其中每一行给定四个整数u，v，x和y，表示</div>
<div>只考虑这一组联动关系的情况下，编号为u的齿轮转动x圈，编号为v的齿轮会转动y圈。请注意，x为正整数，而y为</div>
<div>非零整数，但是y有可能为负数。</div>
<div>T&lt;=32，N&lt;=1000，M&lt;=10000且x与y的绝对值均不超过100</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出T行，对应每一组数据。首先应该输出标识这是第几组数据，参见样例输出。之后输出判定结果，如果N个组合</div>
<div>齿轮可以同时正常运行，则输出Yes，否则输出No。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
3 3<br/>
1 2 3 5<br/>
2 3 5 -7<br/>
1 3 3 -7<br/>
3 3<br/>
1 2 3 5<br/>
2 3 5 -7<br/>
1 3 3 7</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case #1: Yes<br/>
Case #2: No</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By AHdoc命题 鸣谢Loi_DQS上传">By AHdoc命题 鸣谢Loi_DQS上传</a></p></div>

