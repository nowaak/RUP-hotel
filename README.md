#  Dokumentacja w Markdown

##  Instalacja:

Piszemy w markdown. Prosty edytor markdowna znajduje sie pod: https://github.com/marktext/marktext/releases

Pobieramy plik wykonywalny dla danego systemu operacyjnego.

Po pobraniu całość jest gotowa do użytku.

* * *

## Szablon dokumentów:

uwagi w [].

```markdown
# [Tytuł dokumentu]



## RUP Hotel



### Autor:



### Korekta: 



### Wersja:



### Data:



### Kierownik Projektu: Michał Starski



---



## Spis treści:



1. Punkt 1



2. Punkt 2



3. Punkt 3
[...]

---
## Punkt 1
**Wszelkie pogrubienia**
[Jezeli chcecie dodac tabelkę, listę etc. piszecie "@" i wybieracie odpowiednią opcje w dostepnej listy]
## Punkt 2
[tutaj tekst]
---
[...]
```

## Obsługa Git-a

Forkujemy repozytorium: https://github.com/michalStarski/RUP-hotel

Komendy w Git Bash:

> git clone <link do forka>

Klonujemy repozytorium.

Dodaj nowego branch'a.

> git checkout -b <nazwa branch'a>

Zastosuj zmiany.

Status repozytorium możesz sprawdzić komendą:

> git diff

Jezeli wszystko się zgadza zacommituj i zpushuj zmiany.

> git add .

> git commit -am "<nazwa commita>"

> git push origin <nazwa branch'a>

Możliwe, że bedziesz musiał zalogowac sie na swoje konto github.

Wejdź na strone swojego forka na github'ie, przejdź na stronę nowo stworzonego brancha i kliknij "Pull request".

Czekaj na review.
