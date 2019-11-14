
# 题目描述

小牛拥有着一个$1\times n$的草场。这个草场比较的神奇，每一个草都有一个美味值。小牛比较的贪心，他会优先吃掉美味值较小的草。题目会给出一个$n\times n$的表格，代表着两两草之间的大小比较关系，如下图所示。($a$为该位置草的美味值并且保证这个图不会有冲突)

<div class="table-wrapper"><table>
    <thead>
    <tr>
    <th></th>
    <th><span class="mjpage"><svg xmlns:xlink="http://www.w3.org/1999/xlink" width="2.284ex" height="2.009ex" style="vertical-align: -0.671ex;" viewBox="0 -576.1 983.4 865.1" role="img" focusable="false" xmlns="http://www.w3.org/2000/svg" aria-labelledby="MathJax-SVG-5-Title">
<title id="MathJax-SVG-5-Title">a_1</title>
<defs aria-hidden="true">
<path stroke-width="1" id="E5-MJMATHI-61" d="M33 157Q33 258 109 349T280 441Q331 441 370 392Q386 422 416 422Q429 422 439 414T449 394Q449 381 412 234T374 68Q374 43 381 35T402 26Q411 27 422 35Q443 55 463 131Q469 151 473 152Q475 153 483 153H487Q506 153 506 144Q506 138 501 117T481 63T449 13Q436 0 417 -8Q409 -10 393 -10Q359 -10 336 5T306 36L300 51Q299 52 296 50Q294 48 292 46Q233 -10 172 -10Q117 -10 75 30T33 157ZM351 328Q351 334 346 350T323 385T277 405Q242 405 210 374T160 293Q131 214 119 129Q119 126 119 118T118 106Q118 61 136 44T179 26Q217 26 254 59T298 110Q300 114 325 217T351 328Z"></path>
<path stroke-width="1" id="E5-MJMAIN-31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path>
</defs>
<g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)" aria-hidden="true">
 <use xlink:href="#E5-MJMATHI-61" x="0" y="0"></use>
 <use transform="scale(0.707)" xlink:href="#E5-MJMAIN-31" x="748" y="-213"></use>
</g>
</svg></span></th>
    <th><span class="mjpage"><svg xmlns:xlink="http://www.w3.org/1999/xlink" width="2.284ex" height="2.009ex" style="vertical-align: -0.671ex;" viewBox="0 -576.1 983.4 865.1" role="img" focusable="false" xmlns="http://www.w3.org/2000/svg" aria-labelledby="MathJax-SVG-6-Title">
<title id="MathJax-SVG-6-Title">a_2</title>
<defs aria-hidden="true">
<path stroke-width="1" id="E6-MJMATHI-61" d="M33 157Q33 258 109 349T280 441Q331 441 370 392Q386 422 416 422Q429 422 439 414T449 394Q449 381 412 234T374 68Q374 43 381 35T402 26Q411 27 422 35Q443 55 463 131Q469 151 473 152Q475 153 483 153H487Q506 153 506 144Q506 138 501 117T481 63T449 13Q436 0 417 -8Q409 -10 393 -10Q359 -10 336 5T306 36L300 51Q299 52 296 50Q294 48 292 46Q233 -10 172 -10Q117 -10 75 30T33 157ZM351 328Q351 334 346 350T323 385T277 405Q242 405 210 374T160 293Q131 214 119 129Q119 126 119 118T118 106Q118 61 136 44T179 26Q217 26 254 59T298 110Q300 114 325 217T351 328Z"></path>
<path stroke-width="1" id="E6-MJMAIN-32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z"></path>
</defs>
<g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)" aria-hidden="true">
 <use xlink:href="#E6-MJMATHI-61" x="0" y="0"></use>
 <use transform="scale(0.707)" xlink:href="#E6-MJMAIN-32" x="748" y="-213"></use>
</g>
</svg></span></th>
    <th><span class="mjpage"><svg xmlns:xlink="http://www.w3.org/1999/xlink" width="2.284ex" height="2.009ex" style="vertical-align: -0.671ex;" viewBox="0 -576.1 983.4 865.1" role="img" focusable="false" xmlns="http://www.w3.org/2000/svg" aria-labelledby="MathJax-SVG-7-Title">
