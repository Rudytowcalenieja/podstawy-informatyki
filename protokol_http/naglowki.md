# Nagłówki Żądania

- **Accept:**
    \*/\* <br>
    Definiuje typy mediów, które klient może zaakceptować od serwera
- **Accept-Encoding:**
	gzip, deflate, br
    Określa kodowanie, za pomocą którego zostanie przesłana zawartość
- **Accept-Language:**
	pl,en-US;q=0.7,en;q=0.3 <br>
    Wskazuje język naturalny i ustawienia regionalne preferowane przez klienta
- **Connection:**
	keep-alive <br>
    Pozwala na obsługę wszystkich zasobów strony internetowej przez jedno połączenie
- **Host:**
	httpbin.org <br>
    Obowiązkowe pole nagłówka, które zawiera informacje dotyczące hosta internetowego i numeru portu zasobu, z którego zażądano danych
- **Origin:**
	null <br>
    Zapewnienia kontekstu bezpieczeństwa dla żądania origin, z wyjątkiem przypadków, gdy informacje o originie byłyby poufne lub niepotrzebne
- **TE:**
	Trailers <br>
    Używany w protokole HTTP, aby określić, jakie kodowania transferu (np. kompresje lub inne mechanizmy przekształcania danych) klient jest w stanie zaakceptować w odpowiedzi od serwera
- **User-Agent:**
	Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:84.0) Gecko/20100101 Firefox/84.0 <br>
    Nagłówek identyfikujący, wysyłany protokołem HTTP przez program (np. przeglądarkę internetową lub bota) w celu wykonania połączenia z serwerem WWW

# Nagłówki Odpowiedzi

- **access-control-allow-credential:**
	true <br>
    Informuje przeglądarkę, że serwer zezwala na poświadczenia dla żądania między źródłami
- **access-control-allow-origin:**
	null <br>
    Udostępnia domenę witryny wysyłającej żądanie
- **content-length:**
	440 <br>
    Określa długość w bajtach przesyłanej zawartości
- **content-type:**
	application/json <br>
    Wskazuje, w którym formacie dane są wysyłane do metod HTTP interfejsu API usług REST serwera Rule Execution Server lub zwracane przez te metody
- **date:**
	Wed, 19 Mar 2025 13:21:11 GMT <br>
    Wyświetla datę i czas, kiedy serwer wygenerował odpowiedź
- **server:**
	gunicorn/19.9.0 <br>
    Informuje o oprogramowaniu serwera HTTP, w tym o wersji PHP, które obsługuje żądanie
- **X-Firefox-Spdy:**
	h2 <br>
    Wskazuje, że przeglądarka Firefox używa protokołu SPDY lub HTTP/2 do komunikacji z serwerem