
# Description

<div class="content"><p>输入两个数字，输出它们之和</p></div>

# Input

<div class="content"><p>一行两个数字A,B(0&lt;=A,B&lt;100)</p>
<p></p></div>

# Output

<div class="content"><p>输出这两个数字之和</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">3</span></div>

# Hint

<div class="content"><p></p><p>Q: Where are the input and the output? A: Your program shall always <font color="#ff0000">read input from stdin (Standard Input) and write output to stdout (Standard Output)</font>. For example, you can use &#39;scanf&#39; in C or &#39;cin&#39; in C++ to read from stdin, and use &#39;printf&#39; in C or &#39;cout&#39; in C++ to write to stdout. You <font color="#ff0000">shall not output any extra data</font> to standard output other than that required by the problem, otherwise you will get a &#34;Wrong Answer&#34;. User programs are not allowed to open and read from/write to files. You will get a &#34;Runtime Error&#34; or a &#34;Wrong Answer&#34; if you try to do so. Here is a sample solution for problem 1000 using C++/G++:</p><br/>
<pre><br/>
#include <iostream></iostream><br/>
using namespace std;<br/>
int  main()<br/>
{<br/>
    int a,b;<br/>
    cin &gt;&gt; a &gt;&gt; b;<br/>
    cout &lt;&lt; a+b &lt;&lt; endl;<br/>
    return 0;<br/>
}</pre><br/>
<p>It&#39;s important that the return type of main() must be int when you use G++/GCC,or you may get compile error. Here is a sample solution for problem 1000 using C/GCC:</p><br/>
<pre><br/>
#include <stdio.h></stdio.h><br/>
<br/>
int main()<br/>
{<br/>
    int a,b;<br/>
    scanf(&#34;%d %d&#34;,&amp;a, &amp;b);<br/>
    printf(&#34;%d\n&#34;,a+b);<br/>
    return 0;<br/>
}</pre><br/>
<p>Here is a sample solution for problem 1000 using PASCAL:</p><br/>
<pre><br/>
program p1000(Input,Output); <br/>
var <br/>
  a,b:Integer; <br/>
begin <br/>
   Readln(a,b); <br/>
   Writeln(a+b); <br/>
end.</pre><br/>
<p>Here is a sample solution for problem 1000 using JAVA: Now java compiler is jdk 1.5, next is program for 1000</p><br/>
<pre><br/>
import java.io.*;<br/>
import java.util.*;<br/>
public class Main<br/>
{<br/>
            public static void main(String args[]) throws Exception<br/>
            {<br/>
                    Scanner cin=new Scanner(System.in);<br/>
                    int a=cin.nextInt(),b=cin.nextInt();<br/>
                    System.out.println(a+b);<br/>
            }<br/>
}</pre><br/>
<p>Old program for jdk 1.4</p><br/>
<pre><br/>
import java.io.*;<br/>
import java.util.*;<br/>
<br/>
public class Main<br/>
{<br/>
    public static void main (String args[]) throws Exception<br/>
    {<br/>
        BufferedReader stdin = <br/>
            new BufferedReader(<br/>
                new InputStreamReader(System.in));<br/>
<br/>
        String line = stdin.readLine();<br/>
        StringTokenizer st = new StringTokenizer(line);<br/>
        int a = Integer.parseInt(st.nextToken());<br/>
        int b = Integer.parseInt(st.nextToken());<br/>
        System.out.println(a+b);<br/>
    }<br/>
}</pre><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

