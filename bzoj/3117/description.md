
# Description

<div class="content"><div class="ptx" lang="en-US">
<div>内存是计算机重要的资源之一，程序运行的过程中必须对内存进行分配。 </div>
<div>经典的内存分配过程是这样进行的： </div>
<div>1. 内存以内存单元为基本单位，每个内存单元用一个固定的整数作为标识，称为地址。地址从0开始连续排列，地</div>
<div>址相邻的内存单元被认为是逻辑上连续的。我们把从地址i开始的s个连续的内存单元称为首地址为i长度为s的地址</div>
<div>片。 </div>
<div>2. 运行过程中有若干进程需要占用内存，对于每个进程有一个申请时刻T，需要内存单元数M及运行时间P。在运行</div>
<div>时间P内（即T时刻开始，T+P时刻结束），这M个被占用的内存单元不能再被其他进程使用。 </div>
<div>3、假设在T时刻有一个进程申请M个单元，且运行时间为P，则： </div>
<div>1. 若T时刻内存中存在长度为M的空闲地址片，则系统将这M个空闲单元分配给该进程。若存在多个长度为M个空闲</div>
<div>地址片，则系统将首地址最小的那个空闲地址片分配给该进程。</div>
<div>2. 如果T时刻不存在长度为M的空闲地址片，则该进程被放入一个等待队列。对于处于等待队列队头的进程，只要</div>
<div>在任一时刻，存在长度为M的空闲地址片，系统马上将该进程取出队列，并为它分配内存单元。注意，在进行内存</div>
<div>分配处理过程中，处于等待队列队头的进程的处理优先级最高，队列中的其它进程不能先于队头进程被处理。 </div>
<div>现在给出一系列描述进程的数据，请编写一程序模拟系统分配内存的过程。 </div>
</div></div>

# Input

<div class="content"><div class="ptx" lang="en-US">
<div>第一行是一个数N，表示总内存单元数（即地址范围从0到N-1）。</div>
<div>从第二行开始每行描述一个进程的三个整数T、M、P（M &lt;= N）。</div>
<div>最后一行用三个0表示结束。 </div>
<div>数据已按T从小到大排序。 </div>
<div>输入文件最多10000行，且所有数据都小于109。 </div>
<div>输入文件中同一行相邻两项之间用一个或多个空格隔开。</div>
</div></div>

# Output

<div class="content"><div class="ptx" lang="en-US"><span style="font-size: medium">包括2行。 <br/>
第一行是全部进程都运行完毕的时刻。 <br/>
第二行是被放入过等待队列的进程总数。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
1 3 10<br/>
2 4 3<br/>
3 4 4<br/>
4 1 4<br/>
5 3 4<br/>
0 0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">12<br/>
2</span></div>

# Hint

<div class="content"><p></p><p> <img src="/source/bzoj/3117/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwMy92djEuanBn.jpg" width="638" height="646" alt=""/></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

