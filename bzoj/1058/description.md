
# Description

<div class="content"><div>　　小Q的妈妈是一个出纳，经常需要做一些统计报表的工作。今天是妈妈的生日，小Q希望可以帮妈妈分担一些工</div>
<div>作，作为她的生日礼物之一。经过仔细观察，小Q发现统计一张报表实际上是维护一个可能为负数的整数数列，并</div>
<div>且进行一些查询操作。在最开始的时候，有一个长度为N的整数序列，并且有以下三种操作： INSERT i k 在原数</div>
<div>列的第i个元素后面添加一个新元素k； 如果原数列的第i个元素已经添加了若干元素，则添加在这些元素的最后（</div>
<div>见下面的例子） MIN_GAP 查询相邻两个元素的之间差值（绝对值）的最小值 MIN_SORT_GAP 查询所有元素中最接</div>
<div>近的两个元素的差值（绝对值） 例如一开始的序列为 5 3 1 执行操作INSERT 2 9将得到： 5 3 9 1 此时MIN_GAP</div>
<div>为2，MIN_SORT_GAP为2。 再执行操作INSERT 2 6将得到： 5 3 9 6 1 注意这个时候原序列的第2个元素后面已经</div>
<div>添加了一个9，此时添加的6应加在9的后面。这个时候MIN_GAP为2，MIN_SORT_GAP为1。于是小Q写了一个程序，使</div>
<div>得程序可以自动完成这些操作，但是他发现对于一些大的报表他的程序运行得很慢，你能帮助他改进程序么？</div></div>

# Input

<div class="content"><div>　　第一行包含两个整数N，M，分别表示原数列的长度以及操作的次数。第二行为N个整数，为初始序列。接下来</div>
<div>的M行每行一个操作，即“INSERT i k”，“MIN_GAP”，“MIN_SORT_GAP”中的一种（无多余空格或者空行）。</div></div>

# Output

<div class="content"><p>　　对于每一个“MIN_GAP”和“MIN_SORT_GAP”命令，输出一行答案即可。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 5<br/>
5 3 1<br/>
INSERT 2 9<br/>
MIN_SORT_GAP<br/>
INSERT 2 6<br/>
MIN_GAP<br/>
MIN_SORT_GAP</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
2<br/>
1</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">N , M ≤500000 对于所有的数据，序列内的整数不超过5*10^8。</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

