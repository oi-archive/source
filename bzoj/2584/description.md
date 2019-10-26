
# Description

<div class="content"><p><span style="font-size: medium">江苏省常州高级中学是一所百年名校，这里萦绕着无数人难以忘怀的回忆。  Will 记得，在他小的时候，常州高级中学改建以前，学校里有一片高大的水杉林，每到水杉落叶之时，针状的叶子会像毯子一样盖在地上，走在上面浪漫而又闲适。那时，Will 和同学们还喜欢用这些针叶，在水杉树下，玩“取叶子”的游戏。 游戏一开始，大家先将 n片针叶平铺在地上。接着，每一轮可以有一个同学选择一片针叶，按水平或者垂直方向将针叶移走（也就是平移到无穷远处）——当然，前提是移动过程中不被任何尚未移走的针叶所阻碍。如果某一轮针叶的移动会被阻碍，那么这次移动就是非法的，是不被允许的。n轮过后，当针叶都被<br/>
移走时，游戏也就结束了。 针叶并不是任何时刻都可以被移动的。当针叶很多的时候，判断每一轮中一片针叶是否可以按一个特定的方向移动是一件很麻烦的事情。 现在我们将地面抽象为平面直角坐标系，n 片针叶抽象为平面上 n 条互不相交的线段，并将其从 1到n编号，Will 还将给出每一轮游戏中，他想要移动的针叶编号以及移动方向，请你帮助他： <br/>
1)  找出最早的一次非法移动出现在哪一轮； <br/>
2)  给出一个合法的移动方案完成这个游戏。 <br/>
注意：在线段移动时仅端点接触不会造成阻碍，具体请参见样例。 </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行包含一个正整数n，表示针叶的数量。 <br/>
接下来 n行，每行 4个整数，描述针叶的位置信息。其中第 i 行的整数为 ai，bi，ci，di，表示编号为 i 的针叶所抽象成的线段的端点为(ai, bi)和(ci, di)。 接下来 n 行，每行 2 个整数，描述移动操作。其中第 i 行的整数为 pi，qi，表示第 i 轮移动的针叶编号为 pi，方向为 qi。其中 qi为一个 0 到 3 之间的整数，0 表示向左平移（即 x 轴负方向） ，1 表示向上平移（即 y 轴正方向） ，2 表示向右平移，3表示向下平移。 <br/>
输入数据保证： <br/>
  所有线段长度为正，两两之间没有公共点，且不存在垂直或者水平的线<br/>
段; <br/>
  p1到pn恰好组成一个1到 n的排列； <br/>
  Will 所给出的移动操作中一定存在非法移动； <br/>
  n轮均合法的移动操作总是存在的。 <br/>
 </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">一共包含n + 1行。 <br/>
输出的第一行包含一个1到n之间的整数，表示最早出现非法移动的是哪一轮。 接下来 n行，每行两个整数，内容同输入格式所述，描述一个合法的移动序列。 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 <br/>
2 5 5 8 <br/>
2 1 3 5 <br/>
5 2 6 5 <br/>
7 0 4 2 <br/>
3 1 4 0 <br/>
2 0 <br/>
3 0 <br/>
4 0 <br/>
1 2 <br/>
5 1 </span></div>

# Sample Output

<div class="content"><span class="sampledata">3 <br/>
2 0 <br/>
3 0 <br/>
4 3 <br/>
1 2 <br/>
5 1 </span></div>

# Hint

<div class="content"><p></p><p>在 Will 给出的移动方案的第 3轮中，编号为 4的针叶向左移动会被编号为 5<br/><br/>
的针叶阻碍。</p><br/>
<p></p><br/>
<p><img height="375" alt="" width="770" src="/source/bzoj/2584/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTIwMi8xLmpwZw==.jpg"/></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢 PTY">鸣谢 PTY</a></p></div>

