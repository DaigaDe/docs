---
layout: base
title:  'Statistics of mark in UD_Sinhala-STB'
udver: '2'
---

## Treebank Statistics: UD_Sinhala-STB: Relations: `mark`

This relation is universal.

2 nodes (0%) are attached to their parents as `mark`.

2 instances of `mark` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.

The following 2 pairs of parts of speech are connected with `mark`: <tt><a href="si_stb-pos-ADJ.html">ADJ</a></tt>-<tt><a href="si_stb-pos-PART.html">PART</a></tt> (1; 50% instances), <tt><a href="si_stb-pos-NOUN.html">NOUN</a></tt>-<tt><a href="si_stb-pos-ADP.html">ADP</a></tt> (1; 50% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 4 mark	color:blue
1	අනෙකුත්	අනෙක්	DET	_	_	2	det	_	_
2	සමාගම්	සමාගම්	NOUN	_	Animacy=Inan|Case=Nom|Gender=Neut|Number=Plur	6	nsubj	_	_
3	නුසුදුසු	නුසුදුසු	ADJ	_	Degree=Pos	5	dep	_	_
4	බව	බව	PART	_	AdpType=Post	3	mark	_	_
5	පවසා	පවස	VERB	_	Tense=Past|VerbForm=Part	6	dep	_	_
6	ප්‍රතික්ෂේප	ප්‍රතික්ෂේප	NOUN	_	_	0	root	_	_
7	කර	කර	VERB	_	Tense=Past|VerbForm=Part	6	compound:lvc	_	_
8	ඇත	ඇත	AUX	_	Aspect=Perf|VerbForm=Fin	7	aux	_	_
9	.	.	PUNCT	_	_	6	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 5 mark	color:blue
1	එය	එය	PRON	_	Case=Nom|Number=Sing|PronType=Dem	9	obj	_	_
2	හුදු	හුදු	ADJ	_	Degree=Pos	4	amod	_	_
3	දේශපාලන	දේශපාලන	NOUN	_	Case=Nom|Gender=Neut	4	nmod	_	_
4	කයිවාරුවක්	කයිවාරු	NOUN	_	Case=Acc|Definite=Ind|Gender=Neut|Number=Sing	9	obl	_	_
5	යැයි	යැයි	ADP	_	_	4	mark	_	_
6	තවත්	තව	DET	_	_	7	det	_	_
7	අය	අය	NOUN	_	Animacy=Anim|Case=Nom|Definite=Def	9	nsubj	_	_
8	දැඩි	දැඩි	ADJ	_	Degree=Pos	9	advmod	_	_
9	විවේචන	විවේචන	NOUN	_	Case=Nom|Gender=Neut|Number=Plur	0	root	_	_
10	කළහ	කර	VERB	_	Mood=Ind|Person=3|Tense=Past|VerbForm=Fin|Voice=Act	9	compound:lvc	_	_
11	.	.	PUNCT	_	_	9	punct	_	_

~~~


