
# Description

<div class="content"><p> Byteasar is a programmer who works on a revolutionary text editor. In the editor there are two types of operations: one type allows to edit text in the editor, and the other type allows to undopreviously performed operations. One of the innovative features of this editor is a multilevel undo operation. It works as follows. We say that a text editing operation is an operation of level 0. Anundo operation of level I (for i=1,2…) undoes the last operation of level at most i-1 which is not undone. For instance, an undo operation of level 1 can undo only editing operations, and an undo operation of level 2 can undo editing operations as well as undo operations of level 1 (but no undo operations of greater levels).</p>
<div>More formally, each of the already performed operations can be in two states: active or undone. Let x be one of the operations. Just after performing the operation x, it is in the state active. If x is an undo operation of level i, we find the most recent operation in state active of level at most i-1 (denote it by x1) and change the state of the operation x1 to undone. If x1 is also an undo operation, we must change to active the state of the operation which x1 had undone (say x2). We continue in the same manner: whenever the state of an undo operation xj which had previously undone some operation x(j+1) changes, we must also change the state of the operation x(j+1) (which, of course, may result in changing states of further operations). The whole chain of state modifications finishes when an editing operation is reached.</div>
<div>For simplicity, the current contents of text in the editor will be specified by a single integer s, called the editor state (equal to 0 at the beginning). Each editing operation specifies the editor state that it produces. The editor state depends on the last editing operation in the state active. Help Byteasar and write a program which keeps track of the editor state.</div>
<div>Let us see this in action: the following table shows some operations performed by Byteasar and the editor state after performing each of them. The symbol Es denotes an editing operation which changes the editor state to s, whereas the symbol Ui denotes an undo operation of level i.</div>
<div>Operation<span class="Apple-tab-span" style="white-space:pre">		</span>       E1<span class="Apple-tab-span" style="white-space:pre">	</span>E2<span class="Apple-tab-span" style="white-space:pre">	</span>E5<span class="Apple-tab-span" style="white-space:pre">	</span>U1<span class="Apple-tab-span" style="white-space:pre">	</span>U1<span class="Apple-tab-span" style="white-space:pre">	</span>U3<span class="Apple-tab-span" style="white-space:pre">	</span>E4<span class="Apple-tab-span" style="white-space:pre">	</span>U2<span class="Apple-tab-span" style="white-space:pre">	</span>U1<span class="Apple-tab-span" style="white-space:pre">	</span>U1<span class="Apple-tab-span" style="white-space:pre">	</span>E1</div>
<div>Editor state<span class="Apple-tab-span" style="white-space:pre">	</span>0<span class="Apple-tab-span" style="white-space:pre">	</span>1<span class="Apple-tab-span" style="white-space:pre">	</span>2<span class="Apple-tab-span" style="white-space:pre">	</span>5<span class="Apple-tab-span" style="white-space:pre">	</span>2<span class="Apple-tab-span" style="white-space:pre">	</span>1<span class="Apple-tab-span" style="white-space:pre">	</span>2<span class="Apple-tab-span" style="white-space:pre">	</span>4<span class="Apple-tab-span" style="white-space:pre">	</span>2<span class="Apple-tab-span" style="white-space:pre">	</span>1<span class="Apple-tab-span" style="white-space:pre">	</span>0<span class="Apple-tab-span" style="white-space:pre">	</span>1</div>
<div>First, Byteasar performed three editing operations. The editor state changed from 0 to 1, then to 2, and finally to 5. Next, he performed two undo operations of level 1, which undid the operations E5 and E2 (changing their state to undone). Thus the editor state was restored to 1. The following undo operation of level 3 undid the last operation U1 (changing its state to undone), consequently restoring the operation E2 (changing its state back to active). As a result the editor state changed once again to 2. Operation U2 undid the operation E4, operation U1 once again undid the restored operation E2, the last operation U1 undid the operation E1, and the final operation is E1.</div></div>

# Input

<div class="content"><p>The first line of the input contains a positive integer n, specifying the number of operations performed by Byteasar. The next n lines contain descriptions of operations, one per line, each being an integer Ai(-n&lt;=Ai&lt;=N,Ai&lt;&gt;0) ). If Ai&gt;0, then it specifies an editing operation which modifies the editor state to Ai. If Ai&lt;0, then it specifies an undo operation of level -Ai. You can assume that for every undo operation there will be some operation in the state active of smaller level to undo.</p></div>

# Output

<div class="content"><p>Your program should output n lines. The i-th line should contain one integer specifying the editor state after performing the first i operations from the input.</p></div>

# Sample Input

<div class="content"><span class="sampledata">11<br/>
1<br/>
2<br/>
5<br/>
-1<br/>
-1<br/>
-3<br/>
4<br/>
-2<br/>
-1<br/>
-1<br/>
1</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2<br/>
5<br/>
2<br/>
1<br/>
2<br/>
4<br/>
2<br/>
1<br/>
0<br/>
1</span></div>

# Hint

<div class="content"><p></p><p> N&lt;=300 000</p><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

