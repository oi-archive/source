
# Description

<div class="content"><div>文艺青年JYY非常喜欢观看歌剧表演。</div>
<div>JYY知道所有演员的长相和名字， 但是却对不上号，JYY希望有一天能够知道每一个演员到底是谁。</div>
<div>JSOI歌剧团一共有N个演员，并进行了M次演出。</div>
<div>所有演员由1到N编号，并且第i次演出共有Ki演员参加。</div>
<div>JYY看过所有N个演员的照片(即知道这N个演员的长相),也看过演员的名单(即知道这N个演员的姓名，假设没有同名的情况)，</div>
<div>并且仔细观摩了所有的M次演出：每次演出JYY都知道有哪些演员参加了本次表演并且能够分辨出他们的长相。</div>
<div>现在JYY想知道，看完这M次演出之后，他是不是能够把所有演员的名字和长相都一一对应了呢？</div>
<div></div></div>

# Input

<div class="content"><div>输入一行包含两个正整数N和M。</div>
<div>接下来M行，每行首先包含一个整数Ki，接下来Ki个不同的1到N之间的整数，表示参与此次演出的演员编号。</div>
<div>N , M , Sigma(i)Ki 均小于等于10^5</div>
<div></div></div>

# Output

<div class="content"><div>输出文件包含一行N个整数，第i个整数ai表示编号为i的演员在第ai场演出之后JYY就可以将他的编号和长相对应起来。</div>
<div>如果M次演出之后JYY仍然不能认出这个演员，则ai为0。</div>
<div>输出时，整数之间用一个空格分开，行末没有空格。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">4 3<br/>
1 1<br/>
1 3<br/>
1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 3 2 3<br/>
提示<br/>
每一场演出可以确定一个演员的长相，而 4 号演员是唯一一直没有参加过演出的。<br/>
由于 JYY 一开始知道所有演员的长相，所以第三场演出后 JYY 也可以确认 4 号演员的长相。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Round3">Round3</a></p></div>

