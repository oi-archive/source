
<div class="content">
<!--begin main-->
<!-- InstanceBeginEditable name="content" -->

# 试题来源


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
<div id="pcont1" style="margin-top:20px;display:block;">

# 问题描述


<div class="pdcont">
lanxisi带领着他的拆迁队来整治一个街道。这个街道由N个旧房子组成，从左到右编号为1..N。每个旧房子i有一个正整数的美观度A<sub>i</sub>。<br/>
lanxisi希望整个街道从左到右美观度严格递增，也就是保证A<sub>i</sub>&lt;A<sub>j</sub>（i&lt;j）。但是旧的街道明显不符合这个要求，于是lanxisi希望拆迁一些旧房子并在原地建立新房子来满足这一要求。但是与很多拆迁队一样，很多钉子户拒绝拆迁。所以lanxisi希望能保留最多的旧房子来满足某些钉子户，当然，保留一个旧房子需要给房子主人Bi的赔偿金。最后，总花费=整治好以后所有房子美观度之和+赔偿金之和。<br/>
现在，请你求出lanxisi最多能保留多少旧房子和整治这个街道所需要的最少总花费（当然是在保留旧房子最多这个前提下的）。重建后房屋的美观值应当是一个正整数。
</div>

# 输入格式


<div class="pdcont">
第一行有1个整数N，表示旧房子个数。<br/>
第二行有N个整数，第i个数A<sub>i</sub>表示旧房子的美观度。<br/>
第三行有N个整数，第i个数B<sub>i</sub>表示保留旧房子的赔偿金。
</div>

# 输出格式


<div class="pdcont">
第一行输出2个整数，表示保留的旧房子数量、总花费的大小。
</div>

# 样例输入一


<div class="pdcont">
4<br/>
2 1 7 4<br/>
1 5 4 3
</div>

# 样例输出一


<div class="pdcont">
2 25
</div>

# 样例输入二


<div class="pdcont">
6<br/>
1 6 3 4 7 7<br/>
1 2 1 1 1 9
</div>

# 样例输出二


<div class="pdcont">
4 29
</div>

# 数据规模和约定


<div class="pdcont">
20%的数据中，1&lt;=N&lt;=20。<br/>
40%的数据中，1&lt;=N&lt;=7000。<br/>
100%的数据中，1&lt;=N&lt;=100000，0&lt;=A<sub>i</sub>,B<sub>i</sub>&lt;=100000000。<br/>
100%的数据中，时间限制为1s。
</div>
</div>
<script type="text/javascript">
var viewType = "f";
_codeLines = document.createElement("OL");
e("pcode").appendChild(_codeLines);
function getGPID() {
	return "A1246";
}
var gpid = getGPID();
function getProbTitle() {
	return "拆迁队(鲁逸沁)";
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
				portxd("/problem.Problem.dt", {cmd:"indata",gpid:"A1246",dataid:"all"},function(obj) {
					if (obj["ret"]+""=="1")
					{
						downloadByHandle(obj["handle"]);
					}
				});
			}
		}
		newT("br", _dlist);
		for (var i = 0; i < inCnt; ++i) { var ca = newT("A", newT("LI", _dlist), "", "input" + (i+1) + ".txt"); ca.dataId = i+1; ca.href = "###"; ca.onclick = function() { portxd("/problem.Problem.dt", {cmd:"indata",gpid:"A1246",dataid:this.dataId},function(obj) { if (obj["ret"]+""=="1") { downloadByHandle(obj["handle"]); } }); } } } } initProb(); function weiboShareClick() { var _w = 16 , _h = 16; var param = { url:location.href, type:'3', count:'', /**是否显示分享数，1显示(可选)*/ appkey:'1707773381', /**您申请的应用appkey,显示分享来源(可选)*/ title:"试题 "+getProbTitle(), /**分享的文字内容(可选，默认为所在页面的title)*/ pic:'http://www.tsinsen.com/images/tsinsen100.png', /**分享图片的路径(可选)*/ ralateUid:'', /**关联用户的UID，分享微博会@该用户(可选)*/ language:'zh_cn', /**设置语言，zh_cn|zh_tw(可选)*/ rnd:new Date().valueOf() } rrShareOnclick(param, "http://service.weibo.com/share/share.php"); } function qqShareClick() { var cont = removeHTML(getProbContent()); var param = { url:location.href, showcount:'0',/*是否显示分享总数,显示：'1'，不显示：'0' */ desc:'',/*默认分享理由(可选)*/ summary:cont,/*分享摘要(可选)*/ title:getProbTitle(),/*分享标题(可选)*/ site:'清橙网络自动评测系统',/*分享来源 如：腾讯网(可选)*/ pics:'http://www.tsinsen.com/images/tsinsen100.png', /*分享图片的路径(可选)*/ style:'203', width:22, height:22 }; rrShareOnclick(param, "http://sns.qzone.qq.com/cgi-bin/qzshare/cgi_qzshare_onekey"); } function renrenShareClick() { var cont = removeHTML(getProbContent()); var param = { resourceUrl : '', //分享的资源Url pic : 'http://www.tsinsen.com/images/tsinsen100.png', //分享的主题图片Url title :getProbTitle(), //分享的标题 description : cont //分享的详细描述 }; rrShareOnclick(param); } var lineNum = 0; function addline(st) { newT("LI", _codeLines, ((++lineNum)&1)?"odd":"even", st.replace("@你的代码", '<span class="Y">@你的代码</span>')); }
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
			var l1 = newT("span", divS, "", "
# la


