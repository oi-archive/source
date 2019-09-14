# 题目描述


<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:#FFFFFF;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:19px;line-height:19px;white-space:normal;">
<span class="mw-headline" id=".E6.8F.8F.E8.BF.B0">描述 USACO 1.3.2</span> 
</h2>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:19px;font-size:13px;white-space:normal;background-color:#FFFFFF;">
<span style="font-size:18px;">由于乳制品产业利润很低，所以降低原材料（牛奶）价格就变得十分重要。帮助梅丽乳业找到最优的牛奶采购方案。</span> 
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:19px;font-size:13px;white-space:normal;background-color:#FFFFFF;">
<span style="font-size:18px;">梅丽乳业从一些奶农手中采购牛奶，并且每一位奶农为乳制品加工企业提供的价格是不同的。此外，就像每头奶牛每天只能挤出固定数量的奶，每位奶农每天能提供的牛奶数量是一定的。每天梅丽乳业可以从奶农手中采购到小于或者等于奶农最大产量的整数数量的牛奶。</span> 
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:19px;font-size:13px;white-space:normal;background-color:#FFFFFF;">
<span style="font-size:18px;">给出梅丽乳业每天对牛奶的需求量，还有每位奶农提供的牛奶单价和产量。计算采购足够数量的牛奶所需的最小花费。</span> 
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:19px;font-size:13px;white-space:normal;background-color:#FFFFFF;">
<span style="font-size:18px;">注：每天所有奶农的总产量大于梅丽乳业的需求量。</span> 
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:#FFFFFF;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:19px;line-height:19px;white-space:normal;">
<span class="mw-headline" id=".E6.A0.BC.E5.BC.8F"><br/>
格式</span> 
</h2>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:19px;font-size:13px;white-space:normal;background-color:#FFFFFF;">
<b><span style="font-size:18px;">PROGRAM NAME</span></b><span style="font-size:18px;">: milk</span> 
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:19px;font-size:13px;white-space:normal;background-color:#FFFFFF;">
<b><span style="font-size:18px;">INPUT FORMAT</span></b><span style="font-size:18px;">:file milk.in</span> 
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:19px;font-size:13px;white-space:normal;background-color:#FFFFFF;">
<span style="font-size:18px;">第 1 行共二个数值:N,(0&lt;=N&lt;=2,000,000)是需要牛奶的总数；M,(0&lt;= M&lt;=5,000)是提供牛奶的农民个数。</span> 
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:19px;font-size:13px;white-space:normal;background-color:#FFFFFF;">
<span style="font-size:18px;">第 2 到 M+1 行:每行二个整数:P</span><sub><span style="font-size:18px;">i</span></sub><span style="font-size:18px;"> 和 A</span><sub><span style="font-size:18px;">i</span></sub><span style="font-size:18px;">。</span> 
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:19px;font-size:13px;white-space:normal;background-color:#FFFFFF;">
<span style="font-size:18px;">P</span><sub><span style="font-size:18px;">i</span></sub><span style="font-size:18px;">(0&lt;= P</span><sub><span style="font-size:18px;">i</span></sub><span style="font-size:18px;">&lt;=1,000) 是农民 i 的牛奶的价格。</span> 
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:19px;font-size:13px;white-space:normal;background-color:#FFFFFF;">
<span style="font-size:18px;">A</span><sub><span style="font-size:18px;">i</span></sub><span style="font-size:18px;">(0 &lt;= A</span><sub><span style="font-size:18px;">i</span></sub><span style="font-size:18px;"> &lt;= 2,000,000)是农民 i 一天能卖给Marry的牛奶制造公司的牛奶数量。</span> 
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:19px;font-size:13px;white-space:normal;background-color:#FFFFFF;">
<b><span style="font-size:18px;">OUTPUT FORMAT</span></b><span style="font-size:18px;">:file milk.out</span> 
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:19px;font-size:13px;white-space:normal;background-color:#FFFFFF;">
<span style="font-size:18px;">单独的一行包含单独的一个整数，表示Marry的牛奶制造公司拿到所需的牛奶所要的最小费用</span> 
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:#FFFFFF;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:19px;line-height:19px;white-space:normal;">
<span class="mw-headline" id="SAMPLE_INPUT"><br/>
SAMPLE INPUT</span> 
</h2>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#FFFFFF;line-height:1.1em;font-size:18px;"> 100 5
 5 20
 9 40
 3 10
 8 80
 6 30
</pre>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:#FFFFFF;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:19px;line-height:19px;white-space:normal;">
<span class="mw-headline" id="SAMPLE_OUTPUT"><br/>
SAMPLE OUTPUT</span> 
</h2>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#FFFFFF;line-height:1.1em;font-size:18px;">630</pre>
