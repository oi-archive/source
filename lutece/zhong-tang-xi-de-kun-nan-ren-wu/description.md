
# Content

为了考察三澄美琴的聪明程度，中堂系给三澄美琴出了一道题

<img src="/source/lutece/zhong-tang-xi-de-kun-nan-ren-wu/img/aHR0cDovLzViMDk4OGU1OTUyMjUuY2RuLnNvaHVjcy5jb20vaW1hZ2VzLzIwMTgwMzI5LzA2MWIyNmI3YjgwMDQ5ZTY5MzE0MmEzZTIyZjdkM2Q4LmpwZWc=.jpeg" width = "400" />

给定 $n$ 个整数$A_i$ ，可以确定$n$个 $B_i$

<math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
  <msub>
    <mi>B</mi>
    <mi>i</mi>
  </msub>
  <mo>=</mo>
  <munderover>
    <mo>&#x2211;<!-- ∑ --></mo>
    <mrow class="MJX-TeXAtom-ORD">
      <mi>j</mi>
      <mo>=</mo>
      <mi>i</mi>
    </mrow>
    <mi>n</mi>
  </munderover>
  <msub>
    <mi>A</mi>
    <mi>j</mi>
  </msub>
</math>
定义<math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
  <mi>f</mi>
  <mo stretchy="false">(</mo>
  <mi>i</mi>
  <mo>,</mo>
  <mi>j</mi>
  <mo stretchy="false">)</mo>
  <mo>=</mo>
  <mrow>
    <mo>{</mo>
    <mtable rowspacing="4pt" columnspacing="1em">
      <mtr>
        <mtd>
          <mn>0</mn>
        </mtd>
        <mtd />
        <mtd>
          <mo stretchy="false">(</mo>
          <mi>i</mi>
          <mo>,</mo>
          <mi>j</mi>
          <mo stretchy="false">)</mo>
          <mo>=</mo>
          <mo stretchy="false">(</mo>
          <mn>1</mn>
          <mo>,</mo>
          <mn>1</mn>
          <mo stretchy="false">)</mo>
        </mtd>
      </mtr>
      <mtr>
        <mtd>
          <mi>m</mi>
          <mi>i</mi>
          <mi>n</mi>
          <mo stretchy="false">(</mo>
          <mi>f</mi>
          <mo stretchy="false">(</mo>
          <mi>i</mi>
          <mo>&#x2212;<!-- − --></mo>
          <mn>1</mn>
          <mo>,</mo>
          <mi>j</mi>
          <mo>+</mo>
          <mn>1</mn>
          <mo stretchy="false">)</mo>
          <mo>,</mo>
          <mi>f</mi>
          <mo stretchy="false">(</mo>
          <mi>i</mi>
          <mo>,</mo>
          <mo fence="false" stretchy="false">&#x2308;<!-- ⌈ --></mo>
          <mfrac>
            <mi>j</mi>
            <mn>2</mn>
          </mfrac>
          <mo fence="false" stretchy="false">&#x2309;<!-- ⌉ --></mo>
          <mo stretchy="false">)</mo>
          <mo>+</mo>
          <msub>
            <mi>B</mi>
            <mi>i</mi>
          </msub>
          <mo stretchy="false">)</mo>
        </mtd>
        <mtd />
        <mtd>
          <mi>i</mi>
          <mo>,</mo>
          <mi>j</mi>
          <mo>&#x2208;<!-- ∈ --></mo>
          <mo stretchy="false">[</mo>
          <mn>1</mn>
          <mo>,</mo>
          <mi>n</mi>
          <mo stretchy="false">]</mo>
          <mo>,</mo>
          <mtext>&#xA0;</mtext>
          <mo stretchy="false">(</mo>
          <mi>i</mi>
          <mo>,</mo>
          <mi>j</mi>
          <mo stretchy="false">)</mo>
          <mo>&#x2260;<!-- ≠ --></mo>
          <mo stretchy="false">(</mo>
          <mn>1</mn>
          <mo>,</mo>
          <mn>1</mn>
          <mo stretchy="false">)</mo>
        </mtd>
      </mtr>
      <mtr>
        <mtd>
          <msup>
            <mn>10</mn>
            <mrow class="MJX-TeXAtom-ORD">
              <mn>11037</mn>
            </mrow>
          </msup>
        </mtd>
        <mtd />
        <mtd>
          <mi>o</mi>
          <mi>t</mi>
          <mi>h</mi>
          <mi>e</mi>
          <mi>r</mi>
          <mi>w</mi>
          <mi>i</mi>
          <mi>s</mi>
          <mi>e</mi>
        </mtd>
      </mtr>
    </mtable>
    <mo fence="true" stretchy="true" symmetric="true"></mo>
  </mrow>
</math>
求$f(n,1)$

# Standard Input

共有$t$组数据
$t\le 100,n\le 1e5$, 总共的$N\le 1e5,1\le A_i\le 1e4$, $A_{i+1} \le A_i$

# Standard Output

输出$f(n,1)$

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>3
3
1 1 1
5
28 26 25 24 1
10
996 901 413 331 259 241 226 209 139 49</td><td>5
233
11037</td></tr></table>


# Constraints



# Note



# Source


