# ExamplesARKO

###### [ARKO] Computer Architecture, Warsaw University of Technology

## **[PL]**
**Przykłady zadań z asemblera w środowisku MIPS**

*New*
- [x] [Uppercase](MIPS/Uppercase.asm)
  - Zamiana wszystkich małych liter na wielkie
- [x] [Supplement](MIPS/Supplement.asm) 
  - Zastępowanie cyfr ich dopełnieniem do 9 \(0->9, 1->8, 2->7 itd.).
- [x] [Numbers](MIPS/Numbers.asm)
  - Wypisywanie najdłuższego ciągu cyfr znalezionego w łańcuchu wejściowym.
- [x] [ReverseNum](MIPS/ReverseNum.asm)
  - Odwrócenie kolejności cyfr \(tylko).
- [x] [DecConversion](MIPS/DecConversion.asm)
  - Skanowanie \(konwersja) i wyświetlanie największej liczby dziesiętnej z łańcucha.
- [x] [DecCount](MIPS/DecCount.asm)
  - Zliczanie liczb dziesiętnych w łańcuchu.
- [ ] Usunięcie z łańcucha znaków z określonego podzbioru \(cyfr, małych liter itp.)
- [ ] Usunięcie z łańcucha sekwencji znaków o pozycji i długości zadanej w postaci liczb, z właściwą reakcją na nieprawidłowe wartości argumentów.
- [ ] Zastępowanie co trzeciej małej litery przez odpowiadającą jej wielką.
- [ ] Usuwanie z każdej ciągłej sekwencji wszystkich wielkich liter oprócz pierwszej litery.
- [x] [ChangeLetters](MIPS/ChangeLetters.asm)
  - Wczytywanie czterech liter z sekwencji, zamiana środkowych miejscami i wyświetlenie rezultatu, przy czym nie można stosować instrukcji lb i sb.
- [x] [DeleteLetters](MIPS/DeleteLetters.asm)
  - Usuwanie liter z podanej na wejściu sekwencji.
- [x] [ZBuffer](MIPS/ZBuffer)
  - Generowanie dwóch trójkątów po podaniu odpowiednich wierzchołków z zastosowaniem algorytmu Z-Buffer.

