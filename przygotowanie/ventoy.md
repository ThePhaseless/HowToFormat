---
layout: default
title: Ventoy
parent: Przygotowanie
nav_order: 3
---
<!-- markdownlint-disable MD025 -->
# Pobieranie i instalowanie Ventoy'a

A zatem wiadomo już *co*, następne pytanie to

## Jak?

Najpierw potrzebujemy czegoś, z czego uruchomimy nasz instalator. Wchodzimy więc na [stronę pobierania](https://github.com/ventoy/Ventoy/releases) i w zależności od systemu sprawnego komputera pobieramy najnowsze wydanie z zakładki *assets*:

- Windows: `ventoy-*losowe numerki*-windows.zip`
- Linux: `ventoy-*losowe numerki*-linux.tar.gz`
- Pozostałe: `ventoy-*losowe numerki*-livecd.iso`

{: .info }
W tej wersji poradnika (nie znaczy to, że będą inne, ale to też nie jest wykluczone) założę, że używać będziemy Windowsa.

Pobrany plik wypakowujemy (prawy przycisk myszy -> wypakuj/extract). Upewnij się, że pliki zostały wypakowywane do oddzielnego folderu (np. ventoy-1.0.94-windows), a nie bezpośrednio w folderze pobranych.

Upewnij się, że pendrive jest podłączony.

Wchodzimy w nowo utworzony folder i uruchamiamy `Ventoy2Disk.exe`. W liście `Device` wybieramy naszego pendrive'a.

{: .info }
Jeżeli będziemy instalować to na nowoczesnym komputerze, zalecane jest zaznaczyć: `Option -> Partition Style -> GPT`. (*insert ChatGPT joke here*)

{: .warning }
Następny krok spowoduje usunięcie plików z pendrive'a **nieodwracalnie**. Upewnij się, że masz kopię zapasową plików które chcesz zachować.

Pozostało nacisnąć `Install`, potwierdzić ~~sprzedaż duszy~~ 2 razy i patrzeć jak wszystko dzieje się za nas.

Po chwili wszystko powinno być gotowe! Sprawdź czy widzisz nowy dysk o nazwie `Ventoy` w eksploratorze plików.

Tak? No to [pora na system(y)!](windows)
