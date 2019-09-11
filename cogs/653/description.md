# 题目描述


<p><b>【问题描述</b>】</p>
<div>正如本题标题所言，你的任务是计算一些整数的和，真的很简单，对吧？错，实际并非如此，因为这里面有很多跟普通的加法不同的地方，比如操作符、操作数啦等等。请仔细阅读下面的细节： <br/>
首先，你要抛开普通的加法规则，来进行不带进位的加法运算，那意味着我们必须依照普通加法规则把两个整数相加，但是要忽略掉每一个地方的进位。举个例子，假如我们要把十进制的 55 和 76 相加，使用普通的加法规则得到的结果为 131 ；然而使用“不带进位的加法”规则所得到的结果为 21 ，两种运算的过程如下图 1.2.1 和 1.2.2 所示。 <br/>
 </div>
<table border="0" width="608" height="154">
    <tbody>
        <tr>
            <th width="28" scope="col"> </th>
            <th width="27" scope="col"> </th>
            <th width="35" scope="col">
            <div align="left"><strong>5</strong></div>
            </th>
            <th width="70" scope="col">
            <div align="left"><strong>5</strong></div>
            </th>
            <th width="39" scope="col">
            <div align="left"> </div>
            </th>
            <th width="33" scope="col">
            <div align="left"><strong>5</strong></div>
            </th>
            <th width="27" scope="col">
            <div align="left"><strong>5</strong> </div>
            </th>
            <th width="7" scope="col"> </th>
            <th width="17" scope="col"> </th>
            <th width="17" scope="col"> </th>
            <th width="17" scope="col"> </th>
            <th width="17" scope="col"> </th>
            <th width="26" scope="col"> </th>
        </tr>
        <tr>
            <td><strong>+</strong></td>
            <td> </td>
            <td>
            <div align="left"><strong>7</strong></div>
            </td>
            <td>
            <div align="left"><strong>6</strong></div>
            </td>
            <td>
            <div align="left"><strong>+</strong></div>
            </td>
            <td>
            <div align="left"><strong>7</strong></div>
            </td>
            <td>
            <div align="left"><strong>6</strong></div>
            </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr>
            <td colspan="4"><strong>-------------------------------</strong></td>
            <td> --------</td>
            <td> -------</td>
            <td>------ </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td colspan="4"> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr>
            <td> </td>
            <td> </td>
            <td><strong>1</strong></td>
            <td><strong>1</strong></td>
            <td> </td>
            <td> </td>
            <td> 1</td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr>
            <td><strong>+</strong></td>
            <td><strong>1</strong></td>
            <td><strong>2</strong></td>
            <td> </td>
            <td> +</td>
            <td> 2</td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr>
            <td colspan="4"><strong>--------------------------------</strong></td>
            <td> --------</td>
            <td> -------</td>
            <td>------</td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td colspan="4"> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr>
            <td> </td>
            <td><strong>1</strong></td>
            <td><strong>3</strong></td>
            <td><strong>1</strong></td>
            <td> </td>
            <td> 2</td>
            <td> 1</td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr>
            <td colspan="10">1．2．1 Usual Addition Figure</td>
            <td colspan="10">1．2．2 No Carry Addition</td>
        </tr>
    </tbody>
</table>
<div>其次，这种加法可以在 2 到 16 的任一种进制下运行，举例来说，给定两个十进制数 55 和 76 ，如果我们在十进制下进行这种不带进位的加法运算，他们的和为（ 21 ） 10 ，而在二进制下， 55 和 76 的二进制数分别表示为（ 110111 ） 2 和（ 1001100 ） 2 ，它们的和将为（ 1111011 ） 2 = （ 123 ） 10 。 <br/>
最后一点，给定的操作数不是单一的整数，而是一个整数段，正如我们所知，整数段 [x,y] 表示从 x 开始，以 y 结束的连续的整数，两个整数段 [x1,y1] 、 [x2,y2] 的和等于每一个整数段中所有的整数的和。（如果一个整数在两个段里均存在，它将被计算两次。） <br/>
现在我们可以结束这个问题的阐述了：给定一些基于 2 到 16 进制的整数段，你的任务是依照无进位的加法规则计算它们的和。</div>
<div>【输入格式】</div>
<div>输入文件包含若干个测试数据，第一行是一个整数 T(1 ≤ T ≤ 20) ，表示下面有 T 组测试数据，对于每一组测试数据，第一行有两个整数， N 和 M ， (1 ≤ N ≤ 100 ， 2 ≤ M ≤ 16) ， N 表示整数段的个数， M 表示所求的和的进制数，接下来有 N 行，每一行包含两个 32 位无符号位的整数， x 和 y ，表示整数段 [x,y] （ x,y 均为十进制数，且 x ≤ y ）。</div>
<div>【输出格式】</div>
<div>对于每一组测试数据，输出只有一行，包含一个 32 位无符号位的整数，为计算结果的十进制表示。 <br/>
 </div>
<div>【输入样例】</div>
<div>sumb.in</div>
<div>3 <br/>
2 10 <br/>
55 55 <br/>
76 76 <br/>
2 2 <br/>
55 55 <br/>
76 76 <br/>
3 2 <br/>
0 3 <br/>
8 15 <br/>
4 7</div>
<div><span>sumb.out</span></div>
<div><span>21 <br/>
123 <br/>
0 </span></div>
<p> </p>
