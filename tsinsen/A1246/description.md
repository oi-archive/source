<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　lanxisi带领着他的拆迁队来整治一个街道。这个街道由N个旧房子组成，从左到右编号为1..N。每个旧房子i有一个正整数的美观度A<sub>i</sub>。<br/>
　　lanxisi希望整个街道从左到右美观度严格递增，也就是保证A<sub>i</sub>&lt;A<sub>j</sub>（i&lt;j）。但是旧的街道明显不符合这个要求，于是lanxisi希望拆迁一些旧房子并在原地建立新房子来满足这一要求。但是与很多拆迁队一样，很多钉子户拒绝拆迁。所以lanxisi希望能保留最多的旧房子来满足某些钉子户，当然，保留一个旧房子需要给房子主人Bi的赔偿金。最后，总花费=整治好以后所有房子美观度之和+赔偿金之和。<br/>
　　现在，请你求出lanxisi最多能保留多少旧房子和整治这个街道所需要的最少总花费（当然是在保留旧房子最多这个前提下的）。</div>
# 输入格式

<div class="pdcont">　　第一行有1个整数N，表示旧房子个数。<br/>
　　第二行有N个整数，第i个数A<sub>i</sub>表示旧房子的美观度。<br/>
　　第三行有N个整数，第i个数B<sub>i</sub>表示保留旧房子的赔偿金。</div>
# 输出格式

<div class="pdcont">　　第一行输出2个整数，表示保留的旧房子数量、总花费的大小。</div>
# 样例输入一

<div class="pdcont">　　4<br/>
　　2 1 7 4<br/>
　　1 5 4 3</div>
# 样例输出一

<div class="pdcont">　　2 25</div>
# 样例输入二

<div class="pdcont">　　6<br/>
　　1 6 3 4 7 7<br/>
　　1 2 1 1 1 9</div>
# 样例输出二

<div class="pdcont">　　4 29</div>
# 数据规模和约定

<div class="pdcont">　　20%的数据中，1&lt;=N&lt;=20。<br/>
　　40%的数据中，1&lt;=N&lt;=7000。<br/>
　　100%的数据中，1&lt;=N&lt;=100000，0&lt;=A<sub>i</sub>,B<sub>i</sub>&lt;=100000000。<br/>
　　100%的数据中，时间限制为1s。</div>

</div>