
# Description

<div class="content"><p>　　火星人最近研究了一种操作：求一个字串两个后缀的公共前缀。比方说，有这样一个字符串：madamimadam，<br/>
我们将这个字符串的各个字符予以标号：序号： 1 2 3 4 5 6 7 8 9 10 11 字符 m a d a m i m a d a m 现在，<br/>
火星人定义了一个函数LCQ(x, y)，表示：该字符串中第x个字符开始的字串，与该字符串中第y个字符开始的字串<br/>
，两个字串的公共前缀的长度。比方说，LCQ(1, 7) = 5, LCQ(2, 10) = 1, LCQ(4, 7) = 0 在研究LCQ函数的过程<br/>
中，火星人发现了这样的一个关联：如果把该字符串的所有后缀排好序，就可以很快地求出LCQ函数的值；同样，<br/>
如果求出了LCQ函数的值，也可以很快地将该字符串的后缀排好序。 尽管火星人聪明地找到了求取LCQ函数的快速<br/>
算法，但不甘心认输的地球人又给火星人出了个难题：在求取LCQ函数的同时，还可以改变字符串本身。具体地说<br/>
，可以更改字符串中某一个字符的值，也可以在字符串中的某一个位置插入一个字符。地球人想考验一下，在如此<br/>
复杂的问题中，火星人是否还能够做到很快地求取LCQ函数的值。</p></div>

# Input

<div class="content"><p>　　第一行给出初始的字符串。第二行是一个非负整数M，表示操作的个数。接下来的M行，每行描述一个操作。操<br/>
作有3种，如下所示<br/>
1、询问。语法：Qxy，x,y均为正整数。功能：计算LCQ(x,y)限制：1&lt;=x,y&lt;=当前字符串长度。<br/>
2、修改。语法：Rxd，x是正整数，d是字符。功能：将字符串中第x个数修改为字符d。限制：x不超过当前字<br/>
符串长度。<br/>
3、插入：语法：Ixd，x是非负整数，d是字符。功能：在字符串第x个字符之后插入字符d，如果x=0，则在字<br/>
符串开头插入。限制：x不超过当前字符串长度</p></div>

# Output

<div class="content"><p>　　对于输入文件中每一个询问操作，你都应该输出对应的答案。一个答案一行。</p></div>

# Sample Input

<div class="content"><span class="sampledata">madamimadam<br/>
7<br/>
Q 1 7<br/>
Q 4 8<br/>
Q 10 11<br/>
R 3 a<br/>
Q 1 7<br/>
I 10 a<br/>
Q 2 11</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
1<br/>
0<br/>
2<br/>
1</span></div>

# Hint

<div class="content"><p></p><p>1、所有字符串自始至终都只有小写字母构成。<br/><br/>
2、M&lt;=150,000<br/><br/>
3、字符串长度L自始至终都满足L&lt;=100,000<br/><br/>
4、询问操作的个数不超过10,000个。<br/><br/>
对于第1，2个数据，字符串长度自始至终都不超过1,000<br/><br/>
对于第3，4，5个数据，没有插入操作。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

