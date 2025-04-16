# Grupy Statusów HTTP

HTTP statusy są podzielone na pięć grup, oznaczonych pierwszą cyfrą kodu statusu:

## 1XX - Informacyjne
Statusy z tej grupy wskazują, że żądanie zostało odebrane i jest w trakcie przetwarzania. Przykłady:
- **100 Continue**: Serwer zaakceptował początkową część żądania i klient może kontynuować.

## 2XX - Sukces
Statusy z tej grupy oznaczają, że żądanie zostało pomyślnie przetworzone. Przykłady:
- **200 OK**: Żądanie zakończyło się sukcesem.
- **201 Created**: Zasób został pomyślnie utworzony.

## 3XX - Przekierowania
Statusy te wskazują, że klient musi podjąć dodatkowe działania, aby zakończyć żądanie. Przykłady:
- **301 Moved Permanently**: Zasób został trwale przeniesiony pod inny adres.
- **302 Found**: Zasób tymczasowo znajduje się pod innym adresem.

## 4XX - Błędy klienta
Statusy te oznaczają, że problem leży po stronie klienta. Przykłady:
- **400 Bad Request**: Żądanie jest nieprawidłowe lub nie może być przetworzone.
- **404 Not Found**: Żądany zasób nie został znaleziony.

## 5XX - Błędy serwera
Statusy te wskazują, że serwer napotkał problem podczas przetwarzania żądania. Przykłady:
- **500 Internal Server Error**: Ogólny błąd serwera.
- **503 Service Unavailable**: Serwer jest chwilowo niedostępny.