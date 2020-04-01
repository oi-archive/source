
# Description

<div class="content">You must have heard of the literature &#34;Alice&#39;s Adventures in Wonderland&#34;! The 3D film &#34;Alice in Wonderland&#34; published by Disney Company becomes the most popular film in 2010! Today, Alice starts her new adventure in Wonderland again!

In Wonderland, there are n cities, numbered from 1 to n. The capital is city 1. Cities are connected by bi-directional roads. The road system is constructed so that from every city, there is exactly one way to reach any other. 

Alice hopes that she could make a tour in which she visits each city exactly once then return to the capital. Furthermore, she doesn&#39;t want to traverse any road more than once. Obviously, it is impossible to make such tour with current road system.

However, in Wonderland, we can use magic spells! The Cheshire Cat, with his magic power, plans to construct more roads to make Alice&#39;s dream come true. Sadly, if he used too many magic spells, he would be weaken. &#34;What is the minimum number of roads I have to construct?&#34; - The poor cat wonders. Could you help him answer this question?

输入一棵树，添加最少的边使得存在从1开始的哈密尔顿回路</div>

# Input

<div class="content">The first line of input contains the number n --- the number of cities in Wonderland (3 ≤ n ≤ 100 000). The following n-1 lines describe the roads. Each road is represented by two integers --- the indexes of two cities it connects.

</div>

# Output

<div class="content">The minimum number of roads to construct. 

</div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 2<br/>
2 3<br/>
2 4<br/>
1 5<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
</span></div>

# Hint

<div class="content"><p>In this example, we can construct 2 roads: 3-4 and 4-5, then Alice will be able to take a tour 1-2-3-4-5-1 <br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢陶文博">鸣谢陶文博</a></p></div>

