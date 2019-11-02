<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Description hsmtpi</p>
<p>SMTP(Simple Mail Transfer Protocol，简单邮件传输协议)是TCP/IP协议族<br>中重要的应用层协议，是当代网络点子邮件服务使用的主要的邮件协议之一<br>SMTP协议通过SMTP服务器来实现邮件的转发和存储，一个SMTP服务器主<br>要实现这些功能：<br> 作为一个公共服务器，SMTP服务器通常实现为需要认证的形式，即链接<br>到服务器需要用户名和密码<br> SMTP服务器需要接受来自用户上传邮件的请求<br> SMTP服务器能够根据用户的需求发送邮件<br> SMTP服务器可以储存并维护用户的收到邮件<br> SMTP服务器可以接受来自其他SMTP服务器的转发<br> SMTP服务器应该可以初步的判定非法邮件<br>现在，Rapid需要自己实现一个简单的SMTP服务器<br>为了简化问题，我们的电子邮件的格式非常简单，我们省去了电子邮件<br>的MIME部分和正文部分<br>也就是说，我们的电子邮件不会有正文和附件，MP3等内容，只会有一些简单<br>头部：<br>From 发件人地址<br>To 收件人地址<br>Subject 摘要<br>Date 发送时间<br>这些信息分别用4行表示，题目中所给的信息保证都是合乎语法的,即<br>From和To信息都是用户名@主机.com的形式<br>Subject信息可以是任意字符串<br>Date信息的格式为4位年份-2位月份-2位日期<br>注意，信息合乎语法不代表其合法，具体的参考之后的说明<br>一封样例电子邮件:<br>rapidhere@gmail.com<br>844122492@qq.com<br>Hello,CD,U'R SB<br>2013-4-24<br>垃圾邮件的判定：<br> 邮件的发送者和接受者并不是直接由邮件的From和To头决定的，而是单<br>独提供的，如果提供的信息和邮件的信息不一样，那么邮件非法<br> 无效的发送者和接受者<br> 摘要栏信息长度大于255<br> 非法的日期(合法的日期在1997-1-1到请求的时间为止)</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>Input hsmtp.ini<br>第一行n,q，表示网络上已经有的SMTP服务器数量和请求数量<br>第二行一个字符串HOST，表示我们的SMTP服务器的主机名字<br>之后n个数据块，每个数据块表示一个SMTP服务器<br>每个数据块中<br>第一行一个字符串H，表示该SMTP服务器的主机名字<br>第二行一个整数m，表示该SMTP服务器中已有的用户数量<br>之后m行，每行一个字符串，表示用户名称(不包括@H.com)<br>之后q个数据块，每个数据块表示一次请求<br>第一行一个字符串cmd，表示请求的类型<br>第二行一个时间字符串,表示请求的时间<br>之后若干行描述了请求的类容<br>请求的详细说明:<br> register 用户注册请求，之后两行分别描述用户名(不包<br>括@HOST.com)和密码，保证合乎语法。<br> login 用户登录请求，之后两行分别描述用户民（包括@主机名.com）和<br>密码，保证合乎语法。<br> logout 用户登出，之后一行描述用户名。<br> sendmail 用户发送邮件，之后两行行描述了用户名（包括@主机<br>名.com）和目标地址，之后四行描述了一封邮件，保证合乎语法。<br> getmail 用户下载邮件，之后两行描述了用户名（包或主机名.com）和邮<br>件的摘要，保证合乎语法。<br> transfer 收到其他服务器的转发邮件，之后两行描述了发送用户名和目<br>标用户名（均包括@主机名.com），保证合乎语法。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>Output hsmtp.outi<br />所有的输出首先输出一行请求的时间对于每一个请求，分别按要求输出信息:<br /> register 如果用户名已经存在，输出"Sorry,same username has already<br />registered!"，表示注册失败，否则输出"Register succeeded!",并且记录用<br />户名和密码<br /> login 如果主机名错误，输出"Wrong Host!";如果用户不存在，输<br />出"Invalid username!";如果密码错误，输出"Wrong password!",均表示登<br />录失败，否则输出"Login succeeded!"<br /> logout 该输入保证合法，输出"Logout succeeded : "+用户名字<br /> sendmail 如果主机名错误，输出"Wrong Host!";如果用户未登录，输<br />出"Must login rst!";如果是垃圾邮件，输出"Request reject : spam!";否<br />则输出"Send mail succeeded!"<br />5<br />3 TASK 3 - SMTP SERVER<br /> getmail 如果主机名错误，输出"Wrong Host!";如果用户未登录，输<br />出"Must login rst!";如果没有摘要和用户名符合用户的请求，输<br />出"Requested email not found!";否则输出"Get mail succeeded!",并且在<br />之后的4行打印这封邮件<br /> transfer 如果是非法邮件，输出"Request reject : spam!";否则打<br />印"Transfer : recieved from "加发送地址;如果目标地址是本服务器，那<br />么打印"Store the mail!"，并且储存邮件，否则打印"Transfer : send to<br />"加目标地址;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 6</p>
<p>rapidhost</p>
<p>cdhost</p>
<p>1</p>
<p>844122492</p>
<p>narydyhost</p>
<p>1</p>
<p>dengboyang</p>
<p>ryanhost</p>
<p>2</p>
<p>yexiaorain</p>
<p>yexiaowind</p>
<p>register</p>
<p>2013-04-25</p>
<p>rapidhere@rapidhost.com<br>rapidpassword<br>login<br>2013-04-25<br>rapidhere@nardyhost.com<br>aaaaa<br>sendmail<br>2013-04-25<br>rapidhere@rapidhost.com<br>844122492@cdhost.com<br>rapidhere@rapidhost.com<br>844122492@cdhost.com<br>Hello,CD,U'R SB<br>2013-04-26<br>login<br>2013-04-25<br>rapidhere@rapidhost.com<br>rapidpassword<br>sendmail<br>2013-04-25<br>rapidhere@rapidhost.com<br>844122492@cdhost.com<br>rapidhere@rapidhost.com<br>844122492@cdhost.com<br>Hello,CD,U'R SB<br>2013-04-26<br>sendmail<br>2013-04-26<br>rapidhere@rapidhost.com<br>844122492@cdhost.com<br>rapidhere@rapidhost.com<br>844122492@cdhost.com<br>Hello,CD,U'R SB<br>2013-04-26</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2013-04-25</p>
<p>Register succeeded!</p>
<p>2013-04-25</p>
<p>Wrong Host!</p>
<p>2013-04-25</p>
<p>Must login rst!</p>
<p>2013-04-25</p>
<p>Login succeeded!</p>
<p>2013-04-25</p>
<p>Requeset rejuect : spam!</p>
<p>2013-04-26</p>
<p>Send mail succeeded!</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>Note<br>保证输入数据总大小不超过20Mb<br>服务器数量不超过100个<br>用户总数不超过1000个<br>服务器名称，用户名称，密码长度不超过30<br>摘要长度不超过500<br>8</p>
</div>
</div>