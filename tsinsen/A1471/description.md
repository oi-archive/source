<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　小v家有一条护栏，由n个木板组成。第i个木板的高度是a[i]。现在小镇上流行给护栏画矩形，所以小v也要在自家的护栏上画。若要在区间[x,x+k-1]这个区间画一个宽度为k的矩形（1&lt;=x&lt;=n-k+1）,为了美观，高度一定是这个区间里高度最低的木板。现在小v有m个心中理想的宽度，第i个为ki，(ki与kj之间可能一样，1&lt;=i&lt;=n,1&lt;=j&lt;=n)他想知道对于每个ki，求矩形高度的期望。</div>
# 输入格式

<div class="pdcont">　　第一行一个整数n，表示木板的数目。第2行有n个数，第i个数ai表示第个木板的高度。第3行一个整数m。第4行有m个数，表示小v心中理想的第i个宽度ki</div>
# 输出格式

<div class="pdcont">　　输出m行实数，第i行表示宽度为ki的 矩形高度的期望，只要你的答案和正确答案的差的绝对值小于10的-9次方，你的答案将被视为正确。</div>
# 样例输入

<div class="pddata">3<br/>
3 2 1<br/>
4<br/>
1 2 3 1</div>
# 样例输出

<div class="pddata">2.000000000000000<br/>
1.500000000000000<br/>
1.000000000000000<br/>
2.000000000000000</div>
# 数据规模和约定

<div class="pdcont">　　1 ≤ <i>n</i> ≤ 10<sup>6      </sup><br/>
　　1 ≤ <i>a</i><sub><i>i</i></sub> ≤ 10<sup>9     </sup><br/>
　　1 ≤ <i>m</i> ≤ 10<sup>6</sup><sup>   </sup><br/>
　　1 ≤ <i>k</i><sub><i>i</i></sub> ≤ <i>n</i></div>

</div>