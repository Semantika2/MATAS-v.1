MATAS corpus (version 1.0)

CONTRIBUTORS
Erika Rimkutė, Agnė Bielinskienė, Loic Boizou, Virginijus Dadurkevičius, Jolanta Kovalevskaitė, Andrius Utka

DESCRIPTION
Manually checked, morphologically annotated corpus MATAS 

LANGUAGE
Lithuanian

FORMATS
1. CoNLL-U (CONLLU, conllu)
2. SketchEngine - tab delimited word per line (TAB-WPL, txt)

SIZE
Wordform count:	1,693,410
Sentence count:	144,047

GENRES
Genres	Files	Wordforms	%
documents(dok)	34	237106	14,0
fiction(gro)	33	327642	19,3
scientific(mok)	38	409183	24,2
news(pub)	30	605729	35,8
transcripts(ste)	3	113750	6,7

POS COUNTS
noun(N)	637222
verb(V)	338746
adjective(A)	122391
pronoun(P)	147490
numeral(M)	62265
adverb(R)	105238
preposition(S)	77432
conjunction(C)	129492
particle(Q)	36423
interjection(I)	3015
onomatopoeia(O)	209
abbreviation(Y)	27992
others(X)	5495
punctuation(T)	442306

TAGSETS
morphological annotation presented with 3 different tagsets:
- Universal Dependencies (POS 4 column, morphological categories 6 column), see universaldependencies.org;
- Jablonskis (5 column) see Documentation folder;
- MULTEXT-EAST (10 column), see Documentation folder.

The order of columns matches the order of CoNLL-U.

JABLONSKIS AND MULTEXT-EAST TAGSETS
Jablonskis -> Lithuanian tagset -> human-readable
Multext-East -> English tagset -> machine-readable

There is no essential difference between "Jablonskis" and  MULTEXT-EAST formats in how they treat grammar - both adhere to traditional grammar view. Although, you should note that the scope of MULTEXT-EAST format is somewhat broader. MULTEXT-EAST format distinguishes between subnormal and obscene wordforms while Jablonskis (and UD) does not reflect this. Besides, proper nouns of geografical names, first person names and surnames have special tags in MULTEXT-EAST format, while "Jablonskis" and UD do not have this.

UD TAGSET
UD mark-up differs from traditional grammar view.
- proper nouns are marked as a separate POS (PROPN);
- acronyms are marked up as proper nouns;
- ordinal numerals are treated as adjectives (with the tag "Ord");
- collective numerals are marked-up as nouns (with the tag "Set");
- necessity participles are marked-up as adjectives, necessity is not considered a grammar category;
- adverbial participles2 (būdiniai) are marked-up as adverbs;
- simple past (būtasis) and past tense (būtasis kartinis laikas) are marked-up identically, as past tense (Tense=Past);
- past frequentative (būtasis dažninis) is marked with two joined tags: simple past + iterative aspect (|Tense=Past|Aspect=Iter|).

KNOWN DISCREPANCIES BETWEEN THIS AND UD GUIDELINES:
- auxiliary verbs (AUX) are not distinguished from common verbs (VERB);
- many symbols are marked with punctuation;
- unfinished, split words and fragments are not given POS, they are marked as Xg(other);
- pronoun categories PronType, Poss, Polite are not marked.

KNOWN TAGSET PROBLEMS
- proper substandard and obscene words are not marked-up as proper nouns and so may be confused with common nouns;
- note that lemmas of verbs "dirbti", "nedirbti", "bedirbti", "tebedirbti", "nebedirbti" are treated as different;
- MULTEXT-EAST format has special tags for subnormal and obscene wordforms, as well as for proper nouns of geografical names, first person names and surnames, while "Jablonskis" and UD formats do not reflect this.

