### Sum Of All

<p>You are given a number. You want to compute the sum of all possible resulting numbers after applying the <strong>magic operation</strong>.<br>
In a magic operation, you pick a <strong>non-empty subsequence</strong> from this number, then take these digits out of the number. The remaining digits then fill in the gap, and the number after the magic operation is the integer that is left.</p>
<p>For eg: Let's say the number is <svg width="5.812ex" height="2.009ex" viewBox="0 -748.3 2502.5 865.1" role="img" focusable="false" style="vertical-align: -0.271ex;" aria-hidden="true"><defs><path stroke-width="1" id="E1-MJMAIN-31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path><path stroke-width="1" id="E1-MJMAIN-32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z"></path><path stroke-width="1" id="E1-MJMAIN-33" d="M127 463Q100 463 85 480T69 524Q69 579 117 622T233 665Q268 665 277 664Q351 652 390 611T430 522Q430 470 396 421T302 350L299 348Q299 347 308 345T337 336T375 315Q457 262 457 175Q457 96 395 37T238 -22Q158 -22 100 21T42 130Q42 158 60 175T105 193Q133 193 151 175T169 130Q169 119 166 110T159 94T148 82T136 74T126 70T118 67L114 66Q165 21 238 21Q293 21 321 74Q338 107 338 175V195Q338 290 274 322Q259 328 213 329L171 330L168 332Q166 335 166 348Q166 366 174 366Q202 366 232 371Q266 376 294 413T322 525V533Q322 590 287 612Q265 626 240 626Q208 626 181 615T143 592T132 580H135Q138 579 143 578T153 573T165 566T175 555T183 540T186 520Q186 498 172 481T127 463Z"></path><path stroke-width="1" id="E1-MJMAIN-34" d="M462 0Q444 3 333 3Q217 3 199 0H190V46H221Q241 46 248 46T265 48T279 53T286 61Q287 63 287 115V165H28V211L179 442Q332 674 334 675Q336 677 355 677H373L379 671V211H471V165H379V114Q379 73 379 66T385 54Q393 47 442 46H471V0H462ZM293 211V545L74 212L183 211H293Z"></path><path stroke-width="1" id="E1-MJMAIN-35" d="M164 157Q164 133 148 117T109 101H102Q148 22 224 22Q294 22 326 82Q345 115 345 210Q345 313 318 349Q292 382 260 382H254Q176 382 136 314Q132 307 129 306T114 304Q97 304 95 310Q93 314 93 485V614Q93 664 98 664Q100 666 102 666Q103 666 123 658T178 642T253 634Q324 634 389 662Q397 666 402 666Q410 666 410 648V635Q328 538 205 538Q174 538 149 544L139 546V374Q158 388 169 396T205 412T256 420Q337 420 393 355T449 201Q449 109 385 44T229 -22Q148 -22 99 32T50 154Q50 178 61 192T84 210T107 214Q132 214 148 197T164 157Z"></path></defs><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><use xlink:href="#E1-MJMAIN-31"></use><use xlink:href="#E1-MJMAIN-32" x="500" y="0"></use><use xlink:href="#E1-MJMAIN-33" x="1001" y="0"></use><use xlink:href="#E1-MJMAIN-34" x="1501" y="0"></use><use xlink:href="#E1-MJMAIN-35" x="2002" y="0"></use></g></svg>. One of the subsequences of this number is <strong><svg width="2.325ex" height="2.009ex" viewBox="0 -748.3 1001 865.1" role="img" focusable="false" style="vertical-align: -0.271ex;" aria-hidden="true"><defs><path stroke-width="1" id="E2-MJMAIN-32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z"></path><path stroke-width="1" id="E2-MJMAIN-34" d="M462 0Q444 3 333 3Q217 3 199 0H190V46H221Q241 46 248 46T265 48T279 53T286 61Q287 63 287 115V165H28V211L179 442Q332 674 334 675Q336 677 355 677H373L379 671V211H471V165H379V114Q379 73 379 66T385 54Q393 47 442 46H471V0H462ZM293 211V545L74 212L183 211H293Z"></path></defs><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><use xlink:href="#E2-MJMAIN-32"></use><use xlink:href="#E2-MJMAIN-34" x="500" y="0"></use></g></svg>.</strong> So after removing this subsequence, the resulting number is <strong><svg width="3.487ex" height="2.009ex" viewBox="0 -748.3 1501.5 865.1" role="img" focusable="false" style="vertical-align: -0.271ex;" aria-hidden="true"><defs><path stroke-width="1" id="E3-MJMAIN-31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path><path stroke-width="1" id="E3-MJMAIN-33" d="M127 463Q100 463 85 480T69 524Q69 579 117 622T233 665Q268 665 277 664Q351 652 390 611T430 522Q430 470 396 421T302 350L299 348Q299 347 308 345T337 336T375 315Q457 262 457 175Q457 96 395 37T238 -22Q158 -22 100 21T42 130Q42 158 60 175T105 193Q133 193 151 175T169 130Q169 119 166 110T159 94T148 82T136 74T126 70T118 67L114 66Q165 21 238 21Q293 21 321 74Q338 107 338 175V195Q338 290 274 322Q259 328 213 329L171 330L168 332Q166 335 166 348Q166 366 174 366Q202 366 232 371Q266 376 294 413T322 525V533Q322 590 287 612Q265 626 240 626Q208 626 181 615T143 592T132 580H135Q138 579 143 578T153 573T165 566T175 555T183 540T186 520Q186 498 172 481T127 463Z"></path><path stroke-width="1" id="E3-MJMAIN-35" d="M164 157Q164 133 148 117T109 101H102Q148 22 224 22Q294 22 326 82Q345 115 345 210Q345 313 318 349Q292 382 260 382H254Q176 382 136 314Q132 307 129 306T114 304Q97 304 95 310Q93 314 93 485V614Q93 664 98 664Q100 666 102 666Q103 666 123 658T178 642T253 634Q324 634 389 662Q397 666 402 666Q410 666 410 648V635Q328 538 205 538Q174 538 149 544L139 546V374Q158 388 169 396T205 412T256 420Q337 420 393 355T449 201Q449 109 385 44T229 -22Q148 -22 99 32T50 154Q50 178 61 192T84 210T107 214Q132 214 148 197T164 157Z"></path></defs><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><use xlink:href="#E3-MJMAIN-31"></use><use xlink:href="#E3-MJMAIN-33" x="500" y="0"></use><use xlink:href="#E3-MJMAIN-35" x="1001" y="0"></use></g></svg></strong><strong>.</strong><br>Leading zeros are allowed in the resulting number (number after applying the magic operation). When all digits are removed, the number is considered to be <svg width="1.162ex" height="2.009ex" viewBox="0 -748.3 500.5 865.1" role="img" focusable="false" style="vertical-align: -0.271ex;" aria-hidden="true"><defs><path stroke-width="1" id="E4-MJMAIN-30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z"></path></defs><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><use xlink:href="#E4-MJMAIN-30" x="0" y="0"></use></g></svg>.</p>
<p><strong>Input Format:</strong></p>
<ul>
	<li>The first line contains one integer <svg width="1.636ex" height="2.009ex" viewBox="0 -748.3 704.5 865.1" role="img" focusable="false" style="vertical-align: -0.271ex;" aria-hidden="true"><defs><path stroke-width="1" id="E5-MJMATHI-54" d="M40 437Q21 437 21 445Q21 450 37 501T71 602L88 651Q93 669 101 677H569H659Q691 677 697 676T704 667Q704 661 687 553T668 444Q668 437 649 437Q640 437 637 437T631 442L629 445Q629 451 635 490T641 551Q641 586 628 604T573 629Q568 630 515 631Q469 631 457 630T439 622Q438 621 368 343T298 60Q298 48 386 46Q418 46 427 45T436 36Q436 31 433 22Q429 4 424 1L422 0Q419 0 415 0Q410 0 363 1T228 2Q99 2 64 0H49Q43 6 43 9T45 27Q49 40 55 46H83H94Q174 46 189 55Q190 56 191 56Q196 59 201 76T241 233Q258 301 269 344Q339 619 339 625Q339 630 310 630H279Q212 630 191 624Q146 614 121 583T67 467Q60 445 57 441T43 437H40Z"></path></defs><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><use xlink:href="#E5-MJMATHI-54" x="0" y="0"></use></g></svg><svg width="1.808ex" height="2.009ex" viewBox="0 -690.9 778.5 865.1" role="img" focusable="false" style="vertical-align: -0.405ex;" aria-hidden="true"><defs><path stroke-width="1" id="E6-MJMAIN-2212" d="M84 237T84 250T98 270H679Q694 262 694 250T679 230H98Q84 237 84 250Z"></path></defs><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><use xlink:href="#E6-MJMAIN-2212" x="0" y="0"></use></g></svg> the number of test cases. Then <svg width="1.636ex" height="2.009ex" viewBox="0 -748.3 704.5 865.1" role="img" focusable="false" style="vertical-align: -0.271ex;" aria-hidden="true"><defs><path stroke-width="1" id="E7-MJMATHI-54" d="M40 437Q21 437 21 445Q21 450 37 501T71 602L88 651Q93 669 101 677H569H659Q691 677 697 676T704 667Q704 661 687 553T668 444Q668 437 649 437Q640 437 637 437T631 442L629 445Q629 451 635 490T641 551Q641 586 628 604T573 629Q568 630 515 631Q469 631 457 630T439 622Q438 621 368 343T298 60Q298 48 386 46Q418 46 427 45T436 36Q436 31 433 22Q429 4 424 1L422 0Q419 0 415 0Q410 0 363 1T228 2Q99 2 64 0H49Q43 6 43 9T45 27Q49 40 55 46H83H94Q174 46 189 55Q190 56 191 56Q196 59 201 76T241 233Q258 301 269 344Q339 619 339 625Q339 630 310 630H279Q212 630 191 624Q146 614 121 583T67 467Q60 445 57 441T43 437H40Z"></path></defs><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><use xlink:href="#E7-MJMATHI-54" x="0" y="0"></use></g></svg> test cases follow.</li>
	<li>The first and only line of each test case contains a single integer <svg width="2.064ex" height="2.009ex" viewBox="0 -748.3 888.5 865.1" role="img" focusable="false" style="vertical-align: -0.271ex;" aria-hidden="true"><defs><path stroke-width="1" id="E8-MJMATHI-4E" d="M234 637Q231 637 226 637Q201 637 196 638T191 649Q191 676 202 682Q204 683 299 683Q376 683 387 683T401 677Q612 181 616 168L670 381Q723 592 723 606Q723 633 659 637Q635 637 635 648Q635 650 637 660Q641 676 643 679T653 683Q656 683 684 682T767 680Q817 680 843 681T873 682Q888 682 888 672Q888 650 880 642Q878 637 858 637Q787 633 769 597L620 7Q618 0 599 0Q585 0 582 2Q579 5 453 305L326 604L261 344Q196 88 196 79Q201 46 268 46H278Q284 41 284 38T282 19Q278 6 272 0H259Q228 2 151 2Q123 2 100 2T63 2T46 1Q31 1 31 10Q31 14 34 26T39 40Q41 46 62 46Q130 49 150 85Q154 91 221 362L289 634Q287 635 234 637Z"></path></defs><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><use xlink:href="#E8-MJMATHI-4E" x="0" y="0"></use></g></svg>.</li>
