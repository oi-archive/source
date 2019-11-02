# 

 
 # 题目背景 
<p>FJT（其自称其为DQL）的步伐一向诡异，为了对其路径进行分析，我们需要将他的行进路线绘制出来。</p> 

 
 # 题目描述 
<p>先读入FJT的初始坐标，以后每一次输入为FJT移动一步以后的坐标。FJT每步移动只能在平面坐标系内沿上下左右四个方向移动一个单位长度。</p> 

 
 # 输入格式 
<p>输入FJT的初始坐标及以后每一步位移后的坐标，横坐标与纵坐标之间用空格隔开。所有的横纵坐标都为正整数。</p>

<p>样例输入：</p>

<p>2&nbsp;1</p>

<p>2&nbsp;2</p>

<p>3&nbsp;2</p> 

 
 # 输出格式 
<p>打印FJT的移动轨迹（见样例），其余部分用X填充。当移动违规时输出ERROR（后需换行）。输出后忽略这组数据，继续输入下一组可能正确的数据。要求输出为一个N*N的矩阵，N为输入时最大的横坐标或纵坐标。</p>

<p>样例输出：</p>

<p>X&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;X&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;X</p>

<p>X&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;F&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;F</p>

<p>X&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;F&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;X</p>

<p>&nbsp;</p>

<p>样例输出的空格仅为美观需要，程序输出时可不比考虑FX两个字母间的空格，&nbsp;但要注意末尾换行。</p> 

 
 # 提示 
<p>1&le;N&le;255；</p>

<p>步数在10000步以内。</p> 
