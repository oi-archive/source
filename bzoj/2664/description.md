
# Description

<div class="content"><p><span style="font-size: medium">“我要将有关魔法和奇迹的一切，封印于卡片之中！” <br/>
“这个心愿„„要是这个心愿能够实现„„” <br/>
“对，这样你我都将化为卡片！” <br/>
 <br/>
现在，孵化者被封印在了一张卡片里。这张卡片的效果是：可以使一张魔法<br/>
卡片变为两张（可能是其他类型的）魔法卡片。显然，它是非常珍贵且有价值的<br/>
卡片。 <br/>
 <br/>
我们接下来要关注的是一个以它为背景的，用于训练SpellCard的使用技巧，<br/>
以及：体现了孵化者无与伦比的再生能力的单人卡片游戏，叫做《Incubator》。 <br/>
 <br/>
游戏的道具是一些卡片，分为两类，一类是 Spell，一类是 Witch。我们用大<br/>
写字母’A’、’B’、„„来表示不同的 Spell，用小写字母’a’、’b’、„„来表示不同<br/>
的 Witch。 <br/>
  游戏用到两个牌堆，我们称它们为 S 堆和 W 堆，S 堆中只可能有 Spell，W<br/>
堆中只可能有 Witch。 <br/>
  游戏开始时，S 堆仅有一张卡片’S’，而 W堆中会有若干张卡片，我们把这个<br/>
信息用一个字符串 w来表示，其中 w的首个字符对应 W堆顶部的卡片，w的下<br/>
一个字符对应 W堆从上向下数第二张卡片（如果有的话） ，依次类推。 <br/>
  游戏的目标是进行操作，使得这两个牌堆都变成空的，一共有两种操作： <br/>
    1. 使用魔法消灭 Witch： <br/>
      如果S 堆顶部的Spell克制 W堆顶部的 Witch 才可以进行。 <br/>
      使用后，这两张卡片都被移除。 <br/>
    2. 使用Incubator 进行孵化： <br/>
      如果S 堆非空就可以进行。 <br/>
      需要依照某一孵化规则。 <br/>
  将S堆顶部的卡片移除， 由孵化规则在S堆顶部加入两张新的卡片。 <br/>
   <br/>
  这个游戏一共有N1个克制关系以及 N2个孵化规则。 <br/>
每一个“克制”关系由一个字符串给出，例如： “A-&gt;a”表示’A’克制’a’。 <br/>
每一个孵化规则也由一个字符串给出，例如： “S-&gt;AB” ，表示可以将’S’从堆<br/>
顶移除，之后加入’A’和’B’，其中’A’在’B’的上面。 <br/>
 <br/>
在给定规则以及串 w的情形下，如果存在一个有限多步就可以使得两牌堆均<br/>
为空的操作方法，那么我们称：这个游戏是有解的。 <br/>
 <br/>
你的任务是：给定规则以及 T个串：w1、w2、„„、wT，分别判定这个规则<br/>
和串所对应的游戏是否有解。 </span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行一共有两个正整数：N1、N2。 <br/>
接下来 N1行，每行一个串，表示一个克制关系。 <br/>
接下来 N2行，每行一个串，表示一个孵化规则。 <br/>
接下来 T 行，每行一个串 wi。 <br/>
</span></p>
<p></p></div>

# Output

<div class="content"><p><font size="4"><br/>
一共输出 T行： <br/>
每行为“YES”或“NO”（不包含引号），表示对应的串和规则组成的游戏是<br/>
否是有解的。（有解则输出“YES”，否则输出“NO”） </font></p>
<p><span style="font-size: medium"><br/>
</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">  2 1 <br/>
  A-&gt;a <br/>
  B-&gt;b <br/>
  S-&gt;AB <br/>
  ab <br/>
  cd <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">YES <br/>
NO <br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据： 1≤  N1≤20， 1 ≤  N2≤20， 1 ≤  |wi|≤  20， 1≤  T≤100。 <br/><br/>
保证所有的克制关系串都是合法的，即具有“A-&gt;a”的形式，其中 A 是某<br/><br/>
个大写字母，a 是某个小写字母。 <br/><br/>
保证所有的孵化规则串都是合法的，即具有“S-&gt;AB”的形式，其中 S、A、<br/><br/>
B是某些大写字母，它们可以相同。 <br/><br/>
“-&gt;”是一个长度为 2 的串，其首个字符的 ASCII 码为 45，下一个字符的<br/><br/>
ASCII 码为62 （均是在十进制下） ，这个符号也是 C++中的 Structure dereference。 <br/><br/>
保证串 wi仅包含小写字母。 <br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

