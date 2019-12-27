MATO tekstynas (versija 1.0)

SUDARYTOJAI
Erika Rimkutė, Agnė Bielinskienė, Loic Boizou, Virginijus Dadurkevičius, Jolanta Kovalevskaitė, Andrius Utka

APRAŠYMAS
Ranka taisytas morfologiškai anotuotas tekstynas MATAS pateikiamas CoNLL-U formatu.

KALBA
lietuvių

FORMATAI
1. CoNLL-U (CONLLU, conllu)
2. SketchEngine (tab delimited word per line, TAB-WPL, txt)

DYDIS
Žodžių skaičius:	1693410
Sakinių skaičius:	144047

ŽANRAI
Žanrai	Failai	Žodžiai	%
dokumentinis(dok)	34	237106	14,0
grožinis(gro)	33	327642	19,3
mokslinis(mok)	38	409183	24,2
periodinis(pub)	30	605729	35,8
stenograminis(ste)	3	113750	6,7

KALBOS DALIŲ STATISTIKA:
daiktavardis(N)	637222
veiksmažodis(V)	338746
būdvardis(A)	122391
įvardis(P)	147490
skaitvardis(M)	62265
prieveiksmis(R)	105238
prielinksnis(S)	77432
jungtukas(C)	129492
dalelytė(Q)	36423
jaustukas(I)	3015
ištiktukas(O)	209
trumpinys(Y)	27992
kiti(X)	5495
skyryba(T)	442306

PAŽYMOS
Morfologinis anotavimas yra patiekiamas trimis skirtingais morfologinių pažymių rinkiniais:
- Universal Dependencies (kalbos dalis 4 stulpelyje, morfologinės pažymos 6 stulpelyje), žr. universaldependencies.org;
- Jablonskis (5 stulpelyje), žr. Documentacijos katalogą;
- Multext-EAST (10 stulpelyje po raktažodžio Multext), žr.Documentacijos katalogą;

Stulpelių tvarka atitinka CoNLL-U formato reikalavimus.

JABLONSKIS AND MULTEXT-EAST PAŽYMŲ RINKINIAI
Jablonskis -> lietuviškos pažymos -> pritaikytos žmonėms
Multext-East -> angliškos pažymos -> pritaikytos mašinoms

Esminio semantinio skirtumo tarp formato "Jablonskis" ir formato MULTEXT-EAST nėra. Pagrindinis skirtumas yra tas, kad "Jablonskis" lengviau skaitomas žmonių (šis formatas yra artimas tradiciniams lituanistikos gramatiniams sutrumpinimams), o MULTEXT-EAST - labiau pritaikytas mašinoms. Bendrai žiūrint morfologinių kategorijų supratimas laikosi tradicinio gramatikos požiūrio. 
Paminėtina, kad MULTEXT-EAST formatas neapsiriboja morfosintaksinėmis pažymomis ir turi platesnį žymų aprėptį. MULTEXT-EAST formate specialiomis pažymomis skiriama subnorminė ir necenzūrinė kalba, taip pat specialiomis pažymomis žymimi tam tikri tikriniai daiktvardžiai (geografiniai pavadinimai, vardai ir pavardės).

UD FORMATAS
UD žymėjimas labiau skiriasi nuo tradicinio požiūrio.
- tikriniai daiktavardžiai yra laikomi atskira kalbos dalimi (PROPN);
- akronimai yra laikomi tikriniais daiktavardžiais (su sutrumpinimo pažyma)
- kelintiniai skaitvardžiai yra laikomi būdvardžiais (su Ord pažyma);
- kuopiniai skaitvardžiai yra laikomi daiktavardžiais (su Set pažyma);
- reikiamybės dalyviai nėra laikomi dalyviais, o (veiksmažodžio kilmės) būdvardžiais, reikiamybė nelaikoma gramatine pažyma;
- būdiniai yra laikomi prieveiksmiais;
- būtasis laikas ir būtasis kartinis laikas yra laikomi būtuoju laiku (be papildomos informacijos) (Tense=Past);
- būtasis dažninis yra laikomas dviejų pažymų junginiu, būtojo laiko + dažnumo/dažninio/iteratyvaus aspekto (|Tense=Past|Aspect=Iter|).

ŽINOMI NEATITIKIMAI UD GAIRĖMS
- pagalbiniai veiksmažoždiai (AUX) nėra skiriami nuo bendrų veiksmažodžių (VERB);
- dauguma simbolių yra pažymimi skyrybos ženklais;
- nutrupinties, perskeltiems žodžiams neskiriama kalbos dalis, joms nurodoma nežinoma kalbos dalis (Xg);
- įvardžių rūšies (PronType), savybinė (Poss) ir mandagumo (Polite) kategorijos nėra nurodytos.

ŽINOMOS PAŽYMŲ RINKINIŲ PROBLEMOS
- MULTEXT-EAST sistema neskiria tikrinio ir netikrinio daiktvardžio, kai žodžiai priklauso subnorminių arba necenzūrinių žodžių aibei, todėl nestandartiniai tikriniai gali būti klaidingai nurodomi kaip netikriniai.
- Pastebėtina, kad lemos "dirbti", "nedirbti", "bedirbti", "tebedirbti", "nebedirbti" yra laikomos atskiromis.
- MULTEXT-EAST formate specialiomis pažymomis skiriama subnorminė ir necenzūrinė kalba, tai pat tam tikri tikriniai daiktavardžiai (geografiniai pavadinimai, vardai ir pavardės), tuo tarpu Jablonskio ir UD formatuose ši informacija nėra žymima.
