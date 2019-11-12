# 题目描述


<div>背景</div>
<div> </div>
<div style="text-indent: 21.75pt">基于作者的一些看法，本题已帮读者过滤了单相思和同性之间出现好感的情况。</div>
<div> </div>
<div> </div>
<div>问题描述</div>
<div> </div>
<div style="text-indent: 21.75pt">暑假到来了，某个班决定出去旅行。已知这个班有共有n个人，编号为1..n,其中有m个男生，剩下的全部为女生。由于个人取向问题，男女生之间会有一些好感值。基于背景这个好感值是双向的，即某男对某女的好感值为a，那么该某女对该某男的好感值也为a。很自然每个人会对很多人有好感值。可是每个班都必然有bug男和bug女的存在。即对bug男来说，任何女生对bug男的好感值都为0（bug女同理）。</div>
<div style="text-indent: 21.75pt">该班的班主任是一个很保守的人，他不希望男女之间产生朦胧之感，即使出现朦胧之感，班主任也希望学生之间总的好感值之和尽量的低，同时班主任很爱学生，他希望在总的好感值之和尽量低的情况下尽量多的人能去旅游。为了保证和谐，男生和女生必须都有人去。由于班主任日理万机，他把这个重要的任务交给了你。现在就是考验神牛你的时候了。</div>
<div> </div>
<div> </div>
<div>输入文件</div>
<div> </div>
<div style="text-indent: 21.75pt">第一行有三个整数n，m，s。</div>
<div style="text-indent: 21.75pt">接下来s行，每行三个数a，b，c，描述男生a和女生b之间好感值为c。</div>
<div style="text-indent: 21.75pt"><span style="color: black">所有变量的含义可以参见题目描述。</span></div>
<div> </div>
<div> </div>
<div><span style="color: black">输出文件</span></div>
<div> </div>
<div style="text-indent: 21.75pt"><span style="color: black">只有一行两个整数，既满足题目描述的好感值之和以及去旅游的人数。</span></div>
<div> </div>
<div> </div>
<div><span style="color: black">样例输入</span></div>
<div> </div>
<div><span style="color: black">lovetravel.in</span></div>
<div> </div>
<div>8 4 5</div>
<div> </div>
<div>4 5 10</div>
<div> </div>
<div>6 8 120</div>
<div> </div>
<div>6 1 150</div>
<div> </div>
<div>2 5 30</div>
<div> </div>
<div>3 8 70</div>
<div> </div>
<div> </div>
<div>样例输出</div>
<div> </div>
<div>lovetravel.out</div>
<div> </div>
<div>0 5</div>
<div> </div>
<div> </div>
<div>数据规模和约定</div>
<div> </div>
<div>对于50%的数据中<span>    2&lt;=n&lt;=50   0&lt;=s&lt;=500</span></div>
<p><span style="font-size: 10.5pt">对于</span><span style="font-size: 10.5pt">100%</span><span style="font-size: 10.5pt">的数据中</span><span style="font-size: 10.5pt">   2&lt;=n&lt;=5000   0&lt;=s&lt;=5000</span></p>
