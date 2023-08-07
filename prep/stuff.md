---
layout: default
title: Dobór oprogramowania
parent: Przygotowanie
nav_order: 2
---

<!-- markdownlint-disable MD025 -->
# Przygotowanie programów i systemu

Programy, systemy i skrypty. Może brzmieć przerażająco, ale jeżeli jednak to twój komputer ma się bać Ciebie, a nie na odwrót, to zachęcam do czytania wyjaśnień co właściwie będziemy robili i ewentualnie co jeszcze jesteśmy w stanie zrobić dodatkowo.

## Ventoy

Dla spójności, wygody oraz kompatybilności z linux`em, będziemy używać [Ventoy'a](https://www.ventoy.net/en/index.html).

{: .note-title }
> Czym jest ten Ventoy?
>
> A no jest to "pseudo system", który można zainstalować na nośnikach (w tym przypadku na pendrive'ie), umożliwiający uruchamianie ***prawie*** wszystkich plików `.iso` (w tym instalatorów systemów). Wyjaśnienie dlaczego używamy akurat tego [tutaj](/info/ventoy).

{: info }
> Pliki `.iso` to tak zwane *obrazy dysków*. Z obrazami jednak nie ma za wiele wspólnego. W dużym skrócie powstały na potrzeby kopiowania DVD/CD do plików (nie tylko tych z systemami), żeby potem *włożyć je* wirtualnie, ale z czasem, łatwiej było pobrać taki plik niż znaleźć go wśród sterty płyt. Dla wygody, do dziś nie zmieniono tego rozszerzenia.

## Windows

Teraz musimy wybrać co właściwie będziemy instalować. Do wyboru mamy:

- Windows 10 Vanilla
- Windows 11 Vanilla
- Custom ISO
- Vanilla + Playbook

{: .info }
> Vanilla znaczy podstawowy, oryginalny.

{: .info }
> Custom ISO (*Niestandardowy obraz*) jest to tłumacząc na język zrozumiały, nieoficjalna wersja Windows'a. Tworzone przez społeczność, głównie nastawione są na małą wielkość, prywatność lub/oraz wydajność.

{: .note }
> Playbook to swojego rodzaju duży zbiór poprawek nakładanych już po instalacji systemu, tworzone przez grupy najczęściej tworzące również custom ISO.
Różnią się one sposobem instalacji. Custom ISO jest instaluje już zmodyfikowany system, natomiast playbook`i są stosowane przez użytkownika i wtedy modyfikują one czysty system.

*Więcej informacji się nie dało? Tyle napisałeś a ja dalej nie wiem który powinienem wziąć!*  

Na ratunek przychodzi

### Moja **super** tabelka
<!-- markdownlint-disable MD033 -->

| Typ        | Zalety                                                                                                                                                                                  | Wady                                                                                                                                                                                                                                    |
| ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Vanilla    | - Bezpieczeństwo<br>- Częstotliwość Aktualizacji<br>- Wszystko zainstalowane                                                                                                            | - WSZYSTKO zainstalowane (w tym Candy Crush Saga ❤️)<br>- Zerowa prywatność (śledzenie co kto klika itp)<br>- Wymagane konto Microsoft<br>- Obniżona wydajność przez ogrom procesów i usług w tle                                        |
| Playbook   | - Częstotliwość Aktualizacji<br>- Wydajność<br>- Umiarkowana Prywatność<br>- Mała ilość domyślnych programów<br>- Lista modyfikacji (i kod źródłowy) jest dostępny online (open-source) | - Długość instalacji<br>- Możliwe problemy z większymi aktualizacji Windows'a<br>- Modyfikowanie systemu<br>- Część telemetrii pozostaje włączona                                                                                       |
| Custom ISO | - Wzorowa wydajność<br>- Możliwie maksymalna prywatność<br>- Minimalna ilość domyślnych programów<br>- Mała wielkość systemu<br>- Szybkość przygotowania                                | - Bezpieczeństwo (więcej poniżej)<br>- Możliwe trudności w znalezieniu odpowiedniego<br>- W zależności od wyboru, możliwa niestabilność na niektórych komputerach<br>- Częstotliwość aktualizacji (Samego systemu, nie antywirusa itp.) |

{: .warning }
> Custom ISO uważane są za kontrowersyjne z jednego prostego powodu. Nie wiadomo co dokładnie instalujemy. Nie mają one kodu źródłowego który można sprawdzić i właśnie dlatego pomimo zabezpieczeniem się przed śledzeniem ze strony Microsoftu, nie wykluczone, że nie będziemy śledzeni z innej strony. Osobiście używam Revision OS i do tej pory nie miałem z nim żadnych problemów, jednak proszę, **upewnij się, że możesz ufać twórcom swojego systemu**.

{: .note}
> Z tego właśnie konkretnego powodu powstały Playbook'i. Są bardziej ograniczone jeżeli chodzi o możliwości, ale za to możemy sprawdzić co dokładnie będzie działo się w naszym systemie i często możemy też personalizować swoje ustawienia.

## Opcjonalne: Linux na ratunek dla straconych plików

Wracasz sobie po ciężkim dniu do domu, siadasz przed komputer żeby przejrzeć jedyną kopię zdjęć z tej jednej wycieczki, włączasz go a to nagle... ***nic***. Nie daje znaku życia/sam się restartuje/zawiesza się w losowym momencie. Na szczęście wielkie głowy tworzące wszelakie linux`y umożliwiają uruchomienie go bez żadnej instalacji. Magia, wiem. Co prawda wszelkie zmiany zostaną stracone po zwykłym restarcie komputera, ale dla awaryjnego wrzucenia zdjęć do chmury albo innego dysku czy pendrive'a, będzie idealny.

{: .info }
> Niewykluczone, że nie był to pomysł *tego głupiego komputera* albo pecha żeby popsuć Ci dzień. Dyski (tak samo jak inne podzespoły) się zużywają. Jeżeli po tym poradniku problem dalej będzie się pojawiać, polecam użyć programu [CrystalDiskInfo](https://crystalmark.info/en/download/#CrystalDiskInfo). Pomoże on w sprawdzeniu stanu dysku.

Masz swojego kandydata? Wiesz już czego potrzebujesz? Super! [Idziemy dalej](ventoy)
