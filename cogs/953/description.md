# 题目描述


<p>
<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;"> </span> 
</p>
<p>
<b><span>2</span></b><b><span style="font-family:;">．珍贵的项链</span><span></span></b> 
</p>
<p>
<b><span>  (dividenecklace.pas/c/cpp) </span></b> 
</p>
<p>
<span style="font-family:;">【问题描述】</span><span></span> 
</p>
<p>
<span>         </span><span style="font-family:;">有一个电影的主人公</span><span>(</span><span style="font-family:;">假设叫</span><span>The Best Killer)</span><span style="font-family:;">走在路上</span><span>,</span><span style="font-family:;">突然冥王</span><span>(</span><span style="font-family:;">同样也是财富之神</span><span>)Hades</span><span style="font-family:;">出现在他面前</span><span>,</span><span style="font-family:;">给他了一个长为</span><span>N</span><span style="font-family:;">的环形项链</span><span>,</span><span style="font-family:;">这个项链由一条金丝把各种稀有之物串接起来</span><span>,</span><span style="font-family:;">可以理解为</span><span>,</span><span style="font-family:;">项链串接了从</span><span>1</span><span style="font-family:;">到</span><span>N</span><span style="font-family:;">个物品</span><span>,</span><span style="font-family:;">每个物品拥有一个价值整数</span><span>W<sub>i</sub>,</span><span style="font-family:;">每一个物品占用一个单位</span><span>,</span><span style="font-family:;">让从中选取</span><span>K</span><span style="font-family:;">段宝物</span><span>(</span><span style="font-family:;">不能重叠</span><span>,</span><span style="font-family:;">但可以每段可以挨着</span><span>),</span><span style="font-family:;">使得总价值超过</span><span>Limit,</span><span style="font-family:;">如果超过</span><span>Limit</span><span style="font-family:;">那么</span><span>Hades</span><span style="font-family:;">就把他的宝座让给</span><span>TBK,</span><span style="font-family:;">否则</span><span>TBK</span><span style="font-family:;">就要和</span><span>Hades</span><span style="font-family:;">一起去地下了</span><span>,</span><span style="font-family:;">这时候</span><span>,</span><span style="font-family:;">正在看电影的你立刻暂停了播放</span><span>,</span><span style="font-family:;">预算</span><span>TBK</span><span style="font-family:;">是否要被带走</span><span>.</span> 
</p>
<p>
<span style="font-family:;">【输入】</span><span></span> 
</p>
<p>
<span style="font-family:;">三个整数</span><span>N</span><span style="font-family:;">表示项链上有</span><span>N</span><span style="font-family:;">个物品</span><span>,</span><span style="font-family:;">第二个整数</span><span>K</span><span style="font-family:;">表示分成</span><span>K</span><span style="font-family:;">段</span><span>,</span><span style="font-family:;">第三个整数</span><span>Limit</span><span style="font-family:;">含义见题目描述</span><span></span> 
</p>
<p>
<span style="font-family:;">第二行</span><span>N</span><span style="font-family:;">个整数表示该物品的价值</span><span>W<sub>i</sub></span> 
</p>
<p>
<span style="font-family:;">【输出】</span><span></span> 
</p>
<p>
<span style="font-family:;">第一行一个字符串</span><span>,</span><span style="font-family:;">要么是</span><span>”Go To the Hell”</span><span style="font-family:;">表示无法找到选取方式使得总价值超过</span><span>Limit,</span><span style="font-family:;">要么是</span><span>”</span><span style="font-size:9.0pt;font-family:" color:#313131;"=""> </span><a name="OLE_LINK2"></a><a name="OLE_LINK1"></a><span>New Pluto was born</span><span>”</span><span style="font-family:;">表示超过了</span><span>Limit</span> 
</p>
<p>
<span style="font-family:;">如果第一行输出了</span><span>” New Pluto
was born”</span><span style="font-family:;">那么下一行输出</span><span>TBK</span><span style="font-family:;">能取到的最大的价值</span><span>.</span> 
</p>
<p>
<span style="font-family:;">【输入输出样例</span><span>1</span><span style="font-family:;">】</span><span></span> 
</p>
<table border="1" cellspacing="0" cellpadding="0" width="569" style="border:none;">
<tbody>
<tr>
<td width="285" valign="top" style="border:solid windowtext 1.0pt;">
<p>
<span>dividenecklace.in</span> 
</p>
</td>
<td width="285" valign="top" style="border:solid windowtext 1.0pt;">
<p>
<span>dividenecklace.out</span> 
</p>
</td>
</tr>
<tr>
<td width="285" valign="top" style="border:solid windowtext 1.0pt;">
<p>
<span>10 3 1</span> 
</p>
<p>
<span>1 3 -5 4 -5 4 -5 3 1 -2</span> 
</p>
</td>
<td width="285" valign="top" style="border:solid windowtext 1.0pt;">
<p>
<span>New Pluto was born</span> 
</p>
<p>
<span>14</span> 
</p>
</td>
</tr>
</tbody>
</table>
<p>
<span style="font-family:;">【数据范围】</span> <span></span> 
</p>
<p>
<span>10%</span><span style="font-family:;">数据</span><span>N&lt;=10        K&lt;=10</span> 
</p>
<p>
<span>40%</span><span style="font-family:;">数据</span><span>N&lt;=10<sup>3          </sup>K&lt;=10</span> 
</p>
<p>
<span>50%</span><span style="font-family:;">数据</span><span>N&lt;=10<sup>4          </sup> K&lt;=10</span> 
</p>
<p>
<span>100%</span><span style="font-family:;">数据</span><span>N&lt;=10<sup>6       </sup>K&lt;=10</span> 
</p>
<p>
<span style="font-family:;">其中有</span><span>40%</span><span style="font-family:;">的数据</span><span>K=1</span> 
</p>
<p>
<span>100%</span><span style="font-family:;">数据所有数字均不超过2<sup>63</sup></span> 
</p>
<p>
<br/>
</p>
<p>
<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;"><span></span><span></span></span><span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;vertical-align:super;"></span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;vertical-align:super;"></span> 
</p>
