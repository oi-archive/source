
# Description

<div class="content"><div style="margin: 17pt 0cm 16.5pt"><span style="font-size: medium">       你有一个<i>N</i>*<i>M</i>大的长方形菜园，每个格子代表一块田地。</span><span style="font-size: medium"> 现在你想要检查一下菜园内的田地，于是你决定从右上角出发，在菜园里走一圈回到右上角。最后，所有在你走过的这个环内的田地都被认为检查过了。为了保护植物，你的路径只能在田地边界的小路上走，不能走到田地里面。并且你走过的路径不能自交， 小路保证足够宽，你可以多次沿着一条小路走，并且这些路径都不相交。</span></div>
<div style="line-height: 150%"><span style="font-size: medium">       先在给你菜园的地图，其中有的田地标记为”I”，表示这些田地是你想要检查的；有的田地被标记为”X”，表示这些田地是你不想检查的；有的田地被标记为”.”，表示这些田地你不关心。</span></div>
<div style="line-height: 150%"><span style="font-size: medium">       假设菜园中有K个”I”，那么你要输出K个数字，其中第i个数为：恰好检查任意i个标记为”I”的田地，并且没有检查任何一个标记为”X”的田地的最短路。</span></div></div>

# Input

<div class="content"><div style="margin: 13pt 0cm; line-height: 150%"> <span style="font-size: medium">       输入的第一行为<i>N</i>，<i>M</i>表示田地大小。</span></div>
<div style="line-height: 150%"><span style="font-size: medium">       接下来<i>N</i>行，每行<i>M</i>个字母（”I” ，”X” 或 ”.”）描述菜园。</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">       输出一行，<i>K</i>个数字用空格隔开，如题目描述中所述。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">       2 2<br/>
       XX<br/>
       XI<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">       8<br/>
<br/>
       <br/>
</span></div>

# Hint

<div class="content"><p></p><p>       30%满足K=1；<br/><br/>
       100%数据满足N,M≤50，除了”.”之外的字符最多10个。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2010福建集训">2010福建集训</a></p></div>

