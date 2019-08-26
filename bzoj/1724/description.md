
# Description

<div class="content"><p><span style="font-size: medium">Farmer John想修理牧场栅栏的某些小段。为此，他需要N(1&lt;=N&lt;=20,000)块特定长度的木板，第i块木板的长度为Li(1&lt;=Li&lt;=50,000)。然后，FJ去买了一块很长的木板，它的长度正好等于所有需要的木板的长度和。接下来的工作，当然是把它锯成需要的长度。FJ忽略所有切割时的损失——你也应当忽略它。 FJ郁闷地发现，他并没有锯子来把这块长木板锯开。于是他把这块长木板带到了Farmer Don的农场，想向FD借用锯子。 作为一个有商业头脑的资本家，Farmer Don没有把锯子借给FJ，而是决定帮FJ锯好所有木板，当然FJ得为此付出一笔钱。锯开一块木板的费用，正比于木板的长度。如果这块木板的长度是21，那么锯开它的花费便是21美分。 谈妥条件后，FD让FJ决定切割木板的顺序，以及每次切割的位置。请你帮FJ写一个程序，计算为了锯出他想要的木板，他最少要花多少钱。很显然，按不同的切割顺序来切开木板，FJ的总花费可能不同，因为不同的切割顺序，会产生不同的中间结果。 </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* 第1行: 一个正整数N，表示FJ需要木板的总数 </span></p>
<p><span style="font-size: medium">* 第2..N+1行: 每行包含一个整数，为FJ需要的某块木板的长度</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* 第1行: 输出一个整数，即FJ完成对木板的N-1次切割的最小花费 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
8<br/>
5<br/>
8<br/>
<br/>
<br/>
    FJ打算把一块长为21的木板切成长度分别为8，5，8的三段。<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">34<br/>
输出说明:<br/>
<br/>
 起初，木板的长度为21。第一次切割木板花费21美分，把木板切成长分别为13和8的两块。然后花费1<br/>
3美分把长为13的木板切成长为8和5的两块。这样的总花费是21+13=34美分。如果第一次把木板切成长<br/>
为16和5的两块，那么第二次切木板的花费就是16美分，这样的总花费就是37美分，比刚才花费34美分的方案来的差。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

