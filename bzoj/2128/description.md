
# Description

<div class="content"><p>转眼间一年过去了，高一一班的同学迎来了期末考试。令计算机竞赛教练scp大老板惊讶的是，考试座位在某一个小矩形里面的同学考试分数出奇的一致（众所周知，高一一班的座位是个n*m的矩阵），这不由得让scp大老板心生怀疑。scp大老板有q个疑问，对于某个矩形，分数在a到b之间的同学有几人。（本题要求在线算法，即只有正确输出了上一个询问的答案才会给出下一个询问，所以你不能将询问排序。因为类型只能是传统，所以请大家自觉写在线算法。这套题已经这么水了，请大家就不要用离线算法拿分了。）</p></div>

# Input

<div class="content"><p>（由于数据要求小于5M，本题中输入的t矩阵和v矩阵都将由如下规则生成。对于某个矩阵f，f[i,j]=a[i mod pa +1]+b[i mod pb +1]+c[i mod pc +1]+a[j mod pa +1]+ b[j mod pb +1]+c[j mod pc +1]）输入的第一行的第一个正整数为pa，接下来pa个数为a[1..pa] 输入的第二行的第一个正整数为pb，接下来pb个数为b[1..pb] 输入的第三行的第一个正整数为pc，接下来pc个数为c[1..pc] 输入的第四行包含三个整数n,m,p表示v矩阵的大小为n*m。 v矩阵，表示座位在第i行第j列的同学的考试分数为v[i,j] mod p +1。接下来一行包含一个整数q表示t矩阵的大小为q*6。 t矩阵的每一行的六个数x1,y1,x2,y2,a,b表示这一次询问以座位min（x1 mod n +1,x2 mod n +1）,min(y1 mod m +1,y2 mod m +1)为左上角，max(x1 mod n +1,x2 mod n +1),max(y1 mod m +1,y2 mod m +1)为右下角的矩形里，分数在min(a mod p +1 ,b mod p +1),max(a mod p +1, b mod p +1)之间（包含a,b）的同学有几个。</p></div>

# Output

<div class="content"><p>输出一个正整数，表示所有q次询问结果的异或和。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 7 7 10<br/>
5 4 4 7 11 11<br/>
7 4 7 1 4 3 11 8<br/>
10 10 11<br/>
100<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">50<br/>
【数据规模】<br/>
对于100%以内的数据 pa,pb,pc&lt;3000 输入数据中的所有数字小于等于1000000007。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

