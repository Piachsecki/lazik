# Zadanie projektowe: Sterowania misj ˛a zbierania próbek z Marsa



# 1 Cel zadania

Wykształcenie umiej˛etnosci definiowanie zadanych struktur na podstawie dostarczonego dia- ´
gramu UML oraz jego rozbudowa w ramach dalszego projektowania własnych struktur. 
Opanowanie mechanizmu dziedziczenia oraz niejawnego rzutowania w gór˛e. Wykorzystanie metoda
wirtualnych. Praktyczne wykorzystanie szablonów std::list<> oraz std::shared_ptr<>.


# 2 Zadanie projektowe

Nalezy napisa ˙ c program, który zamodeluje i zwizualizuje sterowanie łazikiem SFR i zbierac´
nie przez niego tubek z próbkami marsjanskiego regolitu. Sterowanie ma sie odbywac przez ´
uzytkownika programu. Zakłada sie, ze w modelowanym otoczeniu oprócz próbek znajdua ˙
sie dwa inne łaziki Perseverance i Curiosity, które w trakcie ruchu łazika SFR nalezy trakto- ˙
wac jako przeszkody. Zakładamy ponadto ze mozemy wyselekcjonowac inny łazik, którym ´
mozemy sterowac. Wówczas dwa inne łaziki nale ´ zy traktowac jako przeszkody. Jednak ze na- ˙
lezy pamietac,´ ze tylko łazik SFR moze zbierac próbki. Zakłada sie, ´ ze w otoczeniu, w który ˙
operuje SFR, znajduje sie co najmniej 5 próbek o nazwach: Montdenier, Montagnac, Salette,
Coulettes, Robine Wiecej informacji na ten temat mozna znalezc na stronie ´
https://www.jpl.nasa.gov/images/pia25065-mapping-perseverances-first-six-samples