</ul>
<p><strong>Output Format:</strong></p>
<p>For each test case output in a seperate line<svg width="0.647ex" height="1.476ex" viewBox="0 -518.7 278.5 635.5" role="img" focusable="false" style="vertical-align: -0.271ex;" aria-hidden="true"><defs><path stroke-width="1" id="E9-MJMAIN-3A" d="M78 370Q78 394 95 412T138 430Q162 430 180 414T199 371Q199 346 182 328T139 310T96 327T78 370ZM78 60Q78 84 95 102T138 120Q162 120 180 104T199 61Q199 36 182 18T139 0T96 17T78 60Z"></path></defs><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><use xlink:href="#E9-MJMAIN-3A" x="0" y="0"></use></g></svg><br>The sum of all possible resulting numbers after applying the magic operation modulo <svg width="9.191ex" height="3.076ex" viewBox="0 -977.9 3957.4 1324.4" role="img" focusable="false" style="vertical-align: -0.805ex;" aria-hidden="true"><defs><path stroke-width="1" id="E10-MJMAIN-28" d="M94 250Q94 319 104 381T127 488T164 576T202 643T244 695T277 729T302 750H315H319Q333 750 333 741Q333 738 316 720T275 667T226 581T184 443T167 250T184 58T225 -81T274 -167T316 -220T333 -241Q333 -250 318 -250H315H302L274 -226Q180 -141 137 -14T94 250Z"></path><path stroke-width="1" id="E10-MJMAIN-31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path><path stroke-width="1" id="E10-MJMAIN-30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z"></path><path stroke-width="1" id="E10-MJMAIN-39" d="M352 287Q304 211 232 211Q154 211 104 270T44 396Q42 412 42 436V444Q42 537 111 606Q171 666 243 666Q245 666 249 666T257 665H261Q273 665 286 663T323 651T370 619T413 560Q456 472 456 334Q456 194 396 97Q361 41 312 10T208 -22Q147 -22 108 7T68 93T121 149Q143 149 158 135T173 96Q173 78 164 65T148 49T135 44L131 43Q131 41 138 37T164 27T206 22H212Q272 22 313 86Q352 142 352 280V287ZM244 248Q292 248 321 297T351 430Q351 508 343 542Q341 552 337 562T323 588T293 615T246 625Q208 625 181 598Q160 576 154 546T147 441Q147 358 152 329T172 282Q197 248 244 248Z"></path><path stroke-width="1" id="E10-MJMAIN-2B" d="M56 237T56 250T70 270H369V420L370 570Q380 583 389 583Q402 583 409 568V270H707Q722 262 722 250T707 230H409V-68Q401 -82 391 -82H389H387Q375 -82 369 -68V230H70Q56 237 56 250Z"></path><path stroke-width="1" id="E10-MJMAIN-37" d="M55 458Q56 460 72 567L88 674Q88 676 108 676H128V672Q128 662 143 655T195 646T364 644H485V605L417 512Q408 500 387 472T360 435T339 403T319 367T305 330T292 284T284 230T278 162T275 80Q275 66 275 52T274 28V19Q270 2 255 -10T221 -22Q210 -22 200 -19T179 0T168 40Q168 198 265 368Q285 400 349 489L395 552H302Q128 552 119 546Q113 543 108 522T98 479L95 458V455H55V458Z"></path><path stroke-width="1" id="E10-MJMAIN-29" d="M60 749L64 750Q69 750 74 750H86L114 726Q208 641 251 514T294 250Q294 182 284 119T261 12T224 -76T186 -143T145 -194T113 -227T90 -246Q87 -249 86 -250H74Q66 -250 63 -250T58 -247T55 -238Q56 -237 66 -225Q221 -64 221 250T66 725Q56 737 55 738Q55 746 60 749Z"></path></defs><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><use xlink:href="#E10-MJMAIN-28" x="0" y="0"></use><g transform="translate(389,0)"><use xlink:href="#E10-MJMAIN-31"></use><use xlink:href="#E10-MJMAIN-30" x="500" y="0"></use><use transform="scale(0.707)" xlink:href="#E10-MJMAIN-39" x="1415" y="557"></use></g><use xlink:href="#E10-MJMAIN-2B" x="2066" y="0"></use><use xlink:href="#E10-MJMAIN-37" x="3067" y="0"></use><use xlink:href="#E10-MJMAIN-29" x="3567" y="0"></use></g></svg>.</p>
<p><strong>Constraints:</strong></p>
<ul>
	<li><svg width="12.375ex" height="2.809ex" viewBox="0 -977.9 5328 1209.6" role="img" focusable="false" style="vertical-align: -0.538ex;" aria-hidden="true"><defs><path stroke-width="1" id="E11-MJMAIN-31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path><path stroke-width="1" id="E11-MJMAIN-2264" d="M674 636Q682 636 688 630T694 615T687 601Q686 600 417 472L151 346L399 228Q687 92 691 87Q694 81 694 76Q694 58 676 56H670L382 192Q92 329 90 331Q83 336 83 348Q84 359 96 365Q104 369 382 500T665 634Q669 636 674 636ZM84 -118Q84 -108 99 -98H678Q694 -104 694 -118Q694 -130 679 -138H98Q84 -131 84 -118Z"></path><path stroke-width="1" id="E11-MJMATHI-54" d="M40 437Q21 437 21 445Q21 450 37 501T71 602L88 651Q93 669 101 677H569H659Q691 677 697 676T704 667Q704 661 687 553T668 444Q668 437 649 437Q640 437 637 437T631 442L629 445Q629 451 635 490T641 551Q641 586 628 604T573 629Q568 630 515 631Q469 631 457 630T439 622Q438 621 368 343T298 60Q298 48 386 46Q418 46 427 45T436 36Q436 31 433 22Q429 4 424 1L422 0Q419 0 415 0Q410 0 363 1T228 2Q99 2 64 0H49Q43 6 43 9T45 27Q49 40 55 46H83H94Q174 46 189 55Q190 56 191 56Q196 59 201 76T241 233Q258 301 269 344Q339 619 339 625Q339 630 310 630H279Q212 630 191 624Q146 614 121 583T67 467Q60 445 57 441T43 437H40Z"></path><path stroke-width="1" id="E11-MJMAIN-30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z"></path><path stroke-width="1" id="E11-MJMAIN-35" d="M164 157Q164 133 148 117T109 101H102Q148 22 224 22Q294 22 326 82Q345 115 345 210Q345 313 318 349Q292 382 260 382H254Q176 382 136 314Q132 307 129 306T114 304Q97 304 95 310Q93 314 93 485V614Q93 664 98 664Q100 666 102 666Q103 666 123 658T178 642T253 634Q324 634 389 662Q397 666 402 666Q410 666 410 648V635Q328 538 205 538Q174 538 149 544L139 546V374Q158 388 169 396T205 412T256 420Q337 420 393 355T449 201Q449 109 385 44T229 -22Q148 -22 99 32T50 154Q50 178 61 192T84 210T107 214Q132 214 148 197T164 157Z"></path></defs><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><use xlink:href="#E11-MJMAIN-31" x="0" y="0"></use><use xlink:href="#E11-MJMAIN-2264" x="778" y="0"></use><use xlink:href="#E11-MJMATHI-54" x="1834" y="0"></use><use xlink:href="#E11-MJMAIN-2264" x="2816" y="0"></use><g transform="translate(3873,0)"><use xlink:href="#E11-MJMAIN-31"></use><use xlink:href="#E11-MJMAIN-30" x="500" y="0"></use><use transform="scale(0.707)" xlink:href="#E11-MJMAIN-35" x="1415" y="557"></use></g></g></svg></li>
	<li><svg width="16.912ex" height="2.809ex" viewBox="0 -977.9 7281.6 1209.6" role="img" focusable="false" style="vertical-align: -0.538ex;" aria-hidden="true"><defs><path stroke-width="1" id="E12-MJMAIN-31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path><path stroke-width="1" id="E12-MJMAIN-2264" d="M674 636Q682 636 688 630T694 615T687 601Q686 600 417 472L151 346L399 228Q687 92 691 87Q694 81 694 76Q694 58 676 56H670L382 192Q92 329 90 331Q83 336 83 348Q84 359 96 365Q104 369 382 500T665 634Q669 636 674 636ZM84 -118Q84 -108 99 -98H678Q694 -104 694 -118Q694 -130 679 -138H98Q84 -131 84 -118Z"></path><path stroke-width="1" id="E12-MJMATHI-4E" d="M234 637Q231 637 226 637Q201 637 196 638T191 649Q191 676 202 682Q204 683 299 683Q376 683 387 683T401 677Q612 181 616 168L670 381Q723 592 723 606Q723 633 659 637Q635 637 635 648Q635 650 637 660Q641 676 643 679T653 683Q656 683 684 682T767 680Q817 680 843 681T873 682Q888 682 888 672Q888 650 880 642Q878 637 858 637Q787 633 769 597L620 7Q618 0 599 0Q585 0 582 2Q579 5 453 305L326 604L261 344Q196 88 196 79Q201 46 268 46H278Q284 41 284 38T282 19Q278 6 272 0H259Q228 2 151 2Q123 2 100 2T63 2T46 1Q31 1 31 10Q31 14 34 26T39 40Q41 46 62 46Q130 49 150 85Q154 91 221 362L289 634Q287 635 234 637Z"></path><path stroke-width="1" id="E12-MJMAIN-30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z"></path></defs><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><use xlink:href="#E12-MJMAIN-31" x="0" y="0"></use><use xlink:href="#E12-MJMAIN-2264" x="778" y="0"></use><use xlink:href="#E12-MJMATHI-4E" x="1834" y="0"></use><use xlink:href="#E12-MJMAIN-2264" x="3000" y="0"></use><g transform="translate(4057,0)"><use xlink:href="#E12-MJMAIN-31"></use><use xlink:href="#E12-MJMAIN-30" x="500" y="0"></use><g transform="translate(1001,393)"><use transform="scale(0.707)" xlink:href="#E12-MJMAIN-31"></use><use transform="scale(0.707)" xlink:href="#E12-MJMAIN-30" x="500" y="0"></use><use transform="scale(0.707)" xlink:href="#E12-MJMAIN-30" x="1001" y="0"></use><use transform="scale(0.707)" xlink:href="#E12-MJMAIN-30" x="1501" y="0"></use><use transform="scale(0.707)" xlink:href="#E12-MJMAIN-30" x="2002" y="0"></use><use transform="scale(0.707)" xlink:href="#E12-MJMAIN-30" x="2502" y="0"></use></g></g></g></svg></li>
	<li>It is guaranteed that sum of <svg width="2.064ex" height="2.009ex" viewBox="0 -748.3 888.5 865.1" role="img" focusable="false" style="vertical-align: -0.271ex;" aria-hidden="true"><defs><path stroke-width="1" id="E13-MJMATHI-4E" d="M234 637Q231 637 226 637Q201 637 196 638T191 649Q191 676 202 682Q204 683 299 683Q376 683 387 683T401 677Q612 181 616 168L670 381Q723 592 723 606Q723 633 659 637Q635 637 635 648Q635 650 637 660Q641 676 643 679T653 683Q656 683 684 682T767 680Q817 680 843 681T873 682Q888 682 888 672Q888 650 880 642Q878 637 858 637Q787 633 769 597L620 7Q618 0 599 0Q585 0 582 2Q579 5 453 305L326 604L261 344Q196 88 196 79Q201 46 268 46H278Q284 41 284 38T282 19Q278 6 272 0H259Q228 2 151 2Q123 2 100 2T63 2T46 1Q31 1 31 10Q31 14 34 26T39 40Q41 46 62 46Q130 49 150 85Q154 91 221 362L289 634Q287 635 234 637Z"></path></defs><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><use xlink:href="#E13-MJMATHI-4E" x="0" y="0"></use></g></svg> over all test cases doesn't exceed <svg width="7.489ex" height="2.543ex" viewBox="0 -977.9 3224.4 1094.7" role="img" focusable="false" style="vertical-align: -0.271ex;" aria-hidden="true"><defs><path stroke-width="1" id="E14-MJMAIN-31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path><path stroke-width="1" id="E14-MJMAIN-30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z"></path></defs><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><use xlink:href="#E14-MJMAIN-31"></use><use xlink:href="#E14-MJMAIN-30" x="500" y="0"></use><g transform="translate(1001,393)"><use transform="scale(0.707)" xlink:href="#E14-MJMAIN-31"></use><use transform="scale(0.707)" xlink:href="#E14-MJMAIN-30" x="500" y="0"></use><use transform="scale(0.707)" xlink:href="#E14-MJMAIN-30" x="1001" y="0"></use><use transform="scale(0.707)" xlink:href="#E14-MJMAIN-30" x="1501" y="0"></use><use transform="scale(0.707)" xlink:href="#E14-MJMAIN-30" x="2002" y="0"></use><use transform="scale(0.707)" xlink:href="#E14-MJMAIN-30" x="2502" y="0"></use></g></g></svg>.</li>
