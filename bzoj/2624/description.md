
# Description

<div class="content"><div><span style="font-size: medium"><b> </b><b>  </b>代数学研究的基本对象之一群是一些元素的集合。这些元素之间有一种代数运算，称之为乘法。两个群元素的乘积是一个群元素。一个大家习以为常的群是有理数乘法群，例如，等等，都是这个群中乘法的例子。需要注意的是，如果仅仅考虑有理数的乘法群，另外的一些运算比如加法是不被讨论的。数学家们把乘法抽象出来，就成为了群。群需要满足以下三条性质：</span></div>
<div style="text-indent: 15.75pt"><span style="font-size: medium">结合律：对群中的任意元素a,b,c 有 a(bc)=(ab)c</span></div>
<div style="text-indent: 15.75pt"><span style="font-size: medium">单位元：在群中存在唯一的元素e，它对群中任意的元素a有ea=a，ae=a</span></div>
<div style="text-indent: 57.75pt"><span style="font-size: medium">有理数乘法群的单位元是1</span></div>
<div style="text-indent: 15.75pt"><span style="font-size: medium">逆 元：对群中任意元素a,都存在群中唯一的元素b,使得ab=ba=e</span></div>
<div><span style="font-size: medium"> </span></div>
<div style="text-indent: 15.75pt"><span style="font-size: medium">比如有理数乘法群中，23的逆元就为。从这里可以看出，整数乘法不能构成一个群</span></div>
<div><span style="font-size: medium">需要注意的是，群的定义中并没有交换律，就是说ab不一定等于ba，有理数乘法群作为一个特例，其交换性是没有普遍的意义的</span></div>
<div><span style="font-size: medium"> </span></div>
<div style="text-indent: 15.75pt"><span style="font-size: medium">现在的问题是，给定群的元素的个数（群的阶数），需要知道这样的群有多少种。只要满足上述三条性质，就是群，应该算上。</span></div>
<div><span style="font-size: medium">   </span></div>
<div style="text-indent: 15.75pt"><span style="font-size: medium">下面用四阶群的例子来说明这个问题。抽象地记群元素为e,a,b,c 只要列出一个乘法表，就可以代表一个群。下面给出推导乘法表的步骤：</span></div>
<p><table cellspacing="0" cellpadding="0" width="360" border="0" style="width: 270pt; border-collapse: collapse">
    <tbody>
        <tr style="height: 14.25pt">
            <td nowrap="nowrap" width="72" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; width: 54pt; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">群1</span></div>
            </td>
            <td nowrap="nowrap" width="72" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; width: 54pt; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium"><b>e</b></span></div>
            </td>
            <td nowrap="nowrap" width="72" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; width: 54pt; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium"><b>a</b></span></div>
            </td>
            <td nowrap="nowrap" width="72" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; width: 54pt; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium"><b>b</b></span></div>
            </td>
            <td nowrap="nowrap" width="72" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; width: 54pt; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium"><b>c</b></span></div>
            </td>
        </tr>
        <tr style="height: 14.25pt">
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium"><b>e</b></span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">e (1)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">a (1)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">b (1)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">c (1)</span></div>
            </td>
        </tr>
        <tr style="height: 14.25pt">
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium"><b>a</b></span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">a (1)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">e (2)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">c (3)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">b (3)</span></div>
            </td>
        </tr>
        <tr style="height: 14.25pt">
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium"><b>b</b></span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">b (1)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">c (3)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">e (4)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">a (5)</span></div>
            </td>
        </tr>
        <tr style="height: 14.25pt">
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium"><b>c</b></span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">c (1)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">b (3)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">a (5)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">e (5)</span></div>
            </td>
        </tr>
    </tbody>
