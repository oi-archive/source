
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
传说中的Dystopia大陆是一片神圣美丽的土地，上面生活着具有极高文明的种族Barbarian。这里是一个美好、人人平等、没有压迫的社会，就像世外桃源一般。<br/>
Dystopia大陆上有N处泉水，每种泉水含有M种元素：冰，火，木等等（固定比例）。每一处泉水都是无穷无尽的，但是每次对于每一个矿的开采都需要耗费大量的魔法。<br/>
这里的泉水是Dystopia大陆的灵性和精华之源，令许多周边种族朝思暮想，也因此常常招致来战争。由于Dystopia的人们不善于战争，为了保护这方乐土，Dystopia的人委托爱与美的化身Satan来帮助他们保卫国家。但是Satan不会无条件保护他们，每一次保护他都必须得到每种泉水各10<sup>100</sup>升。<br/>
经过几次战争后，Dystopia的人们发觉Satan的要求实在太多了。为了减少魔法的使用，Dystopia的大法师决定尽可能减少开采的矿的数量，而是增加每个矿开采的泉水总量，然后通过一定比例调配以假乱真。比如有3处泉水，第一处是10%冰+10%火+80%木，第二处是20%冰+20%火+60%木，第三处是30%冰+30%火+40%木。我们可以只开采第一处和第三处的泉水，然后按照1:1的比例就可以调配出和第二处泉水完全相同的混合泉水。<br/>
现在大法师想知道有多少处泉水可以不开采，也就是有多少处泉水可以通过除它以外的其他泉水调配出来。如果有两处泉水的成分完全相同，大法师会不动脑子地认为它们都可以不开采，而不是必须开采一处或者都必须开采。
</div>

# 输入格式


<div class="pdcont">
输入的第一行包含两个整数N和M，如题所述。<br/>
接下来N行，每行M个实数，分别是第i种元素的百分比。保证所有M个数之和为100。
</div>

# 输出格式


<div class="pdcont">
输出一个整数，表示可以不开采的泉水的数量。
</div>

# 样例输入


<div class="pddata">
3 3<br/>
10 10 80<br/>
20 20 60<br/>
30 30 40
</div>

# 样例输出


<div class="pddata">
1
</div>

# 样例输入


<div class="pddata">
2 1<br/>
100<br/>
100
</div>

# 样例输出


<div class="pddata">
2
</div>

# 数据说明


<div class="pdcont">
5%数据满足：1≤N≤100，M=1。<br/>
另外15%数据满足：1≤N≤10000，M=2。<br/>
另外30%数据满足：M=3。<br/>
最后50%数据满足：M=4，且保证都是随机数据。<br/>
最后50%中有10%满足：M=4且1≤N≤10。<br/>
所有数据满足：1&lt;=N&lt;=10000，1≤N<sup>M</sup>≤10<sup>12</sup>。
</div>
</div>
<script type="text/javascript">
var viewType = "f";
_codeLines = document.createElement("OL");
e("pcode").appendChild(_codeLines);
function getGPID() {
	return "A1245";
}
var gpid = getGPID();
function getProbTitle() {
	return "元素之泉(刘启鹏)";
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
				portxd("/problem.Problem.dt", {cmd:"indata",gpid:"A1245",dataid:"all"},function(obj) {
					if (obj["ret"]+""=="1")
					{
						downloadByHandle(obj["handle"]);
					}
				});
			}
		}
		newT("br", _dlist);
		for (var i = 0; i < inCnt; ++i) { var ca = newT("A", newT("LI", _dlist), "", "input" + (i+1) + ".txt"); ca.dataId = i+1; ca.href = "###"; ca.onclick = function() { portxd("/problem.Problem.dt", {cmd:"indata",gpid:"A1245",dataid:this.dataId},function(obj) { if (obj["ret"]+""=="1") { downloadByHandle(obj["handle"]); } }); } } } } initProb(); function weiboShareClick() { var _w = 16 , _h = 16; var param = { url:location.href, type:'3', count:'', /**是否显示分享数，1显示(可选)*/ appkey:'1707773381', /**您申请的应用appkey,显示分享来源(可选)*/ title:"试题 "+getProbTitle(), /**分享的文字内容(可选，默认为所在页面的title)*/ pic:'http://www.tsinsen.com/images/tsinsen100.png', /**分享图片的路径(可选)*/ ralateUid:'', /**关联用户的UID，分享微博会@该用户(可选)*/ language:'zh_cn', /**设置语言，zh_cn|zh_tw(可选)*/ rnd:new Date().valueOf() } rrShareOnclick(param, "http://service.weibo.com/share/share.php"); } function qqShareClick() { var cont = removeHTML(getProbContent()); var param = { url:location.href, showcount:'0',/*是否显示分享总数,显示：'1'，不显示：'0' */ desc:'',/*默认分享理由(可选)*/ summary:cont,/*分享摘要(可选)*/ title:getProbTitle(),/*分享标题(可选)*/ site:'清橙网络自动评测系统',/*分享来源 如：腾讯网(可选)*/ pics:'http://www.tsinsen.com/images/tsinsen100.png', /*分享图片的路径(可选)*/ style:'203', width:22, height:22 }; rrShareOnclick(param, "http://sns.qzone.qq.com/cgi-bin/qzshare/cgi_qzshare_onekey"); } function renrenShareClick() { var cont = removeHTML(getProbContent()); var param = { resourceUrl : '', //分享的资源Url pic : 'http://www.tsinsen.com/images/tsinsen100.png', //分享的主题图片Url title :getProbTitle(), //分享的标题 description : cont //分享的详细描述 }; rrShareOnclick(param); } var lineNum = 0; function addline(st) { newT("LI", _codeLines, ((++lineNum)&1)?"odd":"even", st.replace("@你的代码", '<span class="Y">@你的代码</span>')); }
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


