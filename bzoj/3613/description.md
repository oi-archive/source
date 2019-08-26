
# Description

<div class="content"><div>小 Z 是 ZRP（Zombies’ Republic of Poetry，僵尸诗歌共和国）的一名诗歌爱好者，最近 他研究起了诗词音律的问题。</div>
<div>  在过去，诗词是需要编成曲子唱出来的，比如下面这首《菩萨蛮》，唱出来的话其对应 的音符就是这样的：</div>
<div>   南  园  满 地 堆 轻 絮， 愁 闻 一 霎 清 明 雨</div>
<div>   1   1  5 5 6 6 5  4 4 3 3 2 2 1  </div>
<div>因而可以发现，“1 1 5 5 6 6 5 4 4 3 3 2 2 1”这串音符就成为了研究音律的关键。</div>
<div> 小 Z 翻阅了众多史料发现，过去的一首曲子的音调是不下降的 </div>
<div> 小 Z 想要知道对于一首给定的曲子，如何通过提高音调或者降低音调，将它的音调修改 的不下降，</div>
<div>而且使得修改幅度最大的那个音符的修改幅度尽量小。</div>
<div>即如果把一个包含 n 个音 符的曲子看做是一个正整数数列 A[1]…A[n]，</div>
<div>那么 目标是求另一个正整数数列 B[1]…B[n]， 使得对于任意的 1≤i&lt;n 有 B[i] ≤B[i+1]，</div>
<div>而且使得 Ans = Max{|A[j]-B[j]|,1≤j≤n}尽量 小。  小 Z 很快就想清楚了做法，但是鉴于他还忙着写诗，</div>
<div>所以这个任务就交给了你。 </div>
<div></div></div>

# Input

<div class="content"><p>由于数据规模可能较大，因此采用如下方式生成数据。</p>
<div>
<div> 每个数据包含 6 个数：n,Sa,Sb,Sc,Sd,A[1],Mod,意为共有 n 个音符，第一个音符为 A[1]。</div>
<div> 生成规则如下： 定义生成函数 F(x) = Sa*x^3 + Sb*x^2 + Sc*x + Sd; </div>
<div>那么给出递推公式 A[i] = F(A[i-1]) + F(A[i-2])，此处规定 A[0] = 0. </div>
<div>由于中间过程的数可能会特别大，所以要求每一步与 A 中的每个数都对一个给定的数 Mod 取模。</div>
<div></div>
</div></div>

# Output

<div class="content"><p>输出一行，包含一个正整数 Ans。 </p>
<div>
<div></div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 815 6901 3839 178 199 10007 </span></div>

# Sample Output

<div class="content"><span class="sampledata">1334</span></div>

# Hint

<div class="content"><p></p><p>  n≤5000000 </p><br/>
<div>对于 100%的数据, Sa,Sb,Sc,Sd,A[1] ≤10000, Mod≤1000000007 </div><br/>
<div></div><br/>
<div>样例中生成的数列为：  </div><br/>
<div>199 4568 1901，此时将 4568 修改为 3234,1901 也修改为 3234 即可，代价为 1334。 </div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢佚名上传">鸣谢佚名上传</a></p></div>

