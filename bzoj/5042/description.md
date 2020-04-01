
# Description

<div class="content"><div>大家都知道在文理分科的时候总是让人纠结的，纠结的当然不只是自己。比如 YSY 就去读了文科， LWD 知道了很</div>
<div>气。于是他就去卡了 BZOJ 测评机， 晚上他做了一个谜一样的梦，自己在一座全是 YSY 的分科岛。这里有 YSY </div>
<div>草， YSY 花， YSY 糖……每个 YSY 都有一个美（ Ti）丽（ Zhong）值。当然没有小于零的体重啦！LWD 于是不</div>
<div>惜重金卖肉想买下这座岛，可是分科岛的岛主，是一位忠实的区间问题爱好者。他想把小岛传给一个谜一样的爱好</div>
<div>者，所以岛主给了 LWD 一个终极挑战——选出一片区域中最美丽的 YSY。可是岛主的审美观不像 YYR那么专一，</div>
<div>他有时喜欢现代美——最轻的，有时喜欢唐代美——最重的。这让被欢喜冲昏了头脑（血液集中在下半身）的 LWD</div>
<div> 十分苦恼。他要在规定时间内完成挑战赢得买岛的权利，于是只有求助 DalaoYYR，可是 YYR 要准备课件啊。只</div>
<div>有比 YYR 弱很多的你能够帮他了。挑战内容如下岛主将把 N 个 YSY 摆成一个条形，并给出所有 YSY 的美丽值。</div>
<div>挑出多少个就要看岛主心情了，他觉得 LWD 是条汉子就会给出很多很多的 YSY 满足他。岛主将给出 Q 个考验，</div>
<div>询问内容是在给定区间内求出最美丽的 YSY。你已经了解规则了，开始你的表演吧！</div>
<p></p></div>

# Input

<div class="content"><div>第一行为一个整数 N，表示岛主摆出了 N 个 YSY。</div>
<div>接下来一行 N 个整数，表示每个 YSY 的美丽值(单位：kg)，因为 YSY 整体很美所以 YSY</div>
<div>不会超过 1019kg。</div>
<div>接下来一行一个整数 Q，表示岛主有 Q 个考验。<span style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 23.3240013122559px;">Q&lt;=1500000</span></div>
<div>接下来 Q 行，每行三个整数 opt, l, r 。 opt 等于 1 时表示岛主那时喜欢现代美，等于 2</div>
<div>时代表岛主那时喜欢唐代美。询问最美计划在区间[l, r]中进行</div>
<div>100%的数据 N&lt;= 3000000, 美丽值不会超过 1019， Q&lt;= 150000 </div>
<div>数据量巨大，请优化读入</div>
<p></p></div>

# Output

<div class="content"><div>每一行对于每个考验输出结果，以回车符结束。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 5<br/>
1 2 3 4 5<br/>
1 1 2<br/>
2 1 3<br/>
1 2 5<br/>
2 4 5<br/>
2 1 5<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 <br/>
3 <br/>
2 <br/>
5 <br/>
5</span></div>

# Hint

<div class="content"><p></p><p>注意：为减轻主站压力，本题完整版请到http://begin.lydsy.com/JudgeOnline/problem.php?id=4191进行提交，带来不便，敬请谅解。</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By Lazer2001">By Lazer2001</a></p></div>

