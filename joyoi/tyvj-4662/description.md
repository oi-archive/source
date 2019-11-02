# 

 
 # 题目描述 
<p>折半查找：在有序数据中查找一个数x，有返回位置，没有返回0，区间有数时l前r后，找中间的数m=(l+r)/2；if(a[m]==x)&nbsp;return&nbsp;m,否则&nbsp;if(a[m]&lt;x)，则l=m+1；如果if(a[m]&gt;x)&nbsp;则：r=m-1；当l&gt;r，区间都没有时结束。<br />
如&nbsp;：1&middot;&middot;&middot;100页的书，翻到25，第一次应该翻到50，然后在1~49中找25</p> 

 
 # 输入格式 
<p>第1行：n（一个整数）；</p>

<p>第2到n+1行：有n个整数，第2行是第1个整数，<span style="color: rgb(51, 51, 51); font-family: sans-serif, Arial, Verdana, 'Trebuchet MS'; font-size: 13px; line-height: 20.8px; background-color: rgb(255, 255, 255);">第3</span><span style="color: rgb(51, 51, 51); font-family: sans-serif, Arial, Verdana, 'Trebuchet MS'; font-size: 13px; line-height: 20.8px; background-color: rgb(255, 255, 255);">行是</span><span style="color: rgb(51, 51, 51); font-family: sans-serif, Arial, Verdana, 'Trebuchet MS'; font-size: 13px; line-height: 20.8px; background-color: rgb(255, 255, 255);">第2个整数&middot;&middot;&middot;&middot;&middot;&middot;</span><span style="color: rgb(51, 51, 51); font-family: sans-serif, Arial, Verdana, 'Trebuchet MS'; font-size: 13px; line-height: 20.8px; background-color: rgb(255, 255, 255);">第n</span><span style="color: rgb(51, 51, 51); font-family: sans-serif, Arial, Verdana, 'Trebuchet MS'; font-size: 13px; line-height: 20.8px; background-color: rgb(255, 255, 255);">行是</span><span style="color: rgb(51, 51, 51); font-family: sans-serif, Arial, Verdana, 'Trebuchet MS'; font-size: 13px; line-height: 20.8px; background-color: rgb(255, 255, 255);">第n-1个整数；</span></p>

<p><span style="line-height: 1.6em;">第n+2行：</span><span style="line-height: 20.8px;">查找的数：</span><span style="line-height: 1.6em;">x。</span></p> 

 
 # 输出格式 
<p><span style="line-height: 20.8px;">第1行：x在数组中的位置。</span></p> 

 
 # 提示 
<p><span style="line-height: 20.8px;">先排序，再查找；</span></p>

<p>C++参考源程序：</p>

<p>#include&lt;iostream&gt;<br />
using&nbsp;namespace&nbsp;std;<br />
int&nbsp;a[1001],n;<br />
void&nbsp;read()<br />
{<br />
&nbsp;&nbsp;&nbsp;&nbsp;int&nbsp;i;<br />
&nbsp;&nbsp;&nbsp;&nbsp;cin&gt;&gt;n;<br />
&nbsp;&nbsp;&nbsp;&nbsp;for(i=1;i&lt;=n;i++)<br />
&nbsp;&nbsp;&nbsp;&nbsp;cin&gt;&gt;a[i];&nbsp;<br />
}&nbsp;<br />
void&nbsp;xuan()<br />
{<br />
&nbsp;&nbsp;&nbsp;&nbsp;int&nbsp;i,j;<br />
&nbsp;&nbsp;&nbsp;&nbsp;for(i=1;i&lt;=n-1;i++)<br />
&nbsp;&nbsp;&nbsp;&nbsp;for(j=i+1;j&lt;=n;j++)<br />
&nbsp;&nbsp;&nbsp;&nbsp;if(a[i]&gt;a[j])<br />
&nbsp;&nbsp;&nbsp;&nbsp;swap(a[i],a[j]);<br />
&nbsp;&nbsp;&nbsp;&nbsp;for(i=1;i&lt;=n;i++)<br />
&nbsp;&nbsp;&nbsp;&nbsp;cout&lt;&lt;a[i]&lt;&lt;&quot;&nbsp;&quot;&lt;&lt;endl;&nbsp;<br />
}<br />
int&nbsp;half(int&nbsp;x,int&nbsp;l,int&nbsp;r)<br />
{<br />
&nbsp;&nbsp;&nbsp;&nbsp;if(l&gt;r)<br />
&nbsp;&nbsp;&nbsp;&nbsp;return&nbsp;0;<br />
&nbsp;&nbsp;&nbsp;&nbsp;int&nbsp;m;<br />
&nbsp;&nbsp;&nbsp;&nbsp;while(l&lt;=r)<br />
&nbsp;&nbsp;&nbsp;&nbsp;{<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;m=(l+r)/2;<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;if(a[m]==x)<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;return&nbsp;m;<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;else&nbsp;if(a[m]&gt;x)<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;r=m-1;<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;else&nbsp;l=m+1;<br />
&nbsp;&nbsp;&nbsp;&nbsp;}<br />
&nbsp;&nbsp;&nbsp;&nbsp;return&nbsp;0;<br />
}<br />
int&nbsp;main()<br />
{<br />
&nbsp;&nbsp;&nbsp;&nbsp;int&nbsp;x,y;<br />
&nbsp;&nbsp;&nbsp;&nbsp;read();<br />
&nbsp;&nbsp;&nbsp;&nbsp;xuan();<br />
&nbsp;&nbsp;&nbsp;&nbsp;cin&gt;&gt;x;<br />
&nbsp;&nbsp;&nbsp;&nbsp;y=half(x,1,n);<br />
&nbsp;&nbsp;&nbsp;&nbsp;if(y==0)<br />
&nbsp;&nbsp;&nbsp;&nbsp;cout&lt;&lt;&quot;没有找到x&quot;;<br />
&nbsp;&nbsp;&nbsp;&nbsp;else&nbsp;cout&lt;&lt;&quot;查找成功-位置在：&quot;&lt;&lt;y&lt;&lt;endl;<br />
&nbsp;&nbsp;&nbsp;&nbsp;return&nbsp;0;&nbsp;<br />
}</p> 
