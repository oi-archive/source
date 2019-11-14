# 

 
 # 题目描述 
<p>
File Transfer Protocol , 文件传输协议，简称FTP。人们可以通过FTP实现资源共享。一般的情况下用户访问一个FTP服务器是通过类似资源管理器的形式对该服务器上的资源进行浏览，并且不同权限的用户可以实现下载文件/文件夹，上传文件/文件夹。<br><br>&#61548;	FTP的基本常识<br>一个FTP服务器的所有资源都以文件的形式按树形结构存储在不同的文件夹里，最低一级的是根目录（即根文件夹），根目录里有若干个文件和文件夹，每一个文件夹里都可以拥有0个或多个文件及文件夹，同一文件夹里不存在名称相同的文件和文件夹。<br>一个用户包含三个属性<br>userType：用户类型<br>userState：用户状态（用户正在执行的操作）<br>userPosition：用户当前所处的位置（即用户正在浏览的文件夹）<br>用户分3种类型：上传用户uploadUser，下载用户downloadUser，匿名用户guest。<br>操作分3种类型：浏览scan，下载download，上传upload。<br>用户的权限是指用户允许进行的操作。不同类型的用户的权限是不同的，见下表<br>用户类型	用户权限<br>下载用户	浏览，下载<br>上传用户	浏览，上传<br>匿名用户	浏览<br>	任何一个用户是不能进行其没有权限的操作的，例如：一个匿名用户想要下载一个文件或者文件夹是不允许的。<br>	一个文件/文件夹包含三个属性：<br>fileName/folderName：文件名（不包含空格和回车）<br>fileSize/folderSize：文件大小<br>（单位byte，0<filesize 100000，0 folderSize 100000000，文件夹的大小是它里面所包含的所有文件大小的总和）<br>fileState/folderState：当前状态<br>当前状态有两种，一种为正常normal（文件/文件夹为正常状态时，允许用户对其进行操作），另一种为上传未完成uploading（处在此种状态时，用户之能够对其进行浏览操作，如果一个文件夹中有一个或多个文件处于uploading状态，那么这个文件夹也处于uploading状态）。<br>一个FTP服务器除了它所拥有的文件资源外，还有如下属性：<br>1．	访问用户的最大数量（包括所有不同类型的用户）maxUserNumber<100。如果当前访问用户数量已经达到最大值的话，其他新的用户对服务器的访问将是失败的。<br>2．	服务器的最大流量maxServerFlux<10000000。<br>3．	单个用户允许的最大下载/上传流量maxUserFluxx。<br>FTP服务器运行的最小时间单位为秒。<br>	每一个用户在同一时刻只能进行一种操作。用户下载和上传文件/文件夹是需要一定时间的，而这个时间决定于用户流量userFlux，单位为byte/second，注意如果某一时刻文件/文件夹仍须上传/下载的大小（>0）小于userFlux的话，上传/下载时间仍将按照一秒钟看待。<br>而userFlux的值是如何确定的呢？<br>	userFlux = min（presentMaxUserFlux, maxUserFlux）<br>	其中，presentMaxUserFlux为当前服务器的单个用户最大流量<br>presentMaxUserFlux = [maxServerFlux / userTotal]<br>（userTotal表示该时刻的正在进行上传和下载操作的用户数量）<br><br>&#61548;	用户的基本命令order<br>一个用户通过一系列命令实现其在FTP服务器上的相关操作。下面介绍这些命令：<br>connect命令，格式：[name]+空格+connect+参数A，例：tsinghua connect 1<br>表示在名叫name的用户请求以A身份连接到服务器上。如果当前的最大使用用户还没达到maxUserNumber，并且该用户未连接到服务器，则连接成功，服务器反馈回一个相关信息“success”。否则反馈信息为“unsuccess”。一旦连接成功，用户其所处的位置userPosition为服务器的根目录。A=1表示上传用户，A=2下载表示用户，A=3表示匿名用户。<br>quit命令，格式：[name]+空格+quit，例tsinghua quit<br>表示名叫name的用户断开与服务器的连接。如果用户未连接反馈“unsuccess”，否则反馈”success”。(注意用户在任何状态下都可以断开与服务器的连接)。<br>cd命令，格式：[name]+空格+cd+空格+[floderName/文件夹名称]，例：THU cd FD<br>表示名叫name的用户希望从当前所处的文件夹进入该文件夹中的一个名叫floderName的文件夹。如果名叫floderName的文件夹存在并且处于normal状态，则改变用户当前所处位置userPosition，反馈相关信息“success”，如果该文件夹不存在或该用户没有成功连接，则反馈信息为“unsuccess”。<br>cd..命令，格式：[name]+空格+cd..，例：9# cd..<br>表示名叫name的用户希望从当前所处的文件夹返回到他的上一级文件夹。如果用户处于根目录或者用户未连接，则命令执行失败返回“unsuccess”，否则返回success，并且改变用户所处位置userPosition。<br>download命令，格式：[name]+空格+download+空格+[name1]，例：A download 1.txt<br>表示名叫name的用户希望从当前所处文件夹下载名为name1的文件或者文件夹。如果用户未连接，用户没有下载权限，名为name1的文件/文件夹不存在，或者该文件/文件夹处于uploading状态时，反馈信息“unsuccess”，否则返回“success”并且开始下载该文件/文件夹。(一旦一个下载命令开始执行，那么执行该命令的用户所下载的是下载命令执行的那一时刻的那一个文件/文件夹，也就是说如果一个用户正在下在某个文件夹，在下载过程中，有另外一用户在这个文件夹里面上传文件，那么原下载用户是不可能下载到这个新上传的文件的)<br>upload命令，格式：[name]+空格+upload+空格+[name1]+空格+[size]，例:A upload B 1<br>表示名叫name的用户希望在当前所处的文件夹上传一个名叫name1的大小为size的文件/文件夹。注意：用户通过upload命令上传文件夹只能为空文件夹，当size=0表示上传文件夹，size>0表示上传文件。如果当前目录已经存在了同名的文件/文件夹，用户未成功连接或者用户没有上传权限，反馈信息“success”，否则反馈“unsuccess”，并且开始上传文件/文件夹。（如果一个用户想要上传一个非空文件夹，是很容易通过一系列upload以及cd命令实现的）<br>除上传文件和下载文件/文件夹命令需要耗时外，其他的命令都不需要执行时间。<br>【任务描述】<br>你的任务是模拟一个FTP服务器在某一时间段内的运行过程。<br></p> 

 
 # 输入格式 