<title id="MathJax-SVG-7-Title">a_3</title>
<defs aria-hidden="true">
<path stroke-width="1" id="E7-MJMATHI-61" d="M33 157Q33 258 109 349T280 441Q331 441 370 392Q386 422 416 422Q429 422 439 414T449 394Q449 381 412 234T374 68Q374 43 381 35T402 26Q411 27 422 35Q443 55 463 131Q469 151 473 152Q475 153 483 153H487Q506 153 506 144Q506 138 501 117T481 63T449 13Q436 0 417 -8Q409 -10 393 -10Q359 -10 336 5T306 36L300 51Q299 52 296 50Q294 48 292 46Q233 -10 172 -10Q117 -10 75 30T33 157ZM351 328Q351 334 346 350T323 385T277 405Q242 405 210 374T160 293Q131 214 119 129Q119 126 119 118T118 106Q118 61 136 44T179 26Q217 26 254 59T298 110Q300 114 325 217T351 328Z"></path>
<path stroke-width="1" id="E7-MJMAIN-33" d="M127 463Q100 463 85 480T69 524Q69 579 117 622T233 665Q268 665 277 664Q351 652 390 611T430 522Q430 470 396 421T302 350L299 348Q299 347 308 345T337 336T375 315Q457 262 457 175Q457 96 395 37T238 -22Q158 -22 100 21T42 130Q42 158 60 175T105 193Q133 193 151 175T169 130Q169 119 166 110T159 94T148 82T136 74T126 70T118 67L114 66Q165 21 238 21Q293 21 321 74Q338 107 338 175V195Q338 290 274 322Q259 328 213 329L171 330L168 332Q166 335 166 348Q166 366 174 366Q202 366 232 371Q266 376 294 413T322 525V533Q322 590 287 612Q265 626 240 626Q208 626 181 615T143 592T132 580H135Q138 579 143 578T153 573T165 566T175 555T183 540T186 520Q186 498 172 481T127 463Z"></path>
</defs>
<g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)" aria-hidden="true">
 <use xlink:href="#E7-MJMATHI-61" x="0" y="0"></use>
 <use transform="scale(0.707)" xlink:href="#E7-MJMAIN-33" x="748" y="-213"></use>
</g>
</svg></span></th>
    <th><span class="mjpage"><svg xmlns:xlink="http://www.w3.org/1999/xlink" width="2.284ex" height="2.009ex" style="vertical-align: -0.671ex;" viewBox="0 -576.1 983.4 865.1" role="img" focusable="false" xmlns="http://www.w3.org/2000/svg" aria-labelledby="MathJax-SVG-8-Title">
<title id="MathJax-SVG-8-Title">a_4</title>
<defs aria-hidden="true">
<path stroke-width="1" id="E8-MJMATHI-61" d="M33 157Q33 258 109 349T280 441Q331 441 370 392Q386 422 416 422Q429 422 439 414T449 394Q449 381 412 234T374 68Q374 43 381 35T402 26Q411 27 422 35Q443 55 463 131Q469 151 473 152Q475 153 483 153H487Q506 153 506 144Q506 138 501 117T481 63T449 13Q436 0 417 -8Q409 -10 393 -10Q359 -10 336 5T306 36L300 51Q299 52 296 50Q294 48 292 46Q233 -10 172 -10Q117 -10 75 30T33 157ZM351 328Q351 334 346 350T323 385T277 405Q242 405 210 374T160 293Q131 214 119 129Q119 126 119 118T118 106Q118 61 136 44T179 26Q217 26 254 59T298 110Q300 114 325 217T351 328Z"></path>
<path stroke-width="1" id="E8-MJMAIN-34" d="M462 0Q444 3 333 3Q217 3 199 0H190V46H221Q241 46 248 46T265 48T279 53T286 61Q287 63 287 115V165H28V211L179 442Q332 674 334 675Q336 677 355 677H373L379 671V211H471V165H379V114Q379 73 379 66T385 54Q393 47 442 46H471V0H462ZM293 211V545L74 212L183 211H293Z"></path>
</defs>
<g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)" aria-hidden="true">
 <use xlink:href="#E8-MJMATHI-61" x="0" y="0"></use>
 <use transform="scale(0.707)" xlink:href="#E8-MJMAIN-34" x="748" y="-213"></use>
</g>
</svg></span></th>
    </tr>
    </thead>
    <tbody>
    <tr>
    <td><span class="mjpage"><svg xmlns:xlink="http://www.w3.org/1999/xlink" width="2.284ex" height="2.009ex" style="vertical-align: -0.671ex;" viewBox="0 -576.1 983.4 865.1" role="img" focusable="false" xmlns="http://www.w3.org/2000/svg" aria-labelledby="MathJax-SVG-5-Title">
