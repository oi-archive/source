# 

 
 # 题目描述 
<p><span style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif; font-size: 15px; line-height: 24px; background-color: rgba(255, 255, 255, 0.8);">输入化学方程式，判断反应类型（只有化合，分解，复分解，置换四种类型）。</span></p> 

 
 # 输入格式 
<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif; font-size: 15px; line-height: 24px;">type.in</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif; font-size: 15px; line-height: 24px;">一行（长度&le;255），一个化学方程式（没有反应条件,上箭头表示为&#39;（up）&#39;，下箭头表示为&lsquo;（down）&rsquo;，无下标（如&#39;O₂&#39;写为&lsquo;O2&rsquo;））。</p> 

 
 # 输出格式 
<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif; font-size: 15px; line-height: 24px;">type.out</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif; font-size: 15px; line-height: 24px;">一行，反应类型（combination&nbsp;reaction，decomposition&nbsp;reaction，double&nbsp;replacement&nbsp;reaction，single&nbsp;displacement&nbsp;reaction）。</p> 

 
 # 提示 
<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif; font-size: 15px; line-height: 24px;">数据规模：</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif; font-size: 15px; line-height: 24px;">100%的数据保证：读入的化学方程式长度&le;255，保证所给的化学方程式属于化合，分解，复分解，置换四种类型，保证化学方程式合法。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif; font-size: 15px; line-height: 24px;">测试点数目：10；</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif; font-size: 15px; line-height: 24px;">每个测试点分值：10；</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif; font-size: 15px; line-height: 24px;">时间限制：1000ms；</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif; font-size: 15px; line-height: 24px;">内存限制：128000KB。</p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>C+O2=CO2</td><td>combination reaction</td></tr><tr><td>CaCO3+2HCl=CaCO3+H2O+CO2(up)</td><td>double replacement reaction</td></tr></table>
