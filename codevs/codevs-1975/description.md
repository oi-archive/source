<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>化学方程式是个很烦人的东西, 不仅背起来很麻烦, 连配平都是很麻烦的事情.</span></p>
<p><span>举例说, 铜和浓硝酸生成硝酸铜, 水和二氧化氮. 铜的化学式是Cu, 硝酸是HNO<sub>3</sub>, 硝酸铜是Cu(NO<sub>3</sub>)<sub>2</sub>, 二氧化氮是NO<sub>2</sub>, 水是H<sub>2</sub>O.</span></p>
<p><span>则这个式子简单写起来就是Cu+HNO<sub>3</sub>→Cu(NO<sub>3</sub>)<sub>2</sub>+NO<sub>2</sub>↑+H<sub>2</sub>O.</span></p>
<p><span>但是仔细观察可以看到, 硝酸根在反应前只有一个, 但是反应后却出现了两个, 而且反应前氢原子只有一个, 而反应后氢原子却有两个. 所以为了客观描述, 我们需要在两侧加上系数, 使得反应前后原子总数不变.</span></p>
<p><span>加上系数之后是Cu+4HNO<sub>3</sub>=Cu(NO<sub>3</sub>)<sub>2</sub>+2NO<sub>2</sub>↑+2H<sub>2</sub>O.</span></p>
<p><span>这个算是个比较好配平的式子, 如果若是铜和稀硝酸呢? 已知铜和稀硝酸生成硝酸铜, 水和一氧化氮. 铜的化学式是Cu, 硝酸是HNO<sub>3</sub>, 硝酸铜是Cu(NO<sub>3</sub>)<sub>2</sub>, 一氧化氮是NO, 水是H<sub>2</sub>O. 未配平就是Cu+HNO<sub>3</sub>→Cu(NO<sub>3</sub>)<sub>2</sub>+NO↑+H<sub>2</sub>O.</span></p>
<p><span>然后配平之后就是3Cu+8HNO<sub>3</sub>=3Cu(NO<sub>3</sub>)<sub>2</sub>+2NO↑+4H<sub>2</sub>O.</span></p>
<p><span>现在请你给一个化学方程式进行配平, 如果无法配平, 请输出“Error”.</span></p>
<p><span>注意, 一个方程式有无限种配平的可能性, 要求输出时全部系数的最小公因数为1.</span></p>
<p><span>题目保证有机化合物会写成最简式, 例如乙醇不会写成C<sub>2</sub>H<sub>5</sub>OH而会写成C<sub>2</sub>H<sub>6</sub>O, 但是像碱式碳酸铜依然会写成Cu<sub>2</sub>CO<sub>3</sub>(OH)<sub>2</sub>而不会合并为Cu<sub>2</sub>CH<sub>2</sub>O<sub>5</sub>. 即原子团不会被拆开.</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    第1行为2个正整数N<sub>Rea</sub>和N<sub>Pro</sub>, 表示反应物的种类数和生成物的种类数.</p>
<p>    第2~N<sub>Rea</sub>+1行每行包含1个字符串. 第i行表示每种反应物的化学式Rea<sub>i</sub>, 其中只可能包含大写或者小写英文字母, 括号和数字. 保证第一个字符一定是字母, 如果某个元素代表的字母后面包括一个数字则表示有该数字个的该元素, 如果括号后面出现数字则表示该离子团或者官能团有该字母个.</p>
<p>    第N<sub>Rea</sub>+2~N<sub>Rea</sub>+N<sub>Pro</sub>+1行行每行包含有1个字符串. 第i行的字符串表示该生成物的化学式Pro<sub>i</sub>.</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; 1个完整的字符串, 代表化学方程式, 无需添加反应条件, 中间使用西文半角等号. 中间的各个物质按照输入顺序输出.</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>【输入样例1】</span><br><span>2 3</span><br><span>Cu</span><br><span>HNO3</span><br><span>Cu(NO3)2</span><br><span>NO</span><br><span>H2O</span><br><span>【输入样例2】</span><br><span>4 3</span><br><span>H2S</span><br><span>K2Cr2O7</span><br><span>H2SO4</span><br><span>Cr2(SO4)3</span><br><span>K2SO4</span><br><span>S</span><br><span>H2O</span><br><span>【输入样例3】</span><br><span>1 2</span><br><span>H2O2</span><br><span>H2O</span><br><span>H2</span><br><span>【输入样例4】</span><br><span>1 3</span><br><span>KMnO4</span><br><span>K2MnO4</span><br><span>MnO2</span><br><span>O2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>【输出样例1】</span><br><span>3Cu+8HNO3=3Cu(NO3)2+2NO+4H2O</span><br><span>【输出样例2】</span><br><span>3H2S+K2Cr2O7+4H2SO4=Cr2(SO4)3+K2SO4+3S+7H2O</span><br><span>【输出样例3】</span><br><span>Error</span><br><span>【输出样例4】</span><br><span>2KMnO4=K2MnO4+MnO2+O2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>1≤NRea, NPro≤100; 1≤Length(Reai)≤20.</span><br><span>题目不保证数据中的化学反应一定可以发生或者符合客观事实.</span><br><span>题目中涉及的化学元素有:</span><br><span>H, He, Li, Be, B, C, N, O, F, Ne, Na, Mg, Al, Si, P, S, Cl, Ar, K, Ca, </span><br><span>Sc, Ti, V, Cr, Mn, Fe, Co, Ni, Cu, Zn, Ga, Ge, As, Se, Br, Kr, Rb, Sr, Y, Zr, </span><br><span>Nb, Mo, Tc, Ru, Rh, Pd, Ag, Cd, In, Sn, Sb, Te, I, Xe, Cs, Ba, La, Ce, Pr, Nd, </span><br><span>Pm, Sm, Eu, Gd, Tb, Dy, Ho, Er, Tm, Yb, Lu, Hf, Ta, W, Re, Os, Ir, Pt, Au, Hg, </span><br><span>Tl, Pb, Bi, Po, At, Rn, Fr, Ra, Ac, Th, Pa, U, Np, Pu, Am, Cm, Bk, Cf, Es, Fm, </span><br><span>Md, No, Lr, Rf, Db, Sg, Bh, Hs, Mt, Ds, Rg, Cn.</span></p>
</div>
</div>