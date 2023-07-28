---
layout: default
title: Ventoy
parent: Przygotowanie
nav_order: 3
---

# Pobieranie i instalowanie Ventoy'a

A zatem wiadomomo już co, następne pytanie to

## Jak?

Pierwszo potrzebujemy czegoś, z czego uruchomimy nasz instalator. Wchodzimy więc na [stronę pobierania]("https://github.com/ventoy/Ventoy/releases") i w zależności od systemu sprawnego komputera pobieramy:

- Windows: `ventoy-*losowe numberki*-windows.zip`
- Linux: `ventoy-*losowe numberki*-linux.tar.gz`
- Pozostałe: `ventoy-*losowe numberki*-livecd.iso`

{: .info }
W tej wersji poradnika (nie znaczy to, że będą inne, ale to też nie jest wykluczone) założę, że użwać będziemy Windowsa.

Pobrany plik wypakowywujemy (prawy przycisk myszy -> wypakuj/exctract). Upewnij się, że pliki zostały wypakowywane do oddzielnego folderu (np. ventoy-1.0.94-windows), a nie bezpośrednio w folderze pobranych.

Upewniamy się, że pendrive jest podłączony.

Wchodzimy w nowo utworzony folder i uruchamiamy `Ventoy2Disk.exe`. W liście `Device` wybieramy naszego pendrive'a.

{: .warning }
Następny krok spowoduje usunięcie plików z pendrive'a **nieodwracalnie**. Upewnij się, że masz kopię zapasową plików które chcesz zachować.

Pozostało nacisnąć `Install`, potwierdzić ~~sprzedaż duszy~~ 2 razy i patrzeć jak wszystko dzieje się za nas.

Gotowe! Powinniśmy teraz widzieć nowy dysk `Ventoy`.

[Pora na system(y)](windows)