---
layout: base
title:  'Statistics of advmod:emph in UD_Czech-CLTT'
udver: '2'
---

## Treebank Statistics: UD_Czech-CLTT: Relations: `advmod:emph`

This relation is a language-specific subtype of <tt><a href="cs_cltt-dep-advmod.html">advmod</a></tt>.

294 nodes (1%) are attached to their parents as `advmod:emph`.

294 instances of `advmod:emph` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.26530612244898.

The following 14 pairs of parts of speech are connected with `advmod:emph`: <tt><a href="cs_cltt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="cs_cltt-pos-ADV.html">ADV</a></tt> (146; 50% instances), <tt><a href="cs_cltt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="cs_cltt-pos-CCONJ.html">CCONJ</a></tt> (58; 20% instances), <tt><a href="cs_cltt-pos-X.html">X</a></tt>-<tt><a href="cs_cltt-pos-PART.html">PART</a></tt> (28; 10% instances), <tt><a href="cs_cltt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="cs_cltt-pos-PART.html">PART</a></tt> (25; 9% instances), <tt><a href="cs_cltt-pos-NUM.html">NUM</a></tt>-<tt><a href="cs_cltt-pos-ADV.html">ADV</a></tt> (14; 5% instances), <tt><a href="cs_cltt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="cs_cltt-pos-ADV.html">ADV</a></tt> (6; 2% instances), <tt><a href="cs_cltt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="cs_cltt-pos-CCONJ.html">CCONJ</a></tt> (4; 1% instances), <tt><a href="cs_cltt-pos-ADV.html">ADV</a></tt>-<tt><a href="cs_cltt-pos-ADV.html">ADV</a></tt> (4; 1% instances), <tt><a href="cs_cltt-pos-VERB.html">VERB</a></tt>-<tt><a href="cs_cltt-pos-ADV.html">ADV</a></tt> (3; 1% instances), <tt><a href="cs_cltt-pos-ADV.html">ADV</a></tt>-<tt><a href="cs_cltt-pos-CCONJ.html">CCONJ</a></tt> (2; 1% instances), <tt><a href="cs_cltt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="cs_cltt-pos-PART.html">PART</a></tt> (1; 0% instances), <tt><a href="cs_cltt-pos-ADV.html">ADV</a></tt>-<tt><a href="cs_cltt-pos-PART.html">PART</a></tt> (1; 0% instances), <tt><a href="cs_cltt-pos-DET.html">DET</a></tt>-<tt><a href="cs_cltt-pos-ADV.html">ADV</a></tt> (1; 0% instances), <tt><a href="cs_cltt-pos-SYM.html">SYM</a></tt>-<tt><a href="cs_cltt-pos-ADV.html">ADV</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 2 advmod:emph	color:blue
1	Obsahuje	obsahovat	VERB	VB-S---3P-AA---	Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	_
2	zejména	zejména	ADV	Db-------------	_	3	advmod:emph	_	_
3	závazky	závazek	NOUN	NNIP4-----A----	Animacy=Inan|Case=Acc|Gender=Masc|Number=Plur|Polarity=Pos	1	obj	_	_
4	z	z	ADP	RR--2----------	AdpType=Prep|Case=Gen	6	case	_	LId=z-1
5	dlouhodobých	dlouhodobý	ADJ	AAFP2----1A----	Case=Gen|Degree=Pos|Gender=Fem|Number=Plur|Polarity=Pos	6	amod	_	_
6	půjček	půjčka	NOUN	NNFP2-----A----	Case=Gen|Gender=Fem|Number=Plur|Polarity=Pos	3	nmod	_	_
7	a	a	CCONJ	J^-------------	_	8	cc	_	LId=a-1
8	úvěrů	úvěr	NOUN	NNIP2-----A----	Animacy=Inan|Case=Gen|Gender=Masc|Number=Plur|Polarity=Pos	6	conj	_	SpaceAfter=No
9	.	.	PUNCT	Z:-------------	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 4 advmod:emph	color:blue
1	Vykazují	vykazovat	VERB	VB-P---3P-AA---	Mood=Ind|Number=Plur|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	_
2	se	se	PRON	P7-X4----------	Case=Acc|PronType=Prs|Reflex=Yes|Variant=Short	1	expl:pv	_	_
3	zde	zde	ADV	Db-------------	PronType=Dem	1	advmod	_	_
4	i	i	CCONJ	J^-------------	_	7	advmod:emph	_	LId=i-1
5	nakoupené	nakoupený	ADJ	AAIP1----1A----	Animacy=Inan|Case=Nom|Degree=Pos|Gender=Masc|Number=Plur|Polarity=Pos	7	amod	_	_
6	opční	opční	ADJ	AAIP1----1A----	Animacy=Inan|Case=Nom|Degree=Pos|Gender=Masc|Number=Plur|Polarity=Pos	7	amod	_	_
7	listy	list	NOUN	NNIP1-----A----	Animacy=Inan|Case=Nom|Gender=Masc|Number=Plur|Polarity=Pos	1	nsubj	_	SpaceAfter=No
8	.	.	PUNCT	Z:-------------	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 19	bgColor:blue
# visual-style 19	fgColor:white
# visual-style 21	bgColor:blue
# visual-style 21	fgColor:white
# visual-style 21 19 advmod:emph	color:blue
1	V	v	ADP	RR--6----------	AdpType=Prep|Case=Loc	2	case	_	LId=v-1
2	případech	případ	NOUN	NNIP6-----A----	Animacy=Inan|Case=Loc|Gender=Masc|Number=Plur|Polarity=Pos	9	obl	_	_
3	uvedených	uvedený	ADJ	AAIP6----1A----	Animacy=Inan|Case=Loc|Degree=Pos|Gender=Masc|Number=Plur|Polarity=Pos	2	amod	_	_
4	v	v	ADP	RR--6----------	AdpType=Prep|Case=Loc	5	case	_	LId=v-1
5	odstavci	odstavec	NOUN	NNIS6-----A----	Animacy=Inan|Case=Loc|Gender=Masc|Number=Sing|Polarity=Pos	3	obl	_	_
6	2	2	NUM	C}-------------	NumForm=Roman|NumType=Card	5	nummod	_	_
7	účetní	účetní	ADJ	AAFP1----1A----	Case=Nom|Degree=Pos|Gender=Fem|Number=Plur|Polarity=Pos	8	amod	_	LId=účetní-1
8	jednotky	jednotka	NOUN	NNFP1-----A----	Case=Nom|Gender=Fem|Number=Plur|Polarity=Pos	9	nsubj	_	_
9	mohou	moci	VERB	VB-P---3P-AA--1	Mood=Ind|Number=Plur|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	_
10	provádět	provádět	VERB	Vf--------A----	Polarity=Pos|VerbForm=Inf	9	xcomp	_	_
11	inventarizaci	inventarizace	NOUN	NNFS4-----A----	Case=Acc|Gender=Fem|Number=Sing|Polarity=Pos	10	obj	_	_
12	i	i	CCONJ	J^-------------	_	16	advmod:emph	_	LId=i-1
13	v	v	ADP	RR--6----------	AdpType=Prep|Case=Loc	16	case	_	LId=v-1
14	průběhu	průběh	NOUN	NNIS6-----A----	Animacy=Inan|Case=Loc|Gender=Masc|Number=Sing|Polarity=Pos	13	fixed	_	_
15	účetního	účetní	ADJ	AANS2----1A----	Case=Gen|Degree=Pos|Gender=Neut|Number=Sing|Polarity=Pos	16	amod	_	LId=účetní-1
16	období	období	NOUN	NNNS2-----A----	Case=Gen|Gender=Neut|Number=Sing|Polarity=Pos	10	obl	_	_
17	(	(	PUNCT	Z:-------------	_	9	punct	_	SpaceAfter=No
18	dále	dále	ADV	Db------------1	_	9	dep	_	LId=dále-3
19	jen	jen	PART	TT-------------	_	21	advmod:emph	_	LId=jen-1
20	„	"	PUNCT	Z:-------------	_	21	punct	_	SpaceAfter=No
21	průběžná	průběžná	X	X@-------------	_	9	dep	_	LGloss=(from_multi_word_term)
22	inventarizace	inventarizace	X	X@-------------	_	21	nmod	_	SpaceAfter=No|LGloss=(from_multi_word_term)
23	“	"	PUNCT	Z:-------------	_	21	punct	_	SpaceAfter=No
24	)	)	PUNCT	Z:-------------	_	9	punct	_	SpaceAfter=No
25	.	.	PUNCT	Z:-------------	_	9	punct	_	_

~~~


