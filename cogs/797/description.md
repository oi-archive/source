
<span>【问题描述】 </span><br/>
<span>APIO王国正被忍者攻击！忍者非常厉害，因为他们在进攻的时候可以躲在</span><br/>
<span>阴影里面使得其他人看不到他们。整个王国除了国王居住的APIO城堡以外都已</span><br/>
<span>经被占领了。在城堡前，有N个灌木丛，从1到N编号，有K个忍者躲在恰好</span><br/>
<span>K个灌木丛后面。APIO城堡里有M个守卫。守卫i监视着编号从Ai到Bi 的连续</span><br/>
<span>的一段灌木丛。每个守卫都向国王报告在他所监视范围内是否有忍者出现。作为</span><br/>
<span>国王的仆人，你需要告诉国王，基于守卫的报告，哪些灌木丛后面一定躲着一个</span><br/>
<span>忍者，即对于任何和守卫报告不矛盾的忍者排列方式，在这个灌木丛后面都躲着</span><br/>
<span>一个忍者。 </span><br/>
<span>你需要写一个程序来输出所有的这些灌木丛的编号。 </span><br/>
<span>【数据范围】 </span><br/>
<span>1 ≤ N ≤ 100,000  灌木的数量； </span><br/>
<span>1 ≤ K ≤ N  忍者数； </span><br/>
<span>0 ≤ M &lt; 100,000  守卫数。 </span><br/>
<span> </span><br/>
<span>对于10%的数据，N ≤ 20， M ≤ 100； </span><br/>
<span>对于50%的数据，N ≤ 1000， M ≤ 1000。 </span><br/>
<span>【输入格式】 </span><br/>
<span>从标准输入读入数据。 </span><br/>
<span>第一行包含三个用空格分隔的整数N, K, M，N是灌木丛的个数，K是忍者</span><br/>
<span>的个数，M是守卫的个数。 </span><br/>
<span>接下来M行，每行描述一个守卫的信息。其中的第i行包含三个整数Ai</span><span>, Bi</span><span>, </span><br/>
<span>Ci，表示第i个守卫的监视范围是从Ai 到Bi（Ai</span><span> ≤ Bi）。Ci 是0或者1，若是0表</span><br/>
<span>示范围内没有看到忍者，1表示范围内有至少一个忍者。 </span><br/>
<span>输入数据保证至少存在一种忍者排列方式满足所有条件。 </span><br/>
<span>【输出格式】 </span><br/>
<span>输出到标准输出。 </span><br/>
<span>若存在灌木丛，在其后面一定躲着忍者，则将这些一定躲着忍者的灌木丛按</span><br/>
<span>照编号从小到大的顺序依次输出，每个一行。即若有X个这样的灌木丛，则需</span><br/>

# 样例输入1


