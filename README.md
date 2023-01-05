# Zadanie projektowe: Sterowania misj ˛a zbierania próbek z Marsa



# 1 Cel zadania

Wykształcenie umiej˛etnosci definiowanie zadanych struktur na podstawie dostarczonego dia- ´
gramu UML oraz jego rozbudowa w ramach dalszego projektowania własnych struktur. Opanowanie mechanizmu dziedziczenia oraz niejawnego rzutowania w gór˛e. Wykorzystanie metoda
wirtualnych. Praktyczne wykorzystanie szablonów std::list<> oraz std::shared_ptr<>.


# 2 Zadanie projektowe

Nalezy napisa ˙ c program, który zamodeluje i zwizualizuje sterowanie łazikiem SFR i zbiera- ´
nie przez niego tubek z próbkami marsjanskiego regolitu. Sterowanie ma si˛e odbywa ´ c przez ´
uzytkownika programu. Zakłada si˛e, ˙ ze w modelowanym otoczeniu oprócz próbek znajduj ˛a ˙
si˛e dwa inne łaziki Perseverance i Curiosity, które w trakcie ruchu łazika SFR nalezy trakto- ˙
wac jako przeszkody. Zakładamy ponadto, ´ ze mo ˙ zemy wyselekcjonowa ˙ c inny łazik, którym ´
mozemy sterowa ˙ c. Wówczas dwa inne łaziki nale ´ zy traktowa ˙ c jako przeszkody. Jednak ´ ze na- ˙
lezy pami˛eta ˙ c,´ ze tylko łazik SFR mo ˙ ze zbiera ˙ c próbki. Zakłada si˛e, ´ ze w otoczeniu, w który ˙
operuje SFR, znajduje si˛e co najmniej 5 próbek o nazwach: Montdenier, Montagnac, Salette,
Coulettes, Robine (patrz rys. 3). Wi˛ecej informacji na ten temat mozna znale´z ˙ c na stronie ´
https://www.jpl.nasa.gov/images/pia25065-mapping-perseverances-first-six-samples
