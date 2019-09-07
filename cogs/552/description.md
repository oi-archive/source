# 题目描述


<div>[说明]此题中出现的所有数全为整数</div>
<div>[背景]SubRaY有一天得到一块西瓜,是长方体形的....</div>
<div>[题目描述]SubRaY发现这块西瓜长m厘米,宽n厘米,高h厘米.他发现如果把这块西瓜平均地分成m*n*h块1立方厘米的小正方体,那么每一小块都会有一个营养值(可能为负,因为西瓜是有可能坏掉的,但是绝对值不超过200).</div>
<div>现在SubRaY决定从这m*n*h立方厘米的西瓜中切出mm*nn*hh立方厘米的一块小西瓜(一定是立方体形,长宽高均为整数),然后吃掉它.他想知道他最多能获得多少营养值.(0&lt;=mm&lt;=m,0&lt;=nn&lt;=n,0&lt;=hh&lt;=h.mm,nn,hh的值由您来决定).</div>
<div>换句话说,我们希望从一个m*n*h的三维矩阵中,找出一个三维子矩阵,这个子矩阵的权和最大.</div>
<div> </div>
<div> </div>
<div> </div>
<div> </div>
<div> <img alt="" src="/images/matrix.JPG"/></div>
<div> </div>
<div> </div>
<div> </div>
<div> </div>
<div> </div>
<div align="center">一个2*3*4的例子,最优方案为切红色2*3*1部分</div>
<div>[输入][matrix.in]</div>
<div>首行三个数h,m,n(注意顺序),分别表示西瓜的高,长,宽.</div>
<div>以下h部分,每部分是一个m*n的矩阵,第i部分第j行的第k个数表示西瓜第i层,第j行第k列的那块1立方厘米的小正方体的营养值.</div>
<div> </div>
<div>[输出][matrix.out]</div>
<div>SubRaY所能得到的最大营养值</div>
<div> </div>
<div>[样例输入]</div>
<div>2 3 4</div>
<div>4 1 2 8</div>
<div>0 5 -48 4</div>
<div>3 0 1 9</div>
<div>2 1 4 9</div>
<div>1 0 1 7</div>
<div>3 1 2 8</div>
<div> </div>
<div>[样例输出]</div>
<div>45</div>
<div> </div>
<div>[数据范围]</div>
<div>对于30%的数据,h=1,1&lt;=m,n&lt;=10</div>
<div>对于全部的数据,1&lt;=h&lt;=32,1&lt;=m,n&lt;=50,保证h&lt;=m,n</div>
