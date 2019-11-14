
# Description

<div class="content"><div>小H和小Z正在玩一个取石子游戏。 取石子游戏的规则是这样的，每个人每次可以从一堆石子中取出若干个石子，</div>
<div>每次取石子的个数有限制，谁不能取石子时就会输掉游戏。 小H先进行操作，他想问你他是否有必胜策略，如果有</div>
<div>，第一步如何取石子。</div></div>

# Input

<div class="content"><div>输入文件的第一行为石子的堆数N </div>
<div>接下来N行，每行一个数Ai，表示每堆石子的个数 接下来一行为每次取石子个数的种类数M </div>
<div>接下来M行，每行一个数Bi，表示每次可以取的石子个数，</div>
<div>输入保证这M个数按照递增顺序排列。</div>
<div>N≤10<span class="Apple-tab-span" style="white-space:pre">	</span>Ai≤1000</div>
<div>对于全部数据，M≤10，Bi≤10</div></div>

# Output

<div class="content"><div>输出文件第一行为“YES”或者“NO”，表示小H是否有必胜策略。 </div>
<div>若结果为“YES”,则第二行包含两个数，第一个数表示从哪堆石子取，第二个数表示取多少个石子，</div>
<div>若有多种答案，取第一个数最小的答案，</div>
<div>若仍有多种答案，取第二个数最小的答案。</div></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
7<br/>
6<br/>
9<br/>
3<br/>
2<br/>
1<br/>
2</span></div>

# Sample Output

<div class="content"><span class="sampledata">YES<br/>
1 1<br/>
Hint<br/>
样例中共有四堆石子，石子个数分别为7、6、9、3，每人每次可以从任何一堆石子中取出1个或者2个石子，小H有<br/>
必胜策略，事实上只要从第一堆石子中取一个石子即可。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day2">Day2</a></p></div>

