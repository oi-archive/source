# 

 
 # 题目描述 
<p>
<a href="files/heap.rar">课件下载</a><br><br>【堆，二叉堆理论知识】<br><br>堆的定义<br>　&#8226; 堆是一个完全二叉树<br>　　–所有叶子在同一层或者两个连续层<br>　　–最后一层的结点占据尽量左的位置<br>　&#8226; 堆性质<br>　　–为空, 或者最小元素在根上<br>　　–两棵子树也是堆<br><br>存储方式<br>　&#8226; 最小堆的元素保存在heap[1..hs]内<br>　　– 根在heap[1]<br>　　–K的左儿子是2k, K的右儿子是2k+1, <br>　　–K的父亲是[k/2]<br><br><center><img src="/source/joyoi/tyvj-3179/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzE3OS9wcm9ibGVtc19pbWFnZXMvMTUwMC8xYS5ibXA=.bmp"></img></center><br><br><br>删除最小值元素<br>　&#8226; 三步法<br>　　– 直接删除根<br>　　– 用最后一个元素代替根上元素<br>　　– 向下调整<br><br><center><img src="/source/joyoi/tyvj-3179/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzE3OS9wcm9ibGVtc19pbWFnZXMvMTUwMC8yLmJtcA==.bmp"></img></center><br><br><br>　&#8226; 首先选取当前结点p的较小儿子，如果比p大, 调整停止；否则交换p和儿子, 继续调整<br><br><center><img src="/source/joyoi/tyvj-3179/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzE3OS9wcm9ibGVtc19pbWFnZXMvMTUwMC8zLmJtcA==.bmp"></img></center><br><br><br>插入元素和向上调整<br>　&#8226; 插入元素是先添加到末尾, 再向上调整<br>　&#8226; 向上调整: 比较当前结点p和父亲, 如果父亲比p小，停止; 否则交换父亲和p, 继续调整<br><br>堆的建立（堆的构造）<br>　　1、自底向上堆构造算法：<br>　　在初始化一棵包含几个节点的完全二叉树时，按给定的顺序来效置键；然后按照下面的方法对树进行“堆化”（如下图）从最后的父母节点开始，到根为止，该算法检查这些节点的键是否满足父母优势要求。如果该节点不满足，该算法把节点的键k和它子女的最大键进行交换，然后再检查在新位置上，k是不是满足父母优势要求。这个过程一直继续到对k的父母优势要求满足为止，对于以当前父母节点为根的子树，在完成了它“堆化”以后，该算法对于该节点的直接前趋进行同样的操作。在对树的根完成了这种操作以后，该算法就停止了。     <br><br><center><img src="/source/joyoi/tyvj-3179/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzE3OS9wcm9ibGVtc19pbWFnZXMvMTUwMC81LmJtcA==.bmp"></img></center><br>                                <br>　　2、自顶向下堆构造算法：<br>　　通过把新的键连续插入预先构造好的堆，来构造一个新堆，如何把一个新的键k插入到堆中呢？首先，把一个包含键k的新节点附加在当前堆的最后一个叶子后面，然后按照下面的方法把k筛选到它的适当位置，拿k和它父母的键作比较，如果后者大于等于k，算法停止；否则，交换这两个键并把k和它的新父母做比较。这种交换一直持续到k不大于它的最后一个父母，或者是达到了树的根为止（如下图）。在这个算法中，我们也可以把一个空节点向上筛选，直到达到合适的位置，才把k的值赋予它。<br><br><center><img src="/source/joyoi/tyvj-3179/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzE3OS9wcm9ibGVtc19pbWFnZXMvMTUwMC82LmJtcA==.bmp"></img></center><br>  <br>　　显然，这个插入操作所需的键值比较次数不可能超过堆的高度。因为包含几个节点的堆的高度大约是log2n所以插入的时间效率属于o（logn）。<br><br>删除堆中某个元素（不一定是堆顶元素）<br>　　1、以堆中最后一个元素取代被删除元素留下的空位（此举确保堆首先是一个完全二叉树）。<br>　　2、堆调整（堆化）。<br><br>时间复杂度分析<br>　&#8226; 向上调整/向下调整<br>　　– 每层是常数级别, 共logn层, 因此为：O(logn)<br>　&#8226; 插入/删除<br>　　– 只调用一次向上或向下调整, 因此都是：O(logn)<br>　&#8226; 建堆<br>　　– 高度为h的结点有n/2h+1个,总时间为：O(n*logn)<br><br>【堆，这种数据结构适合解决何种类型的问题？】<br>　　？？？........<br>　　D$#@&(<):>M"|{_#!@SAQ$&GBD^KFG(*&$#$BK}{?<:>"X~@^<br><br><br>＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝<br><br><br>【堆排序实践】<br><br>　　输入n个整数（ n <= 10^5），按从大到小排序后输出。<br>　　操作步骤：<br>　　　1) 建立堆。（直接在待排序数据A[]上建立最大堆）<br>　　　2) 重复调整堆。取出堆首元素（根元素），交换至堆尾部，堆容量减1，继续调整。<br></p> 

 
 # 输入格式 
<p>
　　二行，第一行，一个整数值n（ n <= 10^5 ）；第二行，n个整数，每个整数均小于2^31，每个整数间有一个空格间隔。</p> 

 
 # 输出格式 
<p>
　　一行，排好序（从大到小的顺序！！）的n个数据，每个数据间用一个空格间隔。<br></p> 

 
 # 提示 
<p>
优秀范例代码展示（构架清晰、代码简洁、高效！）<br><br><center><img src="/source/joyoi/tyvj-3179/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzE3OS9wcm9ibGVtc19pbWFnZXMvMTUwMC80LmJtcA==.bmp"></img></center><br></p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>4
4 5 2 897</td><td>897 5 4 2</td></tr></table>
