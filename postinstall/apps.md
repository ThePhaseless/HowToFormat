---
layout: default
title: Aplikacje
parent: Po instalacji
nav_order: 2
---
<!-- markdownlint-disable MD025 -->
# Ułatwiacze życia

## [winget](https://learn.microsoft.com/en-us/windows/package-manager/winget)

Moje ulubione narzędzie. Wyobraź sobie świat, gdzie wszystkie instalatory, biblioteki i programy można zdobyć w jednym miejscu bez potrzeby zapamiętywania linków. Właśnie od tego powstał program autorstwa Microsoft'u: `winget`. Wszystkie Windows'y 11 oraz nowsze Windows'y 10 mają go zainstalowanego, więc nic tak na prawdę nie musisz robić. Nie jest to jednak typowa aplikacja. Jest komendą do konsoli. (Sama konsola też jest domyślnie instalowana)
![winget](winget.png)

### Użycie

Szukamy jednego z programów:

- Terminal *(zalecane)*
- PowerShell

{: .note-title }
> Technicznie rzecz biorąc, Terminal uruchomi PowerShell'a, ale za to będzie o wiele ładniej wyglądać!

Użycie polega na tym:

`winget *polecenie* *argument/y*`

Na przykład:

- `winget search firefox` - komenda przeszukująca bazę programów o nazwie *Firefox*
- `winget install mozilla.firefox` - komenda pobierająca program o ID: `mozilla.firefox`
- `winget pin discord.discord` - powstrzymuje aktualizacje Discord'a
- `winget` - wszystkie pozostałe polecenia ;)

### Paczka programów

Dla chętnych, oto moja paczka programów:
[Pobierz](/winget.json)
