
# Description

<div class="content"><div>最近，一个方块填数的游戏风靡全球：给定一个n*m的方块。n行从上到下标号为1到n，m列从左到右标号为1到m。</div>
<div>如果一个方格所在的行的标号和所在的列的标号都是奇数，那么该方格就称为奇方格。游戏的开始所有的奇方格中</div>
<div>都填上了数。你需要在其他的方格里填数，如果填完数后，方块满足下面条件，你就赢得了这个游戏：</div>
<div>1、任意一个a1*b1的子方块中所有数的和大于0；</div>
<div>2、任意一个a2*b2的子方块中所有数的和小于0；</div>
<div>其中，a1、 b1、 a2、 b2都是在游戏的开始给定的。 一个a*b的子方块是指行标号在i（1≤i≤n-a+1）到i+a-1之</div>
<div>间，列标号在j(1≤j≤m-b+1)到j+b-1之间的所有的方格的集合。小P很喜欢这种游戏，他希望你帮助写一个程序给</div>
<div>出一种填数的方案，或者告诉他这样的方案不存在。</div></div>

# Input

<div class="content"><div>
<div>第一行为用空格分开的6个正整数n,m,a1,b1,a2,b2，都在1到100之间。</div>
<div>从第2行起到(n+1)/2行，每一行有(m+1)/2个整数，</div>
<div>第i+1行的第k(k=1,2,…,(m+1)/2)个数表示在游戏开始时方块的第2i-1行，2j-1列的方格所填的整数。这些整数都在-100到100之间。</div>
<div>n,m,a1,b1,a2,b2，都在1到100之间。</div>
</div></div>

# Output

<div class="content"><div>如果填数方案不存在，输出一行“No”。</div>
<div>如果填数方案存在，第一行输出“Yes”。</div>
<div>接下来的n行，每一行有用空格分开的m个整数，描述一个填数方案。 </div>
<div>输出的每一个整数必须在-10^9到10^9之间。</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 3 2 2 3 3<br/>
1 1<br/>
1 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">Yes<br/>
1 -1 1<br/>
-4 5 -4<br/>
1 -1 1<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢 vfleaking">鸣谢 vfleaking</a></p></div>