<title id="MathJax-SVG-5-Title">a_1</title>
<defs aria-hidden="true">
<path stroke-width="1" id="E5-MJMATHI-61" d="M33 157Q33 258 109 349T280 441Q331 441 370 392Q386 422 416 422Q429 422 439 414T449 394Q449 381 412 234T374 68Q374 43 381 35T402 26Q411 27 422 35Q443 55 463 131Q469 151 473 152Q475 153 483 153H487Q506 153 506 144Q506 138 501 117T481 63T449 13Q436 0 417 -8Q409 -10 393 -10Q359 -10 336 5T306 36L300 51Q299 52 296 50Q294 48 292 46Q233 -10 172 -10Q117 -10 75 30T33 157ZM351 328Q351 334 346 350T323 385T277 405Q242 405 210 374T160 293Q131 214 119 129Q119 126 119 118T118 106Q118 61 136 44T179 26Q217 26 254 59T298 110Q300 114 325 217T351 328Z"></path>
<path stroke-width="1" id="E5-MJMAIN-31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path>
</defs>
<g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)" aria-hidden="true">
 <use xlink:href="#E5-MJMATHI-61" x="0" y="0"></use>
 <use transform="scale(0.707)" xlink:href="#E5-MJMAIN-31" x="748" y="-213"></use>
</g>
</svg></span></td>
    <td>=</td>
    <td>&gt;</td>
    <td>=</td>
    <td>&lt;</td>
    </tr>
    <tr>
    <td><span class="mjpage"><svg xmlns:xlink="http://www.w3.org/1999/xlink" width="2.284ex" height="2.009ex" style="vertical-align: -0.671ex;" viewBox="0 -576.1 983.4 865.1" role="img" focusable="false" xmlns="http://www.w3.org/2000/svg" aria-labelledby="MathJax-SVG-6-Title">
<title id="MathJax-SVG-6-Title">a_2</title>
<defs aria-hidden="true">
<path stroke-width="1" id="E6-MJMATHI-61" d="M33 157Q33 258 109 349T280 441Q331 441 370 392Q386 422 416 422Q429 422 439 414T449 394Q449 381 412 234T374 68Q374 43 381 35T402 26Q411 27 422 35Q443 55 463 131Q469 151 473 152Q475 153 483 153H487Q506 153 506 144Q506 138 501 117T481 63T449 13Q436 0 417 -8Q409 -10 393 -10Q359 -10 336 5T306 36L300 51Q299 52 296 50Q294 48 292 46Q233 -10 172 -10Q117 -10 75 30T33 157ZM351 328Q351 334 346 350T323 385T277 405Q242 405 210 374T160 293Q131 214 119 129Q119 126 119 118T118 106Q118 61 136 44T179 26Q217 26 254 59T298 110Q300 114 325 217T351 328Z"></path>
<path stroke-width="1" id="E6-MJMAIN-32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z"></path>
</defs>
<g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)" aria-hidden="true">
 <use xlink:href="#E6-MJMATHI-61" x="0" y="0"></use>
 <use transform="scale(0.707)" xlink:href="#E6-MJMAIN-32" x="748" y="-213"></use>
</g>
</svg></span></td>
    <td>&lt;</td>
    <td>=</td>
    <td>&lt;</td>
    <td>&lt;</td>
    </tr>
    <tr>
    <td><span class="mjpage"><svg xmlns:xlink="http://www.w3.org/1999/xlink" width="2.284ex" height="2.009ex" style="vertical-align: -0.671ex;" viewBox="0 -576.1 983.4 865.1" role="img" focusable="false" xmlns="http://www.w3.org/2000/svg" aria-labelledby="MathJax-SVG-7-Title">
<title id="MathJax-SVG-7-Title">a_3</title>
<defs aria-hidden="true">
<path stroke-width="1" id="E7-MJMATHI-61" d="M33 157Q33 258 109 349T280 441Q331 441 370 392Q386 422 416 422Q429 422 439 414T449 394Q449 381 412 234T374 68Q374 43 381 35T402 26Q411 27 422 35Q443 55 463 131Q469 151 473 152Q475 153 483 153H487Q506 153 506 144Q506 138 501 117T481 63T449 13Q436 0 417 -8Q409 -10 393 -10Q359 -10 336 5T306 36L300 51Q299 52 296 50Q294 48 292 46Q233 -10 172 -10Q117 -10 75 30T33 157ZM351 328Q351 334 346 350T323 385T277 405Q242 405 210 374T160 293Q131 214 119 129Q119 126 119 118T118 106Q118 61 136 44T179 26Q217 26 254 59T298 110Q300 114 325 217T351 328Z"></path>
<path stroke-width="1" id="E7-MJMAIN-33" d="M127 463Q100 463 85 480T69 524Q69 579 117 622T233 665Q268 665 277 664Q351 652 390 611T430 522Q430 470 396 421T302 350L299 348Q299 347 308 345T337 336T375 315Q457 262 457 175Q457 96 395 37T238 -22Q158 -22 100 21T42 130Q42 158 60 175T105 193Q133 193 151 175T169 130Q169 119 166 110T159 94T148 82T136 74T126 70T118 67L114 66Q165 21 238 21Q293 21 321 74Q338 107 338 175V195Q338 290 274 322Q259 328 213 329L171 330L168 332Q166 335 166 348Q166 366 174 366Q202 366 232 371Q266 376 294 413T322 525V533Q322 590 287 612Q265 626 240 626Q208 626 181 615T143 592T132 580H135Q138 579 143 578T153 573T165 566T175 555T183 540T186 520Q186 498 172 481T127 463Z"></path>
</defs>
<g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)" aria-hidden="true">
 <use xlink:href="#E7-MJMATHI-61" x="0" y="0"></use>
 <use transform="scale(0.707)" xlink:href="#E7-MJMAIN-33" x="748" y="-213"></use>
