
# Description

<div class="content"><p><span style="font-size: medium">The N (2 &lt;= N &lt;= 10,000) cows are so excited: it&#39;s prom night! They are dressed in their finest gowns, complete with corsages and new shoes. They know that tonight they will each try to perform the Round Dance. Only cows can perform the Round Dance which requires a set of ropes and a circular stock tank. To begin, the cows line up around a circular stock tank and number themselves in clockwise order consecutively from 1..N. Each cow faces the tank so she can see the other dancers. They then acquire a total of M (2 &lt;= M &lt;= 50,000) ropes all of which are distributed to the cows who hold them in their hooves. Each cow hopes to be given one or more ropes to hold in both her left and right hooves; some cows might be disappointed. For the Round Dance to succeed for any given cow (say, Bessie), the ropes that she holds must be configured just right. To know if Bessie&#39;s dance is successful, one must examine the set of cows holding the other ends of her ropes (if she has any), along with the cows holding the other ends of any ropes they hold, etc. When Bessie dances clockwise around the tank, she must instantly pull all the other cows in her group around clockwise, too. Likewise, if she dances the other way, she must instantly pull the entire group counterclockwise (anti-clockwise in British English). Of course, if the ropes are not properly distributed then a set of cows might not form a proper dance group and thus can not succeed at the Round Dance. One way this happens is when only one rope connects two cows. One cow could pull the other in one direction, but could not pull the other direction (since pushing ropes is well-known to be fruitless). Note that the cows must Dance in lock-step: a dangling cow (perhaps with just one rope) that is eventually pulled along disqualifies a group from properly performing the Round Dance since she is not immediately pulled into lockstep with the rest. Given the ropes and their distribution to cows, how many groups of cows can properly perform the Round Dance? Note that a set of ropes and cows might wrap many times around the stock tank. </span></p>
<div><span style="font-size: medium">    约翰的N(2≤N≤10000)只奶牛非常兴奋，因为这是舞会之夜！她们穿上礼服和新鞋子，别上鲜花，她们要表演圆舞．</span></div>
<div><span style="font-size: medium">    只有奶牛才能表演这种圆舞．圆舞需要一些绳索和一个圆形的水池．奶牛们围在池边站好，</span><span style="font-size: medium">顺时针顺序由1到N编号．每只奶牛都面对水池，这样她就能看到其他的每一只奶牛．</span><span style="font-size: medium">为了跳这种圆舞，她们找了M(2≤M≤50000)条绳索．若干只奶牛的蹄上握着绳索的一端，</span><span style="font-size: medium">绳索沿顺时针方绕过水池，另一端则捆在另一些奶牛身上．这样，一些奶牛就可以牵引另一些奶牛．有的奶牛可能握有很多绳索，也有的奶牛可能一条绳索都没有</span><span style="font-size: medium">对于一只奶牛，比如说贝茜，她的圆舞跳得是否成功，可以这样检验：沿着她牵引的绳索，</span><span style="font-size: medium">找到她牵引的奶牛，再沿着这只奶牛牵引的绳索，又找到一只被牵引的奶牛，如此下去，若最终能回到贝茜，则她的圆舞跳得成功，因为这一个环上的奶牛可以逆时针牵引而跳起旋转的圜舞．如果这样的检验无法完成，那她的圆舞是不成功的．</span></div>
<div><span style="font-size: medium">    如果两只成功跳圆舞的奶牛有绳索相连，那她们可以同属一个组合．</span></div>
<div><span style="font-size: medium">    给出每一条绳索的描述，请找出，成功跳了圆舞的奶牛有多少个组合？</span></div></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: Two space-separated integers: N and M </span></p>
<p><span style="font-size: medium">* Lines 2..M+1: Each line contains two space-separated integers A and B that describe a rope from cow A to cow B in the clockwise direction.</span></p>
<div><span style="font-size: medium">    第1行输入N和M，接下来M行每行两个整数A和B，表示A牵引着B.</span></div></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: A single line with a single integer that is the number of groups successfully dancing the Round Dance. </span></p>
<div><span style="font-size: medium">    成功跳圆舞的奶牛组合数．</span></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 4<br/>
2 4<br/>
3 5<br/>
1 2<br/>
4 1<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
ASCII art for Round Dancing is challenging. Nevertheless, here is a<br/>
representation of the cows around the stock tank:<br/>
       _1___<br/>
      /**** \<br/>
   5 /****** 2<br/>
  / /**TANK**|<br/>
  \ \********/<br/>
   \ \******/  3<br/>
    \ 4____/  /<br/>
     \_______/<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">2</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">4</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">这三只奶牛同属一个成功跳了圆舞的组合．而</span><span lang="EN-US"><font face="Times New Roman">3</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">5</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">两只奶牛没有跳成功的圆舞</span></span></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

