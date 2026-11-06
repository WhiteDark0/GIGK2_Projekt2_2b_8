![](GDD_UBB.png)





**Grafika i gry komputerowe**

**GDD**



# Wprowadzenie do pomysłu


Symulator śmieciarza (n.d.z) jest symulatorem, w którym można wcielić się w postać właściciela wysypiska śmieci. Gracz będzie miał za zadanie zarządzać wspomnianym biznesem, zbierać odpady, sprzedawać wartościowe śmieci dzięki zleceniom od klientów lub sprzedaży hurtowej. Dodatkowo gracz będzie miał możliwość poszerzenia swojego interesu poprzez kupowanie potrzebnych maszyn, zatrudnianie pracowników oraz rozwijanie umiejętności.
Gracz będzie musiał też pilnować zarządzania swoimi pieniędzmi, aby nie doszło w ostateczności do bankructwa.
Początkowe planowane jest zrobienie zawartości tak, aby gracz mógł spędzić maksymalnie 1 miesiąc (w grze), aby mógł się zapoznać z zawartymi mechanikami.


# Postacie – wprowadza avatarów i NPC, którzy będą obecni w grze


Gra wprowadza główną postać kontrolowaną przez gracza w widoku pierwszoosobowym oraz postacie NPC jako klientów oraz przechodniów.


# Projekt świata


Akcja gry będzie się odbywać w dwóch miejscach:
- Wysypisko śmieci, gdzie gracz będzie mógł nim zarządzać (budowanie/umieszczanie maszyn, zarządzanie pracownikami, itp)
- Miasto, gdzie gracz będzie mieć możliwość przechadzania się po nim, zbierać śmieci, realizować zlecenia i inne


# Fabuła


Gracz wciela się w rolę młodego biznesmena, który odziedziczył wysypisko śmieci w niewielkim mieście. To biznes rozwijany przez jego rodzinę od pokoleń. Jako osoba bez większego doświadczenia w tej branży, musi stawić czoła trudnemu zadaniu, ale także wyjątkowej szansie. Z jednej strony może doprowadzić wieloletni interes do bankructwa, z drugiej – stać się szanowanym milionerem znanym w całym regionie.


# Rozgrywka - ogólne założenia


Gracz będzie miał możliwość zarządzania swoją firmą jak również przechadzania się po różnych miastach mając na celu rozwijanie swojego biznesu. Złomowisko będzie zawierało szerokie możliwości pod względem budowy maszyn, poszerzenia terenu, zarządzaniem pracownikami i własnoręcznego oddzielania przedmiotów do odpowiednich materiałów. W mieście gracz będzie realizował zlecenia dostarczenia materiałów jak i przedmiotów, zbierał osobiście śmieci z różnych miejsc.
Oprócz finansów istotną mechaniką, która decyduje o tym, czy gracz może rozwijać swoją firmę w wybranym kierunku będzie system reputacji — od bardzo złej do bardzo dobrej. Zmienia się ona w zależności od percepcji staranności wykonywania usług w oczach mieszkańców jak, wpływu świadczonych usług na miasto (z perspektywy urzędników) oraz zasadności praktyk biznesowych.


# Mechaniki - ogólny opis

## Mechaniki dot. zarządzania (finanse, reputacja, itp.)

Podstawowymi wyznacznikami liczbowymi, czy gracz będzie mógł wykonać dana akcję w kontekście zarządzania przedsiębiorstwem są pieniądze (w wirtualnej walucie), poziom doświadczenia, punkty rozwoju oraz reputacja.

W ogólnym założeniu dane wskaźniki zmieniają się, gdy:
#### Pieniądze
Natychmiastowo ich ubywa, gdy gracz dokonuje zakupu przedmiotów, zatrudnia pracowników, itp. Otrzymuje się je natychmiastowo po skończeniu zlecenia czy sprzedaży przedmiotu. Istnieją też opłaty powtarzające się — pensje pracowników (gdy gracz zatrudni kogoś oprócz siebie), opłata za budynek siedziby firmy (raczej już zsumowane czynsz, podatek od nieruchomości oraz opłaty za media). Nie ma możliwości zejścia poniżej 0 — zakupy są niemożliwe, lecz opłaty okresowe mogą doprowadzić do takiej sytuacji, lecz wtedy:
- Jeżeli to pierwsze zejście na minus funduszy — firma pożycza "osobiste środki szefa", np. 5000 waluty
- Jeżeli to kolejny raz albo fundusze nie wystarczyły — ekran przegrania gry; gracz wczytuje poprzedni zapis lub rozpoczyna nową grę
Opcjonalnie można wprowadzić system pożyczek — systematycznie odblokowywane przez proste obliczanie zdolności kredytowej (wartość firmy + poprzednie spłacone pożyczki). Każda pożyczka wprowadza comiesięczne opłaty celem jej spłacenia.

⚠️ TODO: Czy rozwój firmy powinien wpływać na opłaty regularne? Np. Czy nowe obiekty zwiększają rachunek za elektryczność? Wtedy rachunek za prąd powinien być jawnie osobny od innych opłat za budynek.

⚠️ TODO: Nazwa waluty — być może $ bądź kredyty

⚠️ TODO: Ogólna jej wartość — jaka jest minimalna/średnia pensja, ile kosztuje budynek, czynsz oraz przedmioty czy pojazdy?

