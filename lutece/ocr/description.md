
# Content

As everyone knows, `OCR` (Optical Character Recognition) is widely used in automatic character entering, hands writing input and so on. `OCR` is also a popular research subject, which involved `NN` (Neural Network), `AI` (Artificial Intelligence) and even `ISP` (Image Signal Processing).

Hysramp seems interested in the method to grab the valid characters in a digital image. To simplify the problem, we assume that the input images are given by a matrix of digits. Zeros represent white (transparent) while non-zeros are colors to make up the characters. However, the image may be noised by some isolated colored pixels. To filter the noise, Hysramp developed an amateur algorithm that erase the connected-region whose pixel-area less than or equal to a specified threshold value. More detailed, each two pixel is said to be connected if one is located at the nearest $8$(up, down, left right, up-left, up-right, down-left, down-right) pixels of another. And the pixel-area of a connected region is the number of colored pixels, not the sum of the digits!

Here comes the problem, Hysramp ask you to peek out all the valid character sub-image after filtered the noise. The processed sub-image will be matrixes contain only necessary pixels, which means, it should be least size to contain the peeked characters. Moreover, please refer to the sample.

Note that any pixels in one vertical column must belong to one valid character. And each character is isolated with at least one all-zero column.

# Standard Input

The input file consist several test case. The first line of the input contains one integer $T$($T \leq 10$), which indicate the number of test cases. Following each test case will be separated by a blank line.

For each test case, two integer $W$, $H$, $P$ ($0 < W, H \leq 500, 0 \leq P \leq 10$) will take the first line to indicate the width and height of the image and $P$ is the aforementioned threshold value. Following a matrix of digits described the image with $H$ lines, and each line has $W$ digits with no space between.

# Standard Output

For each test case, print the processed sub-images in the order of characters appear in given image from left to right. And `*` for colored pixels while `-` represents white (transparent) pixels. Each sub-image must be separate by a blank line and a blank line is also needed between test cases.

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
<tr><td>1
36 11 4
000000000000000000000000000100001000
010000100100100100011110000111111000
010000100010001000100001000100001000
010000100001010000100000000001000010
011111100000100000011110000001111110
010000100000100000000001000001000010
010100100000100000100001001111000000
010000100000100000011110001000100000
000000000000000000000000001111000000
000000000000000011000000001000100000
001000000000200000000000001111000000</td><td>*----*
*----*
*----*
******
*----*
*----*
*----*

*-----*
-*---*-
--*-*--
---*---
---*---
---*---
---*---

-****-
*----*
*-----
-****-
-----*
*----*
-****-

-*----*--
-******--
-*----*--
---*----*
---******
---*----*
****-----
*---*----
****-----
*---*----
****-----</td></tr></table>


# Constraints



# Note



# Source


