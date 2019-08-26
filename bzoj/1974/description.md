
# Description

<div class="content"><p>随着iPig在P++语言上的造诣日益提升，他形成了自己一套完整的代<br/>
码库。猪王国想参加POI的童鞋们都争先恐后问iPig索要代码库。iPi<br/>
g不想把代码库给所有想要的小猪，只想给其中的一部分既关系好又<br/>
肯出钱的小猪，于是他决定举行了一个超大型拍卖会。 在拍卖会上<br/>
，所有的N头小猪将会按照和iPig的好感度从低到高，从左到右地在i<br/>
Pig面前站成一排。每个小猪身上都有9猪币（与人民币汇率不明），<br/>
从最左边开始，每个小猪依次举起一块牌子，上面写上想付出的买代<br/>
码库的猪币数量（1到9之间的一个整数）。大家都知道，如果自己付<br/>
的钱比左边的猪少，肯定得不到梦寐以求的代码库，因此从第二只起<br/>
，每只猪出的钱都大于等于左边猪出的价钱。最终出的钱最多的小猪<br/>
（们）会得到iPig的代码库真传，向着保送PKU（Pig Kingdom Unive<br/>
rsity）的梦想前进。 iPig对自己想到的这个点子感到十分满意，在<br/>
去现场的路上，iPig就在想象拍卖会上会出现的场景，例如一共会出<br/>
现多少种出价情况之类的问题，但这些问题都太简单了，iPig早已不<br/>
敢兴趣了，他想要去研究更加困难的问题。iPig发现如果他从台上往<br/>
下看，所有小猪举的牌子从左到右将会正好构成一个N位的整数，他<br/>
现在想要挑战的问题是所有可能构成的整数中能正好被P整除的有多<br/>
少个。由于答案过大，他只想要知道答案mod 999911659就行了。 </p></div>

# Input

<div class="content"><p>一行：两个数N（1≤N≤10^18）、P(1≤P≤500)，用一个空格分开。</p></div>

# Output

<div class="content"><p>一行：一个数，表示答案除以999911659的余数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">2 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">15<br/>
样例解释<br/>
方案可以是：12 15 18 24 27 33 36 39 45 48 57 66 69 78 99，共15种。<br/>
数据规模<br/>
测试点	N	P	测试点	N	P<br/>
1	≤1000	≤500	6	≤10^6	≤500<br/>
2	≤10^18	5	7	≤10^18	≤120<br/>
3	≤10^18	≤10	8	≤10^18	≤500<br/>
4	≤10^18	≤10	9	≤10^18	≤500<br/>
5	≤10^18	25	10	≤10^18	≤500<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Sdoi2010 Contest2 Day2">Sdoi2010 Contest2 Day2</a></p></div>

