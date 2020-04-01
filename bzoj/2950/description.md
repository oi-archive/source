
# Description

<div class="content"><div>
<div>
<div>Byteland一直以奇妙的跳舞蝇而闻名于世。驯养的苍蝇能和着音乐的节奏精确地做每一次飞跃。通常，训练者会在</div>
<div>桌上放一排硬币，这些硬币的排列并不按照特定的顺序。每枚硬币上都有一行题字：i→j，i是这枚硬币的编号，j</div>
<div>是站在硬币i上的苍蝇下一步应该飞往的硬币编号。训练者在每个硬币上放一只苍蝇，然后开始放音乐。那些苍蝇</div>
<div>就跟着音乐的节拍开始跳舞，在每一拍中苍蝇都会直接跳到编号为j的硬币上。在舞蹈中，可能会出现多只苍蝇在</div>
<div>同一硬币上的情况。这样，跳舞蝇就会一起继续表演。假定有n只苍蝇，n枚硬币。则一旦确定了n枚硬币上的题字</div>
<div>，那么这场表演也就确定了。然而，对硬币不同的设置也可能导致相同的表演，只要我们把硬币按适当的顺序排列</div>
<div>让我们先来看3枚硬币上的表演。</div>
<div>如果表演是这样进行：</div>
<div>从第一个硬币到第二个，第二个到第三个，第三个又回到第一个硬币（表示为1→2，2→3，3→1）。</div>
<div>具体表演是3只苍蝇绕圈跳跃，从不相遇。那么表演1→2，2→3，3→3，则是与其不同的。</div>
<div>因为该表演为：两拍后，所有的苍蝇在第3枚硬币上相遇，然后一直在原地跳跃。</div>
<div>但是，设置1→2，2→3，3→2，4→4和1→1、2→3、3→2、4→3就是同样的类型。</div>
<div>如果你把前者的硬币从左到右排列，而把后者从右到左排列，就会看到相同的表演。</div>
<div>任务：</div>
<div>如果跳舞蝇的两次表演是相同的，就会使观众不满，请编写一个程序：</div>
<div>读入测试任务的个数；</div>
<div>对每一个测试任务，从PCH.IN中读入两组硬币设置，验证是否能把硬币按一定顺序排列，使跳舞蝇给出相同的表演；</div>
</div>
</div></div>

# Input

<div class="content"><div style="text-align: left">
<div>第一行是测试任务的个数d(1≤d≤100)，以下3*d行，每三行描述一个任务。</div>
<div>三行中的第一行是一个整数n(1≤n≤2000)，表示硬币的个数。</div>
<div>后两行每行均为一套硬币的描述。</div>
<div>格式为n个用空格分开的1…n范围内的整数，第i个整数表示硬币i上的苍蝇应该飞向的硬币的编号。</div>
</div></div>

# Output

<div class="content"><div>对每个任务，输出一行，仅包含一个字母。</div>
<div>如果可以按一定顺序排硬币使表演相同则输出“T”，否则输出“N”。</div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
3<br/>
2 3 1<br/>
2 3 3<br/>
4<br/>
2 3 2 4<br/>
1 3 2 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">N<br/>
T</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

