# 题目描述


<div class="content">
<!--begin main-->
<!-- InstanceBeginEditable name="content" -->
<h3>
【试题来源】
</h3>
<div id="psrc" style="margin-top:20px;display:block;">
<div class="pdcont">
2011中国国家集训队命题答辩
</div>
</div>
<div id="pinputs" style="display:none;">
<div class="pdsec">
输入数据
</div>
<div class="pdcont">
<span class="notice"> 这是一道提交答案的试题，下面给出了该题的输入数据：</span> 
</div>
<div id="inputlist" class="pddata">
</div>
</div>
<p>
<br/>
</p>
<h3>
【问题描述】
</h3>
<div class="pdcont">
众所周知，新世纪的科学很发达，于是Ray 和DarkRaven 开始了星<br/>
际探险，他们在宇宙中开辟了一片空间，建造了N 个空间站。这N 个空<br/>
间站由一些单向的时空隧道连接，这些时空隧道都有一个穿越指数，穿过<br/>
这些时空隧道，你可以走到未来或者回到过去，当然，这些都是由穿越指<br/>
数决定的。<br/>
有一天，Ray 和DarkRaven 开始了一场比赛。他们要从一个空间站S<br/>
出发去另一个空间站T，先到的人获胜。DarkRaven 一定会选一条能最快<br/>
到达T 的路线。他希望Ray 输给他，所以事先在Ray 的飞船上设定了飞<br/>
行路径，使得Ray 从S 到T 只能走一条特定的路径。但是，Ray 有对策，<br/>
他有一台能够操纵时空隧道的机器，这台机器每次可以把某一条时空隧道<br/>
的穿越指数增加或减少1，但是因为操纵机器很累，所以Ray 希望尽可能<br/>
少改动，当然，如果改动后从某个空间站经过一系列的穿越可以在从这个<br/>
空间站出发之前回到这个空间站，那么这样的改动是不允许的。修改之后，<br/>
DarkRaven 依然会走能最快到达终点的路线，所以Ray 是不可能赢的。但<br/>
他请你帮助他确定改动时空隧道的方案，使得他能和DarkRaven 同时到达<br/>
T。
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
输入的第一行包含两个整数N 和M，代表空间站的数目和时空隧道<br/>
的数目。N　　接下来M 行，每行三个整数u、v 和w，代表从空间站u 到空间站<br/>
v 有一条时空隧道，它的穿越指数是w。u,v是0 ... N - 1。<br/>
第M + 2 行包含一个整数p，代表DarkRaven 在Ray 的飞船上设定<br/>
的那条路径的空间站数。第M + 3 行包含p 个数，那条路径上的空间站的<br/>
编号，第一个数是S，最后一个数是T。
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
输出的第一行包含一个整数，表示Ray 走那条路径并且能够赢得比赛<br/>
的情况下操纵时间机器的最小次数。<br/>
接来来输出M 行，其中第i 行输出一个整数w，表示把输入中第i 条<br/>
时空隧道的穿越指数增加w， w 可以是负数。<br/>
4<br/>
如果第一问（操纵时间机器的最小次数）正确，可以得到该测试点<br/>
20% 的分数，如果在此基础上方案可行，能得到该测试点100% 的分数。
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
3 3<br/>
0 1 1<br/>
1 2 2<br/>
0 2 1<br/>
3<br/>
0 1 2
</div>
<h3>
【样例输出】
</h3>
<p>
2<br/>
0<br/>
0<br/>
2
</p>
<h3>
【数据规模】
</h3>
一共有10 个数据，对于第i (1 ≤ i ≤ 10)
个数据， N = i * 500，M
= i * 5000。
<div id="pcont2" style="margin-top:20px;display:none;">
<h3>
【问题描述】
</h3>
<div class="probcontent">
众所周知，新世纪的科学很发达，于是Ray 和DarkRaven 开始了星<br/>
际探险，他们在宇宙中开辟了一片空间，建造了N 个空间站。这N 个空<br/>
间站由一些单向的时空隧道连接，这些时空隧道都有一个穿越指数，穿过<br/>
这些时空隧道，你可以走到未来或者回到过去，当然，这些都是由穿越指<br/>
数决定的。<br/>
有一天，Ray 和DarkRaven 开始了一场比赛。他们要从一个空间站S<br/>
出发去另一个空间站T，先到的人获胜。DarkRaven 一定会选一条能最快<br/>
到达T 的路线。他希望Ray 输给他，所以事先在Ray 的飞船上设定了飞<br/>
行路径，使得Ray 从S 到T 只能走一条特定的路径。但是，Ray 有对策，<br/>
他有一台能够操纵时空隧道的机器，这台机器每次可以把某一条时空隧道<br/>
的穿越指数增加或减少1，但是因为操纵机器很累，所以Ray 希望尽可能<br/>
少改动，当然，如果改动后从某个空间站经过一系列的穿越可以在从这个<br/>
空间站出发之前回到这个空间站，那么这样的改动是不允许的。修改之后，<br/>
DarkRaven 依然会走能最快到达终点的路线，所以Ray 是不可能赢的。但<br/>
他请你帮助他确定改动时空隧道的方案，使得他能和DarkRaven 同时到达<br/>
T。<br/>
<br/>
</div>
<h3>
【输入格式】
</h3>
<div class="probcontent">
输入的第一行包含两个整数N 和M，代表空间站的数目和时空隧道<br/>
的数目。N &lt;= 10000; M &lt;= 100000。<br/>
接下来M 行，每行三个整数u、v 和w，代表从空间站u 到空间站<br/>
v 有一条时空隧道，它的穿越指数是w。0 &lt;= w &lt;= 2000。空间站的编号<br/>
是0 ... N - 1。<br/>
第M + 2 行包含一个整数p，代表DarkRaven 在Ray 的飞船上设定<br/>
的那条路径的空间站数。第M + 3 行包含p 个数，那条路径上的空间站的<br/>
编号，第一个数是S，最后一个数是T。<br/>
<br/>
</div>
<h3>
【输出格式】
</h3>
<div class="probcontent">
输出的第一行包含一个整数，表示Ray 走那条路径并且能够赢得比赛<br/>
的情况下操纵时间机器的最小次数。<br/>
接来来输出M 行，其中第i 行输出一个整数w，表示把输入中第i 条<br/>
时空隧道的穿越指数增加w， w 可以是负数。<br/>
4<br/>
如果第一问（操纵时间机器的最小次数）正确，可以得到该测试点<br/>
20% 的分数，如果在此基础上方案可行，能得到该测试点100% 的分数。<br/>
<br/>
</div>
<h3>
【样例输入】
</h3>
<div class="probexample">
3 3<br/>
0 1 1<br/>
1 2 2<br/>
0 2 1<br/>
3<br/>
0 1 2<br/>
<br/>
</div>
<h3>
【样例输出】
</h3>
<div class="probexample">
2<br/>
0<br/>
0<br/>
2<br/>
<br/>
<p>
<br/>
</p>
</div>
<br/>
<div id="pcode" class="code">
<div id="pcodesu" style="display:none;">
<hr/>
<span class="notice">这是一道完善程序的试题，你只需要在下面程序标注的&#34;<span class="code"><span class="Y">@你的代码</span></span>&#34;的位置补充适当的语句或语句段使程序能正确运行即可，在提交的时候，你要提交的内容只包括补充的内容，不包括其他的代码。</span> 
</div>
<ol>
</ol>
</div>
<div class="ralign">
<a href="###" onclick="showSubmit()">提交</a>   <a href="###" onclick="discussProblem()">试题讨论</a> 
</div>
<script type="text/javascript">
var viewType = "f";
_codeLines = document.createElement("OL");
e("pcode").appendChild(_codeLines);
function getGPID() {
	return "A1253";
}
var gpid = getGPID();
function getProbTitle() {
	return "星际探险(宋方睿)";
}
function getProbType() {
	return "DEFAULT";
}
function getProbContent() { return e("pcont1").innerHTML; }
function getSrc() {
	return "2011中国国家集训队命题答辩";
}
function getCode() {
	return "";
}
function getLangs() {
	return "CPP,C0X,VC9,C,JAVA,PAS,CS";
}
function getInDataCount() {
	return "0";
}
function getSubinter() {
	var inter = "0";
	var iint = parseInt(""+inter);
	if (!(iint>0))
		return 0;
	return iint;
}
function getRemain() {
	var remain = "0";
	var iremain = parseInt(""+remain);
	if (!(iremain>0))
		return 0;
	return iremain;
}
function initProb()
{
	if (getSrc() && getSrc()!="")
		e("psrc").style.display = "block";
	var cod = getCode();
	if (cod && cod.indexOf("@你的代码")>=0)
	{
		e("pcodesu").style.display = "block";
		port_fc(cod, addline);
	}
	if (getSubinter()>0)
	{
		var rem = getRemain();
		var intervalVar;
		var startT = new Date().getTime();
		function setSubInt()
		{
			var passT = Math.floor((new Date().getTime() - startT) / 1000);
			var crem = rem - passT;
			var minu = Math.floor(crem/60); var sec = crem - minu*60;
			var subTxt = "";
			if (crem<=0) subTxt = "<span class="gcolor">现在可以提交</span>";
			else
				subTxt = "<span class="rcolor">还剩" + (minu>0?minu+"分":"") + sec + "秒</span>";
			var html = "代码提交间隔：<span class="uline">" + getSubinter() + "分钟(" + subTxt + ")</span> &nbsp; ";
			e("subinterdiv").innerHTML = html;
			if (crem <= 0) { clearInterval(intervalVar); } } intervalVar = setInterval(setSubInt, 1000); setSubInt(); } if (getProbType()=="SUBMIT") { e("probtypediv").innerHTML = "<span class="uline">提交答案型</span> &nbsp; ";
		e("pinputs").style.display = "block";
		var inCnt = parseInt(getInDataCount());
		var _dlist = newT("UL", e("inputlist"));
		{
			var ca = newT("A", newT("LI", _dlist), "", "下载全部");
			ca.href = "###";
			ca.onclick = function() {
				portxd("/problem.Problem.dt", {cmd:"indata",gpid:"A1253",dataid:"all"},function(obj) {
					if (obj["ret"]+""=="1")
					{
						downloadByHandle(obj["handle"]);
					}
				});
			}
		}
		newT("br", _dlist);
		for (var i = 0; i < inCnt; ++i) { var ca = newT("A", newT("LI", _dlist), "", "input" + (i+1) + ".txt"); ca.dataId = i+1; ca.href = "###"; ca.onclick = function() { portxd("/problem.Problem.dt", {cmd:"indata",gpid:"A1253",dataid:this.dataId},function(obj) { if (obj["ret"]+""=="1") { downloadByHandle(obj["handle"]); } }); } } } } initProb(); function weiboShareClick() { var _w = 16 , _h = 16; var param = { url:location.href, type:'3', count:'', /**是否显示分享数，1显示(可选)*/ appkey:'1707773381', /**您申请的应用appkey,显示分享来源(可选)*/ title:"试题 "+getProbTitle(), /**分享的文字内容(可选，默认为所在页面的title)*/ pic:'http://www.tsinsen.com/images/tsinsen100.png', /**分享图片的路径(可选)*/ ralateUid:'', /**关联用户的UID，分享微博会@该用户(可选)*/ language:'zh_cn', /**设置语言，zh_cn|zh_tw(可选)*/ rnd:new Date().valueOf() } rrShareOnclick(param, "http://service.weibo.com/share/share.php"); } function qqShareClick() { var cont = removeHTML(getProbContent()); var param = { url:location.href, showcount:'0',/*是否显示分享总数,显示：'1'，不显示：'0' */ desc:'',/*默认分享理由(可选)*/ summary:cont,/*分享摘要(可选)*/ title:getProbTitle(),/*分享标题(可选)*/ site:'清橙网络自动评测系统',/*分享来源 如：腾讯网(可选)*/ pics:'http://www.tsinsen.com/images/tsinsen100.png', /*分享图片的路径(可选)*/ style:'203', width:22, height:22 }; rrShareOnclick(param, "http://sns.qzone.qq.com/cgi-bin/qzshare/cgi_qzshare_onekey"); } function renrenShareClick() { var cont = removeHTML(getProbContent()); var param = { resourceUrl : '', //分享的资源Url pic : 'http://www.tsinsen.com/images/tsinsen100.png', //分享的主题图片Url title :getProbTitle(), //分享的标题 description : cont //分享的详细描述 }; rrShareOnclick(param); } var lineNum = 0; function addline(st) { newT("LI", _codeLines, ((++lineNum)&1)?"odd":"even", st.replace("@你的代码", '<span class="Y">@你的代码</span>')); }
function OnUploadCompleted(ret, fn, msg)
{
	if (ret+""=="1")
	{
		setData("lastsubtype", "FILE");
		portxd("/test.SubmitCode.dt", {gpid:gpid,codefn:msg}, function(obj){
			if (""+obj["ret"]=="1")
			{
				window.location.href = "/AllSubmits.page?type=a";
			}
			else
			{
				alert(obj["msg"]);
				showSubmit();
			}
		});
	}
	else
	{
		alert(msg);
		showSubmit();
	}
}
function showSubmit()
{
	var cc = getCode();
	var canUseFile = (cc==null)||(cc=="");
	var isSubmit = (getProbType()=="SUBMIT");
	var canUsePaste = !isSubmit;
	var _langs;
	var _pop = createPopWin("提交代码", function(gdiv){
		var divS = newT("", gdiv, "vsp");
		var fdiv = newT("", gdiv);
		newT("", fdiv, "", '
<iframe id="dataupf" src="/CommonFileUpload.page" style="width:220px;height:40px;margin:0px;padding:0px;border:0px;">
</iframe>
');
		var div = newT("", gdiv);
		fdiv.style.display = "none";
		div.style.display = "block";
		function setDivS1()
		{
			if (!canUsePaste && canUseFile)
			{
				setDivS2()
				return ;
			}
			fdiv.style.display = "none";
			div.style.display = "block";
			divS.innerHTML = "";
			var l1 = newT("span", divS, "", "<b>* 粘贴代码提交</b>");
			if (canUseFile)
			{
				newT("span", divS, "", " &nbsp; &nbsp; &nbsp; ");
				var l2 = newT("a", divS, "", "上传文件提交");
				l2.href = "###";
				l2.onclick = function() {
					setDivS2();
				};
			}
		}
		function toLangDesc(lang)
		{
			if (lang=="CPP") return "C++ (MinGW g++ 4.7.2)";
			if (lang=="C") return "C (MinGW gcc 4.7.2)";
			if (lang=="C0X") return "C++0x (MinGW g++ 4.7.2 --std=c++0x)";
			if (lang=="VC9") return "VC (Microsoft Visual C++ 2008)";
			if (lang=="PAS") return "PAS (Free Pascal Compiler 2.4.0)";
			if (lang=="CS") return "C# (Microsoft .NET 3.5)";
			if (lang=="JAVA") return "Java (Java 1.7.0_15)";
			if (lang=="RUBY") return "Ruby (Ruby 1.8.6)";
			if (lang=="PERL") return "Perl (Perl v5.16.3)";
			if (lang=="PYTHON") return "Python (Python 3.3.0)";
			if (lang=="PYTHON27") return "Python (Python 2.7.3)";
			if (lang=="PHP") return "PHP (PHP 5.4.13)";
			return lang;
		}
		function setDivS2()
		{
			if (canUsePaste && !canUseFile)
			{
				setDivS1()
				return ;
			}
			div.style.display = "none";
			fdiv.style.display = "block";
			divS.innerHTML = "";
			if (canUsePaste)
			{
				var l1 = newT("a", divS, "", "粘贴代码提交");
				l1.href = "###";
				l1.onclick = function() {
					setDivS1();
				};
				newT("span", divS, "", " &nbsp; &nbsp; &nbsp; ");
			}
			var l2 = newT("span", divS, "", "<b>* 上传文件提交</b>");
			if (isSubmit)
			{
				newT("", divS, "", "这是一道提交答案的试题，请将<b>output*.txt</b>打包在一起后提交。");
			}
		}
		var prevsubtype = getData("lastsubtype");
		if (prevsubtype == "FILE")
			setDivS2();
		else
			setDivS1();
		var _lang = newT(null, div, "smallsp", "语言选择：");
		_langs = newT("select", _lang);
		var langs = getLangs();
		var langss = langs.split(",");
		_langs.options.length = 0;
		for (la in langss)
			_langs.options.add(new Option(toLangDesc(langss[la]), langss[la]));
		try {
			var prevlang = getData("lastlang");
			if (prevlang)
			{
				for (var i = 0; i < _langs.options.length; i++) if (_langs.options[i].value == prevlang) _langs.options[i].selected = true; } } catch ( errx ) {}; var _code = newT(null, div, "code"); var _curcode = getCode() || ""; var lineNum = 0; if (_curcode && _curcode.indexOf("@你的代码")>=0)
		{
			var _scodeLines = newT("OL", _code);
			port_fc(_curcode, function(st){ newT("LI", _scodeLines, ((++lineNum)&1)?"odd":"even", st.replace("@你的代码", "<textarea name="code" id="code" class="code" style="height:200px;width:600px;"></textarea>")); });
		}
		else
			_code.innerHTML = "<textarea name="code" id="code" class="code" style="height:430px;width:660px;"></textarea>";
		var _btns = newT("", div, "btns");
		var _okBtn = createButton(_btns, "提交", function() {
			var vgpid = gpid;
			var vlang = _langs.value;
			var vcode = e("code").value;
			if (vcode=="")
			{
				alert("请输入要提交的程序。");
				_okBtn.enableClick();
				return true;
			}
			else
			{
				setData("lastsubtype", "CODE");
				portxd("/test.SubmitCode.dt", {gpid:vgpid,lang:vlang,code:vcode}, function(obj){
					setData("lastlang", vlang);
					if (""+obj["ret"]=="1")
					{
						window.location.href = "/AllSubmits.page?type=a";
					}
					else
					{
						alert(obj["msg"]);
						_okBtn.enableClick();
					}
				});
			}
			return false;
		});
		var _closeBtn = createButton(_btns, "关闭", function() { _pop.doHide(); });
	}, "", function(){}, 800);
}
function formatChange()
{
	if (viewType == "f")
	{
		viewType = "p";
		e("pcont1").style.display = "none";
		e("pcont2").style.display = "block";
		e('fcl').innerHTML = "查看格式化的试题";
	}
	else
	{
		viewType = "f";
		e("pcont2").style.display = "none";
		e("pcont1").style.display = "block";
		e('fcl').innerHTML = "查看未格式化的试题";
	}
}
function discussProblem() { location.href = "/Forum/Index.page?gpid=" + gpid; }
</script>
<!-- InstanceEndEditable -->
<!--end main-->
</div>
</div>
