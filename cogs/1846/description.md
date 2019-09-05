# 题目描述


<div class="content">
<!--begin main-->
<!-- InstanceBeginEditable name="content" -->
<h3>
【问题描述】
</h3>
<div id="pcont1" style="margin-top:20px;display:block;">
<div class="pdcont">
设函数g(N)表示N的约数个数。<br/>
现在给出一个数M，求出所有M的约数x的g(x)的K次方和。<br/>
即计算<br/>
<img src="/upload/image/20141206/20141206075115_45812.png" alt=""/><br/>
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
第一行输入N，K。N表示M由前N小的素数组成。<br/>
接下来N行，<br/>
第i+1行有一个正整数Pi，表示第i小的素数A<sub>i</sub>有P<sub>i</sub>次。<br/>
等式：<br/>
<img src="/upload/image/20141206/20141206075122_37645.png" alt=""/><br/>
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
输出一个数，表示答案。只需输出最后答案除以1000000007的余数。
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
2 3<br/>
1<br/>
3
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
900
</div>
<h3>
【样例说明】
</h3>
<div class="pdcont">
M=2^1*3^3=54<br/>
M的约数有1,2,3,6,9,18,27,54.约数个数分别为1,2,2,4,3,6,4,8.<br/>
Answer=1^3+2^3+2^3+4^3+3^3+6^3+4^3+8^3=900
</div>
<h3>
【数据规模和约定】
</h3>
<div class="pdcont">
<table cellspacing="0" cellpadding="2px" align="center" style="border-collapse:collapse;border:none;">
<tbody>
<tr align="center" style="border:solid 1.0pt;">
<td valign="top" style="border:solid 1.0pt;">
编号<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
N<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
K<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
Pi&lt;=<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
编号<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
N<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
K<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
Pi&lt;=<br/>
</td>
</tr>
<tr align="center" style="border:solid 1.0pt;">
<td valign="top" style="border:solid 1.0pt;">
1<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
50<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
3<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
10000<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
11<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
64970<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
3<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
2^63-1<br/>
</td>
</tr>
<tr align="center" style="border:solid 1.0pt;">
<td valign="top" style="border:solid 1.0pt;">
2<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
50<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
100<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
10000<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
12<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
71321<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
3<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
2^63-1<br/>
</td>
</tr>
<tr align="center" style="border:solid 1.0pt;">
<td valign="top" style="border:solid 1.0pt;">
3<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
50<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
20101125<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
10000<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
13<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
350<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
5<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
2^31-1<br/>
</td>
</tr>
<tr align="center" style="border:solid 1.0pt;">
<td valign="top" style="border:solid 1.0pt;">
4<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
999<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
17651851<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
100000<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
14<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
250<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
6<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
2^31-1<br/>
</td>
</tr>
<tr align="center" style="border:solid 1.0pt;">
<td valign="top" style="border:solid 1.0pt;">
5<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
5000<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
836954247<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
100000<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
15<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
110<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
7<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
2^31-1<br/>
</td>
</tr>
<tr align="center" style="border:solid 1.0pt;">
<td valign="top" style="border:solid 1.0pt;">
6<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
4687<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
1073741823<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
100000<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
16<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
99<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
8<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
2^31-1<br/>
</td>
</tr>
<tr align="center" style="border:solid 1.0pt;">
<td valign="top" style="border:solid 1.0pt;">
7<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
4321<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
123456789<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
100000<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
17<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
80<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
9<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
2^31-1<br/>
</td>
</tr>
<tr align="center" style="border:solid 1.0pt;">
<td valign="top" style="border:solid 1.0pt;">
8<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
5216<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
368756432<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
100000<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
18<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
70<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
10<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
2^31-1<br/>
</td>
</tr>
<tr align="center" style="border:solid 1.0pt;">
<td valign="top" style="border:solid 1.0pt;">
9<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
8080<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
2^31-1<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
100000<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
19<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
60<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
11<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
2^31-1<br/>
</td>
</tr>
<tr align="center" style="border:solid 1.0pt;">
<td valign="top" style="border:solid 1.0pt;">
10<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
10086<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
3<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
2^63-1<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
20<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
50<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
12<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
2^31-1
</td>
</tr>
</tbody>
</table>
</div>
</div>
<script type="text/javascript">
var viewType = "f";
_codeLines = document.createElement("OL");
e("pcode").appendChild(_codeLines);
function getGPID() {
	return "A1240";
}
var gpid = getGPID();
function getProbTitle() {
	return "Submultiple(梁健楠)";
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
				portxd("/problem.Problem.dt", {cmd:"indata",gpid:"A1240",dataid:"all"},function(obj) {
					if (obj["ret"]+""=="1")
					{
						downloadByHandle(obj["handle"]);
					}
				});
			}
		}
		newT("br", _dlist);
		for (var i = 0; i < inCnt; ++i) { var ca = newT("A", newT("LI", _dlist), "", "input" + (i+1) + ".txt"); ca.dataId = i+1; ca.href = "###"; ca.onclick = function() { portxd("/problem.Problem.dt", {cmd:"indata",gpid:"A1240",dataid:this.dataId},function(obj) { if (obj["ret"]+""=="1") { downloadByHandle(obj["handle"]); } }); } } } } initProb(); function weiboShareClick() { var _w = 16 , _h = 16; var param = { url:location.href, type:'3', count:'', /**是否显示分享数，1显示(可选)*/ appkey:'1707773381', /**您申请的应用appkey,显示分享来源(可选)*/ title:"试题 "+getProbTitle(), /**分享的文字内容(可选，默认为所在页面的title)*/ pic:'http://www.tsinsen.com/images/tsinsen100.png', /**分享图片的路径(可选)*/ ralateUid:'', /**关联用户的UID，分享微博会@该用户(可选)*/ language:'zh_cn', /**设置语言，zh_cn|zh_tw(可选)*/ rnd:new Date().valueOf() } rrShareOnclick(param, "http://service.weibo.com/share/share.php"); } function qqShareClick() { var cont = removeHTML(getProbContent()); var param = { url:location.href, showcount:'0',/*是否显示分享总数,显示：'1'，不显示：'0' */ desc:'',/*默认分享理由(可选)*/ summary:cont,/*分享摘要(可选)*/ title:getProbTitle(),/*分享标题(可选)*/ site:'清橙网络自动评测系统',/*分享来源 如：腾讯网(可选)*/ pics:'http://www.tsinsen.com/images/tsinsen100.png', /*分享图片的路径(可选)*/ style:'203', width:22, height:22 }; rrShareOnclick(param, "http://sns.qzone.qq.com/cgi-bin/qzshare/cgi_qzshare_onekey"); } function renrenShareClick() { var cont = removeHTML(getProbContent()); var param = { resourceUrl : '', //分享的资源Url pic : 'http://www.tsinsen.com/images/tsinsen100.png', //分享的主题图片Url title :getProbTitle(), //分享的标题 description : cont //分享的详细描述 }; rrShareOnclick(param); } var lineNum = 0; function addline(st) { newT("LI", _codeLines, ((++lineNum)&1)?"odd":"even", st.replace("@你的代码", '<span class="Y">@你的代码</span>')); }
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
