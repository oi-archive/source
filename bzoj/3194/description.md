
# Description

<div class="content"><div class="ptx" lang="en-US"><span style="font-size: medium">Gnaileux Iew is attracted in Bioinformatics recently. He reads papers day and night and devotes all his mind in studying. Today he is going to review the basic problem in Bioinformatics: DNA sequence alignment. His purpose is to find a simple and effective algorithm that performs global alignment with two highly similar DNA sequences. <br/>
<br/>
A DNA sequence is presented as a sequence of characters, which may be &#39;A&#39;, &#39;G&#39;, &#39;C&#39; or &#39;T&#39;. To align two DNA sequences, some gaps may be inserted to sequences so that two sequences have the same length. And then it is counted up for every pair of matched characters by a score matrix. Gnaileux Iew uses a minimal-score matrix hence the total score of alignment should be minimized. Following is the score matrix Gnaileux Iew uses: <br/>
</span><center><span style="font-size: medium"><img src="/source/bzoj/3194/img/aHR0cDovL3Bvai5vcmcvaW1hZ2VzLzI1MjBfMS5qcGc=.jpg" alt=""/></span></center><span style="font-size: medium"><br/>
For example, an alignment for DNA sequences &#34;AAGACG&#34; and &#34;CAGAGCTC&#34; may be: <br/>
-AAGA-C-G <br/>
CA-GAGCTC <br/>
The total score is 3+0+3+0+0+3+0+3+4=16. <br/>
<br/>
Gnaileux Iew is only interested in aligning highly similar sequences. Strictly speaking, |LCS(A,B)| * 2 / (|A |+ |B|) &gt;= 90%, where A and B are the sequences to align, and LCS(A,B) is the longest common subsequence of A and B. <br/>
</span></div>
<p></p></div>

# Input

<div class="content"><p class="pst"><span style="font-size: medium">contains two lines, which are the two DNA sequences to align. DNA sequences contain only characters &#39;A&#39;, &#39;G&#39;, &#39;C&#39; and &#39;T&#39;. The length of each sequence is not greater than 50000. <br/>
<br/>
You can assume that all the input cases are highly similar sequences. <br/>
</span></p></div>

# Output

<div class="content"><div class="ptx" lang="en-US"><span style="font-size: medium">For each test case print the minimal total score of alignment in one line.</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">AGTGCTGAAAGTTGCGCCAGTGAC<br/>
AGTGCTGAAGTTCGCCAGTTGACG<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">12<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

