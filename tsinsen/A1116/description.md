<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　任何一个正整数都可以用2的幂次方表示。例如：<br/>
　　137=2<sup>7</sup>+2<sup>3</sup>+2<sup>0         </sup><br/>
　　同时约定方次用括号来表示，即a<sup>b</sup> 可表示为a（b）。<br/>
　　由此可知，137可表示为：<br/>
　　2（7）+2（3）+2（0）<br/>
　　进一步：7= 2<sup>2</sup>+2+2<sup>0   </sup>（2<sup>1</sup>用2表示）<br/>
　　3=2+2<sup>0   </sup><br/>
　　所以最后137可表示为：<br/>
　　2（2（2）+2+2（0））+2（2+2（0））+2（0）<br/>
　　又如：<br/>
　　1315=2<sup>10</sup> +2<sup>8</sup> +2<sup>5</sup> +2+1<br/>
　　所以1315最后可表示为：<br/>
　　2（2（2+2（0））+2）+2（2（2+2（0）））+2（2（2）+2（0））+2+2（0）</div>
# 输入格式

<div class="pdcont">　　输入包含一个正整数N（N&lt;=20000），为要求分解的整数。</div>
# 输出格式

<div class="pdcont">　　程序输出包含一行字符串，为符合约定的n的0，2表示（在表示中不能有空格）</div>

</div>