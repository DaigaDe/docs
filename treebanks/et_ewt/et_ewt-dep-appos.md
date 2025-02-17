---
layout: base
title:  'Statistics of appos in UD_Estonian-EWT'
udver: '2'
---

## Treebank Statistics: UD_Estonian-EWT: Relations: `appos`

This relation is universal.

224 nodes (0%) are attached to their parents as `appos`.

224 instances of `appos` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 2.06696428571429.

The following 13 pairs of parts of speech are connected with `appos`: <tt><a href="et_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="et_ewt-pos-PROPN.html">PROPN</a></tt> (111; 50% instances), <tt><a href="et_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="et_ewt-pos-NOUN.html">NOUN</a></tt> (69; 31% instances), <tt><a href="et_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="et_ewt-pos-NUM.html">NUM</a></tt> (11; 5% instances), <tt><a href="et_ewt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="et_ewt-pos-NOUN.html">NOUN</a></tt> (11; 5% instances), <tt><a href="et_ewt-pos-PRON.html">PRON</a></tt>-<tt><a href="et_ewt-pos-NOUN.html">NOUN</a></tt> (7; 3% instances), <tt><a href="et_ewt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="et_ewt-pos-NOUN.html">NOUN</a></tt> (3; 1% instances), <tt><a href="et_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="et_ewt-pos-X.html">X</a></tt> (3; 1% instances), <tt><a href="et_ewt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="et_ewt-pos-PROPN.html">PROPN</a></tt> (2; 1% instances), <tt><a href="et_ewt-pos-ADV.html">ADV</a></tt>-<tt><a href="et_ewt-pos-NOUN.html">NOUN</a></tt> (2; 1% instances), <tt><a href="et_ewt-pos-PRON.html">PRON</a></tt>-<tt><a href="et_ewt-pos-PRON.html">PRON</a></tt> (2; 1% instances), <tt><a href="et_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="et_ewt-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="et_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="et_ewt-pos-ADV.html">ADV</a></tt> (1; 0% instances), <tt><a href="et_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="et_ewt-pos-VERB.html">VERB</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 2 appos	color:blue
1	Brasiilane	brasiillane	NOUN	S	Case=Nom|Number=Sing|Typo=Yes	0	root	0:root	CorrectForm=Brasiillane
2	Kaisei	Kaisei	PROPN	S	Case=Nom|Number=Sing	1	appos	1:appos	NE=B-Per|SpaceAfter=No
3	,	,	PUNCT	Z	_	4	punct	4:punct	_
4	Takarafuji	Takarafuji	PROPN	S	Case=Nom|Number=Sing	1	conj	1:conj	NE=B-Per|SpaceAfter=No
5	,	,	PUNCT	Z	_	6	punct	6:punct	_
6	Takayasu	Takayasu	PROPN	S	Case=Nom|Number=Sing	1	conj	1:conj	NE=B-Per
7	ning	ning	CCONJ	J	_	8	cc	8:cc	_
8	Tochinowaka	Tochinowaka	PROPN	S	Case=Nom|Number=Sing	1	conj	1:conj	NE=B-Per|SpaceAfter=No
9	.	.	PUNCT	Z	_	1	punct	1:punct	_

~~~


~~~ conllu
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 9 appos	color:blue
1	Kas	kas	ADV	D	_	5	advmod	5:advmod	_
2	Delfi	Delfi	PROPN	S	Case=Nom|Number=Sing	5	nsubj	5:nsubj	NE=B-Org
3	ei	ei	AUX	V	Polarity=Neg	5	aux	5:aux	_
4	võiks	võima	AUX	V	Mood=Cnd|Tense=Pres|VerbForm=Fin|Voice=Act	5	aux	5:aux	_
5	tekitada	tekitama	VERB	V	VerbForm=Inf	0	root	0:root	_
6	eraldi	eraldi	ADV	D	_	7	advmod	7:advmod	_
7	rubriiki	rubriik	NOUN	S	Case=Par|Number=Sing	5	obj	5:obj	_
8	"	"	PUNCT	Z	_	9	punct	9:punct	SpaceAfter=No
9	tehnika	tehnika	NOUN	S	Case=Nom|Number=Sing	7	appos	7:appos	SpaceAfter=No
10	"	"	PUNCT	Z	_	9	punct	9:punct	_

~~~


~~~ conllu
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 9 appos	color:blue
1	pipa	pipa	PROPN	S	Case=Nom|Number=Sing	3	parataxis	3:parataxis	NE=B-Per|SpaceAfter=No
2	:	:	PUNCT	Z	_	1	punct	1:punct	_
3	võta	võtma	VERB	V	Mood=Imp|Number=Sing|Person=2|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	0:root	_
4	sirvi	sirvima	VERB	V	Mood=Imp|Number=Sing|Person=2|Tense=Pres|VerbForm=Fin|Voice=Act	3	conj	3:conj	_
5	nt.	nt	NOUN	Y	Abbr=Yes	8	nmod	8:nmod	_
6	george	George	PROPN	S	Case=Nom|Number=Sing	8	nmod	8:nmod	NE=B-Per
7	orwelli	Orwell	PROPN	S	Case=Gen|Number=Sing	6	flat	6:flat	NE=I-Per
8	raamatut	raamat	NOUN	S	Case=Par|Number=Sing	4	obj	4:obj	NE=B-Prod
9	'1984'	'1984'	NUM	N	NumForm=Digit|NumType=Card	8	appos	8:appos	NE=I-Prod

~~~


