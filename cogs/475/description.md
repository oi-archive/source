# 题目描述


<p>
	<br/>
</p>
<p style="text-indent:168.0000pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">工程规划</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">程序名称：projecta</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入文件：projecta.in</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输出文件：projecta.out</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">问题描述：</span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">SERCOI工程组是一个讲究效率的工程小组。为了规划和管理的方便，他们将一个工程分为若干个项目，每个项目都可以独立进行。所有项目都工作完毕时，整个工程也就完成了。每个项目都需要一定的工作时间。工程最后总耗时是从第一个项目开始到最后一个项目结束的这段时间。</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">    各个项目之间可能存在也可以不存在相互制约关系。如果有制约关系，则可能是以下四种之一（设两个项目分别为p和q)：</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">    （1）SAS p q  (p Sart After q Start，项目p在项目q开始之后才能开始）</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">    （2）FAS p q  (p Finish After q Start，项目p在项目q开始之后才能结束）</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">    （3）SAF p q  (p Sart After q Start，项目p在项目q结束之后才能开始）</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">    （4）FAF p q  (p Finish After q Start，项目p在项目q结束之后才能结束）</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">如果没有制约关系，则可同时进行。</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">    例如：SAF 1 3表示项目1必须在项目3完成后才能开始。若项目3工作时间为3，起始时刻为2，则项目1最早在时刻5才能开始。</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">    作为SERCOI小组的项目负责人，请你根据各个项目的工作时间及先后关系，找出一种安排工程的方案，使整个工程尽可能快的完成。</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">    输入文件的第一行为项目总数N（1≤N≤100)，设项目的编号依次为1，2，…，N。下面N行依次为完成每个项目所需的工作时间（每个项目占一行）。这个时间为不超过100的正整数。</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">    接下来若干行是一些项目间先后次序关系的列表，每行的格式为：</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">    &lt;先后次序关系符&gt;  （&lt;项目p编号&gt; ( &lt;项目q编号&gt;</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">    其中：&lt;先后次序关系符&gt;为SAS、FAS、SAF、FAF中的任意一个，“（”表示一个空格符。</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">    整个文件以一个字母“＃”表示结束（单独占一行）</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输出</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">    若问题有解，则输出文件有N行，依次输出项目1到项目N的最早开始时间（设整个工程从0时刻开始）。每行的格式为：（项目编号  最早开始时间）。</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 　 若问题无解，则输出文只有一行，为一个正整数0</span> 
</p>
<p>
	<br/>
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入输出示例</span> 
</p>
<p>
	<span><span style="font-size:16px;line-height:19.200000762939453px;">projecta.in</span></span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">4</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">SAF 2 1</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">FAF 3 2</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">＃</span> 
</p>
<p>
	<br/>
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">projecta.out</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 0</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2 2</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3 1</span> 
</p>
<p>
	<br/>
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">projecta.in</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">SAF 2 1</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">SAF 3 2</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">SAF 1 3</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">＃</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> </span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">projecta.out</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">0</span> 
</p>
<p>
	<br/>
</p>
<p>
	<br/>
</p>
<p>
	<br/>
</p>
