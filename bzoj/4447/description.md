
# Description

<div class="content"><div>小凸得到了一个密码盘，密码盘被等分成N个扇形，每个扇形上有一个数字(0～9)，和一个符号（“+”或&#34;*&#34;)</div>
<div>密码盘解密的方法如下：</div>
<div>首先，选择一个位置开始，顺时针地将数字和符号分别记在数组A和数组C巾</div>
<div>解密的方法如下</div>
<div>B0=A0</div>
<div>当x&gt;0时：</div>
<div>若Cx为“+”，Bx=(Ax+Ax-1)%10，注意：x-1是下标值</div>
<div>若Cx为“*”，Bx= (Ax×Ax-1)%10,注意：x-1是下标值</div>
<div>操作完成后，可以得到一个长度为n的数组B，然后以B0为起点将B数组顺时针写成一个环，解密就完成</div>
<div>了，称得到的环为答案环。</div>
<div>现在小凸得到了一份指令表，指令表上有2种操作。</div>
<div>一种指令是修改操作，即改变原来密码盘上一个位置的数字和符号。</div>
<div>另一种指令是询问操作，具体如下：</div>
<div>首先从指令给出的位置开始完成解密，得到答案环。</div>
<div>答案环上会有一些0连在一起，将这些连在一起的0称为零区间，找出其中距离B0最远的那个零区间，输</div>
<div>出这个距离。</div>
<div>零区问和B0的距离定义为：零区问内所有0到B0距离中的最小值。</div>
<p></p></div>

# Input

<div class="content"><div>第1行包含2个整数n,m，代表密码盘大小和指令个数</div>
<div>接下来n行，每行包含1个整数和1个字符，按顺时针顺序给出了密码盘上的数组和符号</div>
<div>接下来m行，依次给出指令</div>
<div>每行第1个整数代表指令类型</div>
<div>若第1个墼数为1，代表本行对应指令为修改操作，之后依次有2个整数pos，num和1个字符opt，分别</div>
<div>代表修改的位置，以及修改后该位置的数字和字符</div>
<div>若第1个整数为2，代表本行对应指令位询问操作，之后有1个整数pos，代表本次操作中解密的开始位置</div>
<div>密码盘上的位置标号为0到n-l</div>
<div>数据保证合法，即数据中0≤pos&lt;N，0≤num≤9，opt为“+”或“*”</div>
<p></p></div>

# Output

<div class="content"><div>对于每个询问操作1行，输出答案，若答案环上没有0，输出-1</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 8<br/>
0 *<br/>
0 *<br/>
0 *<br/>
0 *<br/>
0 *<br/>
2 0<br/>
1 0 1 +<br/>
1 2 1 +<br/>
2 3<br/>
1 1 1 +<br/>
1 3 1 +<br/>
1 4 1 +<br/>
2 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
2<br/>
-1<br/>
</span></div>

# Hint

<div class="content"><p></p><div>第1个询问，答案环为[0,0,0,0,0]，仅有1个零区间，且B0在其中，所以距离是0</div><br/>
<div>对于第2个询问，答案环为[0,0,1,0,l]，有2个零区间，(0，1)和B0距离是o，(3，3)和B0距离是2，故答案为2</div><br/>
<div>对于第3个询问，答案环为[1，2，2，2，2]，没有零区间，答案是-1</div><br/>
<div>对于100%数据，5 &lt;=n，m≤10^5</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

