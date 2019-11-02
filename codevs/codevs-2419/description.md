<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Farmer John <span style="">的奶牛们喜欢看书，并且</span><span style="font-family: 'Times New Roman';">Farmer John </span><span style="">发现在他的奶牛们稍微看了些有关于自然科学的书时，会产出更多的牛奶。他决定更新牛棚里的图书馆，把原廉价的小说换成算术和数学的课本。不幸的是，有些新书掉到了泥浆里面，现在它们的</span><span style="font-family: 'Times New Roman';">ISBN</span><span style="">号码很难分辨出来了。 </span><br>ISBN<span style="">（国际标准图书编号）是由十个阿拉伯数字组成的编码，用来唯一地标识一本书。前九个阿拉伯数字描述这本书的一些信息，最后一个数字用来验证</span><span style="font-family: 'Times New Roman';">ISBN</span><span style="">码是否正确。要验证</span><span style="font-family: 'Times New Roman';">ISBN</span><span style="">码的正确性，你要把第一个数字乘以十，你要把第二个数字乘以九，你要把第三个数字乘以八</span><span style="font-family: 'Times New Roman';">……</span><span style="">直到最后一个数字乘上一，再把这些积累加起来。如果所得的和不为零，且可以被</span><span style="font-family: 'Times New Roman';">11</span><span style="">整除的话，那么这就是一个合法的</span><span style="font-family: 'Times New Roman';">ISBN</span><span style="">码。 </span><br>比如说 <span style="font-family: 'Times New Roman';">0201103311 </span><span style="">是一个合法的</span><span style="font-family: 'Times New Roman';">ISBN</span><span style="">，因为 </span><br>10*0+9*2+8*0+7*1+6*1+5*0+4*3+3*3+2*1+1*1=55 <br>前九个数字都在<span style="font-family: 'Times New Roman';">0</span><span style="">到</span><span style="font-family: 'Times New Roman';">9</span><span style="">之间。有时候，最后一个数字需要取到</span><span style="font-family: 'Times New Roman';">10</span><span style="">，那么我们就把最后一个数字写成大写</span><span style="font-family: 'Times New Roman';">X</span><span style="">（这时就不叫数字了，呵呵）。比如</span><span style="font-family: 'Times New Roman';">156881111X</span><span style="">也是一个合法的</span><span style="font-family: 'Times New Roman';">ISBN</span><span style="">码。 </span><br>你的任务就是在给你丢失了一个数字的<span style="font-family: 'Times New Roman';">ISBN</span><span style="">码之后，确定那个丢失的数字。丢失数字的地方用</span><span style="font-family: 'Times New Roman';">“?”</span><span style="">表示。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>总共<span style="font-family: 'Times New Roman';">1</span><span style="">行，一个十个数字组成的</span><span style="font-family: 'Times New Roman';">ISBN</span><span style="">码，其中包含用</span><span style="font-family: 'Times New Roman';">“?”</span><span style="">表示的一个丢失的数字。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">总共<span style="font-family: 'Times New Roman';">1</span><span style="font-family: 宋体;">行，就是那个丢失的数码（</span><span style="font-family: 'Times New Roman';">0..9</span><span style="font-family: 宋体;">或大写</span><span style="font-family: 'Times New Roman';">X</span><span style="font-family: 宋体;">）。如果标有的</span><span style="font-family: 'Times New Roman';">&ldquo;?&rdquo;</span><span style="font-family: 宋体;">的位置上没有数字可以使之成为一个合法的</span><span style="font-family: 'Times New Roman';">ISBN</span><span style="font-family: 宋体;">码的话，就输出</span><span style="font-family: 'Times New Roman';">-1</span><span style="font-family: 宋体;">。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>15688?111X</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>注意X和不为0(⊙o⊙)哦</p>
</div>
</div>