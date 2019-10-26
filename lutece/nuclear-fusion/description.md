
# Content

We have a reactor contains a set of $N$ atoms of some chemical elements. 

You are allowed to take any two different atoms and fuse a new one from them. That results in a new atom, whose number( its number in the periodic table of the chemical elements) is equal to the sum of the numbers of original atoms. The fusion operation can be performed several times.

We want to get $M$ new atoms by fusing atoms we have. It is not allowed to split an atom into several atoms. All the $N$ atoms must be used. Please find out whether it is possible.

# Standard Input

There are multiple test cases in the input.

For each test case, the first line of each test case contains two integers $N$ and $M$, indicating the number of atoms we have and the number of atoms we want to get.($1\leq N,M\leq 17$) 

The second line contains space-separated symbols of elements of $N$ atoms. The third line contains space-separated symbols of elements of $M$ atoms which need to be the result of the fusion. These atoms can be the same.

# Standard Output

If the task can be solved, print `YES` in a single line, else print `NO`.

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
<tr><td>10 3
Mn Co Li Mg C P F Zn Sc K
Sn Pt Y
2 1
H H
He
2 2
Bk Fm
Cf Es</td><td>YES
YES
NO</td></tr></table>


# Constraints



# Note

The first task can be solved because 
```
Mn+C+K->Sn
Co+Zn+Sc->Pt
Li+Mg+P+F->Y
```

The first $100$ atoms in the periodic table of the chemical elements:
```
"H","He","Li","Be","B","C","N","O","F","Ne",
"Na","Mg","Al","Si","P","S","Cl","Ar","K","Ca",
"Sc","Ti","V","Cr","Mn","Fe","Co","Ni","Cu",
"Zn","Ga","Ge","As","Se","Br","Kr","Rb","Sr",
"Y","Zr","Nb","Mo","Tc","Ru","Rh","Pd","Ag",
"Cd","In","Sn","Sb","Te","I","Xe","Cs","Ba",
"La","Ce","Pr","Nd","Pm","Sm","Eu","Gd",
"Tb","Dy","Ho","Er","Tm","Yb","Lu","Hf","Ta",
"W","Re","Os","Ir","Pt","Au","Hg","Tl","Pb",
"Bi","Po","At","Rn","Fr","Ra","Ac","Th","Pa",
"U","Np","Pu","Am","Cm","Bk","Cf","Es","Fm" 
```

All the atoms appear in this problem are in the table above.

# Source


