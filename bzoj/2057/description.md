
# Description

<div class="content"><p>ACM（Association of Cup Makers, 制杯者协会）下的工厂生产三种不同大小的咖啡杯（叫做1号，2号和3号）并打包出售。每种包裹用三个正整数(S1, S2, S3)来标记，Si表示包裹中i号杯子的个数。没有S1=S2=S3的包裹。但是最近发现有相同数目的三种杯子的包裹需求两很大，作为满足需求的紧急措施，ACM决定把他们（无限的）仓库中未销售的包裹打开，然后重新包装成三种杯子个数相等的包裹。比如，把三个(1,2,3)，一个(9,4,3)和两个(2,3,2)包裹打开，就可以重新包装成16个(1,1,1)包裹，或者是8个(2,2,2)包裹等等。注意打开包裹得到的所有杯子都要用于重新包装，也就是说，不能有浪费的杯子。 ACM雇佣了你来写一个程序判断通过重新包装是否可能得到三种杯子个数相等的包裹。</p></div>

# Input

<div class="content"><p>输入可能包含多个测试数据，每个数据的第一行是一个整数N，表示仓库中可以找到的包裹种类数，以下N行每行包含3个整数，分别表示在一种包裹里1号，2号，3号杯子的个数。一个包含N=0的测试数据结束整个输入。</p></div>

# Output

<div class="content"><p>对每个数据如果能够得到所要求的包裹，输出Yes，否则输出No。</p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
1 2 3<br/>
1 11 5<br/>
9 4 3<br/>
2 3 2<br/>
4<br/>
1 3 3<br/>
1 11 5<br/>
9 4 3<br/>
2 3 2<br/>
0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Yes<br/>
No<br/>
</span></div>

# Hint

<div class="content"><p></p><p>【数据规模】 80% n&lt;=100 90% n&lt;=1000 100% n&lt;=100000 给出的三个数字 a:=random(10000)+1; b:=random(1000000)+1; c:=random(10021)+1;</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

