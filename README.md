### W każdą środę spotykamy się w gronie znajomych, by obejrzeć kilka horrorów. Nie muszą one być dobre, plan (rzadko przestrzegany), że będzie minimum po jednym:
- strasznym
- śmiesznym
- niszowym

Po seansie każda osoba obecna wpisuje swoją ocenę w skali od 1 do 10.
Dodatkowo, przy lekkiej pomocy TvTropes stworzyłem katalog z kategoriami tych filmów. Ozywiście wszystkie są horrorami, więc trzeba było znaleźć cośinnego, po czym można je podzielić. 
Ostatecznie, każda komórka oznacza, czy motyw występuje, czy nie, przykładowo:

| Title            | action | real_monsters | hurt_children | hurt_animals | blood | badass | romance | funny | artism | parody | body | horror | inversion | atmospheric | paranormal | monsters | zombie |
|------------------|--------|---------------|---------------|--------------|-------|--------|---------|-------|--------|--------|------|--------|-----------|-------------|------------|----------|--------|
| willy wonderland | 1      | 0             | 0             | 0            | 0     | 1      | 1       | 1     | 0      | 1      | 0    | 0      | 0         | 0           | 1          | 0        | 0      |

Później wybieramy osobę, dla któej model ma się nauczyć przewidywać kolejne oceny. Do wyboru są jedyne osoby, które obejrzały minimum 15 filmów, żeby dało się cokolwiek wywnioskować.
 
 Dostępne osoby, wraz z ilością obejrzanych filmów, to:
- xero 72
- osar 64
- marta 55
- stawska  44
- karolina 20
- ania5 19
- kacper 67
- sasiadka6 52
- 2kej 24
- wiku 21
- rafal 27
- alicja 16

Wybierzmy osobę, która obejrzałą najwięcej filmów:
> who='xero'


choose or die predykcja:  7.124999999999999 prawda: 7.0
Poltergeist predykcja:  7.124999999999999 prawda: 7.5
willy wonderland predykcja:  7.124999999999999 prawda: 7.0
The Whole Truth predykcja:  7.124999999999999 prawda: 7.0

itd.

Model całkiem dobrze radzi sobie ze przewidywaniem oceny dla konkretnego filmu.

Na koniec, można jeszcze zobaczyć współczynniki, które powiedzą nam, co wpływa na ocenę filmu. Dla użytkownika "xero" będzie to:
- action 0.0
- spooks -0.1800880604246277
- real_monsters 0.09849235226736754
- hurt_children 0.2255011053676909
- hurt_animals -0.12700875310032397
- blood 0.09849235226736748
- badass 0.3015418194769316
- romance -0.3184384635870388
- funny 0.18008806042462785
- artism 0.4454472166873623
- parody 0.18008806042462785
- body 0.5270429248446228
- horror -0.18008806042462785
- inversion 0.40003417174429917
- atmospheric -0.18008806042462785
- paranormal 0.0
- monsters 0.3015418194769317
- zombie -0.3015418194769317