</g>
</svg></span></td>
    <td>=</td>
    <td>&gt;</td>
    <td>=</td>
    <td>&lt;</td>
    </tr>
    <tr>
    <td><span class="mjpage"><svg xmlns:xlink="http://www.w3.org/1999/xlink" width="2.284ex" height="2.009ex" style="vertical-align: -0.671ex;" viewBox="0 -576.1 983.4 865.1" role="img" focusable="false" xmlns="http://www.w3.org/2000/svg" aria-labelledby="MathJax-SVG-8-Title">
<title id="MathJax-SVG-8-Title">a_4</title>
<defs aria-hidden="true">
<path stroke-width="1" id="E8-MJMATHI-61" d="M33 157Q33 258 109 349T280 441Q331 441 370 392Q386 422 416 422Q429 422 439 414T449 394Q449 381 412 234T374 68Q374 43 381 35T402 26Q411 27 422 35Q443 55 463 131Q469 151 473 152Q475 153 483 153H487Q506 153 506 144Q506 138 501 117T481 63T449 13Q436 0 417 -8Q409 -10 393 -10Q359 -10 336 5T306 36L300 51Q299 52 296 50Q294 48 292 46Q233 -10 172 -10Q117 -10 75 30T33 157ZM351 328Q351 334 346 350T323 385T277 405Q242 405 210 374T160 293Q131 214 119 129Q119 126 119 118T118 106Q118 61 136 44T179 26Q217 26 254 59T298 110Q300 114 325 217T351 328Z"></path>
<path stroke-width="1" id="E8-MJMAIN-34" d="M462 0Q444 3 333 3Q217 3 199 0H190V46H221Q241 46 248 46T265 48T279 53T286 61Q287 63 287 115V165H28V211L179 442Q332 674 334 675Q336 677 355 677H373L379 671V211H471V165H379V114Q379 73 379 66T385 54Q393 47 442 46H471V0H462ZM293 211V545L74 212L183 211H293Z"></path>
</defs>
<g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)" aria-hidden="true">
 <use xlink:href="#E8-MJMATHI-61" x="0" y="0"></use>
 <use transform="scale(0.707)" xlink:href="#E8-MJMAIN-34" x="748" y="-213"></use>
</g>
</svg></span></td>
    <td>&gt;</td>
    <td>&gt;</td>
    <td>&gt;</td>
    <td>=</td>
    </tr>
    </tbody>
    </table>
    </div>

那么这个图所表示的是

![mlwGlR.png](/source/guoj/1316/img/aHR0cHM6Ly9zMi5heDF4LmNvbS8yMDE5LzA4LzE5L21sd0dsUi5wbmc=.png)

但困难的是，小牛自己不会割草，他要请割草工来帮忙他割草。一共有$m-1$个割草工，编号为$2~m$，每两两之间有道路相连接。

我们的小牛开始从$1$位置出发，割完草之后回到$1$位置。每次请求当前割草工帮忙割草（也就是说割草严格要求从美味度小的向美味度大的割）。

割草工一次性能割完一种美味度的草，并且请这个割草工所要的花费为当前美味度的草的个数$\times$当前位置走向这个割草工路径的长度。

聪明的你能帮助小牛，如何花费最小的费用，割完这个草场？

# 输入格式

一个正整数$n$，代表当前草场的长度。

一个$n\times n$的图，代表着当前草场每个位置的两两美味值的比较。

一个正整数$m$，代表割草工的个数加上小牛的起始点。($m-1$严格等于美味值的总数)

以下$m$行，每行$m$个正整数。两两位置之间的距离。

# 输出格式

一个正整数，代表割完这个草场所花最小花费。

# 样例

输入
```
4 
= > = < 
< = < < 
= > = <
> > > = 
4 
0 1 2 1 
0 0 1 1 
0 2 0 3 
0 1 3 0 
```
输出
```
4 
走的路径为1->4->2->3->1(1*1+1*2+1*1)
```

# 数据范围与提示

从开始的位置到每一个割草工的位置的距离值都是给定的 \

从每一个割草工到开始的位置是不需要花钱的 \

30% $0<m<n<=10$ 

60% $m\leq 15,n\leq100$ 

100% $m\leq 18,n\leq1000$

