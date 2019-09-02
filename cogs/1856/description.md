
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
lqp在为出题而烦恼，他完全没有头绪，好烦啊…<br/>
他首先想到了整数拆分。整数拆分是个很有趣的问题。给你一个正整数N，对于N的一个整数拆分就是满足任意m&gt;0，a<sub>1 </sub>,a<sub>2 </sub>,a<sub>3</sub>…a<sub>m</sub>&gt;0，且a<sub>1</sub>+a<sub>2</sub>+a<sub>3</sub>+…+a<sub>m</sub>=N的一个有序集合。通过长时间的研究我们发现了计算对于N的整数拆分的总数有一个很简单的递推式，但是因为这个递推式实在太简单了，如果出这样的题目，大家会对比赛毫无兴趣的。<br/>
然后lqp又想到了斐波那契数。定义F<sub>0</sub>=0，F<sub>1</sub>=1，F<sub>n</sub>=F<sub>n-1</sub>+F<sub>n-2 </sub>(n&gt;1)，F<sub>n</sub>就是斐波那契数的第n项。但是求出第n项斐波那契数似乎也不怎么困难…<br/>
lqp为了增加选手们比赛的欲望，于是绞尽脑汁，想出了一个有趣的整数拆分，我们暂且叫它：整数的lqp拆分。和一般的整数拆分一样，整数的lqp拆分是满足任意m&gt;0，a<sub>1 </sub>,a<sub>2 </sub>,a<sub>3</sub>…a<sub>m</sub>&gt;0，且a<sub>1</sub>+a<sub>2</sub>+a<sub>3</sub>+…+a<sub>m</sub>=N的一个有序集合。但是整数的lqp拆分要求的不是拆分总数，相对更加困难一些。对于每个拆分，lqp定义这个拆分的权值F<sub>a1</sub>F<sub>a2</sub>…F<sub>am</sub>，他想知道对于所有的拆分，他们的权值之和是多少？简单来说，就是求<br/>
<img src="/upload/image/20141208/20141208144752_80121.jpg" alt=""/><br/>

# 输入格式


<div class="pdcont">
输入的第一行包含一个整数N。
</div>

# 输出格式


<div class="pdcont">
输出一个整数，为对于N的整数lqp拆分的权值和mod 10<sup>9</sup>+7。
</div>

# 样例输入


<div class="pddata">
3
</div>

# 样例输出


<div class="pddata">
5
</div>

# 样例说明


<div class="pdcont">
F<sub>0</sub>=0，F<sub>1</sub>=1，F<sub>2</sub>=1，F<sub>3</sub>=2。<br/>
对于N=3，有这样几种lqp拆分：<br/>
3=1+1+1, 权值是1*1*1=1。<br/>
3=1+2，权值是1*2=2。<br/>
3=2+1，权值是2*1=2。<br/>
所以答案是1*1*1+1*2+2*1=5。
</div>

# 数据说明


<div class="pdcont">
20%数据满足：1≤N≤25<br/>
50%数据满足：1≤N≤1000<br/>
100%数据满足：1≤N≤1000000
</div>
</div>
<script type="text/javascript">
var viewType = "f";
_codeLines = document.createElement("OL");
e("pcode").appendChild(_codeLines);
function getGPID() {
	return "A1244";
}
var gpid = getGPID();
function getProbTitle() {
	return "整数的lqp拆分(刘启鹏)";
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
				portxd("/problem.Problem.dt", {cmd:"indata",gpid:"A1244",dataid:"all"},function(obj) {
					if (obj["ret"]+""=="1")
					{
						downloadByHandle(obj["handle"]);
					}
				});
			}
		}
		newT("br", _dlist);
		for (var i = 0; i < inCnt; ++i) { var ca = newT("A", newT("LI", _dlist), "", "input" + (i+1) + ".txt"); ca.dataId = i+1; ca.href = "###"; ca.onclick = function() { portxd("/problem.Problem.dt", {cmd:"indata",gpid:"A1244",dataid:this.dataId},function(obj) { if (obj["ret"]+""=="1") { downloadByHandle(obj["handle"]); } }); } } } } initProb(); function weiboShareClick() { var _w = 16 , _h = 16; var param = { url:location.href, type:'3', count:'', /**是否显示分享数，1显示(可选)*/ appkey:'1707773381', /**您申请的应用appkey,显示分享来源(可选)*/ title:"试题 "+getProbTitle(), /**分享的文字内容(可选，默认为所在页面的title)*/ pic:'http://www.tsinsen.com/images/tsinsen100.png', /**分享图片的路径(可选)*/ ralateUid:'', /**关联用户的UID，分享微博会@该用户(可选)*/ language:'zh_cn', /**设置语言，zh_cn|zh_tw(可选)*/ rnd:new Date().valueOf() } rrShareOnclick(param, "http://service.weibo.com/share/share.php"); } function qqShareClick() { var cont = removeHTML(getProbContent()); var param = { url:location.href, showcount:'0',/*是否显示分享总数,显示：'1'，不显示：'0' */ desc:'',/*默认分享理由(可选)*/ summary:cont,/*分享摘要(可选)*/ title:getProbTitle(),/*分享标题(可选)*/ site:'清橙网络自动评测系统',/*分享来源 如：腾讯网(可选)*/ pics:'http://www.tsinsen.com/images/tsinsen100.png', /*分享图片的路径(可选)*/ style:'203', width:22, height:22 }; rrShareOnclick(param, "http://sns.qzone.qq.com/cgi-bin/qzshare/cgi_qzshare_onekey"); } function renrenShareClick() { var cont = removeHTML(getProbContent()); var param = { resourceUrl : '', //分享的资源Url pic : 'http://www.tsinsen.com/images/tsinsen100.png', //分享的主题图片Url title :getProbTitle(), //分享的标题 description : cont //分享的详细描述 }; rrShareOnclick(param); } var lineNum = 0; function addline(st) { newT("LI", _codeLines, ((++lineNum)&1)?"odd":"even", st.replace("@你的代码", '<span class="Y">@你的代码</span>')); }
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