⚠️ TODO: Jaki jest termin płatności? Czy jest to miesiąc jak zaproponowano dla ew. pożyczek czy też dzień lub tydzień?

#### Poziom doświadczenia
Nie można go stracić. Każdy kolejny poziom doświadczenia (LVL) zdobywa się po zdobyciu określonej liczby punktów doświadczenia (wyższa dla każdego kolejnego poziomu). Niektóre ulepszenia wymagają konkretnego LVL.

#### Punkty rozwoju
Zdobywane poprzez osiąganie kolejnych LVL postaci — np. LVL1 -> LVL2 daje 3 punkty rozwoju (SP). Wymagane zawsze do ulepszeń — reprezentują one pewnien poziom przestudiowanej wiedzy przez właściciela, np. aby zakupić maszynę X musi on mieć ulepszenie Y w drzewku rozwoju za 2 punkty rozwoju.

#### Reputacja
Reprezentowana liczbowo za pomocą zakresu od -100 do +100 z następującymi nazwami opisowymi:
- -100 — -75 — bardzo zła
- -75 — -25 — zła
- -25 — +25 — neutralna
- +25 — +75 - dobra
- +75 — +100 - bardzo dobra

⚠️ TODO: Oś liczbowa z zakresami
⚠️ TODO: Doprecyzować zakresy pod względem <> oraz () — łącznie/rozłącznie
⚠️ TODO: Czy zakres jest zbalansowany? Czy zakresy powinny być równe długością? 200 / 5 = 40. Obecnie "bardzo" ma długość 25, a pozostałe poziomy - 50.


## Mechaniki dot. rozgrywki (wyruszanie w/powrót z trasy, przemieszczanie się, itp.)


# Sterowanie

Gracz steruje swoją postacią szefa bezpośrednio — porusza się w czterech kierunkach za pomocą przycisków WASD (lub lewą gałką kontrolera), a kamerą pierwszoosobową manipuluje za pomocą myszki (lub prawą gałką kontrolera).
Opcjonalnie może być dostępna akcja skoku (Spacja/A) na wypadek, gdyby graczowi udało się zaklinować pomiędzy obiektami.
Dodatkowym modyfikatorem ruchu będzie akcja sprintu (Shift - przytrzymanie/Naciśnięcie lewej gałki - toggle wł/wył).

⚠️ TODO: Czy sprint powinien być ograniczony paskiem staminy?


Sterowanie pojazdami odbywa się identycznie poprzez klawisze WASD:
- W — pedał gazu i jazda do przodu
- A — skręt w lewo
- S — skręt w prawo
- D — hamulec i cofanie

Na kontrolerze sterowanie pojazdami jest podzielone między spusty analogowe oraz lewą gałkę. Z racji, że zarówno spusty jak i gałka są analogowe, tzn. można je nacisnąć/przechylić z siłą od 0-100%, to, co jest typowe dla sterowania kontrolerem, siła nacisku wpływa na, to jak bardzo zmienia się wektor ruchu (na klawiaturze możliwie to zawsze będzie 100%).
Przypisania kontrolera prezentują się następująco:
- RT (prawy spust) — pedał gazu i jazda do przodu
- ruch lewej gałki w lewo — skręt w lewo
- ruch lewej gałki w prawo — skręt w prawo
- LT (lewy spust) — hamulec i jazda do tyłu

W konkteście sterowania elementami interfejsu (zarówno menu nieistniejącymi w świecie gry, takie jak menu główne i menu zapisu jak i panelami zarządzania biznesem z poziomu komputera w świecie gry), to odbywa się ono za pomocą myszki:
- lewy przycisk myszy — naciśnięcie przycisku
- prawy przycisk myszy / ESC — powrót do menu poprzedniego / wyjscie z menu
- rolka (scroll) — przewijanie ewentualnych list przewijalnych

Jeżeli gracz gra na kontrolerze, to należałoby rodzielić sytuacje sterowania menu na zewnątrz i wewnątrz gry.
Poprzez menu główne, zapisu, itp. gracz poruszałby się za pomocą lewej gałki bądź krzyżaka (D-Pad) w celu wybrania opcji, zatwierdziałby ją przyciskiem A, a cofał/wychodził z menu przyciskiem B.
Menu wewnątrzgrowe — panele zarządzania, strony internetowe symulowałoby wirtualny kursor myszy:
- ruch lewej gałki — ruch kursorem w danym kierunku
- lewy przycisk myszy — naciśnięcie przycisku
- B — powrót do menu poprzedniego / wyjscie z menu
- ruch prawej gałki — przewijanie ewentualnych list przewijalnych

⚠️ TODO: Być może scalić oba schematy ruchu w jedną tabelę


# Sposób dystrybucji – w jakich kanałach prowadzona będzie sprzedaż/ promocja


- Twitter/X – promocja gry, zwiastuny, stworzenie społeczności

- Steam – promocja gry, zwiastuny

- YouTube – promocja gry, zwiastuny

- Strona internetowa – promocja gry, zwiastuny


# Model finansowania – w jakim wymiarze rozwiązanie będzie finansowane.

Źródła pozyskania środków:

- Sponsorzy

- YouTube

- Dofinansowania



# Wykonane przez:

Artur Piwowarczyk

Dawid Pawlica

Łukasz Skrzypek
