
# Description

<div class="content"><p>Byteasar likes to live risky. He runs with scissors, submits solutions to contest problems without testing on example inputs, and wants all his files to have path names that are exactly as long as the operating system allows (on Linux, for instance, this is 4095 characters).</p>
<div>When Byteasar is working on someone else&#39;s computer, it might turn out that not all of the files meet his criterion. In this case he tries to introduce symbolic links (symlinks) and use them for creating file paths. You are asked to figure out, for each file in the file system, whether Byteasar can introduce a single symbolic link (of length chosen by him in advance), so that this file can be referred to by a path name of length exactly k characters.</div>
<div>If a file of name file is contained in the chain of directories dir1, dir2, ..., dirj, then itsabsolute file path is /dir1/dir2/.../dirj/file. The root directory can be referred to as / and each file contained directly in this directory has the absolute path of the form /file. A symbolic link is a named shortcut to a directory, which can be placed in any directory in the file system. In this task symlinks to files are not allowed. Using a symlink, we can obtain alternative file paths. For example, if we introduced a symlink to / with name hello in /, then /dir/file,/hello/dir/file and /hello/hello/dir/file would all refer to the same file, but have different path name length. As another example, with a symlink to / with name hi in /dir, one could obtain file paths: /dir/file, /dir/hi/dir/file, /dir/hi/dir/hi/dir/file. Note that it is perfectly legal for symlinks to point upwards, downwards or sidewards in the file system hierarchy, and even back to the directory they are placed in. For the purpose of this problem, ./ or../ or // path components are not considered allowed in path names.</div></div>

# Input

<div class="content"><p>The first line of input contains three positive integers: n (the number of directories other than the root directory), m (the number of files), and k (the desired path name length). The root directory has number 0, and all the remaining directories are numbered 1 through n. Files are numbered 1 through m. The second line contains the length s of the introduced symlink name (we don&#39;t care about the name itself, and assume it will not collide with anything else in the file system).</p>
<div>After that follow n lines describing the directories (other than the root directory) that exist in the file system. The i-th of those lines describes the directory number i and consists of two integers: Pi and Li. They specify that the directory number i has a name of length Li and its parent directory (i.e. the directory in which the i-th directory is directly contained) has number Pi. It is guaranteed that Pi&lt;i.</div>
<div>Finally m lines follow with a description of the files in the file system. The j-th of those lines describes the file number j and consists of two integers: Pj and Lj. They specify that the file numberj has a name of length Lj and its parent directory has number Pj.</div>
<div>All files and directories will have names with positive length, and their absolute file paths will be at most k characters long.</div>
<div></div></div>

# Output

<div class="content"><p>Your program should output m lines, one for each file. The J-th line should contain one word, YESor NO, answering the question: is it possible, by introducing a symlink of length s, to create a path name of length exactly k which refers to the file number j?</p></div>

# Sample Input

<div class="content"><span class="sampledata">2 4 22<br/>
2<br/>
0 1<br/>
1 5<br/>
2 13<br/>
2 10<br/>
1 4<br/>
0 7<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">YES<br/>
YES<br/>
YES<br/>
NO<br/>
</span></div>

# Hint

<div class="content"><p></p><div>Explanation to the example: Let us refer to the symlink as LL, the directory names as a andbbbbb, and the file names as ccccccccccccc, dddddddddd, eeee and fffffff, respectively. The root directory contains the directory a and the file fffffff; the directory a contains the directory bbbbb and the file eeee; and finally the directory bbbbb contains the filesccccccccccccc and dddddddddd.</div><br/>
<div>/</div><br/>
<div>  |- a</div><br/>
<div>  |   |- bbbbb</div><br/>
<div>  |   |   |- ccccccccccccc</div><br/>
<div>  |   |   +- dddddddddd</div><br/>
<div>  |   +- eeee</div><br/>
<div>  +- fffffff</div><br/>
<div>  </div><br/>
<div>In the first case, the absolute file path /a/bbbbb/ccccccccccccc already has the desired length, so we don&#39;t even have to use the symlink. In the second case we can introduce the symlink /a/LL -&gt; /a, and refer to /a/LL/bbbbb/dddddddddd. In the third case, we should introduce the symlink /a/LL -&gt; /, and refer to /a/LL/a/LL/a/LL/a/eeee. In the fourth case we cannot reach the goal regardless of where we introduce the symlink.</div><br/>
<div><br/>
<div>1&lt;=K,S&lt;=1 000 000</div><br/>
<div>N,M&lt;=3000</div><br/>
<div>求译文!请发至lydsy2012@163.com</div><br/>
</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

