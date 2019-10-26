
# Content

You and your friend Christian have decided to take a vacation year and travel all around the world to see magnificent places, meet wonderful people, and experience new cultures. Unfortunately, with different cultures come difficult differences. And the hardest differences engineers like you know of are unit differences. Why are people using miles, firkins, microfortnights, candlepowers, boisseaux, foes, pints, kWh and not to mention degrees Celsius when they instead would be much happier using the standard and beloved SI units of metres, kilograms, seconds, amperes, kelvins and candelas?

<table class="table">
<thead>
<tr><th>Quantity</th><th>Name</th><th>Symbol</th></tr>
</thead>
<tbody>
<tr><td>length</td><td>metre</td><td>$m$</td></tr>
<tr><td>time</td><td>second</td><td>$s$</td></tr>
<tr><td>mass</td><td>kilogram</td><td>$kg$</td></tr>
<tr><td>electric current</td><td>ampere</td><td>$A$</td></tr>
<tr><td>temperature</td><td>kelvin</td><td>$K$</td></tr>
<tr><td>luminous intensity</td><td>candela</td><td>$cd$</td></tr>
</tbody>
</table>

<p class="text-center"><b>Table 1: List of SI units</b></p>

In fact, you love the SI units so much that you refuse to use any other units. Derived units like the joule ($J$), the newton ($N$), and the ohm ($\Omega$) are perfectly expressible in their
equivalent SI units of $kg\ m^2 / s^2$, $kg\ m / s^2$, and $kg\ m^2 / s^3\ A^2$, respectively. So during
your travel, you record all units you come across, along with their definitions. Of course,some definitions are depending on other definitions, like $Pa = N / m^2$.

![title](/source/lutece/dimensions/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNzE4LzIwMTQwOTAxMTg0MzU0MzM2MzQucG5n.png)

With your definitions ready at hand, you don't have to put up with such nonsense as $60$ firkins / microfortnights or $63\ km / h$ anymore, since you can always convert them SI units. Even calculations like $100\ m + 1.3\ km$ and $7\ N \times 8$ become a breeze to you.


# Standard Input

The following syntax is given (`?` denotes "zero or one", `+` denotes "one or more", and `*` denotes "zero or more"):
* `power ::= { integer larger than 1 }`
* `unit ::= { upper or lower case English letter }+`
* `dimension ::= unit ['^' power]?`
* `size ::= {any floating-point number} [' ' dimension]* ['/' [' ' dimension]+]?`
* `operator ::= '+' OR '-' OR '*'`
* `expression ::= size ' ' operator ' ' size`
* `unit definition ::= unit ' = ' size`

All units have length less than $10$, and in a size, no units are repeated.

The first line of the input consists of a single integer $U$, the number of new units.

Then follow $U$ lines with new unit definitions. After the unit definitions follows a line with a single integer $N$, and then $N$ lines with either an expression or a size.

In the input, all powers are less than $5$, and all units are SI unit symbols or previously defined units.

$0 < U \le 100$

$0 < N \le 1000$

Units are case sensitive.

No lines are longer than $140$ characters.

No input, output or part of any computation have size of absolute value above $10^{100}$.

No input, output or part of any computation have unit exponents of absolute value above $10^6$.

No part of any computation will yield division by $0$.

**Please, output the value in Scientific notation, and round to $0.001$, i.e. you can use `%.3E` to output the value.**

# Standard Output

For each computation, output one line with the answer to the expression, or the size itself, converted to SI units. If the answer cannot be computed, output "Incompatible"(without the quotes). The answer should be formatted as a size, with the following clarifications:
* Keep the units on the correct side of the division sign, and for each side, the units must be written in orders given in the list:
`m, s, kg, A, K, cd`.
* Do not output a unit if its exponent is $0$, or its exponent if it is equal to $1$.
* Output one space between each unit and between units and the division sign, `\`.
* Do not output any spaces before or after the exponent sign, `^`.

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
<tr><td>4
km = 1000 m
h = 3600 s
J = 1 kg m^2 / s^2
X = 3 m^2 kg s / A K cd^4
4
100 m + 1.3 km
63 km / h
1E5 J * 0.003 h^2 / km^2
1 J - 2 X</td><td>1.400E+03 m
1.750E+01 m / s
3.888E+03 kg
Incompatible</td></tr></table>


# Constraints



# Note

Make sure that you are using `%.3E` to output your answer. For windows-users, your output for the first test case might look like `1.400E+003 m` instead of the sample output above, but that's OK, just submit and see your result.

# Source


