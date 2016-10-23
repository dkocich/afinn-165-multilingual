# AFINN-165-multilingual

This project contains translation of AFINN-165 keyword list (saved as AFINN-165-en.json) originally available at https://github.com/fnielsen/afinn

The Google Translate API enables to translate text to 100+ different languages (full and up to date list is available in the API documentation https://cloud.google.com/translate/docs/languages).
Each language is stored in its own minified JSON file.
For completeness, the full list of ISO 839-1 language codes currently are:

af, am, ar, az, be, bg, bn, bs, ca, ceb, co, cs, cy, da, de, el, en, eo, es, et, eu, fa, fi, fr, fy, ga, gd, gl, gu, ha, haw, hi, hmn, hr, ht, hu, hy, id, ig, it, iw, ja, jw, ka, kk, km, kn, ko, ku, ky, la, lb, lo, lt, lv, mg, mi, mk, ml, mn, mr, ms, mt, my, ne, nl, no, ny, pa, pl, ps, pt, ro, ru, sd, si, sk, sl, sm, sn, so, sq, sr, st, su, sv, sw, ta, te, tg, th, tl, tr, uk, ur, uz, vi, xh, yi, yo, zh, zu.

## Known problems
- wordlists contain less translated words than the original file (API returns only one top match per translated word)
- it was not possible to translated some languages using the API (is, zh-tw)

## Attribution (thanks for the great tool!)
https://cloud.google.com/translate/attribution
http://translate.google.com/

THIS SERVICE MAY CONTAIN TRANSLATIONS POWERED BY GOOGLE. GOOGLE DISCLAIMS ALL WARRANTIES RELATED TO THE TRANSLATIONS, EXPRESS OR IMPLIED, INCLUDING ANY WARRANTIES OF ACCURACY, RELIABILITY, AND ANY IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.