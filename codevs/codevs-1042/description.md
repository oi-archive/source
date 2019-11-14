<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    我们可以用这样的方式来表示一个十进制数： 将每个阿拉伯数字乘以一个以该数字所处位置的（值减１）为指数，以１０为底数的幂之和的形式。例如：１２３可表示为 １＊１０<sup>２</sup>＋２＊１０<sup>１</sup>＋３＊１０<sup>０</sup>这样的形式。</p>
<p>     与之相似的，对二进制数来说，也可表示成每个二进制数码乘以一个以该数字所处位置的（值－１）为指数，以２为底数的幂之和的形式。一般说来，任何一个正整数Ｒ或一个负整数－Ｒ都可以被选来作为一个数制系统的基数。如果是以Ｒ或－Ｒ为基数，则需要用到的数码为 ０，１，．．．．Ｒ－１。例如，当Ｒ＝７时，所需用到的数码是０，１，２，３，４，５和６，这与其是Ｒ或－Ｒ无关。如果作为基数的数绝对值超过１０，则为了表示这些数码，通常使用英文字母来表示那些大于９的数码。例如对１６进制数来说，用Ａ表示１０，用Ｂ表示１１，用Ｃ表示１２，用Ｄ表示１３，用Ｅ表示１４，用Ｆ表示１５。</p>
<p>在负进制数中是用－Ｒ 作为基数，例如－１５（十进制）相当于１１０００１（－２进制），并且它可以被表示为２的幂级数的和数：</p>
<p>   １１０００１＝１＊（－２）<sup>５</sup>＋１＊（－２）<sup>４</sup>＋０＊（－２）<sup>３</sup>＋０＊（－２）<sup>２</sup>＋ </p>
<p>                 ０＊（－２）<sup>１</sup> ＋１＊（－２）<sup>０</sup></p>
<p><sup>  </sup>  设计一个程序，读入一个十进制数和一个负进制数的基数, 并将此十进制数转换为此负进制下的数：     －Ｒ∈｛－２，－３，－４，．．．，－２０｝　</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>  输入的每行有两个输入数据。</p>
<p>  第一个是十进制数Ｎ（－32768＜＝Ｎ＜＝32767）；  第二个是负进制数的基数－Ｒ。</p>
<p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>结果显示在屏幕上，相对于输入，应输出此负进制数及其基数，若此基数超过１０，则参照１６进制的方式处理。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>30000 -2</p>
<p>-20000 -2</p>
<p>28800 -16</p>
<p>-25000 -16</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>30000=11011010101110000(base-2)</p>
<p>-20000=1111011000100000(base-2)</p>
<p>28000=19180(base-16)</p>
<p>-25000=7FB8(base-16)</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>上面已述。</p>
</div>
</div>