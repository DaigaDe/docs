---
layout: base
title:  'Statistics of nsubj:xsubj in UD_Vietnamese-VTB'
udver: '2'
---

## Treebank Statistics: UD_Vietnamese-VTB: Relations: `nsubj:xsubj`

This relation is a language-specific subtype of <tt><a href="vi_vtb-dep-nsubj.html">nsubj</a></tt>.
There are also 2 other language-specific subtypes of `nsubj`: <tt><a href="vi_vtb-dep-nsubj-nn.html">nsubj:nn</a></tt>, <tt><a href="vi_vtb-dep-nsubj-pass.html">nsubj:pass</a></tt>.

16 nodes (0%) are attached to their parents as `nsubj:xsubj`.

14 instances of `nsubj:xsubj` (88%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.1875.

The following 5 pairs of parts of speech are connected with `nsubj:xsubj`: <tt><a href="vi_vtb-pos-VERB.html">VERB</a></tt>-<tt><a href="vi_vtb-pos-NOUN.html">NOUN</a></tt> (11; 69% instances), <tt><a href="vi_vtb-pos-VERB.html">VERB</a></tt>-<tt><a href="vi_vtb-pos-PROPN.html">PROPN</a></tt> (2; 13% instances), <tt><a href="vi_vtb-pos-NOUN.html">NOUN</a></tt>-<tt><a href="vi_vtb-pos-VERB.html">VERB</a></tt> (1; 6% instances), <tt><a href="vi_vtb-pos-PROPN.html">PROPN</a></tt>-<tt><a href="vi_vtb-pos-VERB.html">VERB</a></tt> (1; 6% instances), <tt><a href="vi_vtb-pos-VERB.html">VERB</a></tt>-<tt><a href="vi_vtb-pos-PRON.html">PRON</a></tt> (1; 6% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 2 nsubj:xsubj	color:blue
1	Xin	xin	VERB	V	_	0	root	_	_
2	tòa	tòa	NOUN	N	_	3	nsubj:xsubj	_	_
3	bảo	bảo	VERB	V	_	1	xcomp	_	_
4	nó	nó	PRON	Pro	_	5	nsubj	_	_
5	trả	trả	VERB	V	_	3	ccomp	_	_
6	lại	lại	ADV	Adv	_	5	advmod	_	_
7	cho	cho	ADP	Pre	_	8	case	_	_
8	tôi	tôi	PRON	Pro	_	5	obl:iobj	_	_
9	"	"	PUNCT	``	_	1	punct	_	_
10	.	.	PUNCT	.	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 11 10 nsubj:xsubj	color:blue
1	Cô gái	cô gái	NOUN	N	_	2	nsubj	_	_
2	tỉnh ngộ	tỉnh ngộ	VERB	V	_	0	root	_	_
3	dần	dần	ADV	Adv	_	2	advmod	_	_
4	và	và	CCONJ	CC	_	5	cc	_	_
5	thú thật	thú thật	VERB	V	_	2	conj	_	_
6	đã	đã	ADV	Adv	_	7	advmod	_	_
7	trực tiếp	trực tiếp	VERB	V	_	5	xcomp	_	_
8	nhìn	nhìn	VERB	V	_	7	xcomp	_	_
9	thấy	thấy	VERB	V	_	8	compound:svc	_	_
10	tuấn	tuấn	PROPN	NNP	_	11	nsubj:xsubj	_	_
11	hít	hít	VERB	V	_	8	ccomp	_	_
12	heroin	heroin	NOUN	Nb	_	11	obj	_	_
13	.	.	PUNCT	.	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 9 nsubj:xsubj	color:blue
1	Thương	thương	VERB	V	_	7	advcl	_	_
2	con	con	NOUN	N	_	1	obj	_	_
3	,	,	PUNCT	,	_	1	punct	_	_
4	năm	năm	NOUN	N	_	7	obl:tmod	_	_
5	1990	1990	NUM	Num	_	4	nummod	_	_
6	ông	ông	NOUN	N	_	7	nsubj	_	_
7	đưa	đưa	VERB	V	_	0	root	_	_
8	cô	cô	NOUN	N	_	7	obj	_	_
9	về	về	VERB	V	_	8	nsubj:xsubj	_	_
10	Hà Nội	Hà Nội	PROPN	NNP	_	9	obj	_	_
11	xin	xin	VERB	V	_	7	xcomp	_	_
12	vào	vào	VERB	V	_	11	compound:dir	_	_
13	trường	trường	NOUN	N	_	12	obj	_	_
14	Nguyễn Đình Chiểu	Nguyễn Đình Chiểu	PROPN	NNP	_	13	nmod	_	_
15	học	học	VERB	V	_	12	advcl:objective	_	_
16	chữ nổi	chữ nổi	NOUN	N	_	15	obj	_	_
17	.	.	PUNCT	.	_	7	punct	_	_

~~~


