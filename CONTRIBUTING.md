# Dołączanie do polskiego przekładu Selah

Dziękujemy za pomoc w czynieniu tego przekładu dokładniejszym,
jaśniejszym i bliższym polszczyźnie. Nie trzeba być uczonym:
powiedz, co widzisz, daj dowody, które masz, i oddziel pewne od
przypuszczenia.

## Zgłosić błąd lub zaproponować poprawkę

- Otwórz **Issue**, jeśli sprawa wymaga rozmowy, jeśli możliwe jest
  więcej niż jedno odczytanie, albo jeśli nie jest jasne, jak
  poprawka wpłynie na wyrównanie (alignment) tokenów.
- Otwórz **Pull request**, jeśli i błąd, i poprawka są oczywiste.
- W sprawach programowych lub bezpieczeństwa/konta/prywatności —
  [Selah Support](https://selahproject.com/support).

## Co warto dołączyć

Księga, rozdział, werset, odpowiednie hebrajskie słowo; obecny
tekst; proponowany tekst; powód zmiany; oraz dowody ze słownika,
gramatyki, kontekstu lub opublikowanych źródeł. Zaznacz też, czy
polski jest twoim językiem ojczystym i czy czytasz hebrajski
bezpośrednio.

## Zasady edycji plików

Pliki mają formę `<book>/<chapter>/<verse>.json`.

- Jeśli zmiana dotyczy obu — edytuj razem odpowiednie części
  `translation` i `gloss`.
- `book`, `chapter`, `verse`, `ref`, hebrajskie wartości `surface`
  oraz porządek i liczba tokenów — **nigdy ich nie zmieniaj**.
  Zepsute wyrównanie to najdroższy błąd.
- **Według tabeli Imion**: יהוה → **Jahwe**; אלהים → **Elohim**;
  אדני → **Adonai**; שדי → **Szaddaj**; שאול → **Szeol**;
  חסד → **chesed**. Na miejscu Imienia **Jehowa**, **PAN** i
  **Bóg** nie są przyjmowane. (Dla pospolitego *elohim* decyduj
  przy każdym tokenie; nie odrzucaj hurtem.)
- Zachowuj znacznik **⟨את⟩** i ⟨nawiasowe⟩ uzupełnienia; nie
  usuwaj ich po cichu. Uzupełnione słowa w nawiasach muszą być
  **polskie**.
- Poza nawiasami — tylko polski alfabet z pełnymi znakami
  diakrytycznymi: bez angielskich wtrąceń, bez cyrylicy, bez CJK,
  bez pisma arabskiego, bez dewanagari.

## Miara metody

Hebrajski — pierwszy. Jeśli dwa odczytania mogą stać — pokaż
rozbieżność; nie podawaj wyboru jako pewności. Nie kopiuj ze
współczesnych przekładów chronionych prawem autorskim.

## Praca z AI

Powiedz otwarcie, jeśli używasz dużego modelu językowego lub
tłumaczenia maszynowego — wraz z własną weryfikacją. Nie przysyłaj
mas niesprawdzonego tekstu. Każde zaproponowane słowo to
odpowiedzialność tego, kto je proponuje.

## Licencja, zapis i ocena

Dołączając, zaświadczasz, że masz do tego prawo, i zgadzasz się,
że wszystko przyjęte zostanie wydane na
[CC BY-SA 4.0](LICENSE.md). Historia Git przechowuje zapis i
otwarte dowody. Opiekunowie sprawdzają propozycje z hebrajskim,
z zasadami, ze źródłami i z wyrównaniem — mogą przyjąć, dopracować
razem z tobą, czekać na dalsze dowody albo odrzucić z podaniem
przyczyny. Oceniane jest słowo, a nie człowiek.
