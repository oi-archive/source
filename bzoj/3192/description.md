
# Description

<div class="content"><div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">箱子再分配问题需要解决如下问题：</span></div>
<div><span style="font-size: medium"> （1）一共有N个物品，堆成M堆。</span></div>
<div><span style="font-size: medium"> （2）所有物品都是一样的，但是它们有不同的优先级。</span></div>
<div><span style="font-size: medium"> （3）你只能够移动某堆中位于顶端的物品。</span></div>
<div><span style="font-size: medium"> （4）你可以把任意一堆中位于顶端的物品移动到其它某堆的顶端。若此物品是当前所有物品中优先级最高的，可以直接将之删除而不用移动。</span></div>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">（5）求出将所有物品删除所需的最小步数。删除操作不计入步数之中。</span></div>
<div><span style="font-size: medium"> （6）只是一个比较难解决的问题，这里你只需要解决一个比较简单的版本：</span></div>
<div><span style="font-size: medium">         不会有两个物品有着相同的优先级，且M=2</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行是包含两个整数N1,N2分别表示两堆物品的个数。</span></div>
<div><span style="font-size: medium">接下来有N1行整数按照从顶到底的顺序分别给出了第一堆物品中的优先级，数字越大，优先级越高。</span></div>
<div><span style="font-size: medium">再接下来的N2行按照同样的格式给出了第二堆物品的优先级。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">对于每个数据，请输出一个整数，即最小移动步数。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
1<br/>
4<br/>
5<br/>
2<br/>
7<br/>
3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
 <br/>
 </span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">1&lt;=N1+N2&lt;=100000</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

