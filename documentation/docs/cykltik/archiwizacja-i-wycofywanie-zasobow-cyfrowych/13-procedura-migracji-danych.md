---
id: 13-procedura-migracji-danych
title: Załącznik 4. Migracja danych i wycofywanie systemów teleinformatycznych
description: Normatywne wymagania dla migracji danych, zachowania dostępności i udokumentowanego wycofania systemu teleinformatycznego.
sidebar_label: Zał. 4 Migracja i systemy
sidebar_position: 13
keywords: [migracja danych, wycofanie systemu, dostępność, integralność, metadane]
tags: [cykl-zycia-tik, załącznik]
opracowanie: Bartłomiej Wilk
data_zgloszenia: 29 kwietnia 2026 r.
data_aktualizacji: 11 maja 2026 r.
wersja_robocza: true
---

# Załącznik 4. Migracja danych i wycofywanie systemów teleinformatycznych

## Zakres załącznika

Załącznik określa minimalne wymagania dla migracji danych i wycofywania systemów teleinformatycznych. Łączy treści z wcześniejszych materiałów dotyczących procedury migracji danych, wymagań dla systemów, kryteriów wycofania systemu i dokumentowania procesu wycofania.

## Zasada podstawowa

Migracja i wycofanie systemu nie mogą prowadzić do utraty danych, dokumentów, metadanych, relacji, kontekstu, integralności ani dostępności cyfrowej. System źródłowy powinien pozostać dostępny albo zabezpieczony do czasu potwierdzenia, że dane zostały przeniesione, zarchiwizowane albo opisane w sposób umożliwiający ich dalsze użycie.

## Minimalne wymagania dla migracji

Migracja powinna obejmować:

- inwentaryzację danych, dokumentów, załączników, multimediów, rekordów, statusów i metadanych;
- wskazanie właściciela danych, właściciela systemu i osób odpowiedzialnych za odbiór;
- decyzję, które zasoby są migrowane, archiwizowane, pozostawione tylko do odczytu albo przeznaczone do brakowania;
- mapowanie pól, identyfikatorów, statusów, dat, wersji, relacji i uprawnień;
- przeniesienie informacji o publikacji, archiwizacji, dostępności i ograniczeniach dostępu;
- zachowanie oryginału albo kopii kontrolnej do czasu odbioru;
- test kompletności, odczytu, wyszukiwania, integralności i dostępności;
- protokół migracji i decyzję o dalszym losie systemu źródłowego.

## Zachowanie dostępności po migracji

Migracja powinna chronić dostępność treści, dokumentów i formularzy. Należy przenieść albo odtworzyć elementy, które pozwalają użytkownikom korzystać z informacji: strukturę stron, nagłówki, etykiety, teksty alternatywne, transkrypcje, napisy, opisy linków, język dokumentu, kolejność czytania, metadane dostępności i informacje o dostępie alternatywnym.

Testy migracji powinny obejmować zasoby aktywne i archiwalne. Próbka testowa powinna zawierać zasoby typowe oraz trudne: stare pliki PDF, skany, multimedia, formularze, załączniki BIP, strony projektów i rekordy powiązane z dokumentacją sprawy.

## Minimalne wymagania dla systemów

System wykorzystywany do publikacji, przechowywania albo obsługi zasobów cyfrowych powinien umożliwiać co najmniej:

- przypisanie właściciela, statusu, dat i podstawowych metadanych;
- oznaczanie treści archiwalnych i wycofanych;
- eksport danych, dokumentów, załączników i metadanych w udokumentowanym formacie;
- zachowanie historii publikacji albo informacji o wersji;
- kontrolę uprawnień i ograniczeń dostępu;
- zachowanie informacji o dostępności i dostępie alternatywnym;
- przygotowanie danych do migracji albo archiwizacji;
- udokumentowane wyłączenie po zakończeniu procesu.

Brak tych funkcji powinien być traktowany jako ryzyko przy utrzymaniu albo zamówieniu systemu.

## Kryteria wycofania systemu

System może zostać wycofany, gdy:

- ustalono pełny zakres danych, dokumentów, metadanych, załączników, logów i integracji;
- określono, które zasoby wymagają dalszego dostępu publicznego, dostępu na wniosek albo ograniczenia;
- wykonano migrację albo archiwizację zasobów wymagających zachowania;
- potwierdzono dostępność i odczyt zasobów po migracji;
- udokumentowano dane niemigrowane oraz podstawę ich dalszego przechowywania albo brakowania;
- ustalono sposób obsługi użytkowników po wyłączeniu systemu;
- kierownictwo albo właściciel systemu zatwierdził zamknięcie.

## Ryzyka wymagające kontroli

Najważniejsze ryzyka to utrata metadanych, utrata relacji między rekordem a załącznikiem, utrata podpisów albo historii wersji, zmiana znaczenia danych po konwersji, utrata dostępności dokumentów, brak przekierowań, niepełny eksport, brak testu odtworzenia, nieuprawnione ujawnienie danych i brak możliwości wykazania, co stało się z danymi po wyłączeniu systemu.

## Dokumentowanie procesu

Dokumentacja migracji i wycofania systemu powinna zawierać zakres, podstawę decyzji, osoby odpowiedzialne, wyniki testów, wykaz błędów, działania naprawcze, decyzję o danych niemigrowanych, potwierdzenie dostępności zasobów publicznych i datę zakończenia procesu.

## Powiązane materiały pomocnicze

Szczegółowe rozwinięcia znajdują się w materiałach: [Wymagania dla systemów](./24-wymagania-dla-systemow.md), [Kryteria wycofania systemu](./25-kryteria-wycofania-systemu.md), [Dokumentowanie procesu wycofania](./26-dokumentowanie-procesu-wycofania.md), [Lista kontrolna wycofania systemu](./37-lista-kontrolna-wycofania-systemu.md), [Rejestr wycofania systemów](./41-rejestr-wycofania-systemow.md) i [Schemat procesu wycofania systemu](./45-schemat-procesu-wycofania-systemu.md).


