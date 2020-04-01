<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　有两位医生和两位病人，每位医生需要为每位病人做一场手术。为了避免医生的手直接接触到病人，医生在手术中必须佩带手套。然而，手套被使用后，内表面会沾染医生的汗液，外表面会沾染病人的血液。医生和病人都不愿意接触到其他人的汗液或血液。现在，只有两副手套，如何完成这四场手术？<br/>
　　使用传统的方法，是不可能通过两副手套完成四场手术的。于是，我们想到了一个神奇的方法——将两副手套套在一起！但是，将手套套在一起可能导致接触面的损坏。根据多年的临床经验总结，只有两副手套的接触面均为全新（没有任何汗液和血液且没有被损坏过）的情况下，才不会导致接触面损坏，否则接触的两个表面均会被损坏。若一副手套的某个表面被损坏过，则医生和病人都不再愿意接触该表面。在尝试了各种方法后，我们得到了下面的解决方案：<br/>
　　步骤一：医生<i>0</i>给病人<i>0</i>做手术，使用手套<i>b</i>套手套<i>a</i>（手套<i>b</i>在外面）<br/>
　　步骤二：医生<i>0</i>给病人<i>1</i>做手术，使用手套<i>a</i><br/>
　　步骤三：医生<i>1</i>给病人<i>0</i>做手术，使用手套<i>b</i><br/>
　　步骤四：医生<i>1</i>给病人<i>1</i>做手术，使用手套<i>a</i>套手套<i>b</i>（手套<i>a</i>在外面）<br/>
　　显然，佩戴过多的手套会影响手术质量，所以我们规定一场手术中最多使用两副手套套在一起。现在，我们有<i>n</i>位医生，<i>m</i>位病人，其中某些医生需要给某些病人做手术。请你帮忙计算，最少使用多少副手套可以完成所有手术？<br/>
　　值得注意的是：一副手套被当做一个整体，不可以拆成“两只”分别使用。此外，如果有必要，手套是可以“翻过来”使用的。</div>
# 输入格式

<div class="pdcont">　　输入的第一行包含一个正整数<i>T</i>，表示该文件中含有<i>T</i>组测试数据。<br/>
　　对于每组测试数据：第一行有三个正整数<i>n</i>、<i>m</i>、<i>s</i>。表示有<i>n</i>位医生（编号<i>0</i>至<i>n-1</i>），有<i>m</i>位病人（编号<i>0</i>至<i>m-1</i>），有<i>s</i>场手术（编号<i>0</i>至<i>s-1</i>）。随后<i>s</i>行，按编号顺序描述每一场手术。每行有两个非负整数<i>x</i>、<i>y</i>，表示<i>x</i>号医生和<i>y</i>号病人需要做一场手术。数据保证不会出现两场相同的手术。</div>
# 输出格式

<div class="pdcont">　　输出中应包含<i>T</i>组测试数据的答案。<br/>
　　对于每一组答案：第一行包含一个正整数<i>p</i>，表示你需要使用<i>p</i>副手套（从字母<i>a</i>开始顺序编号）。随后<i>s</i>行，你需要按<b>时间顺序</b>描述每场手术安排，每场手术单独使用一行。对于一场手术，你需要先输出它的编号，随后输出它使用的手套数量<i>k</i>（必须是<i>1</i>或<i>2</i>），接下来以<b>自内向外</b>（从医生向病人）的顺序输出所使用的<i>k</i>副手套的编号（字母），并用空格分隔。特别地。若某副手套在该次手术中是以“翻过来”的状态使用的，则用对应的大写字母来表示，否则用小写字母表示，详见样例。</div>
# 样例输入

<div class="pddata">2<br/>
2 2 4<br/>
0 1<br/>
0 0<br/>
1 0<br/>
1 1<br/>
3 2 3<br/>
0 1<br/>
1 0<br/>
2 1</div>
# 样例输出

<div class="pddata">2<br/>
1 2 a b<br/>
0 1 a<br/>
2 1 b<br/>
3 2 b a<br/>
3<br/>
0 2 a b<br/>
1 2 A B<br/>
2 1 c</div>
# 数据规模和约定

<div class="pdcont"><table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">测试点编号<br/>
</td><td style="border:solid 1.0pt"><i>n</i><br/>
</td><td style="border:solid 1.0pt">m<br/>
</td><td style="border:solid 1.0pt"><i>s</i><br/>
</td><td style="border:solid 1.0pt">T<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">1<br/>
</td><td style="border:solid 1.0pt"><i>n</i> ≤ 3<br/>
</td><td style="border:solid 1.0pt"><i>m </i>≤ 3<br/>
</td><td rowspan="10" style="border:solid 1.0pt"><i>s </i>≤ <i>n*m</i><br/>
</td><td rowspan="10" style="border:solid 1.0pt">T ≤ 10<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">2<br/>
</td><td style="border:solid 1.0pt"><i>n</i> =1<br/>
</td><td style="border:solid 1.0pt"><i>m </i>≤ 10<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">3<br/>
</td><td style="border:solid 1.0pt"><i>n</i> ≤ 4<br/>
</td><td style="border:solid 1.0pt"><i>m </i>≤ 4<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">4<br/>
</td><td style="border:solid 1.0pt"><i>n</i> ≤ 6<br/>
</td><td style="border:solid 1.0pt"><i>m </i>≤ 6<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">5<br/>
</td><td style="border:solid 1.0pt"><i>n</i> ≤ 6<br/>
</td><td style="border:solid 1.0pt"><i>m </i>≤ 10<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">6<br/>
</td><td style="border:solid 1.0pt"><i>n</i> ≤ 7<br/>
</td><td style="border:solid 1.0pt"><i>m </i>≤ 7<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">7<br/>
</td><td style="border:solid 1.0pt"><i>n</i> ≤ 8<br/>
</td><td style="border:solid 1.0pt"><i>m </i>≤ 8<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">8<br/>
</td><td style="border:solid 1.0pt"><i>n</i> ≤ 9<br/>
</td><td style="border:solid 1.0pt"><i>m </i>≤ 9<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">9<br/>
</td><td style="border:solid 1.0pt"><i>n</i> ≤ 9<br/>
</td><td style="border:solid 1.0pt"><i>m </i>≤ 10<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">10<br/>
</td><td style="border:solid 1.0pt"><i>n</i> ≤ 10<br/>
</td><td style="border:solid 1.0pt"><i>m </i>≤ 10<br/>
</td></tr></tbody></table></div>

</div>