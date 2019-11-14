
# Description

<div class="content"><div>小A和小B是一对好朋友，他们经常一起愉快的玩耍。最近小B沉迷于**师手游，天天刷本，根本无心搞学习。但是</div>
<div>已经入坑了几个月，却一次都没有抽到SSR，让他非常怀疑人生。勤勉的小A为了劝说小B早日脱坑，认真学习，决</div>
<div>定以抛硬币的形式让小B明白他是一个彻彻底底的非洲人，从而对这个游戏绝望。两个人同时抛b次硬币，如果小A</div>
<div>的正面朝上的次数大于小B正面朝上的次数，则小A获胜。但事实上，小A也曾经沉迷过拉拉游戏，而且他一次UR也</div>
<div>没有抽到过，所以他对于自己的运气也没有太大把握。所以他决定在小B没注意的时候作弊，悄悄地多抛几次硬币</div>
<div>，当然，为了不让小B怀疑，他不会抛太多次。现在小A想问你，在多少种可能的情况下，他能够胜过小B呢？由于</div>
<div>答案可能太大，所以你只需要输出答案在十进制表示下的最后k位即可。</div>
<div></div></div>

# Input

<div class="content"><div>有多组数据，对于每组数据输入三个数a,b,k，分别代表小A抛硬币的次数，小B抛硬币的次</div>
<div>数，以及最终答案保留多少位整数。</div>
<div>1≤a,b≤10^15,b≤a≤b+10000,1≤k≤9，数据组数小于等于10。</div>
<div></div></div>

# Output

<div class="content"><div>对于每组数据，输出一个数，表示最终答案的最后k位为多少，若不足k位以0补全。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">2 1 9</span></div>

# Sample Output

<div class="content"><span class="sampledata">000000004<br/>
6<br/>
3 2 1<br/>
【样例解释】<br/>
对于第一组数据，当小A抛2次硬币，小B抛1次硬币时，共有4种方案使得小A正面朝上的<br/>
次数比小B多。(01,0),(10,0),(11,0),(11,1)<br/>
对于第二组数据，当小A抛3次硬币，小B抛2次硬币时，共有16种方案使得小A正面朝上的次数比小B多。(001,00),<br/>
(010,00),(100,00),(011,00),(101,00),(110,00),(111,00),(011,01),(101,01),(110,01),(111,01),(011,10),<br/>
(101,10),(110,10),(111,10),(111,11)</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

