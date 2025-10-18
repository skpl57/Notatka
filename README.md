# Notatka
By Szymon i Maja,
Notatka do Aplikacji Mobilnych (Android Studio)

--------------------------- Git ---------------------------
- git init

- git config user.name "username"
- git config user.email "email"

- git add . - dodaje wszystkie pliki
- git commit -m "commit name"
- stwórz puste repozytorium na githubie
- skopiuj link
- git push -u origin master (!!!MUSI BYĆ MASTER A NIE MAIN!!!)
	
	potem tylko:
- git add .
- git commit -m "pusty projekt"
- git push

  inne komendy:
- git status - sprawdza czy coś jest do zapisania (commitowania)
- git add/rm <file> -  zapisuje plik (commituje)
- git restore <file> - usuwa niezapisane pliki (które nie były commitowane) -> wraca do poprzedniej wersji

- mechaniktgmobilne - konto Pani na gicie

--------------------------- Windows ---------------------------

- menedżer poświadczeń -> Pświadczenia systemu -> git.hub -> usuń dane!

--------------------------- XML ---------------------------
- katalog manifest - układ z XML'em

- gravity - ustawia dziecko
- layout_gravity - ustawia rodzica
- backgroundTint - kolor tła dla przycisków
- background - kolor tła
  
- "wrap_content" - skraca do minimalnej szerokości, którą potrzebuje (z wysokością tak samo)
- "match_parent" - wydłuża szerokość do szerokości rodzica (z wysokością tak samo)
- adjustViewBounds - dostosowuje do szerokoścki
  
- sp - do tekstu
- dp - do rozmiarów, marginów itp

- Res/drawable -> obrazy
  
--------------------------- Java ---------------------------
- java\com.example.NazwaPliku\Main.java - główny plik kodu

- Toast - dymek wiadomości

- R - katalog "res" (można się odwołać do wielu rzeczy)
- obiekt = findViewById(R.id.idObiektu) -> stworzenie obiektu z elementu z XML (po odpowiedniej lini w onCreate)
- przycisk.setOnClickListner -> new View.OnClickListner  (lepsza praktyka klikania, w onCreate trzeba zrobić)
  
- onSaveInstanceState -> możliwość zapisywania rzeczy (z protected	)
- outState.put...() -> 	wymagane zdefiniowanie co zapisujemy np putInt("ID", zmienna)
  
- savedInstanceState -> to obiekt, który ma wszystkie zapisane informacje z "put"
- savedInstanceState.get...() -> pobiera zapisaną wartość po kluczu, należy podać typ pobieranej wartości np getInt("ID")

