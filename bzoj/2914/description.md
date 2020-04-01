
# Description

<div class="content"><div><span style="font-size: 18pt">   </span><span style="font-size: 15pt">科学家们发现了一种新的放射性元素——ADDON。ADDON是已知的效率最高的核燃料，因此他们决定建立一个ADDON核反应堆。</span></div>
<div style="text-indent: 30pt"><span style="font-size: 15pt">根据计划，一间燃料室是一根竖直的管子。燃料棒（即装有ADDON的圆筒）将一根叠一根的被放进燃料室里，搭建成一个圆柱。燃料棒具有不同的高度。</span></div>
<div style="text-indent: 30pt"><span style="font-size: 15pt">核反应循环开始于将燃料棒放进燃料室中。接下来的步骤才是点火。麻烦的是，圆柱的高度不能是任意的——只有某些特定的高度才能保证反应的安全。这样的高度被称作稳定高度。</span></div>
<div style="text-indent: 30pt"><span style="font-size: 15pt">现在，反应堆的设计师们面临着两个任务：确定燃料室的高度以及选择一个用于制造ADDON的燃料棒的高度集合。</span></div>
<div style="text-indent: 30pt"><span style="font-size: 15pt">我们说一个高度集合是安全的（对于一个特定高度的燃料室），则有：对于任意一根由高度属于这个集合的燃料棒搭建而成的，且高度不超过燃料室的高度的圆柱，它的高度一定是稳定的。</span></div>
<div style="text-indent: 30pt"><span style="font-size: 15pt">我们说一个高度集合是完备的（对于一个特定高度的燃料室），则有：对于任意一根高度是稳定的,</span><span style="font-size: 15pt">并</span><span style="font-size: 15pt">且其高度不超过燃料室高度的圆柱，都一定能够由高度属于该集合的燃料棒搭建而成。</span></div>
<div><b><span style="font-size: 15pt">任务</span></b></div>
<div style="text-indent: 30pt"><span style="font-size: 15pt">写一个程序</span></div>
<div style="margin: 0cm 0cm 0pt 48pt; text-indent: -18pt"><span style="font-size: 15pt">1. </span><span style="font-size: 15pt">读入一个稳定高度的集合；</span></div>
<div style="margin: 0cm 0cm 0pt 48pt; text-indent: -18pt"><span style="font-size: 15pt">2. </span><span style="font-size: 15pt">找出存在一个安全且完备的高度集合的核燃料室的最大可能值；</span></div>
<div style="margin: 0cm 0cm 0pt 48pt; text-indent: -18pt"><span style="font-size: 15pt">3. </span><span style="font-size: 15pt">对于找到的核燃料室，找出一个元素个数最少的安全且完备的高度集合；</span></div>
<div style="margin: 0cm 0cm 0pt 48pt; text-indent: -18pt"><span style="font-size: 15pt">4. </span><span style="font-size: 15pt">将结果输出</span></div></div>

# Input

<div class="content"><div style="text-indent: 30pt"><span style="font-size: 15pt">第一行是一个自然数n（1&lt;=n&lt;=10000），代表所给的稳定高度的个数。</span></div>
<div style="text-indent: 30pt"><span style="font-size: 15pt">接下来的n行，每行是一个不超过10000的正整数。这些数按照升序给出，代表了稳定高度。</span></div></div>

# Output

<div class="content"><div style="text-indent: 30pt"><span style="font-size: medium">第一行是找到的燃料室高度的最大可能值。</span></div>
<div><span style="font-size: medium">接下来的每行按照升序给出你所找到的高度集合中的一个元素。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">14<br/>
5<br/>
10<br/>
12<br/>
15<br/>
17<br/>
20<br/>
21<br/>
22<br/>
24<br/>
26<br/>
27<br/>
30<br/>
31<br/>
33<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">24<br/>
5<br/>
12<br/>
21<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

