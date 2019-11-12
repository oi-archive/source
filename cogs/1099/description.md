# 题目描述


<h3>
	【题目描述】
</h3>
<p>
	<br/>
</p>
<p style="font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;margin-left:auto;font-size:12.800000190734863px;text-align:left;background-color:#FEFEF2;">
	Farmer John為了讓自己從無窮無盡的犁田工作中解放出來，於是買了個新機器人幫助他犁田。<br/>
這個機器人可以完成犁田的任務，可惜有一個小小的缺點：這個犁田機器人一次只能犁一個邊的<br/>
長度是整數的長方形的田地。
</p>
<p style="font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;margin-left:auto;font-size:12.800000190734863px;text-align:left;background-color:#FEFEF2;">
	因為FJ的田地有樹和其他障礙物，所以FJ設定機器人去犁很多不同的長方形。這些長方形允許重<br/>
疊。他給機器人下了P個指令，每個指令包含一個要犁長方形的地。這片田地由長方形的左下角<br/>
和右上角坐標決定。他很好奇最後到底有多少個方格的地被犁過了。
</p>
<p style="font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;margin-left:auto;font-size:12.800000190734863px;text-align:left;background-color:#FEFEF2;">
	一般來說，田地被分割為很多小方格。這些方格的邊和x軸或y軸平行。田地的寬度為X個方格，<br/>
高度為Y個方格 (1 &lt;= X &lt;= 240; 1 &lt;= Y &lt;= 240). FJ執行了I (1 &lt;= I &lt;= 200)個指<br/>
令，每個指令包含4個整數：Xll, Yll, Xur, Yur (1 &lt;= Xll &lt;= Xur; Xll &lt;= Xur &lt;=<br/>
X; 1 &lt;= Yll &lt;= Yur; Yll &lt;= Yur &lt;= Y), 分別是要犁的長方形的左下角坐標和右上角坐<br/>
標。機器人會犁所有的橫坐標在Xll..Xur並且縱坐標在Yll..Yur範圍內的所有方格的地。可能<br/>
這個長方形會比你想像的多一行一列（就是說從第Xll列到第Xur列一共有Xur - Xll + 1列而<br/>
不是Xur - Xll列）。
</p>
<p style="font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;margin-left:auto;font-size:12.800000190734863px;text-align:left;background-color:#FEFEF2;">
	考慮一個6方格寬4方格高的田地。FJ進行了2個操作（如下），田地就被犁成&#34;*&#34;和&#34;#&#34;了。雖然<br/>
一般被犁過的地看起來都是一樣的。但是標成&#34;#&#34;可以更清晰地看出最近一次被犁的長方形。
</p>
<p style="font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;margin-left:auto;font-size:12.800000190734863px;text-align:left;background-color:#FEFEF2;">
	    ......             **....             #####.<br/>
    ......  (1,1)(2,4) **....  (1,3)(5,4) #####.<br/>
    ......             **....             **....<br/>
    ......             **....             **....
</p>
<p style="font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;margin-left:auto;font-size:12.800000190734863px;text-align:left;background-color:#FEFEF2;">
	一共14個方格的地被犁過了。
</p>
<p style="font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;margin-left:auto;font-size:12.800000190734863px;text-align:left;background-color:#FEFEF2;">
	分數: 25
</p>
<p style="font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;margin-left:auto;font-size:12.800000190734863px;text-align:left;background-color:#FEFEF2;">
	題目名稱: rplow
</p>
<p>
	<br/>
</p>
<h3>
	【输入格式】
</h3>
<p>
	<br/>
</p>
<p style="font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;margin-left:auto;font-size:12.800000190734863px;text-align:left;background-color:#FEFEF2;">
	* 第一行: 三個由空格隔開的整數： X, Y, I
</p>
<p style="font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;margin-left:auto;font-size:12.800000190734863px;text-align:left;background-color:#FEFEF2;">
	* 第二行到第I+1行：第i+1行有四個整數Xll, Yll, Xur, Yur，表示第i個指令。
</p>
<p>
	<br/>
</p>
<h3>
	【输出格式】
</h3>
<p>
	<span style="font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;font-size:12.800000190734863px;line-height:15.199999809265137px;background-color:#FEFEF2;">* 第一行: 一個單獨的整數表示被犁過的方格數。</span>
</p>
<h3>
	【样例输入】
</h3>
<pre>6 4 2
1 1 2 4
1 3 5 4</pre>
<h3>
	【样例输出】
</h3>
<pre>14</pre>
<h3>
	【提示】
</h3>
<p>
	</p><p style="font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;margin-left:auto;font-size:12.800000190734863px;text-align:left;background-color:#FEFEF2;">
		輸入細節:
	</p>
	<p style="font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;margin-left:auto;font-size:12.800000190734863px;text-align:left;background-color:#FEFEF2;">
		如同題目描述的例子。
	</p>
<p></p>
<h3>
	【来源】
</h3>
<p>
	<a href="http://www.cnblogs.com/waterfalleagle/articles/1589190.html">http://www.cnblogs.com/waterfalleagle/articles/1589190.html</a>
</p>
