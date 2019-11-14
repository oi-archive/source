<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="font-family: arial, verdana, helvetica, sans-serif;">Linux用户和OSX用户一定对软件包管理器不会陌生。通过软件包管理器，你可以通过一行命令安装某一个软件包，然后软件包管理器会帮助你从软件源下载软件包，同时自动解决所有的依赖（即下载安装这个软件包的安装所依赖的其它软件包），完成所有的配置。Debian/Ubuntu使用的apt-get，Fedora/CentOS使用的yum，以及OSX下可用的homebrew都是优秀的软件包管理器。</p><p>你决定设计你自己的软件包管理器。不可避免地，你要解决软件包之间的依赖问题。如果软件包A依赖软件包B，那么安装软件包A以前，必须先安装软件包B。同时，如果想要卸载软件包B，则必须卸载软件包A。现在你已经获得了所有的软件包之间的依赖关系。而且，由于你之前的工作，除0号软件包以外，在你的管理器当中的软件包都会依赖一个且仅一个软件包，而0号软件包不依赖任何一个软件包。依赖关系不存在环（若有m(m≥2)个软件包A1,A2,A3,…,Am，其中A1依赖A2，A2依赖A3，A3依赖A4，……，Am−1依赖Am，而Am依赖A1，则称这m个软件包的依赖关系构成环），当然也不会有一个软件包依赖自己。</p><p>现在你要为你的软件包管理器写一个依赖解决程序。根据反馈，用户希望在安装和卸载某个软件包时，快速地知道这个操作实际上会改变多少个软件包的安装状态（即安装操作会安装多少个未安装的软件包，或卸载操作会卸载多少个已安装的软件包），你的任务就是实现这个部分。注意，安装一个已安装的软件包，或卸载一个未安装的软件包，都不会改变任何软件包的安装状态，即在此情况下，改变安装状态的软件包数为0。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="font-family: arial, verdana, helvetica, sans-serif;">输入文件的第1行包含1个正整数n，表示软件包的总数。软件包从0开始编号。</p><p>随后一行包含n−1个整数，相邻整数之间用单个空格隔开，分别表示1,2,3,…,n−2,n−1号软件包依赖的软件包的编号。</p><p>接下来一行包含1个正整数q，表示询问的总数。</p><p>之后q行，每行1个询问。询问分为两种：</p><p>installx：表示安装软件包x</p><p>uninstallx：表示卸载软件包x</p><p>你需要维护每个软件包的安装状态，一开始所有的软件包都处于未安装状态。对于每个操作，你需要输出这步操作会改变多少个软件包的安装状态，随后应用这个操作（即改变你维护的安装状态）。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="font-family: arial, verdana, helvetica, sans-serif; font-size: 18px; white-space: normal;">输出文件包括q行。</p><p>输出文件的第i行输出1个整数，为第i步操作中改变安装状态的软件包数。</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: monospace;">7</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="font-family: monospace;">0 0 0 1 1 5</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="font-family: monospace;">5</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="font-family: monospace;">install 5</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="font-family: monospace;">install 6</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="font-family: monospace;">uninstall 1</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="font-family: monospace;">install 4</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="font-family: monospace;">uninstall 0</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: monospace;">3</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="font-family: monospace;">1</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="font-family: monospace;">3</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="font-family: monospace;">2</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="font-family: monospace;">3</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style="font-family: arial, verdana, helvetica, sans-serif;">一开始所有的软件包都处于未安装状态。</p><p><br style="font-family: arial, verdana, helvetica, sans-serif;"></p><p>安装 5 号软件包，需要安装 0,1,5 三个软件包。</p><p><br style="font-family: arial, verdana, helvetica, sans-serif;"></p><p>之后安装 6 号软件包，只需要安装 6 号软件包。此时安装了 0,1,5,6 四个软件包。</p><p><br style="font-family: arial, verdana, helvetica, sans-serif;"></p><p>卸载 1 号软件包需要卸载 1,5,6 三个软件包。此时只有 0 号软件包还处于安装状态。</p><p><br style="font-family: arial, verdana, helvetica, sans-serif;"></p><p>之后安装 4 号软件包，需要安装 1,4 两个软件包。此时 0,1,4 处在安装状态。</p><p><br style="font-family: arial, verdana, helvetica, sans-serif;"></p><p>最后，卸载 0 号软件包会卸载所有的软件包。</p><p><br style="font-family: arial, verdana, helvetica, sans-serif;"><br style="font-family: arial, verdana, helvetica, sans-serif;"><br style="font-family: arial, verdana, helvetica, sans-serif;"></p><p>n=100000</p><p><br style="font-family: arial, verdana, helvetica, sans-serif;"></p><p>q=100000</p><p><br></p>
</div>
</div>