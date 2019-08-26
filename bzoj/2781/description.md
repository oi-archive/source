
# Description

<div class="content"><div> 定义<span>r(s)为一个0/1序列S的补充翻转序列（例如：r(100011)=001110）</span></div>
<div> 现在有一种方法生成一种序列即：<span>sn=sn-1+’1’+r(sn-1)</span></div>
<div> S0=1</div>
<div> S1=110</div>
<div> S2=1101100</div>
<div> S3=110110011100100</div>
<div> ……</div>
<div> 此题所需的序列来自<span>S30</span></div>
<div> 现在有一个机器人放在（<span>0，0）这个点且面朝东方（上北下南左西右东）</span></div>
<div> 它每秒走一步，然后读<span>0/1序列的一个数，如果是1则向左转否则向右转</span></div>
<div> 求经过<span>X步后机器人到了哪里</span></div>
<div> </div></div>

# Input

<div class="content"><div> 若干组数据，每行一个正整数（<span>X&lt;=10<sup>9</sup>）</span></div>
<div> 数据组数<span>&lt;=200</span></div>
<div> -1结尾</div>
<div> </div>
<div> </div></div>

# Output

<div class="content"><p> </p>
<div> 坐标，用括号围起来</div>
<div> </div>
<div> </div></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
 1<br/>
 2<br/>
 3<br/>
 -1<br/>
 <br/>
 </span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
 （1，0）<br/>
 （1，1）<br/>
 （0，1）<br/>
  <br/>
 </span></div>

# Hint

<div class="content"><p></p><p> 对于100%的数据 x&lt;=1000000000</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