</table>
</p>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">有单位元素的性质，可以填上</span></div>
<div><span style="font-size: medium">a*a可能为e,b,c，但不可能为a,否则a*a=a两边乘以a的逆元，得到a=e；</span></div>
<div><span style="font-size: medium">a*a=b和a*a=c的情况是一样的，只是乘法表中元素的位置进行了一个变换，本质没有改变，称为一个群同构；此时可以把a*a得到的元素称为b；</span></div>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">所以只要讨论a*a=e和a*a=b的情况；下面先讨论a*a=e的情况</span></div>
<div><span style="font-size: medium">a*b不能为a或e，a*b为b的话，a=e，也矛盾，所以a*b=c；同理可填上所有的(3)</span></div>
<div><span style="font-size: medium">b*b=e时，b*c=c*b=a，c*c=e，得到群1</span></div>
<div><span style="font-size: medium">b*b=a时，b*c=c*b=e，c*c=a，得到群2</span></div>
<div><span style="font-size: medium"> </span></div>
<p><table cellspacing="0" cellpadding="0" width="360" border="0" style="width: 270pt; border-collapse: collapse">
    <tbody>
        <tr style="height: 14.25pt">
            <td nowrap="nowrap" width="72" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; width: 54pt; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">群2</span></div>
            </td>
            <td nowrap="nowrap" width="72" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; width: 54pt; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium"><b>e</b></span></div>
            </td>
            <td nowrap="nowrap" width="72" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; width: 54pt; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium"><b>a</b></span></div>
            </td>
            <td nowrap="nowrap" width="72" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; width: 54pt; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium"><b>b</b></span></div>
            </td>
            <td nowrap="nowrap" width="72" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; width: 54pt; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium"><b>c</b></span></div>
            </td>
        </tr>
        <tr style="height: 14.25pt">
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium"><b>e</b></span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">e (1)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">a (1)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">b (1)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">c (1)</span></div>
            </td>
        </tr>
        <tr style="height: 14.25pt">
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium"><b>a</b></span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">a (1)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">e (2)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">c (3)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">b (3)</span></div>
            </td>
        </tr>
        <tr style="height: 14.25pt">
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium"><b>b</b></span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">b (1)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">c (3)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">a (4)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">e (5)</span></div>
            </td>
        </tr>
        <tr style="height: 14.25pt">
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium"><b>c</b></span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">c (1)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">b (3)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">e (5)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">a (5)</span></div>
            </td>
        </tr>
    </tbody>
</table>
</p>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">当a*a=b时，按照标号顺序可填出下列的群：</span></div>
<p><table cellspacing="0" cellpadding="0" width="360" border="0" style="width: 270pt; border-collapse: collapse">
    <tbody>
        <tr style="height: 14.25pt">
            <td nowrap="nowrap" width="72" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; width: 54pt; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">群 2’</span></div>
            </td>
            <td nowrap="nowrap" width="72" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; width: 54pt; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium"><b>e</b></span></div>
            </td>
            <td nowrap="nowrap" width="72" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; width: 54pt; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium"><b>a</b></span></div>
            </td>
            <td nowrap="nowrap" width="72" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; width: 54pt; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium"><b>b</b></span></div>
            </td>
            <td nowrap="nowrap" width="72" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; width: 54pt; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium"><b>c</b></span></div>
            </td>
        </tr>
        <tr style="height: 14.25pt">
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium"><b>e</b></span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">e (1)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">a (1)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">b (1)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">c (1)</span></div>
            </td>
        </tr>
        <tr style="height: 14.25pt">
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium"><b>a</b></span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">a (1)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">b (2)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">c (4)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">e (3)</span></div>
            </td>
        </tr>
        <tr style="height: 14.25pt">
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium"><b>b</b></span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">b (1)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">c (4)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">e (6)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">a (5)</span></div>
            </td>
        </tr>
        <tr style="height: 14.25pt">
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium"><b>c</b></span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">c (1)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">e (3)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">a (5)</span></div>
            </td>
            <td nowrap="nowrap" style="border-right: #ece9d8; padding-right: 0.75pt; border-top: #ece9d8; padding-left: 0.75pt; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0.75pt; border-bottom: #ece9d8; height: 14.25pt; background-color: transparent">
            <div><span style="font-size: medium">b (6)</span></div>
            </td>
        </tr>
    </tbody>
</table>
</p>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">但需要注意的是，这并没有得到一个新的群，把群2中的a,b调换位置，就得到了群2’。群2’只是群2的一个同构而已。</span></div>
<div><span style="font-size: medium">综上所述，四阶群一共有2种。</span></div>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">虽然4阶群一定有交换律，但这里再次提醒，这并非一个普遍现象。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div style="text-indent: 15.75pt"><span style="font-size: medium">输入群的阶数n(4&lt;=n&lt;=3000)。 </span></div>
<div style="text-indent: 15.75pt"><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div style="text-indent: 15.75pt"><span style="font-size: medium">输出n阶群的种类数。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
 </span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
Hint<br/><br/>
注意并灵活运用群的三条性质</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

