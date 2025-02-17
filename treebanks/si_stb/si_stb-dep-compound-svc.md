---
layout: base
title:  'Statistics of compound:svc in UD_Sinhala-STB'
udver: '2'
---

## Treebank Statistics: UD_Sinhala-STB: Relations: `compound:svc`

This relation is a language-specific subtype of <tt><a href="si_stb-dep-compound.html">compound</a></tt>.
There are also 2 other language-specific subtypes of `compound`: <tt><a href="si_stb-dep-compound-lvc.html">compound:lvc</a></tt>, <tt><a href="si_stb-dep-compound-prt.html">compound:prt</a></tt>.

14 nodes (2%) are attached to their parents as `compound:svc`.

11 instances of `compound:svc` (79%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.

The following 2 pairs of parts of speech are connected with `compound:svc`: <tt><a href="si_stb-pos-VERB.html">VERB</a></tt>-<tt><a href="si_stb-pos-VERB.html">VERB</a></tt> (13; 93% instances), <tt><a href="si_stb-pos-NOUN.html">NOUN</a></tt>-<tt><a href="si_stb-pos-VERB.html">VERB</a></tt> (1; 7% instances).


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 7 compound:svc	color:blue
1	ෆොන්සේකා	ෆොන්සේකා	PROPN	_	Case=Nom|Gender=Masc|Number=Sing|Person=3	6	nsubj	_	_
2	මහතා	මහතා	NOUN	_	Case=Nom|Definite=Def|Gender=Masc|Number=Sing|Person=3	1	flat	_	_
3	ද	ද	PART	_	AdpType=Post	6	advmod	_	_
4	හමුදාවේ	හමුදාව	NOUN	_	Case=Gen|Definite=Def|Gender=Masc|Number=Sing	5	nmod:poss	_	_
5	සෙබළුන්	සෙබළ	NOUN	_	Case=Acc|Gender=Masc|Number=Plur	6	obj	_	_
6	පාවා	පාව	VERB	_	VerbForm=Part|Voice=Act	0	root	_	_
7	දී	දෙ	VERB	_	Aspect=Perf|Mood=Ind|VerbForm=Part	6	compound:svc	_	_
8	තිබේ	තිබ	AUX	_	Tense=Pres|VerbForm=Fin	7	aux	_	_
9	.	.	PUNCT	_	_	6	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 5 compound:svc	color:blue
1	එසේ	එසේ	ADV	_	AdvType=Man	2	advmod	_	_
2	ගිය	ය	VERB	_	Tense=Past|VerbForm=Part	4	acl	_	_
3	සෑම	සෑම	DET	_	_	4	det	_	_
4	කෙනාම	කෙනා	NOUN	_	Animacy=Anim|Case=Nom|Definite=Def|Gender=Masc|Number=Sing	8	nsubj	_	_
5	පාවා	පාව	VERB	_	Tense=Past|VerbForm=Part	6	compound:svc	_	_
6	දෙන්නකු	දෙන	NOUN	_	Animacy=Anim|Case=Acc|Definite=Ind|Gender=Masc|Number=Sing	8	obj	_	_
7	ලෙස	ලෙස	PART	_	AdpType=Post	6	case	_	_
8	සැලකේ	සලක	VERB	_	Mood=Ind|Tense=Pres|VerbForm=Fin|Voice=Pass	0	root	_	_
9	.	.	PUNCT	_	_	8	punct	_	_

~~~


