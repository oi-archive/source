# 

 
 # 题目描述 
<p><span style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">WINDOWS是一个很庞大的操作系统（当然啦，看占的硬盘空间就知道了），比如说，它的文件查找系统。现在，请你用PASCAL或者C或者C++模拟一下这个操作过程。为了降低难度，所有的文件夹名和文件名都是小写和数字，且不考虑盘符，而且也不会有WINDOWS禁止出现在文件名中的字符。同时，为了增加难度，每个文件夹内可能有重名的文件（夹）。当然，不能让用户等太久，你的程序要在1秒内找到用户要的文件。</span></p> 

 
 # 输入格式 
<p><span style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">输入文件包含多行，第一行是用户查找的文件名，该文件名不会含WINDOWS禁止出现在文件名中的字符，一定带符号&rdquo;.&rdquo;；第二行开始输入一个或多个文件夹的相关信息。文件夹的相关信息用以下格式输入：</span><br style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;" />
<span style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">文件夹名（中间无空格，且无符号&ldquo;.&rdquo;（小数点））+&nbsp;一个空格+文件夹内的文件数（包括文件夹），如果文件夹内还有子文件夹，换行后先输入该子文件夹内容再输入父文件夹内的其他文件夹或文件。每个文件名都带符号&ldquo;.&rdquo;。具体请看样例。</span></p> 

 
 # 输出格式 
<p><span style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">输出所查找文件的路径，一定在至少一个文件夹的目录下。以WINDOWS地址的表示方法表示（&ldquo;\&rdquo;），如果有多个文件，按输入时的顺序输出。每输出一个文件的路径换一行。</span></p> 

 
 # 提示 
<h2>数据范围</h2>

<p>对于50%的数据，输入文件的行数小于100。<br />
对于100%的数据，输入文件的行数小于3000，且每行均少于25个字符。</p>

<h2>来源</h2>

<p>HOI&nbsp;2009</p>

<h2>版权</h2>

<p><span style="line-height: 20.8px;">本用户并不拥有该资料版权。如果无意侵犯了您的权益，请私信管理员或本用户。管理员接到通知后请删题，以避免不必要的纠纷，谢谢！</span></p> 
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
<tr><td>hoi.pas
hoi 2
hoi 0
hoi.pas
hoi.pas</td><td>hoi\hoi.pas
hoi.pas</td></tr><tr><td>chroi.pas
chroi 2
hoi 1
chroi.pas
chroi 1
hoi.pas</td><td>chroi\hoi\chroi.pas</td></tr></table>
