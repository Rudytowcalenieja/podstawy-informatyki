# Typy topologii sieci

## Topologia magistrali
Topologia magistrali (ang. bus topology) to rodzaj topologii sieci komputerowej, w której wszystkie urządzenia są podłączone do jednego wspólnego medium transmisyjnego, zwanego magistralą. Dane przesyłane są wzdłuż magistrali i mogą być odbierane przez każde urządzenie podłączone do sieci.
<br>
Głównie stosowana w przypadku prostego ich rozmieszczenia – niewielkie biura lub sale wykładowe
<br>

### Zalety:
- **Małe użycie kabla**
- **Brak dodatkowych urządzeń**
- **Prostota konfiguracji**
- **Niska cena sieci**
- **odporność na uszkodzenia mechaniczne i zakłócenia elektromagnetyczne**

### Wady:
- **Lokalizacja usterek jest trudna**
- **Tylko jedna możliwa transmisja w danym momencie**
- **Potencjalnie duża liczba kolizji**
- **Awaria głównego kabla powoduje unieruchomienie całej domeny kolizyjnej**
- **Słaba skalowalność**
- **Słabe bezpieczeństwo**

## Topologia gwiazdy
Topologia gwiazdy (ang. star topology) to rodzaj topologii sieci komputerowej, w której wszystkie urządzenia są podłączone do centralnego punktu, którym zazwyczaj jest przełącznik lub koncentrator. Dane przesyłane są z jednego urządzenia do centralnego punktu, a następnie do urządzenia docelowego.
<br>
Stosowama w średnich i dużych sieciach lokalnych, w których pracuje wiele urządzeń (serwerów, komputerów, drukarek)
<br>

### Zalety:
- **Wysoka przepustowość**
- **Wydajność**
- **Łatwa lokalizacja uszkodzeń ze względu na centralne sterowanie**
- **Łatwa rozbudowa**
- **Awaria komputera peryferyjnego (terminala) nie blokuje sieci**
- **Przejrzystość sieci**

### Wady:
- **Ograniczona liczba komputerów**
- **Duża liczba połączeń (duże zużycie kabli)**
- **Gdy awarii ulegnie punkt centralny (koncentrator lub przełącznik), to cała sieć przestaje funkcjonować**

## Topologia pierścienia
Topologia pierścienia (ang. ring topology) to rodzaj topologii sieci komputerowej, w której każde urządzenie jest podłączone do dwóch innych urządzeń, tworząc zamknięty krąg. Dane przesyłane są w jednym kierunku, przechodząc przez każde urządzenie po drodze do celu.
<br>
Topologia pierścienia jest stosowana w sieciach komputerowych, gdzie każde urządzenie jest połączone z dwoma sąsiednimi urządzeniami, tworząc zamknięty pierścień
<br>

### Zalety:
- **Małe zużycie przewodów**
- **Możliwość zastosowania łącz optoelektronicznych, które wymagają bezpośredniego nadawania i odbierania transmitowanych sygnałów**

### Wady:
- **Złożona diagnostyka sieci**
- **Trudna lokalizacja uszkodzenia**
- **Pracochłonna rekonfiguracja sieci**
- **Wymagane specjalne procedury transmisyjne**
- **Dołączenie nowych stacji jest utrudnione, jeśli w pierścieniu jest wiele stacji**
- **Sygnał krąży tylko w jednym kierunku**

## Topologia Punkt - Punkt
W tej topologii przesył danych odbywa się tylko pomiędzy dwoma urządzeniami w sieci, które mogą być do siebie podłączone bezpośrednio, jak również z wykorzystaniem urządzeń pośredniczących.
Topologia ta jest stosowana do łączenia dwóch urządzeń ze sobą np. komputer - drukarka

## Topologia Przekazywania Żetonu
Dane przekazywane są kolejno do urządzeń połączonych w sieć. Urządzenie, które otrzyma porcję danych, analizuje, czy są one adresowane do niego, czy też nie. Jeśli nie - przekazuje je dalej, do sąsiedniego urządzenia.
Zapobiega wzajemnemu zakłócaniu się przesyłanych wiadomości i gwarantuje, że w danej chwili tylko jedna stacja może nadawać dane

## Topologia Wielodostępowa
W tej topologii przesył danych odbywa się poprzez jedno medium transmisyjne (np. kabel koncentryczny), które współdzielone jest przez wiele urządzeń. Urządzenie transmitujące dane wysyła je do wszystkich.
W sieciach o fizycznej topologii magistrali stosuje się logiczną topologię wielodostępową