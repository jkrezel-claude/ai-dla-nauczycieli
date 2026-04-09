# AI dla nauczycieli - Warsztat praktyczny

> Instrukcja krok po kroku. Otwierasz, scrollujesz, robisz.
> Nie musisz znac sie na technologii - wystarczy przegladarka i ciekawosc.

---

## Jak korzystac z tego repozytorium

### Pobierz materialy

1. Kliknij zielony przycisk **"Code"** na gorze tej strony
2. Wybierz **"Download ZIP"**
3. Rozpakuj pobrany plik na pulpicie

Gotowe - masz folder ze wszystkimi plikami, ktore beda Ci potrzebne.

### Przygotuj narzedzia

Otwierz w przegladarce dowolne z tych narzedzi (wszystkie sa darmowe):

| Narzedzie | Adres | Do czego | Darmowy limit |
|-----------|-------|----------|---------------|
| **ChatGPT** | [chatgpt.com](https://chatgpt.com) | Rozmowa, pomysly, grafika | ~15 wiadomosci / 3h (GPT-4o) |
| **Claude** | [claude.ai](https://claude.ai) | Dluzsze dokumenty, analiza, precyzja | ~20 wiadomosci / dzien |
| **Gemini** | [gemini.google.com](https://gemini.google.com) | Research, Google integracja | Praktycznie bez limitu |
| **NotebookLM** | [notebooklm.google.com](https://notebooklm.google.com) | Analiza dokumentow, podcasty AI | Bez limitu |

Wystarczy jedno narzedzie. Jesli nie wiesz ktore - zacznij od **ChatGPT** lub **Gemini**.

### Jak kopiowac prompty

W tej instrukcji znajdziesz gotowe prompty w szarych blokach. Wystarczy najechac myszka na blok i kliknac ikonke kopiowania w prawym gornym rogu:

```
Ten tekst mozesz skopiowac jednym kliknieciem
```

---

## Czesc 1: Twoj pierwszy prompt (15 min)

Zacznijmy od czegos konkretnego. Skopiuj ponizszy prompt, wklej do ChatGPT lub Claude i zobacz co sie stanie:

```
Jestes doswiadczonym nauczycielem w szkole.

Zadanie: Przygotuj kompletny plan lekcji.

Kontekst:
- Temat: Fotosynteza
- Klasa: 6 (szkola podstawowa)
- Czas: 45 minut
- Uczniowie: 25 osob, rozny poziom zaangazowania
- Dostepne: tablica, projektor, internet

Format odpowiedzi:
- Tabela z kolumnami: Czas | Etap lekcji | Co robi nauczyciel | Co robia uczniowie | Materialy
- Na koncu: 3 pytania sprawdzajace zrozumienie
- Zadanie domowe (krotkie, max 15 min)

Ograniczenia:
- Max 30% czasu na wyklad (reszta to aktywnosci uczniow)
- Jezyk prosty, zrozumialy dla 12-latkow
- Uwzglednij rozne style uczenia sie
```

**Dostal plan lekcji w kilka sekund?** Wlasnie tak dziala dobrze napisany prompt.

### Twoja kolej

Zmien w tym prompcie:
- **Temat** - na swoj przedmiot i temat
- **Klase** - na swoja
- **Czas** - na swoj (45, 60, 90 minut)

Skopiuj zmieniony prompt, wklej do narzedzia i porownaj wynik z pierwszym.

---

## Czesc 2: Jak pisac dobre prompty - metoda RZKFO (45 min)

Ten plan lekcji wyszedl dobrze, bo prompt mial jasna strukture. Ta struktura to **RZKFO**:

| Litera | Co to znaczy | Przyklad |
|--------|-------------|----------|
| **R** - Rola | Kim ma byc AI | "Jestes doswiadczonym nauczycielem matematyki" |
| **Z** - Zadanie | Co AI ma zrobic | "Przygotuj 10 zadan z ulamkami" |
| **K** - Kontekst | Szczegoly sytuacji | "Klasa 7, poziom sredni, przed sprawdzianem" |
| **F** - Format | Jak ma wygladac wynik | "Tabela: numer, zadanie, odpowiedz, trudnosc" |
| **O** - Ograniczenia | Czego unikac, limity | "Bez kalkulatora, max 3 dzialania w zadaniu" |

Nie musisz uzywac wszystkich 5 elementow za kazdym razem. Ale im wiecej podasz, tym lepszy bedzie wynik.

### Cwiczenie 1: Zbuduj wlasny prompt (10 min)

Wybierz jedno zadanie ze swojej codziennej pracy i napisz prompt uzywajac RZKFO:

```
Rola: Jestes _________________________ [kim?]

Zadanie: _____________________________ [co ma zrobic?]

Kontekst:
- __________________________________ [klasa, przedmiot, sytuacja]
- __________________________________ [ile osob, jaki poziom]
- __________________________________ [dodatkowe okolicznosci]

Format odpowiedzi:
- __________________________________ [tabela, lista, tekst ciagle?]

Ograniczenia:
- __________________________________ [czego unikac, jakie limity]
```

Wklej gotowy prompt do ChatGPT lub Claude. Sprawdz wynik.

### Cwiczenie 2: Popraw slaby prompt (10 min)

Ponizszy prompt jest celowo slaby. Skopiuj go, wklej do narzedzia i zobacz wynik:

```
Zrob mi cos do lekcji
```

Teraz popraw go uzywajac RZKFO i wklej ponownie. Porownaj wyniki - roznica jest ogromna.

### Cwiczenie 3: Porownaj narzedzia (10 min)

Wez swoj najlepszy prompt z Cwiczenia 1 i wklej go kolejno do:
1. **ChatGPT** (chatgpt.com)
2. **Claude** (claude.ai)
3. **Gemini** (gemini.google.com)

Ktore narzedzie dalo najlepszy wynik dla Twojego zadania? Kazde ma swoje mocne strony:

| Narzedzie | Najlepsze do |
|-----------|-------------|
| ChatGPT | Szybkie pomysly, burza mozgow, grafika (DALL-E) |
| Claude | Dlugie dokumenty, precyzyjne instrukcje, analiza tekstu |
| Gemini | Wyszukiwanie informacji, praca z Google Docs, badania |

### Biblioteka gotowych promptow

Przygotowalismy **20 gotowych promptow** dopasowanych do codziennej pracy nauczyciela. Znajdziesz je tutaj:

**[Pobierz biblioteke promptow](prompty/biblioteka-promptow.md)**

Kazdy prompt jest gotowy do skopiowania - wystarczy uzupelnic miejsca oznaczone `[UZUPELNIJ]`.

---

## Czesc 3: AI czyta Twoje dokumenty (60 min)

AI potrafi analizowac pliki - dokumenty Word, arkusze kalkulacyjne, PDF-y, teksty. Wystarczy je wrzucic do rozmowy.

### Jak wgrac plik

**W ChatGPT:**
1. Na dole okna rozmowy kliknij ikonke **spinacza** (po lewej stronie pola tekstowego)
2. Wybierz plik z dysku
3. Plik pojawi sie w oknie - teraz napisz co AI ma z nim zrobic

**W Claude:**
1. Na dole okna kliknij ikonke **spinacza**
2. Wybierz plik
3. Napisz polecenie

**W Gemini:**
1. Na dole okna kliknij ikonke **+**
2. Wybierz "Upload file"
3. Napisz polecenie

### Cwiczenie 1: Popraw plan lekcji (15 min)

W folderze `pliki/` znajdziesz plik **[plan-lekcji.docx](pliki/plan-lekcji.docx)** - to przykladowy plan lekcji, ktory ma kilka slabych punktow.

1. Wgraj ten plik do ChatGPT lub Claude
2. Skopiuj i wklej ten prompt:

```
Przeanalizuj ten plan lekcji i:

1. Wskazz 3 mocne strony
2. Wskazz 3 elementy do poprawy
3. Zaproponuj poprawiona wersje z uwzglednieniem:
   - Roznicowania dla uczniow z trudnosciami w nauce
   - Elementow aktywizujacych (nie tylko wyklad)
   - Jasnych kryteriow sukcesu dla uczniow

Zachowaj format tabelaryczny.
```

3. Przeczytaj odpowiedz - czy AI trafnie zidentyfikowalo slabe punkty?

### Cwiczenie 2: Przeanalizuj oceny (15 min)

Wgraj plik **[lista-ocen.csv](pliki/lista-ocen.csv)** - to fikcyjny arkusz z ocenami 30 uczniow z 5 przedmiotow.

```
Przeanalizuj ten arkusz ocen:

1. Policz srednia ocen kazdego ucznia (po wszystkich przedmiotach)
2. Zidentyfikuj 5 uczniow z najnizszymi srednimi
3. Dla kazdego z tych uczniow wskazz przedmiot, w ktorym radzi sobie najlepiej
4. Napisz krotka notatke (3-4 zdania) dla wychowawcy o kazdym z tych uczniow

Format: tabela z kolumnami Uczen | Srednia | Najlepszy przedmiot | Notatka
```

### Cwiczenie 3: Przerob opinie (15 min)

Wgraj plik **[opinia-ucznia.txt](pliki/opinia-ucznia.txt)** - to nieformalna opinia o uczniu, napisana "na kolanie".

```
Przerob te opinie na formalna opinie koncowa zgodna ze standardami szkolnymi:

1. Zachowaj wszystkie informacje merytoryczne
2. Uzyj profesjonalnego, ale cieplego jezyka
3. Struktura: postepy w nauce, zachowanie, mocne strony, obszary do rozwoju, rekomendacje
4. Dlugosc: max 1 strona A4

Na koncu zaproponuj 2 alternatywne wersje ostatniego akapitu (rekomendacje).
```

### WAZNE: Bezpieczenstwo i RODO

> **STOP - przeczytaj zanim wrzucisz cokolwiek do AI**

Co **MOZESZ** wrzucac:
- Fikcyjne dane (jak pliki z tego repozytorium)
- Anonimowe dane (imiona zmienione na "Uczen 1", "Uczen 2")
- Ogolnodostepne dokumenty (podstawa programowa, podreczniki)
- Wlasne notatki i plany lekcji

Czego **NIE WRZUCAJ**:
- Prawdziwych imion i nazwisk uczniow
- Prawdziwych ocen z dziennika
- Danych osobowych (PESEL, adresy, telefony)
- Pytan egzaminacyjnych przed egzaminem
- Poufnych dokumentow szkolnych

**Jak anonimizowac dane?** Przed wrzuceniem do AI zamien imiona na "Uczen 1", "Uczen 2" itd. Mozesz tez poprosic AI o pomoc:

```
Zanim zaczniemy - zamien wszystkie imiona i nazwiska w tym dokumencie
na fikcyjne (Uczen 1, Uczen 2 itd.). Pokaz mi zanonimizowana wersje,
a potem pracujmy na niej.
```

---

## Czesc 4: AI jako asystent do czytania (45 min)

Nauczyciele tona w dokumentach - podstawa programowa, regulaminy, metodyki, raporty. AI moze je przeczytac za Ciebie i wyciagnac to, co wazne.

### NotebookLM - Twoja baza wiedzy

NotebookLM to narzedzie Google, ktore pozwala wgrac dokumenty i rozmawiac z nimi jak z ekspertem.

1. Otworz [notebooklm.google.com](https://notebooklm.google.com) (potrzebujesz konta Google)
2. Kliknij **"New Notebook"** (lub "Nowy notatnik")
3. Kliknij **"Add source"** (lub "Dodaj zrodlo") i wgraj plik **[artykul-ai-edukacja.md](pliki/artykul-ai-edukacja.md)** z pobranego folderu
4. Poczekaj az NotebookLM przeanalizuje plik (kilka sekund)

Teraz mozesz zadawac pytania o wgrany dokument:

```
Jakie sa 3 najwazniejsze wnioski z tego artykulu?
```

```
Jak moge wykorzystac te informacje na lekcji [UZUPELNIJ PRZEDMIOT]?
```

```
Przygotuj 5 pytan do dyskusji na rade pedagogiczna
na podstawie tego tekstu.
```

### Funkcja wow: Podcast AI

W NotebookLM kliknij **"Audio Overview"** (lub "Podsumowanie audio"). AI wygeneruje **podcast** - dwoch prowadzacych rozmawia o Twoim dokumencie. To trwa ok. 2 minuty generowania, a podcast ma 5-10 minut.

Mozesz tez dodac wytyczne przed wygenerowaniem:

```
Skup sie na praktycznych zastosowaniach w klasie.
Mow prostym jezykiem, jakbys tlumaczyl to nauczycielowi,
ktory dopiero zaczyna przygode z AI.
```

### Deep Research w Gemini

Gemini ma funkcje "Deep Research", ktora przeszukuje internet i pisze raport.

1. Otworz [gemini.google.com](https://gemini.google.com)
2. Nad polem tekstowym wybierz tryb **"Deep Research"** (jesli dostepny)
3. Wpisz pytanie badawcze, np.:

```
Znajdz najnowsze badania (2024-2026) na temat skutecznosci
wykorzystania sztucznej inteligencji w nauczaniu [UZUPELNIJ PRZEDMIOT]
w szkole sredniej. Podaj zrodla.
```

Gemini przeszuka kilkadziesiat stron i przygotuje raport z linkami do zrodel. Trwa to 2-3 minuty, ale wynik jest bardzo solidny.

---

## Czesc 5: Grafika i muzyka AI - szybki przeglad (30 min)

### Grafika w 2 minuty

Najprostszy sposob: bezposrednio w ChatGPT (model DALL-E) lub Gemini.

Skopiuj i wklej do ChatGPT:

```
Stworz kolorowy plakat edukacyjny na temat [UZUPELNIJ TEMAT]
dla uczniow klasy [UZUPELNIJ].
Styl: przyjazny, kreskowkowy, z duzymi czytelnymi napisami.
Format: pionowy, A3.
```

Wynik pojawi sie w kilka sekund. Mozesz go pobrac i wydrukowac.

Inne narzedzia do grafiki:
- **Ideogram** ([ideogram.ai](https://ideogram.ai)) - najlepsze do tekstu na grafikach
- **Leonardo AI** ([app.leonardo.ai](https://app.leonardo.ai)) - profesjonalne grafiki, 150 tokenow/dzien

### Muzyka AI

**Suno** ([suno.com](https://suno.com)) generuje muzyke z opisu tekstowego. Darmowe konto daje 5 utworow dziennie.

```
Spokojna, instrumentalna muzyka do czytania na lekcji.
Akustyczna gitara, delikatne pianino, bez wokalu.
Tempo wolne, relaksujace. Dlugosc: 2 minuty.
```

```
Energiczny jingle na poczatek lekcji, 15 sekund.
Optymistyczny, z klaskaniem i gwizdaniem.
Styl: reklama telewizyjna dla dzieci.
```

Wygenerowany utwor mozesz pobrac jako MP3 i puszczac na lekcjach.

---

## Czesc 6: Zbuduj wlasna aplikacje - bez programowania (sesja 2)

> Ta czesc bedzie glownym tematem nastepnego spotkania.
> Ponizej znajdziesz zapowiedz i przyklad do wyprobowania w domu.

### Jak to dziala?

1. Opisujesz AI co ma zbudowac (w prompcie)
2. AI generuje kod (plik HTML)
3. Zapisujesz go na dysku
4. Otwierasz w przegladarce
5. Masz dzialajaca aplikacje

Zero instalacji. Zero programowania. Plik dziala offline.

### Sprobuj sam: Timer lekcyjny

Skopiuj ponizszy prompt i wklej do Claude (claude.ai) lub ChatGPT:

```
Stworz kompletny plik HTML z timerem lekcyjnym. Wymagania:

- Duzy, czytelny zegar odliczajacy w centrum ekranu
- Przyciski szybkiego ustawienia: 5 min, 10 min, 15 min, 45 min
- Mozliwosc wpisania dowolnego czasu
- Przycisk Start / Pauza / Reset
- Gdy czas minie: ekran zmienia kolor na czerwony + dzwiek powiadomienia
- Ladny, nowoczesny wyglad (ciemne tlo, duze cyfry)
- Responsywny - dziala na komputerze i telefonie
- Calosc w JEDNYM pliku HTML (CSS i JavaScript w srodku)
- Interfejs po polsku
```

Dostaniesz kod. Skopiuj go, otworz Notatnik na komputerze, wklej, zapisz jako `timer.html` i otworz w przegladarce.

Gotowy przyklad do porownania znajdziesz tutaj: **[aplikacje/timer-lekcyjny.html](aplikacje/timer-lekcyjny.html)**

### Na nastepnym spotkaniu zbudujemy:
- **Losowanie uczniow** - wpisujesz imiona, klikasz i kolo fortuny losuje osobe
- **Generator quizow** - wpisujesz temat, AI tworzy quiz, uczniowie rozwiazuja w przegladarce

---

## Podsumowanie

### Co powinienes miec po szkoleniu:

| # | Co | Gdzie to masz |
|---|---|---------------|
| 1 | Plan lekcji wygenerowany przez AI | Skopiowany z ChatGPT/Claude |
| 2 | 3+ wlasne prompty w formacie RZKFO | Zapisane u siebie |
| 3 | Poprawiony plan lekcji (z pliku) | W historii rozmowy z AI |
| 4 | Analiza ocen z fikcyjnego arkusza | W historii rozmowy z AI |
| 5 | Notatnik w NotebookLM | Na notebooklm.google.com |
| 6 | (Bonus) Grafika lub muzyka | Pobrane na dysk |

### 3 rzeczy do zrobienia w tym tygodniu

Zapisz sobie 3 konkretne zadania, ktore zrobisz z AI w najblizszych dniach. Np.:

1. Przygotuje plan nastepnej lekcji z AI
2. Wgram arkusz ocen (zanonimizowany!) i poprose o analize
3. Wygeneruje grafike na tablice

**Im szybciej zaczniesz uzywac AI w codziennej pracy, tym szybciej zobaczysz efekty.**

---

## Przydatne linki i narzedzia

| Narzedzie | Do czego | Link | Darmowe |
|-----------|----------|------|---------|
| ChatGPT | Rozmowa, pomysly, grafika | [chatgpt.com](https://chatgpt.com) | Tak (z limitem) |
| Claude | Dokumenty, analiza, precyzja | [claude.ai](https://claude.ai) | Tak (z limitem) |
| Gemini | Research, Google integracja | [gemini.google.com](https://gemini.google.com) | Tak |
| NotebookLM | Analiza dokumentow, podcasty | [notebooklm.google.com](https://notebooklm.google.com) | Tak |
| Google AI Studio | Zaawansowane AI, dlugie dokumenty | [aistudio.google.com](https://aistudio.google.com) | Tak |
| Ideogram | Grafika z tekstem | [ideogram.ai](https://ideogram.ai) | Tak (z limitem) |
| Leonardo AI | Profesjonalne grafiki | [app.leonardo.ai](https://app.leonardo.ai) | 150 tokenow/dzien |
| Suno | Muzyka z opisu | [suno.com](https://suno.com) | 5 utworow/dzien |
| Canva | Edycja grafik, prezentacje | [canva.com](https://canva.com) | Tak |

---

*Materialy przygotowane na warsztat praktyczny z AI dla nauczycieli.*
