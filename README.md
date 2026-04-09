# AI dla nauczycieli - Warsztat praktyczny

> Instrukcja krok po kroku. Otwierasz, scrollujesz, robisz.
> Nie musisz znać się na technologii - wystarczy przeglądarka i ciekawość.

---

## Jak korzystać z tego repozytorium

### Pobierz materiały

1. Kliknij zielony przycisk **"Code"** na górze tej strony
2. Wybierz **"Download ZIP"**
3. Rozpakuj pobrany plik na pulpicie

Gotowe - masz folder ze wszystkimi plikami, które będą Ci potrzebne.

### Przygotuj narzędzia

Otwórz w przeglądarce dowolne z tych narzędzi (wszystkie są darmowe):

| Narzędzie | Adres | Do czego | Darmowy limit |
|-----------|-------|----------|---------------|
| **ChatGPT** | [chatgpt.com](https://chatgpt.com) | Rozmowa, pomysły, grafika | ~15 wiadomości / 3h (GPT-4o) |
| **Claude** | [claude.ai](https://claude.ai) | Dłuższe dokumenty, analiza, precyzja | ~20 wiadomości / dzień |
| **Gemini** | [gemini.google.com](https://gemini.google.com) | Research, integracja z Google | Praktycznie bez limitu |
| **NotebookLM** | [notebooklm.google.com](https://notebooklm.google.com) | Analiza dokumentów, podcasty AI | Bez limitu |

Wystarczy jedno narzędzie. Jeśli nie wiesz które - zacznij od **ChatGPT** lub **Gemini**.

### Jak kopiować prompty

W tej instrukcji znajdziesz gotowe prompty w szarych blokach. Wystarczy najechać myszką na blok i kliknąć ikonkę kopiowania w prawym górnym rogu:

```
Ten tekst możesz skopiować jednym kliknięciem
```

---

## Część 1: Twój pierwszy prompt (15 min)

Zacznijmy od czegoś konkretnego. Skopiuj poniższy prompt, wklej do ChatGPT lub Claude i zobacz co się stanie:

```
Jesteś doświadczonym nauczycielem w szkole.

Zadanie: Przygotuj kompletny plan lekcji.

Kontekst:
- Temat: Fotosynteza
- Klasa: 6 (szkoła podstawowa)
- Czas: 45 minut
- Uczniowie: 25 osób, różny poziom zaangażowania
- Dostępne: tablica, projektor, internet

Format odpowiedzi:
- Tabela z kolumnami: Czas | Etap lekcji | Co robi nauczyciel | Co robią uczniowie | Materiały
- Na końcu: 3 pytania sprawdzające zrozumienie
- Zadanie domowe (krótkie, max 15 min)

Ograniczenia:
- Max 30% czasu na wykład (reszta to aktywności uczniów)
- Język prosty, zrozumiały dla 12-latków
- Uwzględnij różne style uczenia się
```

**Dostałeś plan lekcji w kilka sekund?** Właśnie tak działa dobrze napisany prompt.

### Twoja kolej

Zmień w tym prompcie:
- **Temat** - na swój przedmiot i temat
- **Klasę** - na swoją
- **Czas** - na swój (45, 60, 90 minut)

Skopiuj zmieniony prompt, wklej do narzędzia i porównaj wynik z pierwszym.

---

## Część 2: Jak pisać dobre prompty - metoda RZKFO (45 min)

Ten plan lekcji wyszedł dobrze, bo prompt miał jasną strukturę. Ta struktura to **RZKFO**:

| Litera | Co to znaczy | Przykład |
|--------|-------------|----------|
| **R** - Rola | Kim ma być AI | "Jesteś doświadczonym nauczycielem matematyki" |
| **Z** - Zadanie | Co AI ma zrobić | "Przygotuj 10 zadań z ułamkami" |
| **K** - Kontekst | Szczegóły sytuacji | "Klasa 7, poziom średni, przed sprawdzianem" |
| **F** - Format | Jak ma wyglądać wynik | "Tabela: numer, zadanie, odpowiedź, trudność" |
| **O** - Ograniczenia | Czego unikać, limity | "Bez kalkulatora, max 3 działania w zadaniu" |

Nie musisz używać wszystkich 5 elementów za każdym razem. Ale im więcej podasz, tym lepszy będzie wynik.

### Ćwiczenie 1: Zbuduj własny prompt (10 min)

Wybierz jedno zadanie ze swojej codziennej pracy i napisz prompt używając RZKFO:

```
Rola: Jesteś _________________________ [kim?]

Zadanie: _____________________________ [co ma zrobić?]

Kontekst:
- __________________________________ [klasa, przedmiot, sytuacja]
- __________________________________ [ile osób, jaki poziom]
- __________________________________ [dodatkowe okoliczności]

Format odpowiedzi:
- __________________________________ [tabela, lista, tekst ciągły?]

Ograniczenia:
- __________________________________ [czego unikać, jakie limity]
```

Wklej gotowy prompt do ChatGPT lub Claude. Sprawdź wynik.

### Ćwiczenie 2: Popraw słaby prompt (10 min)

Poniższy prompt jest celowo słaby. Skopiuj go, wklej do narzędzia i zobacz wynik:

```
Zrób mi coś do lekcji
```

Teraz popraw go używając RZKFO i wklej ponownie. Porównaj wyniki - różnica jest ogromna.

### Ćwiczenie 3: Porównaj narzędzia (10 min)

Weź swój najlepszy prompt z Ćwiczenia 1 i wklej go kolejno do:
1. **ChatGPT** (chatgpt.com)
2. **Claude** (claude.ai)
3. **Gemini** (gemini.google.com)

Które narzędzie dało najlepszy wynik dla Twojego zadania? Każde ma swoje mocne strony:

| Narzędzie | Najlepsze do |
|-----------|-------------|
| ChatGPT | Szybkie pomysły, burza mózgów, grafika (DALL-E) |
| Claude | Długie dokumenty, precyzyjne instrukcje, analiza tekstu |
| Gemini | Wyszukiwanie informacji, praca z Google Docs, badania |

### Biblioteka gotowych promptów

Przygotowaliśmy **20 gotowych promptów** dopasowanych do codziennej pracy nauczyciela. Znajdziesz je tutaj:

**[Otwórz bibliotekę promptów](prompty/biblioteka-promptow.md)**

Każdy prompt jest gotowy do skopiowania - wystarczy uzupełnić miejsca oznaczone `[UZUPEŁNIJ]`.

---

## Część 3: AI czyta Twoje dokumenty (60 min)

AI potrafi analizować pliki - dokumenty Word, arkusze kalkulacyjne, PDF-y, teksty. Wystarczy je wrzucić do rozmowy.

### Jak wgrać plik

**W ChatGPT:**
1. Na dole okna rozmowy kliknij ikonkę **spinacza** (po lewej stronie pola tekstowego)
2. Wybierz plik z dysku
3. Plik pojawi się w oknie - teraz napisz co AI ma z nim zrobić

**W Claude:**
1. Na dole okna kliknij ikonkę **spinacza**
2. Wybierz plik
3. Napisz polecenie

**W Gemini:**
1. Na dole okna kliknij ikonkę **+**
2. Wybierz "Upload file"
3. Napisz polecenie

### Ćwiczenie 1: Popraw plan lekcji (15 min)

W folderze `pliki/` znajdziesz plik **[plan-lekcji.docx](pliki/plan-lekcji.docx)** - to przykładowy plan lekcji, który ma kilka słabych punktów.

1. Wgraj ten plik do ChatGPT lub Claude
2. Skopiuj i wklej ten prompt:

```
Przeanalizuj ten plan lekcji i:

1. Wskaż 3 mocne strony
2. Wskaż 3 elementy do poprawy
3. Zaproponuj poprawioną wersję z uwzględnieniem:
   - Różnicowania dla uczniów z trudnościami w nauce
   - Elementów aktywizujących (nie tylko wykład)
   - Jasnych kryteriów sukcesu dla uczniów

Zachowaj format tabelaryczny.
```

3. Przeczytaj odpowiedź - czy AI trafnie zidentyfikowało słabe punkty?

### Ćwiczenie 2: Przeanalizuj oceny (15 min)

Wgraj plik **[lista-ocen.csv](pliki/lista-ocen.csv)** - to fikcyjny arkusz z ocenami 30 uczniów z 5 przedmiotów.

```
Przeanalizuj ten arkusz ocen:

1. Policz średnią ocen każdego ucznia (po wszystkich przedmiotach)
2. Zidentyfikuj 5 uczniów z najniższymi średnimi
3. Dla każdego z tych uczniów wskaż przedmiot, w którym radzi sobie najlepiej
4. Napisz krótką notatkę (3-4 zdania) dla wychowawcy o każdym z tych uczniów

Format: tabela z kolumnami Uczeń | Średnia | Najlepszy przedmiot | Notatka
```

### Ćwiczenie 3: Przeróbka opinii (15 min)

Wgraj plik **[opinia-ucznia.txt](pliki/opinia-ucznia.txt)** - to nieformalna opinia o uczniu, napisana "na kolanie".

```
Przeróbka tej opinii na formalną opinię końcową zgodną ze standardami szkolnymi:

1. Zachowaj wszystkie informacje merytoryczne
2. Użyj profesjonalnego, ale ciepłego języka
3. Struktura: postępy w nauce, zachowanie, mocne strony, obszary do rozwoju, rekomendacje
4. Długość: max 1 strona A4

Na końcu zaproponuj 2 alternatywne wersje ostatniego akapitu (rekomendacje).
```

### WAŻNE: Bezpieczeństwo i RODO

> **STOP - przeczytaj zanim wrzucisz cokolwiek do AI**

Co **MOŻESZ** wrzucać:
- Fikcyjne dane (jak pliki z tego repozytorium)
- Anonimowe dane (imiona zmienione na "Uczeń 1", "Uczeń 2")
- Ogólnodostępne dokumenty (podstawa programowa, podręczniki)
- Własne notatki i plany lekcji

Czego **NIE WRZUCAJ**:
- Prawdziwych imion i nazwisk uczniów
- Prawdziwych ocen z dziennika
- Danych osobowych (PESEL, adresy, telefony)
- Pytań egzaminacyjnych przed egzaminem
- Poufnych dokumentów szkolnych

**Jak anonimizować dane?** Zamień imiona i nazwiska **ZANIM** wrzucisz plik do AI. Zrób to samodzielnie - w Wordzie, Excelu lub Notatniku podmień dane na "Uczeń 1", "Uczeń 2" itd. Dopiero zanonimizowany plik wgraj do ChatGPT, Claude czy Gemini.

Nie proś AI o anonimizację - w momencie wgrania pliku z prawdziwymi danymi, AI już je "zobaczyło". To tak jakby dać komuś dokument z danymi uczniów i poprosić "zapomnij co przeczytałeś".

Jeśli chcesz pokazać innym wynik pracy AI (np. na radzie pedagogicznej), ale w oryginalnym dokumencie były prawdziwe dane - wtedy możesz poprosić AI o podmianę imion w **wygenerowanej odpowiedzi**. Ale sam dokument źródłowy musi być zanonimizowany przed wgraniem.

---

## Część 4: AI jako asystent do czytania (45 min)

Nauczyciele toną w dokumentach - podstawa programowa, regulaminy, metodyki, raporty. AI może je przeczytać za Ciebie i wyciągnąć to, co ważne.

### NotebookLM - Twoja baza wiedzy

NotebookLM to narzędzie Google, które pozwala wgrać dokumenty i rozmawiać z nimi jak z ekspertem.

1. Otwórz [notebooklm.google.com](https://notebooklm.google.com) (potrzebujesz konta Google)
2. Kliknij **"New Notebook"** (lub "Nowy notatnik")
3. Kliknij **"Add source"** (lub "Dodaj źródło") i wgraj plik **[artykul-ai-edukacja.md](pliki/artykul-ai-edukacja.md)** z pobranego folderu
4. Poczekaj aż NotebookLM przeanalizuje plik (kilka sekund)

Teraz możesz zadawać pytania o wgrany dokument:

```
Jakie są 3 najważniejsze wnioski z tego artykułu?
```

```
Jak mogę wykorzystać te informacje na lekcji [UZUPEŁNIJ PRZEDMIOT]?
```

```
Przygotuj 5 pytań do dyskusji na radę pedagogiczną
na podstawie tego tekstu.
```

### Funkcja wow: Podcast AI

W NotebookLM kliknij **"Audio Overview"** (lub "Podsumowanie audio"). AI wygeneruje **podcast** - dwóch prowadzących rozmawia o Twoim dokumencie. To trwa ok. 2 minuty generowania, a podcast ma 5-10 minut.

Możesz też dodać wytyczne przed wygenerowaniem:

```
Skup się na praktycznych zastosowaniach w klasie.
Mów prostym językiem, jakbyś tłumaczył to nauczycielowi,
który dopiero zaczyna przygodę z AI.
```

### Deep Research w Gemini

Gemini ma funkcję "Deep Research", która przeszukuje internet i pisze raport.

1. Otwórz [gemini.google.com](https://gemini.google.com)
2. Nad polem tekstowym wybierz tryb **"Deep Research"** (jeśli dostępny)
3. Wpisz pytanie badawcze, np.:

```
Znajdź najnowsze badania (2024-2026) na temat skuteczności
wykorzystania sztucznej inteligencji w nauczaniu [UZUPEŁNIJ PRZEDMIOT]
w szkole średniej. Podaj źródła.
```

Gemini przeszuka kilkadziesiąt stron i przygotuje raport z linkami do źródeł. Trwa to 2-3 minuty, ale wynik jest bardzo solidny.

---

## Część 5: Grafika i muzyka AI - szybki przegląd (30 min)

### Grafika w 2 minuty

Najprostszy sposób: bezpośrednio w ChatGPT (model DALL-E) lub Gemini.

Skopiuj i wklej do ChatGPT:

```
Stwórz kolorowy plakat edukacyjny na temat [UZUPEŁNIJ TEMAT]
dla uczniów klasy [UZUPEŁNIJ].
Styl: przyjazny, kreskówkowy, z dużymi czytelnymi napisami.
Format: pionowy, A3.
```

Wynik pojawi się w kilka sekund. Możesz go pobrać i wydrukować.

Inne narzędzia do grafiki:
- **Ideogram** ([ideogram.ai](https://ideogram.ai)) - najlepsze do tekstu na grafikach
- **Leonardo AI** ([app.leonardo.ai](https://app.leonardo.ai)) - profesjonalne grafiki, 150 tokenów/dzień

### Muzyka AI

**Suno** ([suno.com](https://suno.com)) generuje muzykę z opisu tekstowego. Darmowe konto daje 5 utworów dziennie.

```
Spokojna, instrumentalna muzyka do czytania na lekcji.
Akustyczna gitara, delikatne pianino, bez wokalu.
Tempo wolne, relaksujące. Długość: 2 minuty.
```

```
Energiczny jingle na początek lekcji, 15 sekund.
Optymistyczny, z klaskaniem i gwizdaniem.
Styl: reklama telewizyjna dla dzieci.
```

Wygenerowany utwór możesz pobrać jako MP3 i puszczać na lekcjach.

---

## Część 6: Zbuduj własną aplikację - bez programowania (sesja 2)

> Ta część będzie głównym tematem następnego spotkania.
> Poniżej znajdziesz zapowiedź i przykład do wypróbowania w domu.

### Jak to działa?

1. Opisujesz AI co ma zbudować (w prompcie)
2. AI generuje kod (plik HTML)
3. Zapisujesz go na dysku
4. Otwierasz w przeglądarce
5. Masz działającą aplikację

Zero instalacji. Zero programowania. Plik działa offline.

### Spróbuj sam: Timer lekcyjny

Skopiuj poniższy prompt i wklej do Claude (claude.ai) lub ChatGPT:

```
Stwórz kompletny plik HTML z timerem lekcyjnym. Wymagania:

- Duży, czytelny zegar odliczający w centrum ekranu
- Przyciski szybkiego ustawienia: 5 min, 10 min, 15 min, 45 min
- Możliwość wpisania dowolnego czasu
- Przycisk Start / Pauza / Reset
- Gdy czas minie: ekran zmienia kolor na czerwony + dźwięk powiadomienia
- Ładny, nowoczesny wygląd (ciemne tło, duże cyfry)
- Responsywny - działa na komputerze i telefonie
- Całość w JEDNYM pliku HTML (CSS i JavaScript w środku)
- Interfejs po polsku
```

Dostaniesz kod. Skopiuj go, otwórz Notatnik na komputerze, wklej, zapisz jako `timer.html` i otwórz w przeglądarce.

Gotowy przykład do porównania znajdziesz tutaj: **[aplikacje/timer-lekcyjny.html](aplikacje/timer-lekcyjny.html)**

### Na następnym spotkaniu zbudujemy:
- **Losowanie uczniów** - wpisujesz imiona, klikasz i koło fortuny losuje osobę
- **Generator quizów** - wpisujesz temat, AI tworzy quiz, uczniowie rozwiązują w przeglądarce

---

## Podsumowanie

### Co powinieneś mieć po szkoleniu:

| # | Co | Gdzie to masz |
|---|---|---------------|
| 1 | Plan lekcji wygenerowany przez AI | Skopiowany z ChatGPT/Claude |
| 2 | 3+ własne prompty w formacie RZKFO | Zapisane u siebie |
| 3 | Poprawiony plan lekcji (z pliku) | W historii rozmowy z AI |
| 4 | Analiza ocen z fikcyjnego arkusza | W historii rozmowy z AI |
| 5 | Notatnik w NotebookLM | Na notebooklm.google.com |
| 6 | (Bonus) Grafika lub muzyka | Pobrane na dysk |

### 3 rzeczy do zrobienia w tym tygodniu

Zapisz sobie 3 konkretne zadania, które zrobisz z AI w najbliższych dniach. Np.:

1. Przygotuj plan następnej lekcji z AI
2. Wgraj arkusz ocen (zanonimizowany!) i poproś o analizę
3. Wygeneruj grafikę na tablicę

**Im szybciej zaczniesz używać AI w codziennej pracy, tym szybciej zobaczysz efekty.**

---

## Przydatne linki i narzędzia

| Narzędzie | Do czego | Link | Darmowe |
|-----------|----------|------|---------|
| ChatGPT | Rozmowa, pomysły, grafika | [chatgpt.com](https://chatgpt.com) | Tak (z limitem) |
| Claude | Dokumenty, analiza, precyzja | [claude.ai](https://claude.ai) | Tak (z limitem) |
| Gemini | Research, integracja z Google | [gemini.google.com](https://gemini.google.com) | Tak |
| NotebookLM | Analiza dokumentów, podcasty | [notebooklm.google.com](https://notebooklm.google.com) | Tak |
| Google AI Studio | Zaawansowane AI, długie dokumenty | [aistudio.google.com](https://aistudio.google.com) | Tak |
| Ideogram | Grafika z tekstem | [ideogram.ai](https://ideogram.ai) | Tak (z limitem) |
| Leonardo AI | Profesjonalne grafiki | [app.leonardo.ai](https://app.leonardo.ai) | 150 tokenów/dzień |
| Suno | Muzyka z opisu | [suno.com](https://suno.com) | 5 utworów/dzień |
| Canva | Edycja grafik, prezentacje | [canva.com](https://canva.com) | Tak |

---

*Materiały przygotowane na warsztat praktyczny z AI dla nauczycieli.*
