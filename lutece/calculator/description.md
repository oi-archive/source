
# Content

A simple $8$-digit electronic calculator contains the following buttons: `1234567890+-*/=`. It can be divided into the following categories: 

#####Digit: `1234567890`
You can input any number with digital buttons (ignore leading zero). Notice, the LED of calculator can only display $8$ digits. So when the number of digits large than eight, only the first eight digits will be retained. And when the number of one result"s digits large than eight, error occurs. 

#####Operator: `+-*/` 
For simplicity, all operations are integer operations. Some continuous operators, the last one is valid. When an operator button is pressed, the calculation before that will be completed. 

    Example of type 11+/2+
    Button 1 1 + / 2 +
    Display 1 11 11 11 2 5

#####Equal-sign: `=` 
If the second operand is missing, you can think it equal the first operand. More than one continuous equal-sign means repeat the operation. You can observe the following examples. 

    Example of type `11+*==` 
    Button 1 1 + * = = 
    Display 1 11 11 11 121 1331 

    Example of type "3==+5=" 
    Button 3 = = + 5 = 
    Display 3 3 3 3 5 8 

    Example of type "5=7=+8=" 
    Button 5 = 7 = + 8 = 
    Display 5 5 7 7 7 8 15

# Standard Input

The first line is number of test cases. After that, each case consists of one line, containing a string means pressed button. The length of string is less than $100$. There is no additional space.

# Standard Output

First output the case number. Then output the number of display in the same line. If there is any error occurs, just print `ERROR` please. Please follow the format of the sample output.

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
<tr><td>6 
11+/2+ 
11+*== 
3==+5= 
5=7=+8= 
99999999+1-1= 
1-99999999=</td><td>Case 1: 5 
Case 2: 1331 
Case 3: 8 
Case 4: 15 
Case 5: ERROR 
Case 6: -99999998</td></tr></table>


# Constraints



# Note



# Source