</ul>
<table>
    <thead>
        <th>Sample Input</th>
        <th>Sample Output</th>
    </thead>
    <tbody valign="top">
        <td>2<br>203<br>901</td>
        <td>51<br>192</td>
    </tbody>
</table>

### Explanation

<p>Let's consider the first test case.<br>Non-Empty Subsequences we can remove from the given number are : <svg width="20.153ex" height="2.409ex" viewBox="0 -748.3 8677 1037.3" role="img" focusable="false" style="vertical-align: -0.671ex;" aria-hidden="true"><defs><path stroke-width="1" id="E15-MJMAIN-32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z"></path><path stroke-width="1" id="E15-MJMAIN-2C" d="M78 35T78 60T94 103T137 121Q165 121 187 96T210 8Q210 -27 201 -60T180 -117T154 -158T130 -185T117 -194Q113 -194 104 -185T95 -172Q95 -168 106 -156T131 -126T157 -76T173 -3V9L172 8Q170 7 167 6T161 3T152 1T140 0Q113 0 96 17Z"></path><path stroke-width="1" id="E15-MJMAIN-30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z"></path><path stroke-width="1" id="E15-MJMAIN-33" d="M127 463Q100 463 85 480T69 524Q69 579 117 622T233 665Q268 665 277 664Q351 652 390 611T430 522Q430 470 396 421T302 350L299 348Q299 347 308 345T337 336T375 315Q457 262 457 175Q457 96 395 37T238 -22Q158 -22 100 21T42 130Q42 158 60 175T105 193Q133 193 151 175T169 130Q169 119 166 110T159 94T148 82T136 74T126 70T118 67L114 66Q165 21 238 21Q293 21 321 74Q338 107 338 175V195Q338 290 274 322Q259 328 213 329L171 330L168 332Q166 335 166 348Q166 366 174 366Q202 366 232 371Q266 376 294 413T322 525V533Q322 590 287 612Q265 626 240 626Q208 626 181 615T143 592T132 580H135Q138 579 143 578T153 573T165 566T175 555T183 540T186 520Q186 498 172 481T127 463Z"></path></defs><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><use xlink:href="#E15-MJMAIN-32" x="0" y="0"></use><use xlink:href="#E15-MJMAIN-2C" x="500" y="0"></use><use xlink:href="#E15-MJMAIN-30" x="945" y="0"></use><use xlink:href="#E15-MJMAIN-2C" x="1446" y="0"></use><use xlink:href="#E15-MJMAIN-33" x="1891" y="0"></use><use xlink:href="#E15-MJMAIN-2C" x="2391" y="0"></use><g transform="translate(2836,0)"><use xlink:href="#E15-MJMAIN-32"></use><use xlink:href="#E15-MJMAIN-30" x="500" y="0"></use></g><use xlink:href="#E15-MJMAIN-2C" x="3837" y="0"></use><g transform="translate(4283,0)"><use xlink:href="#E15-MJMAIN-32"></use><use xlink:href="#E15-MJMAIN-33" x="500" y="0"></use></g><use xlink:href="#E15-MJMAIN-2C" x="5284" y="0"></use><g transform="translate(5729,0)"><use xlink:href="#E15-MJMAIN-30"></use><use xlink:href="#E15-MJMAIN-33" x="500" y="0"></use></g><use xlink:href="#E15-MJMAIN-2C" x="6730" y="0"></use><g transform="translate(7175,0)"><use xlink:href="#E15-MJMAIN-32"></use><use xlink:href="#E15-MJMAIN-30" x="500" y="0"></use><use xlink:href="#E15-MJMAIN-33" x="1001" y="0"></use></g></g></svg><br>After removing these digits, the resulting numbers are <svg width="17.828ex" height="2.409ex" viewBox="0 -748.3 7676 1037.3" role="img" focusable="false" style="vertical-align: -0.671ex;" aria-hidden="true"><defs><path stroke-width="1" id="E16-MJMAIN-30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z"></path><path stroke-width="1" id="E16-MJMAIN-33" d="M127 463Q100 463 85 480T69 524Q69 579 117 622T233 665Q268 665 277 664Q351 652 390 611T430 522Q430 470 396 421T302 350L299 348Q299 347 308 345T337 336T375 315Q457 262 457 175Q457 96 395 37T238 -22Q158 -22 100 21T42 130Q42 158 60 175T105 193Q133 193 151 175T169 130Q169 119 166 110T159 94T148 82T136 74T126 70T118 67L114 66Q165 21 238 21Q293 21 321 74Q338 107 338 175V195Q338 290 274 322Q259 328 213 329L171 330L168 332Q166 335 166 348Q166 366 174 366Q202 366 232 371Q266 376 294 413T322 525V533Q322 590 287 612Q265 626 240 626Q208 626 181 615T143 592T132 580H135Q138 579 143 578T153 573T165 566T175 555T183 540T186 520Q186 498 172 481T127 463Z"></path><path stroke-width="1" id="E16-MJMAIN-2C" d="M78 35T78 60T94 103T137 121Q165 121 187 96T210 8Q210 -27 201 -60T180 -117T154 -158T130 -185T117 -194Q113 -194 104 -185T95 -172Q95 -168 106 -156T131 -126T157 -76T173 -3V9L172 8Q170 7 167 6T161 3T152 1T140 0Q113 0 96 17Z"></path><path stroke-width="1" id="E16-MJMAIN-32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z"></path></defs><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><use xlink:href="#E16-MJMAIN-30"></use><use xlink:href="#E16-MJMAIN-33" x="500" y="0"></use><use xlink:href="#E16-MJMAIN-2C" x="1001" y="0"></use><g transform="translate(1446,0)"><use xlink:href="#E16-MJMAIN-32"></use><use xlink:href="#E16-MJMAIN-33" x="500" y="0"></use></g><use xlink:href="#E16-MJMAIN-2C" x="2447" y="0"></use><g transform="translate(2892,0)"><use xlink:href="#E16-MJMAIN-32"></use><use xlink:href="#E16-MJMAIN-30" x="500" y="0"></use></g><use xlink:href="#E16-MJMAIN-2C" x="3893" y="0"></use><use xlink:href="#E16-MJMAIN-33" x="4338" y="0"></use><use xlink:href="#E16-MJMAIN-2C" x="4839" y="0"></use><use xlink:href="#E16-MJMAIN-30" x="5284" y="0"></use><use xlink:href="#E16-MJMAIN-2C" x="5784" y="0"></use><use xlink:href="#E16-MJMAIN-32" x="6229" y="0"></use><use xlink:href="#E16-MJMAIN-2C" x="6730" y="0"></use><use xlink:href="#E16-MJMAIN-30" x="7175" y="0"></use></g></svg> respectively. The sum of all the resulting numbers is <svg width="2.325ex" height="2.009ex" viewBox="0 -748.3 1001 865.1" role="img" focusable="false" style="vertical-align: -0.271ex;" aria-hidden="true"><defs><path stroke-width="1" id="E17-MJMAIN-35" d="M164 157Q164 133 148 117T109 101H102Q148 22 224 22Q294 22 326 82Q345 115 345 210Q345 313 318 349Q292 382 260 382H254Q176 382 136 314Q132 307 129 306T114 304Q97 304 95 310Q93 314 93 485V614Q93 664 98 664Q100 666 102 666Q103 666 123 658T178 642T253 634Q324 634 389 662Q397 666 402 666Q410 666 410 648V635Q328 538 205 538Q174 538 149 544L139 546V374Q158 388 169 396T205 412T256 420Q337 420 393 355T449 201Q449 109 385 44T229 -22Q148 -22 99 32T50 154Q50 178 61 192T84 210T107 214Q132 214 148 197T164 157Z"></path><path stroke-width="1" id="E17-MJMAIN-31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path></defs><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><use xlink:href="#E17-MJMAIN-35"></use><use xlink:href="#E17-MJMAIN-31" x="500" y="0"></use></g></svg> which is the answer.</p>
<table>
    <tbody valign="top">
        <tr>
            <th>Time Limit:</th>
            <td>1.0 sec(s) for each input file.</td>
        </tr>
        <tr>
            <th>Memory Limit:</th>
            <td>256 MB</td>
        </tr>
        <tr>
            <th>Source Limit:</th>
            <td>1024 KB</td>
        </tr>
        <tr>
            <th>Marking Scheme:</th>
            <td>Score is assigned if any testcase passes.</td>
        </tr>
        <tr>
            <th>Allowed Languages:</th>
            <td>Bash, C, C++, C++14, C++17, Clojure, C#, D, Erlang, F#, Go, Groovy, Haskell, Java, Java 8, Java 14, JavaScript(Rhino), JavaScript(Node.js), Julia, Kotlin, Lisp, Lisp (SBCL), Lua, Objective-C, OCaml, Octave, Pascal, Perl, PHP, Python, Python 3, Python 3.8, Racket, Ruby, Rust, Scala, Swift-4.1, Swift, TypeScript, Visual Basic</td>
        </tr>        
    </tbody>
</table>