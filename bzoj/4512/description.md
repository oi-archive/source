
# Description

<div class="content"><div>
<div>
<div>Farmer John decides to build a new fence around parts of his farm, but he keeps getting distracted a</div>
<div>nd ends up building the fence into a much stranger shape than he intended!Specifically, FJ starts at</div>
<div> position (0,0)and takes N steps, each moving one unit of distance north, south, east, or west. Each</div>
<div> step he takes, he lays a unit of fence behind him. For example, if his first step is to the north, </div>
<div>he adds a segment of fence from (0,0) to (0,1). FJ might re-visit points multiple times and he may e</div>
<div>ven lay the same segment of fence multiple times. His fence might even cross over itself if his path</div>
<div> cuts through a run of fencing he has already built.Needless to say, FJ is rather dismayed at the re</div>
<div>sult after he completes the fence. In particular, he notices that it may be the case that he has now</div>
<div> partitioned off some areas of the farm from others, so that one can no longer walk from one region </div>
<div>to another without crossing a fence. FJ would like to add gates to his fences to fix this problem. A</div>
<div> gate can be added to any unit-length segment of fence he has built, allowing passage between the tw</div>
<div>o sides of this segment.Please determine the minimum number of gates FJ needs to build so that every</div>
<div> region of the farm is once again reachable from every other region.</div>
<div>给定一个包含N,S,E,W的移动序列。FJ初始在(0,0)，依次按照移动序列移动，并在移动过程中建设篱笆。如FJ在(0</div>
<div>,0)点，要向N移动，则FJ移动到(0,1)，并在(0,0)和(0,1)之间建一段篱笆。注意到这样建设出的篱笆可能自交，</div>
<div>把平面划分成若干区域。现在要拆除若干段篱笆，使平面连通。输出最少拆除的篱笆段数。1 ≤ N ≤ 1000</div>
</div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains N(1≤N≤1000). The next line contains a string of length N</div>
<div>describing FJ&#39;s path. Each character is either N (north), E (east), S (south), or W (west).</div>
<p></p></div>

# Output

<div class="content"><div>Write out a single integer giving the minimum number of gates FJ needs to build to restore complete connectivity to all regions of his farm. Note that the answer could be zero if the farm is connected to begin with.</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">14<br/>
NNNESWWWSSEEEE<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver鸣谢frank_c1提供翻译">Silver鸣谢frank_c1提供翻译</a></p></div>

