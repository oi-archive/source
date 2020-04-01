
# Description

<div class="content"><div>奶牛Bessie令人惊讶地精通计算机。她在牛棚的电脑里用一组文件夹储存了她所有珍贵的文件，比如：</div>
<div>bessie/</div>
<div>  folder1/</div>
<div>    file1</div>
<div>    folder2/</div>
<div>      file2</div>
<div>  folder3/</div>
<div>    file3</div>
<div>  file4</div>
<div></div>
<div>只有一个“顶层”的文件夹，叫做bessie。</div>
<div>Bessie可以浏览任何一个她想要访问的文件夹。从一个给定的文件夹，每一个文件都可以通过一个“相对路径”被引用。</div>
<div>在一个相对路径中，符号“..”指的是上级目录。如果Bessie在folder2中，她可以按下列路径引用这四个文件：</div>
<div></div>
<div>../file1</div>
<div>file2</div>
<div>../../folder3/file3</div>
<div>../../file4</div>
<div></div>
<div>Bessie想要选择一个文件夹，使得从该文件夹出发，对所有文件的相对路径的长度之和最小。</div></div>

# Input

<div class="content"><div>第一行包含一个整数N（2≤N≤100,000），为所有文件和文件夹的总数量。</div>
<div>为了便于输入，每个对象（文件或文件夹）被赋予一个唯一的1至N之间的ID，其中ID 1指的是顶层文件夹。</div>
<div>接下来有N行。每行的第一项是一个文件或是文件夹的名称。名称仅包含小写字母a-z和数字0-9，长度至多为16个字符。</div>
<div>名称之后是一个整数m。</div>
<div>如果m为0，则该对象是一个文件。</div>
<div>如果m&gt;0，则该对象是一个文件夹，并且该文件夹下共有m个文件或文件夹。</div>
<div>在m之后有m个整数，为该文件夹下的对象的ID。</div></div>

# Output

<div class="content"><div>输出所有文件的相对路径的长度之和的最小值。注意这个值可能超过32位整数的表示范围。</div></div>

# Sample Input

<div class="content"><span class="sampledata">8<br/>
bessie 3 2 6 8<br/>
folder1 2 3 4<br/>
file1 0<br/>
folder2 1 5<br/>
file2 0<br/>
folder3 1 7<br/>
file3 0<br/>
file4 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">42<br/>
<br/>
这个输入样例描述了上面给出的样例目录结构。<br/>
最优解是选择folder1。从这个文件夹出发，相对路径分别为：<br/>
file1<br/>
folder2/file2<br/>
../folder3/file3<br/>
../file4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

