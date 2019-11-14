
# Content

You and your teammates from the anti-bomb squad of the local police have been called to defuse a bomb found in the only pub in town. Fearing the tragic consequences this might produce, you go to the scene as quickly as possible. After some research, you learn that the bad guys have created a tricky way to allow them to defuse the bomb at will. You find a remote control with a button that you can take to a safe place. You also find that it is possible to connect to the bomb through a wireless connection and retrieve an ASCII representation of a code every $2$ seconds. The bomb then gets defused if the button is pressed when the code is a number divisible by $6$. But you have to be careful. If you press the button when the ASCII representation of the code is not a number divisible by $6$ or has an invalid representation for any digit, the bomb will explode instead. You have to rely on your programming skills to write a program able to tell you if it is safe to press the button, before it blows out the pub (and the beer).

# Standard Input

The input consists of an ASCII representation of a code. This code has between $2$ and $8$ digits. Each digit is represented by $5$ rows and $3$ columns of characters, which can be either a space or a star character `*`. No other type of character (except for the new line character) will ever appear in the input. There is also one column of spaces (and only spaces) to separate each digit. After the last digit you will find a column of new line characters. Note that although every digit will always be of size $5 \times 3$, there is no guarantee it will represent a valid digit between $0$ and $9$ inclusive. The valid $5 \times 3$ representations for each digit are given below in Figure F.1.

```
### ### ### ### ### ### ### ### ### ###
***   * *** *** * * *** *** *** *** ***
* *   *   *   * * * *   *     * * * * *
* *   * *** *** *** *** ***   * *** ***
* *   * *     *   *   * * *   * * *   *
***   * *** ***   * *** ***   * *** ***
```

Figure F.1: The hash`#` characters on the top are there only to mark the $3$ columns used for a digit and are not part of the digits’ representation.

The code can have leading zeros, hence an ASCII representation of, for example, $00000076$ represents the number $76$. You may also safely assume that every valid code will correspond to a strictly positive number.

# Standard Output

Print one line with `BEER!!` if it is safe to press the button and defuse the bomb, and `BOOM!!` otherwise.

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
<tr><td>***   * * * *** *** *** ***
* *   * * *   *   *   * *
* *   * *** *** *** *** ***
* *   *   * *     * *   * *
***   *   * *** *** *** ***</td><td>BEER!!</td></tr><tr><td>*** ***   * *** ***   *
*   * *   * * *   *   *
*** * *   * *** ***   *
  * * *   *   * *     *
*** ***   * *** ***   *</td><td>BOOM!!</td></tr><tr><td>*** *** *** * * ***
  *   *   * * * * *
***   * *** *** ***
*     *   *   * * *
***   * ***   * ***</td><td>BEER!!</td></tr></table>


# Constraints



# Note



# Source


