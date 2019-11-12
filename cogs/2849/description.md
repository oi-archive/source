# 题目描述


<meta name="viewport" content="width=device-width initial-scale=1"/>
<title>
自动ac机.md
</title>
<h1>
自动AC机
</h1>
<h3>
题目描述
</h3>
<p>
在一个静谧的晚上，SYOI <strong>julao</strong> HJX坐在湖边静静地撕烤。
</p>
<p>
湖边传来丝微的蛤蟆声，隐隐约约月色下出现一位长者，将手中红色包装的盒子放到HJX手里：“我这是作为一名<strong>长者</strong>，来给你传授一点楞生的经验”。HJX打开盒子一看，竟是无数人梦寐以求的<strong>自动AC机</strong>。
</p>
<p>
<code>XPFAOJ</code>上有$n\ (1\leq n\leq1000000)$道题目，而自动AC机的每次最多只能处理$k\ (1\leq k\leq n)$道题，并且切一道题能涨的分为$s[i]\ (0\leq s[i]\leq1000)$。
</p>
<p>
HJX为了使自己的提交记录看起来不是那么像脚本处理出来的，他打算把OJ上的题目分成几段连续的题让自动AC机处理。HJX为了更进一步的涨分 ，他找来了WHZ来给自己续分数。
</p>
<p>
WHZ可以通过一些膜法，能把区间$[i,j]$的贡献变为：
</p>
<div class="mathjax-block md-end-block" id="mathjax-n12" contenteditable="false" mdtype="math_block" cid="n12">
<span class="MathJax_Preview"></span><span class="MathJax_SVG_Display" style="text-align:center;"><span tabindex="-1" class="MathJax_SVG" id="MathJax-Element-1-Frame" style="font-size:100%;display:inline-block;"><svg xmlns="http://www.w3.org/2000/svg" role="img" style="vertical-align:-3.04ex;" viewBox="0 -2062.6 29343.7 3371.4" focusable="false" width="68.153ex" height="7.83ex"><defs><path id="E1-MJMAIN-28" stroke-width="1" d="M 94 250 Q 94 319 104 381 T 127 488 T 164 576 T 202 643 T 244 695 T 277 729 T 302 750 H 315 H 319 Q 333 750 333 741 Q 333 738 316 720 T 275 667 T 226 581 T 184 443 T 167 250 T 184 58 T 225 -81 T 274 -167 T 316 -220 T 333 -241 Q 333 -250 318 -250 H 315 H 302 L 274 -226 Q 180 -141 137 -14 T 94 250 Z"></path><path id="E1-MJSZ2-2211" stroke-width="1" d="M 60 948 Q 63 950 665 950 H 1267 L 1325 815 Q 1384 677 1388 669 H 1348 L 1341 683 Q 1320 724 1285 761 Q 1235 809 1174 838 T 1033 881 T 882 898 T 699 902 H 574 H 543 H 251 L 259 891 Q 722 258 724 252 Q 725 250 724 246 Q 721 243 460 -56 L 196 -356 Q 196 -357 407 -357 Q 459 -357 548 -357 T 676 -358 Q 812 -358 896 -353 T 1063 -332 T 1204 -283 T 1307 -196 Q 1328 -170 1348 -124 H 1388 Q 1388 -125 1381 -145 T 1356 -210 T 1325 -294 L 1267 -449 L 666 -450 Q 64 -450 61 -448 Q 55 -446 55 -439 Q 55 -437 57 -433 L 590 177 Q 590 178 557 222 T 452 366 T 322 544 L 56 909 L 55 924 Q 55 945 60 948 Z"></path><path id="E1-MJMATHI-6B" stroke-width="1" d="M 121 647 Q 121 657 125 670 T 137 683 Q 138 683 209 688 T 282 694 Q 294 694 294 686 Q 294 679 244 477 Q 194 279 194 272 Q 213 282 223 291 Q 247 309 292 354 T 362 415 Q 402 442 438 442 Q 468 442 485 423 T 503 369 Q 503 344 496 327 T 477 302 T 456 291 T 438 288 Q 418 288 406 299 T 394 328 Q 394 353 410 369 T 442 390 L 458 393 Q 446 405 434 405 H 430 Q 398 402 367 380 T 294 316 T 228 255 Q 230 254 243 252 T 267 246 T 293 238 T 320 224 T 342 206 T 359 180 T 365 147 Q 365 130 360 106 T 354 66 Q 354 26 381 26 Q 429 26 459 145 Q 461 153 479 153 H 483 Q 499 153 499 144 Q 499 139 496 130 Q 455 -11 378 -11 Q 333 -11 305 15 T 277 90 Q 277 108 280 121 T 283 145 Q 283 167 269 183 T 234 206 T 200 217 T 182 220 H 180 Q 168 178 159 139 T 145 81 T 136 44 T 129 20 T 122 7 T 111 -2 Q 98 -11 83 -11 Q 66 -11 57 -1 T 48 16 Q 48 26 85 176 T 158 471 L 195 616 Q 196 629 188 632 T 149 637 H 144 Q 134 637 131 637 T 124 640 T 121 647 Z"></path><path id="E1-MJMAIN-3D" stroke-width="1" d="M 56 347 Q 56 360 70 367 H 707 Q 722 359 722 347 Q 722 336 708 328 L 390 327 H 72 Q 56 332 56 347 Z M 56 153 Q 56 168 72 173 H 708 Q 722 163 722 153 Q 722 140 707 133 H 70 Q 56 140 56 153 Z"></path><path id="E1-MJMATHI-69" stroke-width="1" d="M 184 600 Q 184 624 203 642 T 247 661 Q 265 661 277 649 T 290 619 Q 290 596 270 577 T 226 557 Q 211 557 198 567 T 184 600 Z M 21 287 Q 21 295 30 318 T 54 369 T 98 420 T 158 442 Q 197 442 223 419 T 250 357 Q 250 340 236 301 T 196 196 T 154 83 Q 149 61 149 51 Q 149 26 166 26 Q 175 26 185 29 T 208 43 T 235 78 T 260 137 Q 263 149 265 151 T 282 153 Q 302 153 302 143 Q 302 135 293 112 T 268 61 T 223 11 T 161 -11 Q 129 -11 102 10 T 74 74 Q 74 91 79 106 T 122 220 Q 160 321 166 341 T 173 380 Q 173 404 156 404 H 154 Q 124 404 99 371 T 61 287 Q 60 286 59 284 T 58 281 T 56 279 T 53 278 T 49 278 T 41 278 H 27 Q 21 284 21 287 Z"></path><path id="E1-MJMATHI-6A" stroke-width="1" d="M 297 596 Q 297 627 318 644 T 361 661 Q 378 661 389 651 T 403 623 Q 403 595 384 576 T 340 557 Q 322 557 310 567 T 297 596 Z M 288 376 Q 288 405 262 405 Q 240 405 220 393 T 185 362 T 161 325 T 144 293 L 137 279 Q 135 278 121 278 H 107 Q 101 284 101 286 T 105 299 Q 126 348 164 391 T 252 441 Q 253 441 260 441 T 272 442 Q 296 441 316 432 Q 341 418 354 401 T 367 348 V 332 L 318 133 Q 267 -67 264 -75 Q 246 -125 194 -164 T 75 -204 Q 25 -204 7 -183 T -12 -137 Q -12 -110 7 -91 T 53 -71 Q 70 -71 82 -81 T 95 -112 Q 95 -148 63 -167 Q 69 -168 77 -168 Q 111 -168 139 -140 T 182 -74 L 193 -32 Q 204 11 219 72 T 251 197 T 278 308 T 289 365 Q 289 372 288 376 Z"></path><path id="E1-MJMATHI-73" stroke-width="1" d="M 131 289 Q 131 321 147 354 T 203 415 T 300 442 Q 362 442 390 415 T 419 355 Q 419 323 402 308 T 364 292 Q 351 292 340 300 T 328 326 Q 328 342 337 354 T 354 372 T 367 378 Q 368 378 368 379 Q 368 382 361 388 T 336 399 T 297 405 Q 249 405 227 379 T 204 326 Q 204 301 223 291 T 278 274 T 330 259 Q 396 230 396 163 Q 396 135 385 107 T 352 51 T 289 7 T 195 -10 Q 118 -10 86 19 T 53 87 Q 53 126 74 143 T 118 160 Q 133 160 146 151 T 160 120 Q 160 94 142 76 T 111 58 Q 109 57 108 57 T 107 55 Q 108 52 115 47 T 146 34 T 201 27 Q 237 27 263 38 T 301 66 T 318 97 T 323 122 Q 323 150 302 164 T 254 181 T 195 196 T 148 231 Q 131 256 131 289 Z"></path><path id="E1-MJMAIN-5B" stroke-width="1" d="M 118 -250 V 750 H 255 V 710 H 158 V -210 H 255 V -250 H 118 Z"></path><path id="E1-MJMAIN-5D" stroke-width="1" d="M 22 710 V 750 H 159 V -250 H 22 V -210 H 119 V 710 H 22 Z"></path><path id="E1-MJMAIN-29" stroke-width="1" d="M 60 749 L 64 750 Q 69 750 74 750 H 86 L 114 726 Q 208 641 251 514 T 294 250 Q 294 182 284 119 T 261 12 T 224 -76 T 186 -143 T 145 -194 T 113 -227 T 90 -246 Q 87 -249 86 -250 H 74 Q 66 -250 63 -250 T 58 -247 T 55 -238 Q 56 -237 66 -225 Q 221 -64 221 250 T 66 725 Q 56 737 55 738 Q 55 746 60 749 Z"></path><path id="E1-MJSZ4-28" stroke-width="1" d="M 758 -1237 T 758 -1240 T 752 -1249 H 736 Q 718 -1249 717 -1248 Q 711 -1245 672 -1199 Q 237 -706 237 251 T 672 1700 Q 697 1730 716 1749 Q 718 1750 735 1750 H 752 Q 758 1744 758 1741 Q 758 1737 740 1713 T 689 1644 T 619 1537 T 540 1380 T 463 1176 Q 348 802 348 251 Q 348 -242 441 -599 T 744 -1218 Q 758 -1237 758 -1240 Z"></path><path id="E1-MJSZ4-29" stroke-width="1" d="M 33 1741 Q 33 1750 51 1750 H 60 H 65 Q 73 1750 81 1743 T 119 1700 Q 554 1207 554 251 Q 554 -707 119 -1199 Q 76 -1250 66 -1250 Q 65 -1250 62 -1250 T 56 -1249 Q 55 -1249 53 -1249 T 49 -1250 Q 33 -1250 33 -1239 Q 33 -1236 50 -1214 T 98 -1150 T 163 -1052 T 238 -910 T 311 -727 Q 443 -335 443 251 Q 443 402 436 532 T 405 831 T 339 1142 T 224 1438 T 50 1716 Q 33 1737 33 1741 Z"></path><path id="E1-MJMAIN-32" stroke-width="1" d="M 109 429 Q 82 429 66 447 T 50 491 Q 50 562 103 614 T 235 666 Q 326 666 387 610 T 449 465 Q 449 422 429 383 T 381 315 T 301 241 Q 265 210 201 149 L 142 93 L 218 92 Q 375 92 385 97 Q 392 99 409 186 V 189 H 449 V 186 Q 448 183 436 95 T 421 3 V 0 H 50 V 19 V 31 Q 50 38 56 46 T 86 81 Q 115 113 136 137 Q 145 147 170 174 T 204 211 T 233 244 T 261 278 T 284 308 T 305 340 T 320 369 T 333 401 T 340 431 T 343 464 Q 343 527 309 573 T 212 619 Q 179 619 154 602 T 119 569 T 109 550 Q 109 549 114 549 Q 132 549 151 535 T 170 489 Q 170 464 154 447 T 109 429 Z"></path><path id="E1-MJMAIN-2B" stroke-width="1" d="M 56 237 T 56 250 T 70 270 H 369 V 420 L 370 570 Q 380 583 389 583 Q 402 583 409 568 V 270 H 707 Q 722 262 722 250 T 707 230 H 409 V -68 Q 401 -82 391 -82 H 389 H 387 Q 375 -82 369 -68 V 230 H 70 Q 56 237 56 250 Z"></path><path id="E1-MJMAIN-31" stroke-width="1" d="M 213 578 L 200 573 Q 186 568 160 563 T 102 556 H 83 V 602 H 102 Q 149 604 189 617 T 245 641 T 273 663 Q 275 666 285 666 Q 294 666 302 660 V 361 L 303 61 Q 310 54 315 52 T 339 48 T 401 46 H 427 V 0 H 416 Q 395 3 257 3 Q 121 3 100 0 H 88 V 46 H 114 Q 136 46 152 46 T 177 47 T 193 50 T 201 52 T 207 57 T 213 61 V 578 Z"></path><path id="E1-MJMAIN-2212" stroke-width="1" d="M 84 237 T 84 250 T 98 270 H 679 Q 694 262 694 250 T 679 230 H 98 Q 84 237 84 250 Z"></path><path id="E1-MJMAIN-33" stroke-width="1" d="M 127 463 Q 100 463 85 480 T 69 524 Q 69 579 117 622 T 233 665 Q 268 665 277 664 Q 351 652 390 611 T 430 522 Q 430 470 396 421 T 302 350 L 299 348 Q 299 347 308 345 T 337 336 T 375 315 Q 457 262 457 175 Q 457 96 395 37 T 238 -22 Q 158 -22 100 21 T 42 130 Q 42 158 60 175 T 105 193 Q 133 193 151 175 T 169 130 Q 169 119 166 110 T 159 94 T 148 82 T 136 74 T 126 70 T 118 67 L 114 66 Q 165 21 238 21 Q 293 21 321 74 Q 338 107 338 175 V 195 Q 338 290 274 322 Q 259 328 213 329 L 171 330 L 168 332 Q 166 335 166 348 Q 166 366 174 366 Q 202 366 232 371 Q 266 376 294 413 T 322 525 V 533 Q 322 590 287 612 Q 265 626 240 626 Q 208 626 181 615 T 143 592 T 132 580 H 135 Q 138 579 143 578 T 153 573 T 165 566 T 175 555 T 183 540 T 186 520 Q 186 498 172 481 T 127 463 Z"></path></defs><g fill="currentColor" stroke="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><use xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJSZ4-28"></use><g transform="translate(792)"><use x="0" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJSZ2-2211"></use><g transform="translate(140 -1110)"><use transform="scale(0.707)" x="0" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMATHI-6B"></use><use transform="scale(0.707)" x="521" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-3D"></use><use transform="scale(0.707)" x="1300" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMATHI-69"></use></g><use transform="scale(0.707)" x="815" y="1707" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMATHI-6A"></use></g><use x="2403" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMATHI-73"></use><use x="2873" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-5B"></use><use x="3151" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMATHI-6B"></use><use x="3673" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-5D"></use><use x="3951" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJSZ4-29"></use><use transform="scale(0.707)" x="6709" y="2124" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-32"></use><use x="5420" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-2B"></use><g transform="translate(6421)"><use xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJSZ4-28"></use><g transform="translate(792)"><use x="0" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJSZ2-2211"></use><g transform="translate(85 -1110)"><use transform="scale(0.707)" x="0" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMATHI-6B"></use><use transform="scale(0.707)" x="521" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-3D"></use><use transform="scale(0.707)" x="1300" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-31"></use></g><g transform="translate(147 1151)"><use transform="scale(0.707)" x="0" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMATHI-69"></use><use transform="scale(0.707)" x="345" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-2212"></use><use transform="scale(0.707)" x="1124" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-31"></use></g></g><use x="2403" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMATHI-73"></use><use x="2873" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-5B"></use><use x="3151" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMATHI-6B"></use><use x="3673" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-5D"></use><use x="4173" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-2B"></use><g transform="translate(5174)"><use x="0" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJSZ2-2211"></use><g transform="translate(85 -1110)"><use transform="scale(0.707)" x="0" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMATHI-6B"></use><use transform="scale(0.707)" x="521" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-3D"></use><use transform="scale(0.707)" x="1300" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-31"></use></g><use transform="scale(0.707)" x="815" y="1707" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMATHI-6A"></use></g><use x="6785" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMATHI-73"></use><use x="7255" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-5B"></use><use x="7533" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMATHI-6B"></use><use x="8055" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-5D"></use><use x="8333" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJSZ4-29"></use><use transform="scale(0.707)" x="12906" y="2124" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-32"></use></g><use x="16223" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-2212"></use><use x="17224" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-33"></use><g transform="translate(17724)"><use xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJSZ4-28"></use><g transform="translate(792)"><use x="0" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJSZ2-2211"></use><g transform="translate(85 -1110)"><use transform="scale(0.707)" x="0" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMATHI-6B"></use><use transform="scale(0.707)" x="521" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-3D"></use><use transform="scale(0.707)" x="1300" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-31"></use></g><g transform="translate(147 1151)"><use transform="scale(0.707)" x="0" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMATHI-69"></use><use transform="scale(0.707)" x="345" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-2212"></use><use transform="scale(0.707)" x="1124" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-31"></use></g></g><use x="2403" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMATHI-73"></use><use x="2873" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-5B"></use><use x="3151" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMATHI-6B"></use><use x="3673" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-5D"></use><use x="3951" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJSZ4-29"></use><use transform="scale(0.707)" x="6709" y="2090" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-32"></use></g><use x="23144" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-2212"></use><g transform="translate(24145)"><use xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJSZ4-28"></use><g transform="translate(792)"><use x="0" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJSZ2-2211"></use><g transform="translate(85 -1110)"><use transform="scale(0.707)" x="0" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMATHI-6B"></use><use transform="scale(0.707)" x="521" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-3D"></use><use transform="scale(0.707)" x="1300" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-31"></use></g><use transform="scale(0.707)" x="815" y="1707" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMATHI-6A"></use></g><use x="2403" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMATHI-73"></use><use x="2873" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-5B"></use><use x="3151" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMATHI-6B"></use><use x="3673" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-5D"></use><use x="3951" y="0" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJSZ4-29"></use><use transform="scale(0.707)" x="6709" y="2124" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#E1-MJMAIN-32"></use></g></g></svg></span></span> 
<script type="math/tex; mode=display" id="MathJax-Element-1">
\left(\sum_{k=i}^js[k]\right)^2+\left(\sum_{k=1}^{i-1}s[k]+\sum_{k=1}^js[k]\right)^2-3\left(\sum_{k=1}^{i-1}s[k]\right)^2-\left(\sum_{k=1}^js[k]\right)^2
</script>
</div>
<p>
但由于<code>XPFAOJ</code>是个辣鸡OJ，它上面会有一些bug，每道题有一个bug值$bug[i] (1\leq bug[i]\leq1000000)$，它会影响HJX的刷分计划 。
</p>
<p>
若现在自动AC机要刷的这组题为区间$[i,j]$中的题目，那么这组题的总贡献减去$p^2$，其中$p$是小于等于$bug[i-1]$的最大的素数，若bug[i-1]&lt;2，则p=0。
</p>
<p>
bug[0]=0;
</p>
<p>
现在HJX想要知道他最多能拿多少分。
</p>
<p>
由于HJX要去学习LOL 3级放大的技巧，现在他把这个任务交给了你。
</p>
<h3>
输入格式
</h3>
<p>
第一行两个整数$n,k$分别表示有多少道题 最长区间
</p>
<p>
第二行n个整数$s[i]$表示每道题的得分
</p>
<p>
第三行n个整数$bug[i]$表示每道题的bug值
</p>
<h3>
输出格式
</h3>
<p>
一个整数 表示最大得分
</p>
<h3>
样例输入
</h3>
<pre><p>
<code> 5 2</code> 
</p>

<p>
<code>1 2 3 4 5</code> 
</p>

<p>
<code>5 4 3 2 1 </code> 
</p>
</pre>
<h3>
样例输出
</h3>
<pre><code> 212 </code></pre>
<h3>
样例解释
</h3>
<p>
将1,2分一组，贡献为9
</p>
<p>
将3,4分到一组，贡献为82
</p>
<p>
将5分到一组，贡献为121
</p>
<h3>
数据范围
</h3>
<p>
<img alt="RANGE" src="http://218.28.19.228:8080/cogs/upload/image/20171010/20171010145533_76455.png"/> 
</p>