<p>
你将获得FTP的服务器的初始信息，第一行为3个正整数，分别表示maxUserNumber，maxServerFlux，maxUserFlux。接下来的若干行描述server里已有文件资源的存储情况。<br>第一行总是描述的根目录中的一个文件或者文件夹。<br>如果某一行描述的是一个文件或者文件夹那么该行的数据为name+空格+size，如果size=0表示这是一个文件夹，否则表示一个大小为size的文件。<br>如果某一行描述的是一个文件夹，那么接下来的若干行描述的都是这个文件夹里的内容，直到一个与之对应的减号为止。这些数据都是递归描述的。因为一开始就是描述整个根目录里的文件和文件夹，所以server.txt的最后一行也为减号。（参看输入示例）。<br>整个的模拟过程是围绕着input.txt里的内容展开的，input.txt的每一行为time+空格+order的形式给出，其中 。例如”4 ares connect 1”表示：在服务器开启后4秒钟，名叫ares的用户请求以uploadUser的身份连接到服务器上来。<br>Input.txt的最后一行为一个字符串”down”。<br>所有输入命令的时刻time在input.txt中都以命令出现的先后递增，同一时刻的命令以input.txt中出现的先后顺序确定其执行顺序。<br><br></p> 

 
 # 输出格式 
<p>
请你将每一条命令的反馈信息输出到output.txt当中。<br></p> 
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
<tr><td>
<img border="0" src="/source/joyoi/tyvj-3653/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzY1My9wcm9ibGVtc19pbWFnZXMvMjUwOC8xMjE0LmpwZw==.jpg"></td><td></td></tr></table>
