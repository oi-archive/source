
# Content

There are several ways to encode an image. In this problem we will consider two representations of an image. We assume that the image consists of black and white pixels. There is at least one black pixel and all black pixels are connected with their sides. Coordinates of black pixels are not less than $1$ and not greater than $10$. An example of such an image is at the figure.

![title](/source/lutece/image-encoding/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNDA2LzIwMTQwODE0MTcyMjUzOTQ1Ny5wbmc=.png)

Both representations describe arrangement of black pixels only.
At the first representation we specify in the first line number of black pixels and coordinates of each black pixel in the following lines. Pixels are listed in order of increasing $X$. In case of equality of $X$ they are listed in order of increasing $Y$. Image at the figure is encoded as follows:
```
6
2 3
2 4
3 3
3 4
4 2
4 3
```

At the second representation we specify in the first line coordinates of the lowest left black pixel. Each of the following lines contains a descri_ption of neighbors for one of the pixels. At first, neighbors of the lowest left pixel are specified, then neighbors of its first neighbor (if it exists) are specified, then neighbors of its second neighbor (if it also exists) follow. When all its neighbors are described the descri_ption of the neighbors of its first neighbor follows. The descri_ption of the neighbors of its second neighbor follows then and so on.
Each descri_ptive line contains at most one letter for each neighbor: $R$ for the right, $T$ for the top, $L$ for the left, $B$ for the bottom. If the neighbor was already specified it is not included into the descri_ptive line and vice-versa. Also there is only one descri_ptive line for each pixel. Neighbors are listed counter-clockwise starting with the right. Each descri_ptive line except the last ends with a comma. The last line ends with a full stop. Image at the figure is encoded as follows:
```
2 3
RT,
RT,
,
B,
,
.
```

There are no leading or tailing spaces in any representation. There is exactly one space between $X$ and $Y$ coordinates.

# Standard Input

Input contains multiple test cases.

Each case has one representation of the image will be given to your program in the input.

# Standard Output

For each case ,your program has to write other representation of the image to the output.

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
2 3
2 4
3 3
3 4
4 2
4 3</td><td>2 3
RT,
RT,
,
B,
,
.</td></tr></table>


# Constraints



# Note



# Source


