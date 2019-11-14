
# Description

<div class="content"><div>Sheila 是一名学生,她开着一辆经典的学生车:一辆又老,又慢,又锈,还老是崩坏的车。最近,时速表盘的指针还掉</div>
<div>了。她把指针粘了回去,但是她可能没有粘对角度。因此,当表盘读数为s时,她真实的速度可能是s+c,其中c为未知</div>
<div>常数 (可能是负的) 。Sheila 在最近的行程中仔细地做了一些记录,并希望能用这些记录来计算出c的值。行程由n</div>
<div>段组成。在第 i 段中,她匀速行驶了di的距离,表盘对应的读数一直为si。整个行程花费的时间为t。请你帮Sheila</div>
<div>确定c的值。注意即使Sheila的表盘可能有负的读数,她在每段行程的真实速度也是大于零的。</div></div>

# Input

<div class="content"><div>第一行包含两个整数n(1≤n≤1000)和t(1≤t≤10^6),分别表示Sheila的行程段数和总时间。</div>
<div>接下来n行,每行描述了Sheila的一段行程。</div>
<div>第i行包含两个整数di(1≤di≤1000)和si(|si|≤1000),分别表示第 i 段行程的距离和表盘读数。</div>
<div>时间单位是小时,距离单位是英里,速度单位是英里每小时。</div></div>

# Output

<div class="content"><div>输出常数c,其单位是英里每小时。你的答案绝对或相对误差应该小于10^-6。</div></div>

# Sample Input

<div class="content"><span class="sampledata">样例1<br/>
3 5<br/>
4 -1<br/>
4 0<br/>
10 3<br/>
样例2<br/>
4 10<br/>
5 3<br/>
2 2<br/>
3 6<br/>
3 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">样例1<br/>
3.000000000<br/>
样例2<br/>
-0.508653377</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tangjz提供翻译">鸣谢Tangjz提供翻译</a></p></div>

