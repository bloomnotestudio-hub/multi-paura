# Paura Multi-Store

**Paura Multi-Store** to lokalna aplikacja desktopowa do zarządzania sprzedażą i obsługą zamówień na platformie Allegro.

Aplikacja została opracowana nieodpłatnie na potrzeby wewnętrznej obsługi trzech kont Allegro należących do firmy członka rodziny. Nie jest oferowana jako usługa komercyjna. Aplikacja umożliwia obsługę trzech kont sprzedawców Allegro w jednym interfejsie.

## Główne funkcjonalności

- **Integracja z Allegro REST API** — bezpieczna autoryzacja OAuth 2.0 i synchronizacja zamówień.
- **Obsługa wielu kont** — niezależna synchronizacja zamówień i przesyłek dla każdego konta Allegro.
- **Wysyłam z Allegro (WzA)** — tworzenie przesyłek, monitorowanie ich statusów oraz pobieranie i drukowanie etykiet.
- **Faktury i korekty** — wystawianie dokumentów sprzedaży, wspólna numeracja oraz obsługa faktur korygujących.
- **Integracja z KSeF 2.0** — obsługa faktur ustrukturyzowanych, statusów dokumentów oraz UPO.
- **Archiwizacja danych** — lokalne przechowywanie danych i tworzenie kopii zapasowych.

## Integracja z Allegro

Aplikacja wykorzystuje oficjalne Allegro REST API i autoryzację OAuth 2.0.

Dostęp do danych odbywa się wyłącznie po autoryzacji przez właściciela odpowiedniego konta Allegro.

Obsługiwane są środowiska Allegro Sandbox oraz Production.

## Informacje techniczne

- Platforma: Windows
- Charakter aplikacji: lokalna, do użytku wewnętrznego
- Integracje: Allegro REST API, Wysyłam z Allegro, KSeF 2.0
- Dostępność: aplikacja prywatna, nieudostępniana jako usługa publiczna

## Bezpieczeństwo

Dane uwierzytelniające i informacje dotyczące zamówień są przetwarzane lokalnie. Aplikacja korzysta z mechanizmów autoryzacji oraz kontroli dostępu oferowanych przez zintegrowane systemy.

---

**Paura Multi-Store** — prywatne narzędzie do zarządzania sprzedażą na Allegro.
