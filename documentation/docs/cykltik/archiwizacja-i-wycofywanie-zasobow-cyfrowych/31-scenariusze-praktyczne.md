---
id: 31-scenariusze-praktyczne
title: Scenariusze praktyczne
description: Przykładowe scenariusze stosowania procedury archiwizacji i wycofywania zasobów cyfrowych.
sidebar_label: Scenariusze
sidebar_position: 31
keywords: [scenariusze, BIP, PDF, nagranie, CMS, aplikacja, dane osobowe]
tags: [cykl-zycia-tik, scenariusze]
opracowanie: Bartłomiej Wilk
data_zgloszenia: 29 kwietnia 2026 r.
data_aktualizacji: 29 kwietnia 2026 r.
wersja_robocza: true
---

# Scenariusze praktyczne

## Cel

Celem dokumentu jest pokazanie, jak stosować modele i procedury w typowych sytuacjach operacyjnych. Scenariusze wskazują minimalny tok analizy, decyzję, działania wykonawcze i sposób dokumentowania.

## Zakres

Scenariusze obejmują treści BIP i WWW, multimedia, treści otrzymane od podmiotów zewnętrznych, zasoby projektowe, migrację CMS, wycofanie aplikacji oraz dokumenty zawierające dane osobowe.

Każdy scenariusz należy stosować z uwzględnieniem [Modelu cyklu życia](./06-model-cyklu-zycia.md), [Modelu statusów zasobów](./07-model-statusow-zasobow.md), [Modelu decyzyjnego](./08-model-decyzyjny.md) i [Modelu ryzyk](./09-model-ryzyk.md).

## Zasady

Scenariusz nie zastępuje decyzji. W każdym przypadku trzeba ustalić właściciela zasobu, status, metadane, podstawę publikacji, powiązanie ze sprawą, kwalifikację archiwalną, ryzyka danych osobowych i dostępność cyfrową.

Wycofanie z publikacji nie oznacza usunięcia zasobu. Archiwizacja nie oznacza automatycznego pozostawienia zasobu publicznie. Brak technicznej wygody nie jest podstawą do pominięcia procedury.

## Szczegóły

### Stary PDF w BIP

**Sytuacja:** w BIP znajduje się stary plik PDF dotyczący rozstrzygnięcia, naboru, zamówienia albo komunikatu. Plik jest nieaktualny, ale nadal dostępny pod publicznym adresem URL.

**Analiza:** należy ustalić, czy plik jest informacją publiczną, dokumentem sprawy, treścią wymaganą przepisami BIP, dokumentacją kategorii A albo B oraz czy zawiera dane osobowe. Należy ocenić dostępność pliku i możliwość oznaczenia go jako archiwalnego.

**Decyzja:** typową decyzją jest oznaczenie jako treść archiwalna albo wycofanie z publikacji z zachowaniem dostępu na wniosek. Usunięcie bez zachowania metadanych i podstawy decyzji jest niedopuszczalne.

**Działania:** uzupełnić metadane, zapisać podstawę publikacji, nadać status, przygotować komunikat o archiwalności albo wycofać z widoku publicznego po decyzji administratora BIP i właściciela zasobu.

**Dokumentowanie:** zapisać ID, URL, nazwę, datę publikacji, powód decyzji, status po decyzji, sposób dalszego dostępu, osobę odpowiedzialną i datę.

### Nagranie bez napisów

**Sytuacja:** w serwisie znajduje się nagranie z posiedzenia, szkolenia albo konsultacji bez napisów i transkrypcji.

**Analiza:** należy ustalić znaczenie nagrania dla informacji publicznej, czas dalszej publikacji, możliwość przygotowania napisów, transkrypcji, streszczenia albo dostępu alternatywnego. Uczestniczy koordynator dostępności.

**Decyzja:** jeżeli nagranie pozostaje publiczne, należy zaplanować naprawę dostępności albo zapewnić dostęp alternatywny. Jeżeli publikacja nie jest już potrzebna, można wycofać z publikacji po archiwizacji i wskazaniu trybu uzyskania informacji.

**Działania:** zabezpieczyć oryginał, opisać zakres niedostępności, przygotować napisy albo transkrypcję, zaktualizować opis strony i metadane.

**Dokumentowanie:** zapisać ocenę dostępności, decyzję koordynatora dostępności, zakres naprawy, termin, status i sposób obsługi wniosków.

### Treść zewnętrzna

**Sytuacja:** podmiot opublikował dokument, grafikę, film albo zestaw danych otrzymany od innego podmiotu.

**Analiza:** należy ustalić źródło, prawa do publikacji, odpowiedzialność za treść, aktualność, dane osobowe, dostępność i możliwość archiwizacji. Trzeba odróżnić materiał źródłowy od kopii opublikowanej przez podmiot.

**Decyzja:** treść można utrzymać, oznaczyć jako archiwalną, zastąpić linkiem do źródła, wycofać z publikacji albo zachować jako dokumentację własnego działania.

**Działania:** uzupełnić metadane źródła, oznaczyć pochodzenie, ustalić właściciela po stronie podmiotu, zabezpieczyć kopię opublikowaną, a przy wycofaniu wskazać dalszy dostęp.

