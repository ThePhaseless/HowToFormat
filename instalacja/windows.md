---
layout: default
title: Instalacja Windowsa
parent: Instalacja
nav_order: 4
---

<!-- markdownlint-disable MD025 -->
# Zdobywanie Windowsa

Wszystkie kroki są takie same niezależnie od rodzaju naszego systemu.

Zaznaczamy nasz plik `.iso` z instalatorem wybranego systemu i czekamy chwilkę.

Następnie klikamy kontynuuj, osoby znające swój kod licencji mogą go wpisać i nacisnąć dalej, a ci, którzy go nie mają lub mają go wpisanego w płytę główną, klikamy *Nie mam kodu produktu*.

Wybieramy naszą kupioną ~~lub nie~~ wersję systemu, zaznaczamy **Custom Install**/**Instalacja niestandardowa** i przechodzimy dalej.

## Przygotowanie partycji

W tym momencie powinieneś widzieć swoje wszystkie partycje.

{: .info}
Partycja - wirtualna "część dysku". Potraktuj je jako bardziej zaawansowanych folderach na pliki

{: .note}
Dla osób które mają więcej niż jeden dysk i chcą przeinstalować system na ten sam dysk, zanim zaczniemy usuwanie, zapisz sobie numer dysku, który ma najwięcej partycji, bo to najprawdopodobniej ten, który ma stary system.

{: .warning}
Następny krok usunie wszystkie dane z wybranej partycji, więc uważaj którą usuwasz. Odzyskanie danych z takiej partycji graniczy z cudem.

Teraz usuwamy guzikiem *Delete* **wszystkie** partycje z dysku, który ma w sobie partycję *Windows*.

Po wszystkim powinniśmy mieć coś tym stylu (może być też po angielsku):

`Dysk *jakiś numerek* Nieprzypisane miejsce`

{: .note}
Nie powinno być również innych partycji z tym samym numerkiem dysku co *Nieprzypisane miejsce*!

## Instalacja

Zaznaczamy puste miejsce i klikamy dalej. *Magia sama zacznie się dziać*

Po magicznym momencie instalowania, pora na [wykańczanie](postinstall).
