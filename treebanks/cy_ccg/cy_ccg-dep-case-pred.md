---
layout: base
title:  'Statistics of case:pred in UD_Welsh-CCG'
udver: '2'
---

## Treebank Statistics: UD_Welsh-CCG: Relations: `case:pred`

This relation is a language-specific subtype of <tt><a href="cy_ccg-dep-case.html">case</a></tt>.

660 nodes (2%) are attached to their parents as `case:pred`.

660 instances of `case:pred` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.06363636363636.

The following 8 pairs of parts of speech are connected with `case:pred`: <tt><a href="cy_ccg-pos-ADJ.html">ADJ</a></tt>-<tt><a href="cy_ccg-pos-PART.html">PART</a></tt> (422; 64% instances), <tt><a href="cy_ccg-pos-NOUN.html">NOUN</a></tt>-<tt><a href="cy_ccg-pos-PART.html">PART</a></tt> (211; 32% instances), <tt><a href="cy_ccg-pos-ADV.html">ADV</a></tt>-<tt><a href="cy_ccg-pos-PART.html">PART</a></tt> (13; 2% instances), <tt><a href="cy_ccg-pos-NUM.html">NUM</a></tt>-<tt><a href="cy_ccg-pos-PART.html">PART</a></tt> (8; 1% instances), <tt><a href="cy_ccg-pos-NOUN.html">NOUN</a></tt>-<tt><a href="cy_ccg-pos-ADP.html">ADP</a></tt> (3; 0% instances), <tt><a href="cy_ccg-pos-PROPN.html">PROPN</a></tt>-<tt><a href="cy_ccg-pos-ADP.html">ADP</a></tt> (1; 0% instances), <tt><a href="cy_ccg-pos-PROPN.html">PROPN</a></tt>-<tt><a href="cy_ccg-pos-PART.html">PART</a></tt> (1; 0% instances), <tt><a href="cy_ccg-pos-SYM.html">SYM</a></tt>-<tt><a href="cy_ccg-pos-PART.html">PART</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 6 case:pred	color:blue
1	Mae	bod	AUX	aux	Mood=Ind|Number=Sing|Person=3|Tense=Pres	7	cop	_	SpaceAfter=No
2	'r	y	DET	art	_	3	det	_	_
3	duw	duw	NOUN	noun	Gender=Masc|Number=Sing	7	nsubj	_	_
4	hwn	hwn	PRON	dem	Gender=Masc|PronType=Dem	3	amod	_	_
5	hefyd	hefyd	ADV	adv	_	7	advmod	_	_
6	yn	yn	PART	pred	_	7	case:pred	_	_
7	gysylltiedig	cysylltiedig	ADJ	pos	Degree=Pos|Mutation=SM	0	root	_	_
8	ag	ag	ADP	prep	_	9	case	_	_
9	amser	amser	NOUN	noun	Gender=Masc|Number=Sing	7	obl	_	_
10	a	a	CCONJ	cconj	_	11	cc	_	_
11	henaint	henaint	NOUN	noun	Gender=Masc|Number=Sing	9	conj	_	SpaceAfter=No
12	.	.	PUNCT	punct	_	7	punct	_	SpacesAfter=\s\n

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 2 case:pred	color:blue
1	Mae	bod	AUX	aux	Mood=Ind|Number=Sing|Person=3|Tense=Pres	3	cop	_	SpaceAfter=No
2	'n	yn	PART	pred	_	3	case:pred	_	_
3	rhaid	rhaid	NOUN	noun	Gender=Masc|Number=Sing	0	root	_	_
4	i	i	ADP	prep	_	5	case	_	_
5	ti	ti	PRON	indep	Number=Sing|Person=2|PronType=Prs	6	nsubj	_	_
6	ddod	dod	NOUN	verbnoun	Mutation=SM|Number=Sing|VerbForm=Vnoun	3	acl	_	_
7	cyn	cyn	ADP	prep	_	8	case	_	_
8	yfory	yfory	ADV	adv	_	6	advmod	_	SpaceAfter=No
9	.	.	PUNCT	punct	_	3	punct	_	SpacesAfter=\n

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 6 case:pred	color:blue
1	Yr	y	DET	art	_	2	det	_	_
2	addysg	addysg	NOUN	noun	Gender=Fem|Number=Sing	9	nsubj	_	_
3	gorau	da	ADJ	sup	Degree=Sup	2	amod	_	_
4	i	i	ADP	prep	_	5	case	_	_
5	blentyn	plentyn	NOUN	noun	Gender=Masc|Mutation=SM|Number=Sing	2	nmod	_	_
6	yn	yn	PART	pred	_	7	case:pred	_	_
7	aml	aml	ADV	adv	_	5	advmod	_	_
8	yw	bod	AUX	aux	Mood=Ind|Number=Sing|Person=3|Tense=Pres	9	cop	_	_
9	addysg	addysg	NOUN	noun	Gender=Fem|Number=Sing	0	root	_	_
10	mewn	mewn	ADP	prep	_	11	case	_	_
11	ysgol	ysgol	NOUN	noun	Gender=Fem|Number=Sing	9	nmod	_	_
12	leol	lleol	ADJ	pos	Degree=Pos|Gender=Fem|Mutation=SM|Number=Sing	11	amod	_	SpaceAfter=No
13	.	.	PUNCT	punct	_	9	punct	_	_

~~~


