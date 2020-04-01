
# Description

<div class="content"><div> 【故事背景】</div>
<div>长期的宅男生活中，JYY又挖掘出了一款RPG游戏。在这个游戏中JYY会</div>
<div>扮演一个英勇的骑士，用他手中的长剑去杀死入侵村庄的怪兽。</div>
<div>【问题描述】</div>
<div>在这个游戏中，JYY一共有两种攻击方式，一种是普通攻击，一种是法术攻</div>
<div>击。两种攻击方式都会消耗JYY一些体力。采用普通攻击进攻怪兽并不能把怪兽彻底杀死，怪兽的尸体可以变出其他一些新的怪兽，注意一个怪兽可能经过若干次普通攻击后变回一个或更多同样的怪兽；而采用法术攻击则可以彻底将一个怪兽杀死。当然了，一般来说，相比普通攻击，法术攻击会消耗更多的体力值（但由于游戏系统bug，并不保证这一点）。</div>
<div>游戏世界中一共有N种不同的怪兽，分别由1到N编号，现在1号怪兽入</div>
<div>侵村庄了，JYY想知道，最少花费多少体力值才能将所有村庄中的怪兽全部杀死呢？</div>
<div></div></div>

# Input

<div class="content"><p></p>
<div>第一行包含一个整数N。</div>
<div>接下来N行，每行描述一个怪兽的信息；</div>
<div>其中第i行包含若干个整数，前三个整数为Si，Ki和Ri，表示对于i号怪兽，</div>
<div>普通攻击需要消耗Si的体力，法术攻击需要消耗Ki的体力，同时i号怪兽死亡后会产生Ri个新的怪兽。表示一个新出现的怪兽编号。同一编号的怪兽可以出现多个。</div>
<div>
<div></div>
</div></div>

# Output

<div class="content"><p> 输出一行一个整数，表示最少需要的体力值。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
4 27 3 2 3 2<br/>
3 5 1 2<br/>
1 13 2 4 2<br/>
5 6 1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">26</span></div>

# Hint

<div class="content"><p></p><div>【样例说明】</div><br/>
<div>首先用消耗4点体力用普通攻击，然后出现的怪兽编号是2，2和3。花费</div><br/>
<div>10点体力用法术攻击杀死两个编号为2的怪兽。剩下3号怪兽花费1点体力进</div><br/>
<div>行普通攻击。此时村庄里的怪兽编号是2和4。最后花费11点体力用法术攻击</div><br/>
<div>将这两只怪兽彻底杀死。一共花费的体力是4+5+5+1+5+6=26。</div><br/>
<div>【数据范围】</div><br/>
<div>2&lt;=N&lt;=2*10^5,1&lt;=Ri,Sigma(Ri)&lt;=10^6,1&lt;=Ki,Si&lt;=5*10^14</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Round2 By 佚名上传">Round2 By 佚名上传</a></p></div>

