# 题目描述


<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;font-weight:bold;"="">【问题描述】</span><span style="font-family:;" 宋体";font-size:10.5pt;font-weight:bold;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:;" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;">城市街道交费系统最近创立了。一辆汽车左转一次需付费</span><span style="font-family:Microsoft YaHei;">$1</span><span style="font-family:Microsoft YaHei;">，右转一次需付费</span><span style="font-family:Microsoft YaHei;">$5</span><span style="font-family:Microsoft YaHei;">。只有当前进、左转、右转都无路可走的时候，调头才是允许的，调头每次付费</span><span style="font-family:Microsoft YaHei;">$10</span><span style="font-family:Microsoft YaHei;">。</span></span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">给出一张城市地图，要求你求出从起始点到达终止点的花费最少的路径。幸运的是，所有的道路都是正北、正南、正西或正东方向的。</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:;" 宋体";font-size:10.5pt;font-weight:bold;"=""><span style="font-family:Microsoft YaHei;">【样例</span><span style="font-family:Microsoft YaHei;">1</span><span style="font-family:Microsoft YaHei;">】</span></span><span style="font-family:;" 宋体";font-size:10.5pt;font-weight:bold;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:;" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;">如下图，符号‘</span><span style="font-family:Microsoft YaHei;">#</span><span style="font-family:Microsoft YaHei;">’代表街道，符号‘</span></span><span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;font-weight:bold;"="">.</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;">’代表障碍区，符号‘</span><span style="font-family:Microsoft YaHei;">E</span><span style="font-family:Microsoft YaHei;">’表示起始站且汽车面朝东，符号‘</span><span style="font-family:Microsoft YaHei;">F</span><span style="font-family:Microsoft YaHei;">’表示汽车终止点。</span></span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">...........</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">....#####..</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">....#...#..</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">....#...#．．</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">.#E######..</span>
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">....#......</span>
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">.##F#......</span>
</p>
<p style="text-indent:21pt;">
	<span style="font-family:;" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;">最便宜的路径花费</span><span style="font-family:Microsoft YaHei;">$8</span><span style="font-family:Microsoft YaHei;">：直走，然后左转</span><span style="font-family:Microsoft YaHei;">3</span><span style="font-family:Microsoft YaHei;">次，最后右转到终止点</span><span style="font-family:Microsoft YaHei;">F</span><span style="font-family:Microsoft YaHei;">。如果先直走然后右转</span><span style="font-family:Microsoft YaHei;">2</span><span style="font-family:Microsoft YaHei;">次，花费将是</span><span style="font-family:Microsoft YaHei;">$10</span><span style="font-family:Microsoft YaHei;">。</span></span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:;" 宋体";font-size:10.5pt;font-weight:bold;"=""><span style="font-family:Microsoft YaHei;">【样例</span><span style="font-family:Microsoft YaHei;">2</span><span style="font-family:Microsoft YaHei;">】</span></span><span style="font-family:;" 宋体";font-size:10.5pt;font-weight:bold;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:;" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;">如图</span><span style="font-family:Microsoft YaHei;">10</span></span><span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">-</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;">2</span><span style="font-family:Microsoft YaHei;">，符号‘</span><span style="font-family:Microsoft YaHei;">S</span><span style="font-family:Microsoft YaHei;">’表示起始站且汽车面朝南。最便宜的路径花费</span><span style="font-family:Microsoft YaHei;">$7</span><span style="font-family:Microsoft YaHei;">：立刻左转，直走，在第一个岔路口左转，随后右转。</span></span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">.....................</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">.#######.............</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">.#.....#.......#.....</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">.###...#.......#.....</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">...#...#.......#.....</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">.###...#.......#.....</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">.#.....#.......#.....</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">.############F#####..</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">.......#..........#..</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">.......#..........#..</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">...#...#...#####..#..</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">...#...#...#.#.#..#..</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">..#S########.#.#..#..</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">...#.......#.###..#..</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">...#.......#......#..</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">...........########..</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">.....................</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:;" roman";font-size:10.5pt;"="" new="" times=""><span style="font-family:Microsoft YaHei;">城市地图高度最小为</span><span style="font-family:Microsoft YaHei;">4</span><span style="font-family:Microsoft YaHei;">，</span></span><span style="font-family:;" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;">最大为</span><span style="font-family:Microsoft YaHei;">30</span><span style="font-family:Microsoft YaHei;">，城市地图宽度亦最小为</span><span style="font-family:Microsoft YaHei;">4</span><span style="font-family:Microsoft YaHei;">最大为</span><span style="font-family:Microsoft YaHei;">30</span><span style="font-family:Microsoft YaHei;">。只有一个起点、一个终点，他们之间总存在可通达的路径。同时由于地图周围一圈均是障碍区，所以汽车是没有可能开除城市的。</span></span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;font-weight:bold;"="">【输入】</span><span style="font-family:;" 宋体";font-size:10.5pt;font-weight:bold;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:;" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;">输入文件</span><span style="font-family:Microsoft YaHei;">erp.in</span><span style="font-family:Microsoft YaHei;">如下：</span></span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:;" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;">（</span><span style="font-family:Microsoft YaHei;">1</span><span style="font-family:Microsoft YaHei;">）第一行有</span><span style="font-family:Microsoft YaHei;">2</span><span style="font-family:Microsoft YaHei;">个整数，地图高度</span><span style="font-family:Microsoft YaHei;">h</span><span style="font-family:Microsoft YaHei;">和宽度</span><span style="font-family:Microsoft YaHei;">w</span><span style="font-family:Microsoft YaHei;">。</span></span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:;" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;">（</span><span style="font-family:Microsoft YaHei;">2</span><span style="font-family:Microsoft YaHei;">）其后</span><span style="font-family:Microsoft YaHei;">h</span><span style="font-family:Microsoft YaHei;">行每行</span><span style="font-family:Microsoft YaHei;">w</span><span style="font-family:Microsoft YaHei;">个字母，将是以下字母中的一个：</span></span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">‘.’表示障碍区</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">‘#’表示道路</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">‘E’表示起始点且汽车面朝东</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">‘W’ 表示起始点且汽车面朝西</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">‘N’ 表示起始点且汽车面朝北</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">‘S’ 表示起始点且汽车面朝南</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">‘F’ 表示终点</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;font-weight:bold;"="">【输出】</span><span style="font-family:;" 宋体";font-size:10.5pt;font-weight:bold;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:;" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;">输出文件</span><span style="font-family:Microsoft YaHei;">erp.out</span><span style="font-family:Microsoft YaHei;">仅包含一个整数，即为最便宜路径的费用。</span></span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;font-weight:bold;"="">【样例】</span><span style="font-family:;" 宋体";font-size:10.5pt;font-weight:bold;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">erp.in</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""> </span><span style="font-family:;" 宋体";font-size:10.5pt;"=""> </span><span style="font-family:;" 宋体";font-size:10.5pt;"=""> </span><span style="font-family:;" 宋体";font-size:10.5pt;"=""> </span><span style="font-family:;" 宋体";font-size:10.5pt;"=""> </span><span style="font-family:;" 宋体";font-size:10.5pt;"=""> </span><span style="font-family:;" 宋体";font-size:10.5pt;"=""> </span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">8 11</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""> </span><span style="font-family:;" 宋体";font-size:10.5pt;"=""> </span><span style="font-family:;" 宋体";font-size:10.5pt;"=""> </span><span style="font-family:;" 宋体";font-size:10.5pt;"=""> </span><span style="font-family:;" 宋体";font-size:10.5pt;"=""> </span><span style="font-family:;" 宋体";font-size:10.5pt;"=""> </span><span style="font-family:;" 宋体";font-size:10.5pt;"=""> </span><span style="font-family:;" 宋体";font-size:10.5pt;"=""> </span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">...........</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">....#####..</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">....#...#..</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">....#...#..</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">.#E######..</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">....#......</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">.##F#......</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">...........</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">erp.out</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family: Microsoft YaHei;" 宋体";font-size:10.5pt;"="">8</span><span style="font-family:;" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
	<br/>
</p>
