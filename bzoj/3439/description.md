
# Description

<div class="content"><p><span style="font-size: medium"><br/>
 背景</span></p>
<p><span style="font-size: medium">    想Kpm当年为了防止别人随便进入他的MC，给他的PC设了各种奇怪的密码和验证问题（不要问我他是怎么设的。。。），于是乎，他现在理所当然地忘记了密码，只能来解答那些神奇的身份验证问题了。。。</span></p>
<p><span style="font-size: medium"> 描述</span></p>
<p><span style="font-size: medium">    Kpm当年设下的问题是这样的：</span></p>
<p><span style="font-size: medium">    现在定义这么一个概念，如果字符串s是字符串c的一个后缀，那么我们称c是s的一个kpm串。</span></p>
<p><span style="font-size: medium">    系统将随机生成n个由a…z组成的字符串，由1…n编号（s1,s2…,sn），然后将它们按序告诉你，接下来会给你n个数字，分别为k1…kn，对于每一个ki，要求你求出列出的n个字符串中所有是si的kpm串的字符串的编号中第ki小的数，如果不存在第ki小的数，则用-1代替。（比如说给出的字符串是cd,abcd,bcd,此时k1=2，那么”cd”的kpm串有”cd”,”abcd”,”bcd”,编号分别为1,2,3其中第2小的编号就是2）（PS：如果你能在相当快的时间里回答完所有n个ki的查询，那么你就可以成功帮kpm进入MC啦~~）</span></p></div>

# Input

<div class="content"><p> </p>
<p><span style="font-size: medium">    第一行一个整数 n 表示字符串的数目</span></p>
<p><span style="font-size: medium">    接下来第二行到n+1行总共n行，每行包括一个字符串，第i+1行的字符串表示编号为i的字符串</span></p>
<p><span style="font-size: medium">    接下来包括n行，每行包括一个整数ki，意义如上题所示</span></p>
<p><span style="font-size: medium"> </span></p></div>

# Output

<div class="content"><p> </p>
<p><span style="font-size: medium">    包括n行，第i行包括一个整数，表示所有是si的kpm串的字符串的编号中第ki小的数</span></p>
<p><span style="font-size: medium"> </span></p></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
    3<br/>
    cd<br/>
    abcd<br/>
    bcd<br/>
    2<br/>
    3<br/>
    1<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">    2<br/>
    -1<br/>
    2<br/>
<br/>
样例解释<br/>
<br/>
    “cd”的kpm 串有”cd”,”abcd”,”bcd”,编号为1,2,3，第2小的编号是<br/>
<br/>
    2，”abcd”的kpm串只有一个，所以第3小的编号不存在，”bcd”的kpm<br/>
<br/>
    串有”abcd”,”bcd”,第1小的编号就是2。<br/>
<br/>
数据范围与约定<br/>
<br/>
    设所有字符串的总长度为len<br/>
<br/>
<br/>
    对于100%的数据，1&lt;=n&lt;=100000,0<len<=300000<br>
<br/>
</len<=300000<br></span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Kpmcup#0 By Greens
">Kpmcup#0 By Greens<br/>
</a></p></div>