*Old*
- [ ] Program sumujący wprowadzane z konsoli dziesiętne liczby stałopozycyjne zawierające do 200 cyfr.
- [ ] Wyświetlanie obrazu z pliku .BMP w formacie 24 bpp z odbiciem lustrzanym względem pionowej osi symetrii.
- [ ] Rotacja obrazu zapisanego w pliku .BMP w fromacie 1 bpp o 90 stopni.
- [ ] Kalkulator działający w notacji polskiej odwrotnej operujący na liczbach całkowitych zapisanych w systemie siódemkowym.
- [ ] Obliczanie pierwiastka całkowitego liczby całkowitej algorytmem nierestytucyjnym.
- [ ] Program czytający program asemblerowy MIPS i generujący statystykę liczb wystąpień poszczególnych instrukcji i dyrektyw asemblera.
- [ ] Program przetwarzający tekst poprawnego programu w języku C poprzez zastępowanie w stałych znakowych \(pojedynczych znakach i łańcuchach) znaków spoza zakresu ASCII odpowiednimi sekwencjami \xnn.
- [ ] Wejściowy plik tekstowy zawiera tekst naturalny z datami zapisanymi w dowolnym typowym formacie numerycznym \(dd.mm.yy, mm/dd/yy, yyyy-mm-dd, z 2- lub 4-cyfrową reprezentacją roku). Program przetwarza tekst poprzez zmianę postaci wszystkich dat na jednolitą - wybraną przez użytkownika.
- [ ] Program dopisujący na końcu pliku tekstowego wiersz tekstu zawierający kolejną liczbę dziesiętną bez znaku po ostatniej znalezionej w pliku. Jeśli plik nie istnieje lub nie zawiera liczb - w ostatnim wierszu powinna pojawić się liczba 1.
- [ ] Program czyta plik .BMP zawierający obraz zapisany w formacie 1, 2 lub 4 bpp \(jeden format do wyboru) i wyświetla górny lewy róg obrazu \(max. 64x24 piksele) na konsoli używające do reprezentacji poszczególnych pikseli pojedynczych znaków ASCII. Program musi poprawnie obsługiwać pliki zawierające obrazy o dowolnej rozdzielczości, również mniejszej od 64x24.
- [ ] Dzielenie liczb zmiennopozycyjnych IEEE binary64 przez IEEE binary32 bez użycia jednostki zmiennopozycyjnej.
- [ ] Generowanie obrazu o zadanej wysokości/szerokości z umieszczonym centralnie kołem o zadanej średnicy. Użyć algorytmu Bresenhama do równoczesnego kreślenia 8 punktów okręgu oraz dowolnego prostego algorytmu wypełniania koła.
- [ ] Mnożenie liczby zmiennopozycyjnej IEEE binary64 przez 32-bitową liczbę całkowitą ze znakiem, z wynikiem binary64.
- [ ] Wyświetlanie obrazu z pliku .BMP 24 bpp z proporcjonalnym skaolowaniem w dół w pionie i w poziomie tak, aby wysokość wyświetlanego obrazu nie przekraczała np. 600 pikseli.
- [ ] Program zmieniający stałe binarne w programie źródłowym w języku C na zgodne ze standardem AnSI stałe szesnastkowe o możliwie najkrótszej reprezentacji \(0b100001 -> 0x21).
- [ ] Wyświetlanie obrazu gładko cieniowanego trójkąta o zadanych współrzędnych (x,y) i kolorach wierzchołków (rgb).
- [ ] Wyświetlanie obrazu z pliku .BMP \(do wyboru - odcienie szarości 8 BPP lub kolorowy 24 BPP z zamianą na skalę szarości) w postaci czarno-białej \(dwa kolory pikseli) przy użyciu techniki drżenia \(dithering). Błąd odwzorowania powinien propagować do kolejnego piksela w wierszu. Błąd odwzorowania koloru ostatniego piksela w wierszu propaguje do piksela położonego pod lub nad nim w kolejnym wierszu - w kolejnych wierszach następuje zmiana kierunku propagacji błędu i kolejności określania kolorów pikseli.
- [ ] Mnożenie dziesiętnych liczb stałopozycyjnych bez znaku zawierających do 50 cyfr znaczących.
- [ ] Dzielenie liczb całkowitych ze znakiem z wynikiem zmiennopozycyjnym IEEE binary64, bez użycia jednostki zmiennopozycyjnej ani dzielenia stałopozycyjnego.
- [ ] Program przetwarzający plik źródłowy w języku asemblerowym, zastępujący stałe szesnastkowe w tradycyjnej notacji asemblerowej \(np. 0abch, 123h) stałymi w notacji zgodnej ze składnią C \(0xabc, 0x123). Program nie powinien zmieniać postaci stałych innych, niż szesnastkowe.
- [ ] Wyświetlanie obrazu z pliku .BMP 24 bpp z rotacją o 90 stopni w prawo.
- [ ] Wyświetlanie obrazu z pliku .BMP 24 bpp z redukcją nasycenia barw w stosunku x/256, x zadawane jako parametr.
- [ ] Wyświetlanie symulowanego obrazu poziomego widma barw widzialnych \(od czerwieni do fioletu) o zadanej przez użytkownika wysokości \(>=1) i szerokości \(>=3).
- [ ] Skanowanie z tekstu źródłowego liczb całkowitych bez znaku w dowolnym zapisie zgodnym ze składnią języka C \(óswmkowych, dziesiętnych, szesnastkowych) i wyświetlenie każdej z nich w trzech postaciach: ósemkowej, dziesiętnej i szesnastkowej. Wymagana poprawna obsługa zakresu 0..2^32-1

**Przykłady zadań z asemblera w środowisku Intelx86**

*New*
- [x] [ChangeCase](x86/ChangeCase)
  - Zamiana formatowania wyrazów
- [x] [DeleteEvenNum](x86/DeleteEvenNum)
  - Usuwanie liczb parzystych
- [ ] [Tetrahedron](x86/Tetrahedron)
  - Obracający się czworościan zgodnie z naciskanymi klawiszami kontrolnymi

`Exercises made by MSc Eng Grzegorz Mazur, IIPW and MSc Eng Sławomir Niespodziany, IIPW`
