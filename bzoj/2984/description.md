
# Description

<div class="content"><div style="clear: both; table-layout: fixed; margin: 10px 30px; overflow: auto; word-break: break-all; white-space: normal; text-align: left">给一条长为N~10^18的纸带，从左到右每个整数的位置标号为0..N，接下来有K~1W个操作，每次选取位置X，将整条纸带在X处对折。如果X是边缘则什么也不做。问最后纸带长度。</div></div>

# Input

<div class="content"></div>

# Output

<div class="content"></div>

# Sample Input

<div class="content"><span class="sampledata">9 5 <br/>
5 9 2 8 3 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p><p>The segment names look as follows:  <br/><br/>
Starting situation: {0 1 2 3 4 5 6 7 8 9}. <br/><br/>
Consecutively applying the folds:</p><br/>
<p>The segment names look as follows:  <br/><br/>
Starting situation: {0 1 2 3 4 5 6 7 8 9}. <br/><br/>
Consecutively applying the folds: <br/><br/>
--&gt; {0 (1;9) (2;8) (3;7) (4;6) 5} --&gt; {(1;9) (0;2;8) (3;7) (4;6) 5} --&gt; {(0;2;8) (1;3;7;9) (4;6) 5} --&gt; <br/><br/>
{(0;2;8) (1;3;7;9) (4;6) 5} --&gt; {(1;3;7;9) (0;2;4;6;8) 5}. <br/><br/>
 <br/><br/>
 </p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

