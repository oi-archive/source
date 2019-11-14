# 

 
 # 题目背景 
<p>饿&hellip;&hellip;</p> 

 
 # 题目描述 
<p>大家都玩过迷宫吧，那让我们来看一看这道题：</p>

<p>1&nbsp;&nbsp;4&nbsp;&nbsp;5&nbsp;&nbsp;6</p>

<p>2&nbsp;&nbsp;3&nbsp;&nbsp;8&nbsp;&nbsp;7</p>

<p>11&nbsp;10&nbsp;9&nbsp;&nbsp;16</p>

<p>12&nbsp;13&nbsp;14&nbsp;15</p>

<p>这是一个4*4的迷宫。上面有1到16的数字。现在我们要你编一个程序，告诉我们怎样从1走到16。</p>

<p>【输入样例】</p>

<p>4&nbsp;4</p>

<p>1&nbsp;&nbsp;4&nbsp;&nbsp;5&nbsp;&nbsp;6</p>

<p>2&nbsp;&nbsp;3&nbsp;&nbsp;8&nbsp;&nbsp;7</p>

<p>11&nbsp;10&nbsp;9&nbsp;&nbsp;16</p>

<p>12&nbsp;13&nbsp;14&nbsp;15</p>

<p>【输出样例】</p>

<p>V&gt;^&gt;&gt;V&lt;V&lt;&lt;V&gt;&gt;&gt;^</p> 

 
 # 输入格式 
<p>输入i,j，表示迷宫的长和宽。</p>

<p>输入a[i,j]，表示迷宫。</p> 

 
 # 输出格式 
<p>输出迷宫的行走顺序。</p> 

 
 # 提示 
<p>1、{题目备注}</p>

<p>（1）输入的迷宫方阵一行里每个一位数字要隔两个空格。如果是两位数字就隔一个空格。一个两位数和一个一位数之间只要一个空格(两位数字在前的情况)。</p>

<p>（2）行走的路径图标为：</p>

<p>上：^（英文&ldquo;shift+6&rdquo;）</p>

<p>下：V（一定是大写）</p>

<p>左：&lt;（英文&ldquo;shift+,&rdquo;）</p>

<p>右：&gt;（英文&ldquo;shift+。&rdquo;）</p>

<p>2、{数据范围}</p>

<p>0&lt;i,j&lt;99</p>

<p>0&lt;a[i,j]&lt;99</p> 
