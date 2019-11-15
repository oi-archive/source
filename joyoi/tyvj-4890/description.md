# 

 
 # 题目背景 
<p>可爱的点们生活在数轴上，它们天天很开心&hellip;&hellip;</p> 

 
 # 题目描述 
<p>开学了，数轴上的点自然是不想去上课的，于是他们便躲在了数轴里。</p>

<p>老师们见开学了却没有学生来上课，便按照学生的住址登门拜访。</p>

<p>可是住在数轴里的点可没有将错就错，它们早已经离开了自己原本在数轴上的位置。</p>

<p>老师们无能为力，只好排成一条线段，站在数轴上，即数轴上的闭区间<span><span class="katex"><span class="katex-mathml"><math><semantics><mrow><mo>[</mo><mi>a</mi><mo separator="true">,</mo><mi>b</mi><mo>]</mo></mrow><annotation encoding="application/x-tex">[a,b]</annotation></semantics></math></span></span></span>，我们把这种线段叫做&ldquo;老师战线&rdquo;。</p>

<p>现在在数轴上有<span><span class="katex"><span class="katex-mathml"><math><semantics><mrow><mi>m</mi></mrow><annotation encoding="application/x-tex">m</annotation></semantics></math></span></span></span>个没有准时去上学的点，它们心里都很害怕，如果自己所在的位置<span><span class="katex"><span class="katex-mathml"><math><semantics><mrow><mi>p</mi></mrow><annotation encoding="application/x-tex">p</annotation></semantics></math></span></span></span>，被&ldquo;老师战线&rdquo;覆盖的次数达到了<span><span class="katex"><span class="katex-mathml"><math><semantics><mrow><mi>t</mi></mrow><annotation encoding="application/x-tex">t</annotation></semantics></math></span></span></span>，那么它们就会被抓走。</p>

<p>而老师们想更多的布置&ldquo;老师战线&rdquo;，而点们又想要尽可能少的被抓走。</p>

<p>现在你同时受到了两者的请求，你能帮助<strong>他们</strong>吗?</p> 

 
 # 输入格式 
<p>第一行两个整数<span><span class="katex"><span class="katex-mathml"><math><semantics><mrow><mi>n</mi><mo separator="true">,</mo><mi>m</mi></mrow><annotation encoding="application/x-tex">n,m</annotation></semantics></math></span></span></span>分别表示&ldquo;老师战线&rdquo;数和点数。</p>

<p>接下来<span><span class="katex"><span class="katex-mathml"><math><semantics><mrow><mi>n</mi></mrow><annotation encoding="application/x-tex">n</annotation></semantics></math></span></span></span>行，每行两个整数<span><span class="katex"><span class="katex-mathml"><math><semantics><mrow><mi>a</mi><mo separator="true">,</mo><mi>b</mi></mrow><annotation encoding="application/x-tex">a,b</annotation></semantics></math></span></span></span>(<span><span class="katex"><span class="katex-mathml"><math><semantics><mrow><mi>a</mi><mo>&le;</mo><mi>b</mi></mrow></semantics></math></span></span></span>)，表示&rdquo;老师战线&ldquo;<span><span class="katex"><span class="katex-mathml"><math><semantics><mrow><mo>[</mo><mi>a</mi><mo separator="true">,</mo><mi>b</mi><mo>]</mo></mrow><annotation encoding="application/x-tex">[a,b]</annotation></semantics></math></span></span></span>的端点。</p>

<p>接下来<span><span class="katex"><span class="katex-mathml"><math><semantics><mrow><mi>m</mi></mrow><annotation encoding="application/x-tex">m</annotation></semantics></math></span></span></span>行，每行两个整数<span><span class="katex"><span class="katex-mathml"><math><semantics><mrow><mi>p</mi><mo separator="true">,</mo><mi>t</mi></mrow><annotation encoding="application/x-tex">p,t</annotation></semantics></math></span></span></span>，表示位于<span><span class="katex"><span class="katex-mathml"><math><semantics><mrow><mi>p</mi></mrow><annotation encoding="application/x-tex">p</annotation></semantics></math></span></span></span>的点不想上学，并不能被覆盖超过<span><span class="katex"><span class="katex-mathml"><math><semantics><mrow><mi>t</mi></mrow><annotation encoding="application/x-tex">t</annotation></semantics></math></span></span></span>条&rdquo;老师战线&ldquo;.</p> 

 
 # 输出格式 
<p>一个整数，表示最多能放入的&ldquo;老师战线&rdquo;数。</p> 

 
 # 提示 
<p>对于<span><span class="katex"><span class="katex-mathml"><math><semantics><mrow><mn>1</mn><mn>0</mn><mn>0</mn></mrow></semantics></math></span></span></span>%的数据，满足<span><span class="katex"><span class="katex-mathml"><math><semantics><mrow><mn>1</mn><mo>&le;</mo><mi>t</mi><mo>&le;</mo><mi>n</mi><mo>&le;</mo><mn>2</mn><mo>&lowast;</mo><mn>1</mn><msup><mn>0</mn><mn>5</mn></msup></mrow><annotation encoding="application/x-tex">1&nbsp;\leq&nbsp;t&nbsp;\leq&nbsp;n&nbsp;\leq&nbsp;2*10^5</annotation></semantics></math></span></span></span>，<span><span class="katex"><span class="katex-mathml"><math><semantics><mrow><mn>1</mn><mo>&le;</mo><mi>m</mi><mo>&le;</mo><mn>4</mn><mo>&lowast;</mo><mn>1</mn><msup><mn>0</mn><mn>5</mn></msup></mrow><annotation encoding="application/x-tex">1&nbsp;\leq&nbsp;m&nbsp;\leq&nbsp;4*10^5</annotation></semantics></math></span><span class="katex-html"><span class="base textstyle uncramped"><span class="mord"><span class="msupsub"><span class="vlist"><span class="baseline-fix"><span class="fontsize-ensurer reset-size5 size5"><span style="font-size: 0em;">​</span></span>​</span></span></span></span></span></span></span></span>，<span><span class="katex"><span class="katex-mathml"><math><semantics><mrow><mi mathvariant="normal">∣</mi><mi>a</mi><mi mathvariant="normal">∣</mi><mo separator="true">,</mo><mi mathvariant="normal">∣</mi><mi>b</mi><mi mathvariant="normal">∣</mi><mo separator="true">,</mo><mi mathvariant="normal">∣</mi><mi>p</mi><mi mathvariant="normal">∣</mi><mo>&le;</mo><mn>1</mn><msup><mn>0</mn><mn>7</mn></msup></mrow><annotation encoding="application/x-tex">|a|,|b|,|p|&nbsp;\leq&nbsp;10^7</annotation></semantics></math></span><span class="katex-html"><span class="base textstyle uncramped"><span class="mord"><span class="msupsub"><span class="vlist"><span class="baseline-fix"><span class="fontsize-ensurer reset-size5 size5"><span style="font-size: 0em;">​</span></span>​</span></span></span></span></span></span></span></span>.</p>

<h3>注意：<span><span class="katex"><span class="katex-mathml"><math><semantics><mrow><mi>p</mi></mrow><annotation encoding="application/x-tex">p</annotation></semantics></math></span></span></span>相同时<span><span class="katex"><span class="katex-mathml"><math><semantics><mrow><mi>t</mi></mrow><annotation encoding="application/x-tex">t</annotation></semantics></math></span></span></span>取最小值！</h3> 
