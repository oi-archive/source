
# Description

<div class="content"><p>Byteotia的领土被占领了，国王Byteasar正在打算组织秘密抵抗运动。国王需要选一些人来进行这场运动，而这些人被分为两部分：一部分成为同谋者活动在被占领区域，另一部分是后勤组织在未被占领的领土上运转。但是这里出现了一个问题： 1. 后勤组织里的任意两人都必须是熟人，以促进合作和提高工作效率。 2. 同谋者的团体中任意两人都不能是熟人。 3. 每一部分都至少要有一个人。国王想知道有多少种分配方案满足以上条件，当然也有可能不存在合理方案。现在国王将这个问题交由你来解决！</p></div>

# Input

<div class="content"><p>第一行一个整数n（2&lt;=n&lt;=5000）表示有n个人参与该抵抗运动，标号为1..n。 之后有n行，第i行的第一个数ki（0&lt;=ki&lt;=n-1）表示i认识ki个人,随后的ki个数表示i的熟人。 p.s.输入满足：如果i是x的熟人，x会在i的序列中出现同时i也会出现在x的熟人序列中。</p></div>

# Output

<div class="content"><p>符合条件的方案总数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">     <br/>
4<br/>
2 2 3<br/>
2 1 3<br/>
3 1 2 4<br/>
1 3<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3</span></div>

# Hint

<div class="content"><p></p><p>Hint 1和4分到同谋者组织，2和3为后勤组织。 2和4分到同谋者组织，1和3为后勤组织。 4单独分到同谋者组织，1和2、3为后勤组织。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

