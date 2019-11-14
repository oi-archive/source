# 

 
 # 题目背景 
<p>NOIP2016提高组</p> 

 
 # 题目描述 
<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">本题中，我们将用符号[c]表示对c向下取整，例如：[3.0」=&nbsp;[3.1」=[3.9」=3。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">蛐蛐国最近蚯蚓成灾了！隔壁跳蚤国的跳蚤也拿蚯蚓们没办法，蛐蛐国王只好去请神刀手来帮他们消灭蚯蚓。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">蛐蛐国里现在共有n只蚯蚓（n为正整数)。每只蚯蚓拥有长度，我们设第i只蚯蚓的长度为a_i(i=1,2,...,n)，并保证所有的长度都是<span style="box-sizing: border-box; font-weight: 700; color: rgb(81, 81, 81);">非负</span>整数（即:可能存在长度为0的蚯蚓）。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">每一秒，神刀手会在所有的蚯蚓中，准确地找到最长的那一只（如有多个则任选一个）将其切成两半。神刀手切开蚯蚓的位置由常数p(是满足0&lt;p&lt;1的有理数)决定，设这只蚯蚓长度为x，神刀手会将其切成两只长度分别为[px]和x-[px]的蚯蚓。特殊地，如果这两个数的其中一个等于0，则这个长度为0的蚯蚓也会被保留。此外，除了刚刚产生的两只新蚯蚓，其余蚯蚓的长度都会增加q(是一个非负整常数)。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">蛐蛐国王知道这样不是长久之计，因为蚯蚓不仅会越来越多，还会越来越长。蛐蛐国王决定求助于一位有着洪荒之力的神秘人物，但是救兵还需要m秒才能到来......</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">(m为非负整数）</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">蛐蛐国王希望知道这m秒内的战况。具体来说，他希望知道：</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">&bull;m秒内，每一秒被切断的蚯蚓被切断前的长度（有m个数）</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">&bull;m秒后，所有蚯蚓的长度（有n+m个数)。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">蛐蛐国王当然知道怎么做啦！但是他想考考你......</p> 

 
 # 输入格式 
<p><span style="box-sizing: border-box; font-weight: 700; color: rgb(81, 81, 81); font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">输入格式：</span></p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">&nbsp;</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">第一行包含六个整数n,m,q,u,v,t，其中：n,m,q的意义见【问题描述】；u,v,t均为正整数；你需要自己计算p=u/v(保证0&lt;u&lt;v)t是输出参数，其含义将会在【输出格式】中解释。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">第二行包含n个非负整数，为ai,a2,...,an，即初始时n只蚯蚓的长度。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">同一行中相邻的两个数之间，恰好用一个空格隔开。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">保证1&lt;=n&lt;=10^5，0&lt;m&lt;7*10^6，0&lt;u&lt;v&lt;10^9，0&lt;=q&lt;=200，1&lt;t&lt;71，0&lt;ai&lt;10^8。</p> 

 
 # 输出格式 
<p><span style="box-sizing: border-box; font-weight: 700; color: rgb(81, 81, 81); font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">输出格式：</span></p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">&nbsp;</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">第一行输出[m/t]个整数，按时间顺序，依次输出第t秒，第2t秒，第3t秒&hellip;&hellip;被切断蚯蚓（在被切断前）的长度。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">第二行输出[(n+m)/t]个整数，输出m秒后蚯蚓的长度；需要按从大到小的顺序，依次输出排名第t，第2t，第3t&hellip;&hellip;的长度。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">同一行中相邻的两个数之间，恰好用一个空格隔开。即使某一行没有任何数需要&nbsp;输出，你也应输出一个空行。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">请阅读样例来更好地理解这个格式。</p>

<h2 style="box-sizing: border-box; margin: 2em 0px 1.6rem; font-weight: 600; font-size: 1.25em; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif;">输入输出样例</h2>

<div class="am-g" style="box-sizing: border-box; margin: 0px -1rem; width: auto; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">
<div class="am-u-md-6" style="box-sizing: border-box; width: 414.01px; padding-left: 1rem; padding-right: 1rem; float: left; position: relative;"><span style="box-sizing: border-box; font-weight: 700; color: rgb(81, 81, 81);">输入样例#1：</span>

<pre style="box-sizing: border-box; line-height: 1.6; margin-top: 1rem; margin-bottom: 1rem; font-size: 1.3rem; font-family: Monaco, Menlo, Consolas, &quot;Courier New&quot;, FontAwesome, monospace; background-color: rgb(248, 248, 248); padding: 1rem; word-break: break-all; color: rgb(85, 85, 85); border: 1px solid rgb(222, 222, 222); border-radius: 0px;">
3&nbsp;7&nbsp;1&nbsp;1&nbsp;3&nbsp;1
3&nbsp;3&nbsp;2</pre>
</div>

<div class="am-u-md-6" style="box-sizing: border-box; width: 414.01px; padding-left: 1rem; padding-right: 1rem; float: right; position: relative;"><span style="box-sizing: border-box; font-weight: 700; color: rgb(81, 81, 81);">输出样例#1：</span>

<pre style="box-sizing: border-box; line-height: 1.6; margin-top: 1rem; margin-bottom: 1rem; font-size: 1.3rem; font-family: Monaco, Menlo, Consolas, &quot;Courier New&quot;, FontAwesome, monospace; background-color: rgb(248, 248, 248); padding: 1rem; word-break: break-all; color: rgb(85, 85, 85); border: 1px solid rgb(222, 222, 222); border-radius: 0px;">
3&nbsp;4&nbsp;4&nbsp;4&nbsp;5&nbsp;5&nbsp;6
6&nbsp;6&nbsp;6&nbsp;5&nbsp;5&nbsp;4&nbsp;4&nbsp;3&nbsp;2&nbsp;2</pre>
</div>
</div>

<div class="am-g" style="box-sizing: border-box; margin: 0px -1rem; width: auto; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">
<div class="am-u-md-6" style="box-sizing: border-box; width: 414.01px; padding-left: 1rem; padding-right: 1rem; float: left; position: relative;"><span style="box-sizing: border-box; font-weight: 700; color: rgb(81, 81, 81);">输入样例#2：</span>

<pre style="box-sizing: border-box; line-height: 1.6; margin-top: 1rem; margin-bottom: 1rem; font-size: 1.3rem; font-family: Monaco, Menlo, Consolas, &quot;Courier New&quot;, FontAwesome, monospace; background-color: rgb(248, 248, 248); padding: 1rem; word-break: break-all; color: rgb(85, 85, 85); border: 1px solid rgb(222, 222, 222); border-radius: 0px;">
3&nbsp;7&nbsp;1&nbsp;1&nbsp;3&nbsp;2
3&nbsp;3&nbsp;2</pre>
</div>

<div class="am-u-md-6" style="box-sizing: border-box; width: 414.01px; padding-left: 1rem; padding-right: 1rem; float: right; position: relative;"><span style="box-sizing: border-box; font-weight: 700; color: rgb(81, 81, 81);">输出样例#2：</span>

<pre style="box-sizing: border-box; line-height: 1.6; margin-top: 1rem; margin-bottom: 1rem; font-size: 1.3rem; font-family: Monaco, Menlo, Consolas, &quot;Courier New&quot;, FontAwesome, monospace; background-color: rgb(248, 248, 248); padding: 1rem; word-break: break-all; color: rgb(85, 85, 85); border: 1px solid rgb(222, 222, 222); border-radius: 0px;">
4&nbsp;4&nbsp;5
6&nbsp;5&nbsp;4&nbsp;3&nbsp;2</pre>
</div>
</div>

<div class="am-g" style="box-sizing: border-box; margin: 0px -1rem; width: auto; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">
<div class="am-u-md-6" style="box-sizing: border-box; width: 414.01px; padding-left: 1rem; padding-right: 1rem; float: left; position: relative;"><span style="box-sizing: border-box; font-weight: 700; color: rgb(81, 81, 81);">输入样例#3：</span>

<pre style="box-sizing: border-box; line-height: 1.6; margin-top: 1rem; margin-bottom: 1rem; font-size: 1.3rem; font-family: Monaco, Menlo, Consolas, &quot;Courier New&quot;, FontAwesome, monospace; background-color: rgb(248, 248, 248); padding: 1rem; word-break: break-all; color: rgb(85, 85, 85); border: 1px solid rgb(222, 222, 222); border-radius: 0px;">
3&nbsp;7&nbsp;1&nbsp;1&nbsp;3&nbsp;9
3&nbsp;3&nbsp;2</pre>
</div>

<div class="am-u-md-6" style="box-sizing: border-box; width: 414.01px; padding-left: 1rem; padding-right: 1rem; float: right; position: relative;"><span style="box-sizing: border-box; font-weight: 700; color: rgb(81, 81, 81);">输出样例#3：</span>

<pre style="box-sizing: border-box; line-height: 1.6; margin-top: 1rem; margin-bottom: 1rem; font-size: 1.3rem; font-family: Monaco, Menlo, Consolas, &quot;Courier New&quot;, FontAwesome, monospace; background-color: rgb(248, 248, 248); padding: 1rem; word-break: break-all; color: rgb(85, 85, 85); border: 1px solid rgb(222, 222, 222); border-radius: 0px;">
//空行
2</pre>
</div>
</div> 

 
 # 提示 
<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">【样例解释1】</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">在神刀手到来前：3只蚯蚓的长度为3,3,2。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">1秒后：一只长度为3的蚯蚓被切成了两只长度分别为1和2的蚯蚓，其余蚯蚓的长度增加了1。最终4只蚯蚓的长度分别为(1,2),4,3。括号表示这个位置刚刚有一只蚯蚓被切断</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">2秒后：一只长度为4的蚯蚓被切成了1和3。5只蚯蚓的长度分别为：2,3,(1,3),4。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">3秒后：一只长度为4的蚯蚓被切断。6只蚯蚓的长度分别为：3,4,2,4,(1,3)。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">4秒后：一只长度为4的蚯蚓被切断。7只蚯蚓的长度分别为：4,(1,3),3,5,2,4。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">5秒后：一只长度为5的蚯蚓被切断。8只蚯蚓的长度分别为：5,2,4,4,(1,4),3,5。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">6秒后：一只长度为5的蚯蚓被切断。9只蚯蚓的长度分别为：（1,4),3,5,5,2,5,4,6。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">7秒后：一只长度为6的蚯蚓被切断。10只蚯蚓的长度分别为：2,5,4,6,6,3,6,5,(2,4)。所以，7秒内被切断的蚯蚓的长度依次为3,4,4,4,5,5,6。7秒后，所有蚯蚓长度从大到小排序为6,6,6,5,5,4,4,3,2,2</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">【样例解释2】</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">这个数据中只有t=2与上个数据不同。只需在每行都改为每两个数输出一个数即可。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">虽然第一行最后有一个6没有被输出，但是第二行仍然要重新从第二个数再开始输出。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">【样例解释3】</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">这个数据中只有t=9与上个数据不同。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">注意第一行没有数要输出，但也要输出一个空行。</p> 