**Dokumentowanie:** zapisać źródło, datę pozyskania, podstawę publikacji, właściciela, decyzję i ograniczenia prawne albo techniczne.

### Zamknięcie projektu

**Sytuacja:** zakończył się projekt finansowany ze środków publicznych, a serwis projektu, dokumenty, załączniki i dane są nadal publiczne albo rozproszone w systemach.

**Analiza:** należy ustalić obowiązki retencji projektowej, promocyjnej, archiwalnej, informacyjnej i dostępnościowej. Trzeba wskazać, które zasoby są dokumentacją projektu, a które treścią informacyjną.

**Decyzja:** zasoby projektowe należy zarchiwizować, część publiczną oznaczyć jako archiwalną albo wycofać z publikacji po zapewnieniu dostępu na wniosek.

**Działania:** wykonać inwentaryzację, uporządkować metadane, powiązać z aktami projektu, zabezpieczyć strony i pliki, ustalić okres publicznej ekspozycji i miejsce przechowywania.

**Dokumentowanie:** zapisać wykaz zasobów, kategorie, okresy przechowywania, statusy, lokalizacje i decyzje właściciela projektu.

### Zmiana CMS

**Sytuacja:** podmiot przenosi serwis WWW albo BIP do nowego CMS.

**Analiza:** należy ustalić zakres migracji, treści nieaktualne, treści archiwalne, linki, załączniki, metadane, historię zmian, konta, przekierowania i wymagania dostępności.

**Decyzja:** treści aktywne należy migrować, treści historyczne zarchiwizować albo oznaczyć, a treści wycofywane zachować zgodnie z decyzją. Stary CMS można wyłączyć dopiero po eksporcie i teście odtworzenia.

**Działania:** przygotować mapowanie pól, eksport testowy, test odtworzenia, listę przekierowań, kopię źródłową i protokół migracji.

**Dokumentowanie:** zapisać zakres migracji, wynik testu, różnice między systemami, decyzje dla treści pominiętych i termin wyłączenia.

### Wycofanie aplikacji

**Sytuacja:** aplikacja mobilna albo webowa przestaje być utrzymywana, ponieważ kończy się umowa, wsparcie albo finansowanie.

**Analiza:** należy ustalić dane w aplikacji, konta użytkowników, logi, integracje, dokumenty, obowiązki informacyjne, kanał zastępczy i ryzyka ochrony danych.

**Decyzja:** aplikację można wycofać dopiero po migracji albo archiwizacji danych, teście odtworzenia i komunikacji do użytkowników. Jeżeli aplikacja obsługuje usługę publiczną, trzeba wskazać kanał zastępczy.

**Działania:** wykonać eksport, ograniczyć nowe dane, poinformować użytkowników, zamknąć integracje, zabezpieczyć dokumentację techniczną i odebrać dane od wykonawcy.

**Dokumentowanie:** zapisać decyzję o wycofaniu, zakres danych, wynik migracji, ryzyka resztkowe, komunikację i osobę odpowiedzialną.

### Dokument z danymi osobowymi

**Sytuacja:** opublikowany dokument zawiera dane osobowe, których dalsza publiczna ekspozycja budzi wątpliwości.

**Analiza:** należy rozróżnić obowiązek przechowywania dokumentu od zasadności dalszej publikacji. Należy ocenić podstawę prawną publikacji, minimalizację, anonimizację, dostęp na wniosek i kwalifikację archiwalną.

**Decyzja:** możliwe jest ograniczenie publicznego dostępu, anonimizacja kopii publicznej, pozostawienie dokumentu w aktach sprawy albo archiwizacja z dostępem na wniosek. RODO nie jest automatyczną podstawą zniszczenia dokumentu.

**Działania:** skonsultować IOD, zabezpieczyć oryginał, przygotować wersję zanonimizowaną albo wycofać kopię publiczną, uzupełnić metadane i status.

**Dokumentowanie:** zapisać zakres danych, podstawę decyzji, opinię IOD, sposób dalszego dostępu, wersję publiczną i miejsce przechowywania oryginału.

## Ryzyka

W scenariuszach najczęściej występują ryzyka prawne, archiwalne, dostępnościowe, technologiczne, organizacyjne i ochrony danych osobowych. Dla każdego przypadku należy wskazać ryzyka blokujące, które uniemożliwiają wycofanie albo wyłączenie systemu do czasu ich usunięcia.

## Powiązania

Scenariusze należy stosować z [Procedurą archiwizacji zasobów](./10-procedura-archiwizacji-zasobow.md), [Procedurą wycofywania treści](./11-procedura-wycofywania-tresci.md), [Procedurą wycofywania systemów](./12-procedura-wycofywania-systemow.md), [Procedurą migracji danych](./13-procedura-migracji-danych.md), [Standardem metadanych](./16-standard-metadanych.md), [Standardem formatów archiwalnych](./17-standard-formatow-archiwalnych.md), [Standardem dostępu do treści archiwalnych](./19-standard-dostepu-do-tresci-archiwalnych.md) oraz [Retencją i danymi osobowymi](./22-retencja-i-dane-osobowe.md).
