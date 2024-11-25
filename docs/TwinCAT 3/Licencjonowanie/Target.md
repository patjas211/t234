---
title: Target
parent: Licencjonowanie
nav_order: 1
layout: page
---

# Licencjonowanie Target 

Niniejsza  instrukcja  opisuje  sposób  samodzielnego  aktywowania licencji bezpośrednio na sterowniku.

Instrukcja  nie  opisuje  przypadku  wgrywania  licencji  na  moduł EL6070 lub klucz USB C9900-L100.

## Protokół odbioru

Na początku warto sprawdzić zakupione licencje. Do realizacji procesu licencjonowania będzie potrzebny numer „BADE-IN” (wpisujemy tylko znaki zaznaczone na zielono). Znajdziemy je na Fakturze VAT lub na Potwierdzeniu zamówienia.

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/03686114-9b65-4247-8163-20b10967f38d)


TCxxxx-xx**40** – **40** oznacza platformę sprzętową.

## TwinCAT

Mając protokół odbioru, otwieramy Solution i nawiązujemy połączenie ze sterownikiem, na który chcemy wgrać licencje. Następnie otwieramy zakładkę licencyjną.

W zakładce *License / Manage Licenses* zaznaczamy *Disable automatic detection of required licenses for project* oraz wybieramy licencje zgodne z zamówieniem (tylko te, które są na zamówieniu).

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/7ffb5261-c446-4091-a818-3d3b4ade6154)

Następnie w zakładce *Order information (Runtime)* dopasowujemy licencję do urządzenia docelowego (dla sterownika – Target ) 

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/dba2d51e-b05c-4f4a-aad3-66a8723300dd)

Następnie wpisujemy numer zamówienia (tylko cyfry z numeru BADE-IN) oraz wybieramy platformę zgodną z zamówieniem (powinna zostać rozpoznana automatycznie).

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/731d0988-ae64-4a1a-8709-87099591f348)


Docelowa platforma zdefiniowana jest w nazwie licencji na zamówieniu np. TC1000-00**40**

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/75ca9ddb-e8fd-4460-a19c-ac2e3da31c70)


Wybieramy *Generate File* i zapisujemy plik w dowolnym miejscu na komputerze.

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/456e6db1-b5a4-4c74-b2d3-190151feb70b)


Jeżeli mamy skonfigurowaną pocztę to możemy automatycznie utworzyć maila wybierając:

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/40fd062b-ec3f-4c56-b096-ad1221f5b7e5)

Wygenerowany przez nas plik wysyłamy w załączniku na adres **tclicense@beckhoff.com**. Zapytanie jest automatycznie przetwarzane przez serwer. Treść maila nie ma znaczenia.  

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/08a1957f-8da1-4d22-84e8-4361374eeca3)

Odpowiedź powinna pojawić się w ciągu kilku minut.

W odpowiedzi otrzymamy plik rejestracyjny – zapisujemy go chwilowo w dowolnym miejscu na swoim komputerze.

W opisie widzimy nazwy wszystkich licencji w pakiecie.

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/74576fe2-e246-40c0-b2b5-5846fd122564)

Dodajemy otrzymany plik rejestracyjny przyciskiem License Response File:

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/79e46287-9bc0-4034-9dab-f6a38a79ab0b)

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/69451a24-bd5e-4d2c-88a3-9df1911ee9ff)

Aktywujemy konfigurację TwinCATa:

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/9dea9360-7c1c-4cda-a18e-e10a7cdbe3e4)

Licencje są już aktywne:

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/f364b055-d7c5-4c9e-931e-4da83f45fa69)










