---
layout: base
title:  'Malayalam UD'
udver: '2'
---

# UD for Malayalam <span class="flagspan"><img class="flag" src="../../flags/svg/IN.svg" /></span>

## Tokenization and Word Segmentation

* In general, words are delimited by whitespace characters or punctuations.
* Multiword tokens are relatively common in Malayalam. In the following situations, we understand orthographic tokens
  as corresponding to multiple syntactic words and split them:
  * The copula ആക് / _āk_ “to be” is written as a suffix of the nominal/adjectival predicate. However, sometimes
    it is suffixed to another word in the clause, indicating that it is a clitic rather than a derivational morpheme
    that would derive a verb from a noun/adjective.
  * The quotative particle or the complimentizer എന്ന് / _enn_ “that” usually occurs as a suffix of the verb or the
    copula. Given that we split the copula as a syntactic word, we split the complementizer as well. (Also, it
    increases parallelism with languages where complementizers are independent words, and avoids having to define a
    language-specific feature for verb with complementizer.)
  * The coordinating clitics -ഉം / _-um_ and -ഓ / _-ō_ are written together with conjuncts but analyzed as separate
    syntactic words.
  * In orthography sometimes the object and the verb of a sentence occur as a multiword token. For example, in the
    sentence പെൺകുട്ടി തന്റെ സുഹൃത്തിന് കത്തെഴുതി. / _peṇkuṭṭi tanṟe suhr̥ttin katteḻuti._
    “The girl wrote a letter to her friend.”, കത്ത് / _katt_ “letter” and എഴുതി / _eḻuti_ ”wrote” occur as a multiword
    token and are split.

## Morphology

### Tags

* Malayalam uses all the 17 POS tags, including particles ([PART]()).
* The noun tag [NOUN]() is intended for common nouns only.
  Abstract nouns are also tagged `NOUN`.
  The nouns in Malayalam are marked for case and number.
* Proper nouns include the name of a specific individual, place, or object and are tagged [PROPN]().
* Pronouns are tagged [PRON](). The nominal reflexive താൻ / _tān_ is also tagged `PRON`.
* The numeral “one” which functions as the indefinite article is tagged [DET](). For example, ഒരു വീട് / _oru vīṭ_ “a house”.
  Quantifiers like ഒരുപാട് / _orupāṭ_ “a lot” that act as modifiers are also tagged `DET`.
* Cardinal numbers (including ഒരു / _ŏru_ “one” if it denotes primarily quantity) are tagged [NUM]().
* The emphatic markers -ഏ / _-ē_ and തന്നേ / _tannē_, the coordination clitics -ഉം / _-um_ and ഓ / _-ō_, and the quotative particle എന്ന് / _enn_ are tagged [PART]().
* The tag [ADJ]() covers both free adjectives, such as പഴയ / _paḻaya_ “old”,
  and derived adjectives, such as സന്തോഷകരമായ / _santōṣakaramāya_ “pleasant”.
* The tag [ADV]() covers adverbs like സങ്കടത്തോടെ / _saṅkaṭattōṭe_ “sadly”, തീർച്ചയായും / _tīṟ̕ccayāyuṁ_ “certainly”.
* Finite and nonfinite verb forms are tagged [VERB]() or [AUX]().
* Malayalam has the following auxiliary verbs [AUX]():
  *  ആക് / _āk_ “to be” is used as a copula to denote existential and stative meanings.
  It can also function as lexical verb conveying the meanings of “to have”, “to take place”, “to be able to”.
  *  ഉണ്ട് / _uṇṭ_ “to be” is used as a copula to denote existential and stative meanings but additionally it has a possessive meaning ‘to have’.
  * Modal auxiliaries:
    * കഴിയുക / _kaḻiyuka_ “to be able, can”
    * വേണം / _vēṇaṁ_ “want”
