<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    通过代数基本定理，我们知道若计算重根，一个n 次的多项式在复数域内恰好有n 个零点(函数值为0 的点)。现给定一个整系数多项式F[x]，它的n 个零点恰好都是有理数(即可以写成两个整数相除的形式)；同时，若我们把它所有的非零零点(函数自变量不为0，函数值为0)去重，则可以得到r 个互不相同的非零零点，其中第i 个非零零点可以被表示成下式：<br>    sgn<sub>i</sub> ∗(q<sub>i/</sub>p<sub>i</sub>)<br>    式中sgn<sub>i</sub>表示第i 个零点的符号，p<sub>i</sub>和q<sub>i</sub>为互质的两个正整数。 <br>    现在告诉你F[x]，要求你输出将他因式分解后的形式。 </p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    输入只有一行，包含多项式F[x]。<br>    多项式一定是如下的形式：<br>                         a<sub>n</sub>x<sup>n</sup> + a<sub>n−1</sub>x<sup>n−1</sup> + ⋯ a<sub>1</sub>x + a<sub>0</sub> </p>
<p>    次数一定为从高到低，其中a<sub>i</sub>为整数，并且若a<sub>i</sub>为0，则省略该项，若a<sub>i</sub>为负数，则省<br>    略之前的加号，若ai的绝对值为1 且i 不为0，则不输出1，并且保证an不为0.<br>    详见样例输入。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; 输出一行，表示因式分解后的形式，格式如下：<br />&nbsp; &nbsp; a<sub>n</sub> (x + u<sub>1</sub>/v<sub>1</sub>)^t<sub>1</sub>(x + u<sub>2</sub>/v<sub>2</sub>)^t<sub>2</sub> &hellip; (x + u<sub>s</sub>/v<sub>s</sub>)^t<sub>s</sub>&nbsp;<br />&nbsp; &nbsp; 其中u，v 互质，且v 为正整数。<br />&nbsp; &nbsp;&nbsp;其中ui/vi从大到小排列，若ui/vi = 0 则该项为x^ti，若ui/vi为负数，则省略加号，若vi为1，则省略/vi。<br />&nbsp; &nbsp; 若ti为1 则省略^ti。<br />&nbsp; &nbsp; 若an为&plusmn;1 则将1 省略。<br />&nbsp; &nbsp; 详见样例输出。&nbsp;</p>
<p>&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【样例1】<br>8x^7-258x^5+2112x^3-512x<br>【样例2】<br>-x^2+2x-1<br>【样例3】<br>3471669046846136046501981x^16+523705101892702183583476074x^15-42170475511736822251046719791x^14+1154700113321007935575518213810x^13-15255851192246009548151164015605x^12+99166092441431509593886082283198x^11-252943893149267918788703854873893x^10-21090741362454393977165098185618x^9-744504531988547875370750460900x^8-14556479621520611267680614120x^7-170558365363069027452907248x^6-1198338832152898113421152x^5-4675893106661778820032x^4-7817710219819447680x^3</p>
<p> </p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【1】<br>8(x-4)^2(x-1/2)x(x+1/2)(x+4)^2<br>【2】<br>-(x-1)^2<br>【3】<br>3471669046846136046501981(x-167/13)^5x^3(x+2/171)^7(x+215)</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>求不卡评测机好么</p>
</div>
</div>