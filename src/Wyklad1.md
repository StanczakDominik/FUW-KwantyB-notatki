# Organizacja 

## Terminy

* Kolokwium 7 stycznia 2019
    * egzamin zerowy
    * zwalnia z pisemnego (przy dosyć dobrym zdaniu)
    * bardziej trening przed egzaminem
* Egzamin pisemny 29 stycznia
    * część testowa - do 3+, tak/nie, są ujemne punkty
    * część zadaniowa - do 4+
    * Dopuszczenie do egzaminu pisemnego z automatu
    * w pakiecie, części nie są niezależne
* Egzamin ustny 30 stycznia - do 5
    * gotowe kilkanaście pytań, losujemy po dwa, rozmowa rzędu pół do godziny
* Egzamin pisemny poprawkowy 18 lutego
* Egzamin ustny poprawkowy 19 lutego

* Zaczepianie prowadzącego przed/po zajęciach, konsultacje do dogadania mailowo
* Zadania domowe bez sprawdzania raz na dwa tygodnie
* Istnieje strona domowa, trzeba ją znaleźć
* Notatki skanowane i wywieszane na stronie, bez texowania

## Książki
Książek jest kilka i żadna się do końca nie nadaje

* W. Nolting - *Fundamentals of Many-body Physics*
* Klasyk - Negele, Orland - *Quantum Many-Particle Systems* - formalizm
  fajnie wyjaśniony, ale raczej bez fizyki, dużo błędów typograficznych
* Z cyklu "niektórzy lubią" - Fetter, Walecka - po polsku 
* Abrimosov - Gorkov - Dzialoshinski
* Bruus, Flensberg

Książki które są kolorowe i fajne ale czasami jest w nich trochę pozamiatane
pod dywan (do rozumienia fizyki, ale nie każdy rachunek jest do odtworzenia):

* Actland, Simons
* Pierce Coleman
* Do poduszki - Mattuch - językiem dla przedszkolaków - rysunki, **kawały**
    * kwazicząstka wytłumaczona na przykładzie **kwazikonia**

Polecane notatki wykładowe, będzie raczej przeliczanie wszystkiego (bez prac
domowych dla wytrwałych!)

## Treść wykładu

* pomijamy efekty relatywistyczne
* układy takie jak ciała stałe, nadprzewodniki, przewodniki
* efekty kwantowe widoczne w makroskali

Efekty kwantowe istotne gdy

$$ T < T_{char} $$

Dla metali byłaby to temperatura Fermiego $ 10^4 K $.

# Mechanika kwantowa pojedynczej cząstki (wersja nierelatywistyczna)

* **stany** $ \bra{\psi} \in H $
* Iloczyn skalarny $ \braket{\psi|\phi} \in C $, symetryczny ze sprzężeniem
* Obserwable kojarzone z operatorami hermitowskimi
    * Stany własne służące do konstrukcji bazy w przestrzeni
* $\hat{r} \bra{r} = r \bra{r}$
* $\hat{p} \bra{p} = r \bra{p}$
* $\braket{r|\nu} = \psi_\nu(r) $ - funkcja falowa
* relacja zupełności - $\int dr^3 \ket{r} \bra{r} = 1 $ (tożsamość)
* $\int dp^3 \ket{p} \bra{p} = 1 $
* $\braket{r|\nu} = \psi_{\nu}(r)$
* 1 = \int dr | \psi_\nu (r) |^2 = \int dr \psi_\nu^* (r) \psi_\nu (r) = \int dr \braket{\nu|r} \braket{r|\nu} = \bra{\nu} \int dr \ket{r|r} \ket{\nu} = \braket{\nu|\nu}$
* $\braket{r|r'} = \delta(r - r')$

> Wszyscy wiedzą, że to się nazywa bra, a to się nazywa ket? Tak?
> Odwrotnie!

Bierzemy bazę ortonormalną $ \{ \bra{\nu} \} $ i dowolny stan ortonormalny unormowany $\braket{\psi|\psi} = 1 $
