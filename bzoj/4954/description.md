
# Description

<div class="content"><div>细胞自动制造公司 (Automatic Cellular Manufacturing) 最近刚刚获得批量生产零件的新工艺专利。它的方法使</div>
<div>用到包含两种细胞状态的二维网格,每个单元的细胞要么为空,要么为满。当然,具体的细节是专有的。最初,网格中</div>
<div>的一组单元被填充为需要复制的细胞副本。进过一系列离散的步骤,网格中的每个单元会根据自身及附近的八个单</div>
<div>元的状态同步进行细胞状态更新。如果这九个单元中有奇数个位置的细胞是满的,那么这个单元的下一个状态也是</div>
<div>满的,否则会是空的。图1显示了一个由三个满细胞的单元组成的简单模式在复制过程中的几个步骤。</div>
<div><img src="/source/bzoj/4954/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTcwOC81NS5wbmc=.png" width="837" height="184" alt=""/></div>
<div></div>
<div>图1. 复制过程。</div>
<div>然而,一个bug已经蛰伏在工艺中了。在每次更新单元状态之后,网格中某一个单元的状态可能自动变化。例如,图2</div>
<div>显示了可能的变化,其中一个细胞在第一次状态更新后出现了自动变化,另一个细胞在第三次状态更新后出现了自动</div>
<div>变化。</div>
<div><img src="/source/bzoj/4954/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTcwOC82Ni5wbmc=.png" width="853" height="195" alt=""/></div>
<div></div>
<div>图2. 复制过程中的错误。该图对应样例输入1。</div>
<div>很不幸,最初的细胞模式丢失了,只有 (可能受到bug影响的) 复制结果保留了下来。你能否编个程序确定可能的最</div>
<div>小的非空的初始细胞模式来产生给定的最终模式呢?</div></div>

# Input

<div class="content"><div>第一行包含两个整数w(1≤w≤300)和h(1≤h≤300),其中w和h表示最终模式的边框宽度与高度。</div>
<div>接下来h 行,每行包含w个字符,描述了最终的模式。每个字符要么是&#39;.&#39;(表示该单元为空),要</div>
<div>么是&#39;#&#39;(表示该单元为满) 。</div>
<div>保证在第一行、最后一行、第一列、最后一列均存在至少一个单元是满的。</div></div>

# Output

<div class="content"><div>输出最小的非空的可能产生最终模式的初始模式,这里假设每个阶段至多会有一个单元状态自动变化。</div>
<div>模式的大小取决于边框内的区域。</div>
<div>如果由多种可能的最小的非空的初始模式,那么任意一种答案都是可接受的。</div>
<div>请你使用字符&#39;.&#39;表示空的单元,使用&#39;#&#39;表示满的单元。请你用必须要使用的最小行数和列数来输出这个模式。</div></div>

# Sample Input

<div class="content"><span class="sampledata">样例1<br/>
10 10<br/>
.#...#...#<br/>
##..##..##<br/>
##.#.##...<br/>
##.#.##...<br/>
.#...#####<br/>
...##..#.#<br/>
......###.<br/>
##.#.##...<br/>
#..#..#..#<br/>
##..##..##<br/>
样例2<br/>
8 8<br/>
##..#.##<br/>
#.####.#<br/>
.#.#.#..<br/>
.##.#.##<br/>
.#.#.#..<br/>
.##.#.##<br/>
#..#.###<br/>
##.#.##.<br/>
样例3<br/>
5 4<br/>
#....<br/>
..###<br/>
..###<br/>
..###</span></div>

# Sample Output

<div class="content"><span class="sampledata">样例1<br/>
.#<br/>
##<br/>
样例2<br/>
####<br/>
#..#<br/>
#.##<br/>
###.<br/>
样例3<br/>
#</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tangjz提供翻译">鸣谢Tangjz提供翻译</a></p></div>

