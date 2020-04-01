
# Description

<div class="content"><p><span style="font-size: medium">applepi手里有一本书《创世纪》，里面记录了这样一个故事……<br/>
上帝手中有着N 种被称作“世界元素”的东西，现在他要把它们中的一部分投放到一个新的空间中去以建造世界。每种世界元素都可以限制另外一种世界元素，所以说上帝希望所有被投放的世界元素都有至少一个没有被投放的世界元素能够限制它，这样上帝就可以保持对世界的控制。<br/>
由于那个著名的有关于上帝能不能制造一块连自己都不能举起的大石头的二律背反命题，我们知道上帝不是万能的，而且不但不是万能的，他甚至有事情需要找你帮忙——上帝希望知道他最多可以投放多少种世界元素，但是他只会O(2^N) 级别的算法。虽然上帝拥有无限多的时间，但是他也是个急性子。你需要帮助上帝解决这个问题。</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行是一个整数N，表示世界元素的数目。<br/>
第二行有 N 个整数A1, A2, …, AN。Ai 表示第i 个世界元素能够限制的世界元素的编号。</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">一个整数，表示最多可以投放的世界元素的数目。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
2 3 1 3 6 5<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>样例说明<br/><br/>
选择2、3、5 三个世界元素即可。分别有1、4、6 来限制它们。</p><br/>
<p>数据范围与约定<br/><br/>
对于30% 的数据，N≤10。<br/><br/>
对于60% 的数据, N≤10^5。<br/><br/>
对于 100% 的数据，N≤10^6，1≤Ai≤N，Ai≠i。</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Poetize4">Poetize4</a></p></div>