* There are four main (de)verbal forms, distinguished by the UPOS tag and the value of the VerbForm feature:
  * Finite verb [Fin](/u/feat/VerbForm.html#Fin), tagged [VERB]() or [AUX]().
    It is marked for [Tense]() and it can occur in the main clause without an auxiliary.
  * Nominalized form of a verb is annotated as [Vnoun](/u/feat/VerbForm.html#Vnoun) with the UPOS [VERB]().
    These forms (sometimes also called gerunds in the literature) end in -ത് / _-t_. Despite being nominalized,
    they are marked for [Tense]() and assign the nominative case to their subjects. They occur with the
    auxiliary ആക് / _āk_ “to be”. <!-- DZ: I would contrast them with the deverbal nouns that are tagged [NOUN]() but I do not know any example so far. -->
  * Infinitive [Inf](/u/feat/VerbForm.html#Inf), tagged `VERB` or `AUX`.
  * Participle [Part](/u/feat/VerbForm.html#Part), tagged `VERB` or `AUX`.

### Nominal Features

* Inherent [Gender]() of nouns determines which personal pronoun can refer to the noun, and it is sometimes reflected
  as agreement on adjectives. It is not reflected on verbs (unlike in related Tamil). We do not annotate the gender
  of nouns in data but we do so for third-person pronouns with one of three values:
  [Masc](https://universaldependencies.org/u/feat/Gender.html#Masc),
  [Fem](https://universaldependencies.org/u/feat/Gender.html#Fem) or
  [Neut](https://universaldependencies.org/u/feat/Gender.html#Neut).
* Like `Gender`, [Animacy]() is also an inherent feature of nominal words ([NOUN](), [PROPN](), and [PRON]()). It has
  two values:
  [Anim](https://universaldependencies.org/u/feat/Animacy.html#Anim) and
  [Inan](https://universaldependencies.org/u/feat/Animacy.html#Inan).
  Animacy is grammatically relevant because inanimate nouns may occur without accusative marking when used ad direct
  objects. Animates include nouns denoting persons, animals, or trees.
* The two values of [Number]() are
  [Sing](https://universaldependencies.org/u/feat/Number.html#Sing) and
  [Plur](https://universaldependencies.org/u/feat/Number.html#Plur).
  The following parts of speech inflect for number: [NOUN](), [PROPN](), [PRON](). There is no agreement in `Number`,
  that is, the number of nouns is not reflected in the form of verbs or adjectives.
* [Case]() has 13 possible values:
  [Nom](https://universaldependencies.org/u/feat/Case.html#Nom),
  [Acc](https://universaldependencies.org/u/feat/Case.html#Acc),
  [Gen](https://universaldependencies.org/u/feat/Case.html#Gen),
  [Dat](https://universaldependencies.org/u/feat/Case.html#Dat),
  [Ins](https://universaldependencies.org/u/feat/Case.html#Ins),
  [Loc](https://universaldependencies.org/u/feat/Case.html#Loc),
  [Abl](https://universaldependencies.org/u/feat/Case.html#Abl),
  [All](https://universaldependencies.org/u/feat/Case.html#All),
  [Cmp](https://universaldependencies.org/u/feat/Case.html#Cmp),
  [Com](https://universaldependencies.org/u/feat/Case.html#Com),
  [Ben](https://universaldependencies.org/u/feat/Case.html#Ben),
  [Cau](https://universaldependencies.org/u/feat/Case.html#Cau),
  [Voc](https://universaldependencies.org/u/feat/Case.html#Voc).
  Malayalam is an agglutinative language and the spatiotemporal and/or case-like morphemes are analyzed as postpositions.
  The Case feature occurs with the nominal words, i.e., [NOUN](), [PROPN](), [PRON](), [NUM]() and also with nominalized verb forms.

### Verbal Features

* Finite verbs always have one of eight values of [Mood]():
  [Ind](https://universaldependencies.org/u/feat/Mood.html#Ind),
  [Irr](https://universaldependencies.org/u/feat/Mood.html#Irr),
  [Cnd](https://universaldependencies.org/u/feat/Mood.html#Cnd),
  [Des](https://universaldependencies.org/u/feat/Mood.html#Des),
  [Nec](https://universaldependencies.org/u/feat/Mood.html#Nec),
  [Imp](https://universaldependencies.org/u/feat/Mood.html#Imp),
  [Prp](https://universaldependencies.org/u/feat/Mood.html#Prp) or
  [Opt](https://universaldependencies.org/u/feat/Mood.html#Opt).
* Verbs in the indicative mood always have one of three values of [Tense]():
  [Past](https://universaldependencies.org/u/feat/Tense.html#Past),
  [Pres](https://universaldependencies.org/u/feat/Tense.html#Pres) or
  [Fut](https://universaldependencies.org/u/feat/Tense.html#Fut).
* [Aspect]() has five possible values:
  [Hab](https://universaldependencies.org/u/feat/Aspect.html#Hab),
  [Imp](https://universaldependencies.org/u/feat/Aspect.html#Imp),
  [Perf](https://universaldependencies.org/u/feat/Aspect.html#Perf),
  [Prog](https://universaldependencies.org/u/feat/Aspect.html#Prog),
  [Iter](https://universaldependencies.org/u/feat/Aspect.html#Iter).
* [Voice]() has three possible values:
  [Act](https://universaldependencies.org/u/feat/Voice.html#Act),
  [Pass](https://universaldependencies.org/u/feat/Voice.html#Pass),
  [Cau](https://universaldependencies.org/u/feat/Voice.html#Cau).
* [Polarity]() has two values:
  [Pos](https://universaldependencies.org/u/feat/Polarity.html#Pos) and
  [Neg](https://universaldependencies.org/u/feat/Polarity.html#Neg).

### Pronouns, Determiners, Quantifiers

* [PronType]() is used with pronouns [PRON]().
* [NumType]() is used with numerals [NUM]().
* [Person]() is a lexical feature of personal pronouns (PRON) and has three values 1, 2 and 3.
* [Clusivity]() distinguishes inclusive and exclusive 1st person plural pronouns.
* [Deixis]() distinguishes proximate and remote demonstratives and 3rd person singular and plural pronouns.

## Syntax

### Core Arguments, Oblique Arguments and Adjuncts

* Malayalam is a verb-final language; both SOV and OSV orders are possible.
* Core arguments are marked by the morphological cases nominative (subject) and accusative (object). Core arguments
  are bare noun phrases without postpositions. Neither subject nor object are cross-referenced by verbal morphology.
* Subjects have the following characteristics:
    * Case marking: Subjects occur in nominative case without adpositions.
    * Passivization: Subjects are suppressed when verbs are passivized.
* Objects have the following characteristics:
    * Case marking: Objects occur in accusative case without adpositions.
    * Passivization: Objects become (non-expletive) subjects when verbs are passivized.
* Non-nominative subjects are attached as [nsubj]().
* Adjuncts and non-core arguments are attached as [obl]().

## Relations Overview

* [nsubj:pass]() for nominal subjects in passive clauses.
* [nmod:poss]() for possessive adjectives.
   ~~~sdparse
   പെൺകുട്ടി തന്റെ സുഹൃത്തിന് കത്ത് എഴുതി .
   nsubj(എഴുതി, പെൺകുട്ടി)
   nmod:poss(സുഹൃത്തിന്, തന്റെ)
   obl(എഴുതി, സുഹൃത്തിന്)
   obj(എഴുതി, കത്ത്)
   punct(എഴുതി, .)
   ~~~
   'The girl wrote a letter to her friend'
* [mark]() for the quotative particle introducing a finite clause subordinate to another clause.
   ~~~sdparse
   ആര് ആണ് എഴുതിയത് എന്ന് അവർക്ക് അറിയില്ല .
   nsubj(എഴുതിയത്, ആര്)
   cop(എഴുതിയത്, ആണ്)
   ccomp(അറിയില്ല, എഴുതിയത്)
   mark(എഴുതിയത്, എന്ന്)
   obl(അറിയില്ല, അവർക്ക്)
   punct(അറിയില്ല, .)
   ~~~
   'They don't know who wrote it'
 * [cop]() for the copular or the non-verbal predicates.
   ~~~sdparse
   നിങ്ങൾ ഒരു വിദ്യാർത്ഥി ആണോ ?
   nsubj(വിദ്യാർത്ഥി, നിങ്ങൾ)
   det(വിദ്യാർത്ഥി, ഒരു)
   cop(വിദ്യാർത്ഥി, ആണോ)
   punct(വിദ്യാർത്ഥി, ?)
   ~~~
   'Are you a student?'
 * [cc]() for coordinating conjunctions.
   ~~~sdparse
   അവൻ പുകവലി ഉം മദ്യപാനം _ഉം നിർത്താൻ ശ്രമിച്ചു .
   nsubj(ശ്രമിച്ചു, അവൻ)
   obj(നിർത്താൻ, പുകവലി)
   cc(പുകവലി, ഉം)
   conj(പുകവലി, മദ്യപാനം)
   cc(മദ്യപാനം, _ഉം)
   xcomp(ശ്രമിച്ചു, നിർത്താൻ)
   punct(ശ്രമിച്ചു, .)
   ~~~
   'He tried to quit smoking and drinking'

## Treebanks

There is [1](../treebanks/ml-comparison.html) Malayalam UD treebank:

  * [Malayalam-UFAL](../treebanks/ml_ufal/index.html)
