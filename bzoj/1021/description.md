
# Description

<div class="content"><p>　　Alice、Bob和Cynthia总是为他们之间混乱的债务而烦恼，终于有一天，他们决定坐下来一起解决这个问题。<br/>
不过，鉴别钞票的真伪是一件很麻烦的事情，于是他们决定要在清还债务的时候尽可能少的交换现金。比如说，Al<br/>
ice欠Bob 10元，而Cynthia和他俩互不相欠。现在假设Alice只有一张50元，Bob有3张10元和10张1元，Cynthia有3<br/>
张20元。一种比较直接的做法是：Alice将50元交给Bob，而Bob将他身上的钱找给Alice，这样一共就会有14张钞票<br/>
被交换。但这不是最好的做法，最好的做法是：Alice把50块给Cynthia，Cynthia再把两张20给Alice，另一张20给<br/>
Bob，而Bob把一张10块给C，此时只有5张钞票被交换过。没过多久他们就发现这是一个很棘手的问题，于是他们找<br/>
到了精通数学的你为他们解决这个难题。</p></div>

# Input

<div class="content"><p>　　输入的第一行包括三个整数：x1、x2、x3（-1,000≤x1，x2，x3≤1,000），其中 x1代表Alice欠Bob的钱（如<br/>
果x1是负数，说明Bob欠了Alice的钱） x2代表Bob欠Cynthia的钱（如果x2是负数，说明Cynthia欠了Bob的钱） x3<br/>
代表Cynthia欠Alice的钱（如果x3是负数，说明Alice欠了Cynthia的钱）<br/>
接下来有三行<br/>
每行包括6个自然数： <br/>
a100，a50，a20，a10，a5，a1 <br/>
b100，b50，b20，b10，b5，b1 <br/>
c100，c50，c20，c10，c5，c1 <br/>
a100表示Alice拥有的100元钞票张数，b50表示Bob拥有的50元钞票张数，以此类推。<br/>
另外，我们保证有a10+a5+a1≤30，b10+b5+b1≤30，c10+c5+c1≤30，而且三人总共拥有的钞票面值总额不会<br/>
超过1,000。<br/>
<br/>
</p></div>

# Output

<div class="content"><p>　　如果债务可以还清，则输出需要交换钞票的最少张数；如果不能还清，则输出“impossible”（注意单词全部<br/>
小写，输出到文件时不要加引号）。</p></div>

# Sample Input

<div class="content"><span class="sampledata">输入一 <br/>
10 0 0 <br/>
0 1 0 0 0 0 <br/>
0 0 0 3 0 10<br/>
 0 0 3 0 0 0 <br/>
输入二 <br/>
-10 -10 -10 <br/>
0 0 0 0 0 0 <br/>
0 0 0 0 0 0 <br/>
0 0 0 0 0 0 </span></div>

# Sample Output

<div class="content"><span class="sampledata">输出一<br/>
5<br/>
输出二<br/>
0</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据，x1、x2、x3 ≤ |1,000|。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

