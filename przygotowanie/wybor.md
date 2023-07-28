---
layout: default
title: Dobiór oprogramowania
parent: Przygotowanie
nav_order: 1
---

## Przygotowanie programów i systemu

### Co, jak, gdzie i kiedy?

Programy, systemy i skrypty. Może brzmieć przerażająco, ale nie ma co się bać. Każdy kiedyś przez to przechodził. Jeżeli jednak to jednak twój komputer ma się bać Ciebie, a nie ty jego, to zachęcam do czytania wyjaśnień co właściwie będziemy robili i co jeszcze jesteśmy w stanie zrobić dodatkowo.

{: .note-title }
> Ciekawostka
>
> Tutaj będą czyste wyjaśnienia, głównie dla ciekawskich. Na przykład: Czy wiedziałęś że zwierzęciem narodowym Szkocji jest jednorożec?

{: .info }
> Te będą zawierać ważniejsze informacje albo odnośniki do różnych [podstron](/cotyturobisz).

{: .warning }
> Czerwonych natomiast sugeruje nie ignorować.

Koniec tego flexowania kolorowymi prostokątami. Wracamy do pracy. Na razie tylko sprawdzimy jakie mamy opcje, pobieraniem zajmiemy się później.

Idźmy więc zgodnie z kolejnością zadanych pytań.

### Co?

#### Ventoy

Dla spójności, wygody oraz kompatybilności z linuxem, będziemy używać [Ventoy'a](https://www.ventoy.net/en/index.html).

{: .note-title }
> Czym jest ten Ventoy?
>
> A no jest to "mini system", który można zainstalować w tym przypadku na pendrive'ie, który umożliwia uruchamianie ***prawie*** wszystkich instalatorów systemów. Wyjaśnienie dlaczego używamy akurat tego [tutaj](/info/ventoy).

#### Windows

Teraz musimy wybrać co właściwie będziemy instalować. Do wyboru mamy:

- Windows 10 Vanilla
- Windows 11 Vanilla
- Custom ISO
- Vanilla + Playbook

{: .info }
> Vanilla znaczy podstawowy, oryginalny.

{: .info }
> Custom ISO jest to tłumacząc na język zrozumiały, nieoficjalna wersja Windows'a. Głównie nastawiona na małą wielkość, prywatność lub/oraz wydajność.

{: .note }
> Playbook to swojego rodzaju duży zbiór poprawek nakładanych już po instalacji sysstemu stworzonych przez konkretną grupę najczęściej tworzącą również Custom ISO.
Odróżnia się je sposobem instalacji. Custom ISO jest już instaluje już zmodyfikowany system, natomiast playbooki są *wykonywane* przez użytkownika i wtedy zmieniają one czysty (vaniliowy) system.

*Więcej informacji się nie dało? Tyle napisałeś a ja dalej nie wiem który powinienem wziąć!*  

Na ratunek przychodzi

#### Moja **super** tableka

| Typ        | Zalety                                                                                                                                                                                  | Wady                                                                                                                                                                                                                                    |
| ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Vanilla    | - Bezpieczeństwo<br>- Częstotliwość Aktualizacji<br>- Wszystko zainstalowane                                                                                                            | - WSZYSTKO zainstalowane (w tym Candy Crush Saga ❤️)<br>- Zerowa prywatność (śledzenie co kto klika itp)<br>- Wymagane konto Microsoft<br>- Obniżona wydajność przez ogrom procesów i usług w tle                                        |
| Playbook   | - Częstotliwość Aktualizacji<br>- Wydajność<br>- Umiarkowana Prywatność<br>- Mała ilość domyślnych programów<br>- Lista modyfikacji (i kod źródłowy) jest dostępny online (open-source) | - Długość instalacji<br>- Możliwe problemy z większymi aktualizacji Windows'a<br>- Modyfikowanie systemu<br>- Część telemetrii pozostaje włączona                                                                                       |
| Custom ISO | - Wzorowa wydajność<br>- Możliwie maksymalna prywatność<br>- Minimalna ilość domyślnych programów<br>- Mała wielkość systemu<br>- Szybkość przygotowania                                | - Bezpieczeństwo (więcej poniżej)<br>- Możliwe trudności w znalezieniu odpowiedniego<br>- W zależności od wyboru, możliwa niestabilność na niektórych komputerach<br>- Częstotliwość aktualizacji (Samego systemu, nie antywirusa itp.) |

#### Opcjonalne: Linux na ratunek dla straconych plików!

Wracasz sobie po ciężkim dniu do domu, siadasz przed komputer żeby przejrzeć jedyną kopię zdjęć z tej jednej wycieczki, włączasz go a to nagle... ***nic***. Nie daje znaku życia/sam się restartuje/zawiesza się w losowym momencie. Na szczęście wielkie głowy tworzące wszelakie linuxy umożliwiają uruchomienie go bez żadnej instalacji. Magia, wiem. Co prawda wszelkie zmiany zostaną stracone po zwykłym restarcie komputera, ale dla awaryjnego wrzucenia zdjęć do chmury albo innego dysku czy pendrive'a, będzie idealny.

{: .info }
Niewykluczone, że nie był to pomysł *tego głupiego komputera* albo pecha żeby popsuć Ci dzień. Dyski (tak samo jak inne podzespoły) się zużywają. Jeżeli po tym poradniku problem dalej będzie się pojawiać, polecam użyć programu [CrystalDiskInfo](https://crystalmark.info/en/download/#CrystalDiskInfo). Pomoże on w sprawdzeniu stanu dysku.

Masz swojego kandydata? Wiesz już czego potrzebujesz? Super! [Idziemy dalej](ventoy)
