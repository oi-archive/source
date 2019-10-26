
# Description

<div class="content"><div><span style="font-size: medium">    贝西和其他奶牛们都喜欢巧克力，所以约翰准备买一些送给她们。奶牛巧克力专卖店里</span></div>
<div><span style="font-size: medium">有N种巧克力，每种巧克力的数量都是无限多的。每头奶牛只喜欢一种巧克力，调查显示，</span></div>
<div><span style="font-size: medium">有Ci头奶牛喜欢第i种巧克力，这种巧克力的售价是P。</span></div>
<div><span style="font-size: medium">    约翰手上有B元预算，怎样用这些钱让尽量多的奶牛高兴呢？下面举个例子：假设约翰</span></div>
<div><span style="font-size: medium">有50元钱，商店里有S种巧克力：</span></div>
<p><table cellspacing="0" cellpadding="0" border="1">
    <tbody>
        <tr style="height: 16.5pt">
            <td nowrap="nowrap" width="139" style="border-right: #ece9d8; padding-right: 0cm; border-top: #ece9d8; padding-left: 0cm; padding-bottom: 0cm; border-left: #ece9d8; width: 104.25pt; padding-top: 0cm; border-bottom: #ece9d8; height: 16.5pt; background-color: transparent">
            <div><span style="font-size: medium">  巧克力品种</span></div>
            </td>
            <td nowrap="nowrap" width="142" style="border-right: #ece9d8; padding-right: 0cm; border-top: #ece9d8; padding-left: 0cm; padding-bottom: 0cm; border-left: #ece9d8; width: 106.5pt; padding-top: 0cm; border-bottom: #ece9d8; height: 16.5pt; background-color: transparent">
            <div><span style="font-size: medium">    单价</span></div>
            </td>
            <td nowrap="nowrap" width="153" style="border-right: #ece9d8; padding-right: 0cm; border-top: #ece9d8; padding-left: 0cm; padding-bottom: 0cm; border-left: #ece9d8; width: 114.75pt; padding-top: 0cm; border-bottom: #ece9d8; height: 16.5pt; background-color: transparent">
            <div><span style="font-size: medium">高兴的奶牛数量</span></div>
            </td>
        </tr>
        <tr style="height: 102pt">
            <td nowrap="nowrap" width="139" style="border-right: #ece9d8; padding-right: 0cm; border-top: #ece9d8; padding-left: 0cm; padding-bottom: 0cm; border-left: #ece9d8; width: 104.25pt; padding-top: 0cm; border-bottom: #ece9d8; height: 102pt; background-color: transparent">
            <div><span style="font-size: medium">    1<br/>
                2<br/>
                3<br/>
                4<br/>
                5</span></div>
            </td>
            <td nowrap="nowrap" width="142" style="border-right: #ece9d8; padding-right: 0cm; border-top: #ece9d8; padding-left: 0cm; padding-bottom: 0cm; border-left: #ece9d8; width: 106.5pt; padding-top: 0cm; border-bottom: #ece9d8; height: 102pt; background-color: transparent">
            <div><span style="font-size: medium">    5<br/>
                1<br/>
                10<br/>
                7<br/>
                60</span></div>
            </td>
            <td nowrap="nowrap" width="153" style="border-right: #ece9d8; padding-right: 0cm; border-top: #ece9d8; padding-left: 0cm; padding-bottom: 0cm; border-left: #ece9d8; width: 114.75pt; padding-top: 0cm; border-bottom: #ece9d8; height: 102pt; background-color: transparent">
            <div><span style="font-size: medium">    3<br/>
                1<br/>
                4<br/>
                2<br/>
                1</span></div>
            </td>
        </tr>
        <tr>
            <td style="border-right: #ece9d8; padding-right: 0cm; border-top: #ece9d8; padding-left: 0cm; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0cm; border-bottom: #ece9d8; background-color: transparent">
            <div><span style="font-size: medium"> </span></div>
            </td>
            <td style="border-right: #ece9d8; padding-right: 0cm; border-top: #ece9d8; padding-left: 0cm; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0cm; border-bottom: #ece9d8; background-color: transparent">
            <div><span style="font-size: medium"> </span></div>
            </td>
            <td style="border-right: #ece9d8; padding-right: 0cm; border-top: #ece9d8; padding-left: 0cm; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0cm; border-bottom: #ece9d8; background-color: transparent">
            <div><span style="font-size: medium"> </span></div>
            </td>
        </tr>
    </tbody>
</table>
</p>
<div><span style="font-size: medium">    显然约翰不会去买第五种巧克力，因为他钱不够，不过即使它降价到50，也不该选择</span></div>
<div><span style="font-size: medium">它，因为这样只会让一头奶牛高兴，实在太浪费了。最好的买法是：第二种买1块，第一种</span></div>
<div><span style="font-size: medium">买3块，第四种买2块，第三种买2块，正好用完50元，可以让1+3+2+2=8头牛高兴。</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行：两个用空格分开的整数：N和B，1&lt;=N≤100000，1≤B≤10^18</span></div>
<div><span style="font-size: medium">第二行到N+1行：第i+l行，是两个用空格分开的整数：Pj和Ci，1≤Pi，Ci≤10^18</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">第一行：一个整数，表示最多可以让几头奶牛高兴</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 50<br/>
5 3<br/>
1 1<br/>
10 4<br/>
7 2<br/>
60 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">8</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

