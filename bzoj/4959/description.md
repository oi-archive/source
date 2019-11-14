
# Description

<div class="content"><div>在最近被提出的Visual Python++编程语言中,一个语句块被表示为一个由字符组成的矩形,其中左上角在r1行c1列,</div>
<div>右下角在r2行c2列。对于r1≤r≤r2,c1≤c≤c2,所有位于(r,c)的字符被认为是属于这个块的内容。在这些位置中,</div>
<div>满足r=r1或r=r2或c=c1或c=c2的位置被称为是边界。语句块可以嵌套 (矩形包含在其他矩形中) 任意层。在语法正</div>
<div>确的程序中,任意两个语句块要么是嵌套的 (一个包含在另一个中) ,要么是不交的 (不重叠) 。在这两种情况中,</div>
<div>他们的边界也不能重叠。编程人员不需要画出经典程序中的所有矩形,这太浪费时间了,而且Visual Python++也不</div>
<div>可能称为下一个ICPC编程语言。因此程序员只需要在左上角位置放一个字符 &#39;┌&#39; ,在右下角位置放一个字符&#39;┘&#39;</div>
<div>。解析器会自动匹配相应的拐角来获取程序的嵌套结构。你的团队刚刚获得了五小时的合同来开发解析器的这一部</div>
<div>分。</div></div>

# Input

<div class="content"><div>第一行包含一个整数n(1≤n≤10^5),表示拐角对的数量。</div>
<div>接下来n行,每行包含两个整数r和c(1≤r,c≤10^9),指定r行c列为一个左上角。</div>
<div>接下来n行以相同的方式指定了右下角。</div>
<div>所有的拐角位置互不相同。</div></div>

# Output

<div class="content"><div>输出n行,每行包含一个整数。第i行的整数j表示第i个左上角和第j个右下角组成一个矩形。</div>
<div>左上角和右下角均按照他们在输入中的顺序从1到n标号。输出必须是1到n的排列,从而匹配可能嵌套的矩形。</div>
<div>如果存在超过一种合法的匹配,任意一组合法的匹配都是可接受的。如果不存在合法的匹配,输出syntax error。</div></div>

# Sample Input

<div class="content"><span class="sampledata">样例1<br/>
2<br/>
4 7<br/>
9 8<br/>
14 17<br/>
19 18<br/>
样例2<br/>
2<br/>
4 7<br/>
14 17<br/>
9 8<br/>
19 18<br/>
样例3<br/>
2<br/>
4 8<br/>
9 7<br/>
14 18<br/>
19 17<br/>
样例4<br/>
3<br/>
1 1<br/>
4 8<br/>
8 4<br/>
10 6<br/>
6 10<br/>
10 10</span></div>

# Sample Output

<div class="content"><span class="sampledata">样例1<br/>
2<br/>
1<br/>
样例2<br/>
1<br/>
2<br/>
样例3<br/>
syntax error<br/>
样例4<br/>
syntax error</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tangjz提供翻译">鸣谢Tangjz提供翻译</a></p></div>

