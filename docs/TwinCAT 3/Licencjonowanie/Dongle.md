---
title: Dongle
parent: Licencjonowanie
nav_order: 2
layout: page
---


# Licencjonowanie Dongle

Niniejsza instrukcja opisuje sposób samodzielnego aktywowania licencji na urządzeniu licencyjnym takim jak EL6070 lub klucz USB C9900-L100.

Instrukcja nie opisuje przypadku wgrywania licencji bezpośrednio na sterownik.

## Protokół odbioru

Na początku warto sprawdzić zakupione licencje. Do realizacji procesu licencjonowania będzie potrzebny numer „BADE-IN” (wpisujemy tylko znaki zaznaczone na zielono). Znajdziemy je na Fakturze VAT lub na Potwierdzeniu zamówienia.

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/1d917be7-0304-400f-84cf-11c6403938ec)


TCxxxx-xx**40** – **40** oznacza platformę sprzętową.

## TwinCAT

Po podłączeniu sterownika skanujemy moduły w poszukiwaniu EL6070 (EtherCAT) lub C9900-L100 (USB).

W przypadku C9900-L100 przy pierwszym skanowaniu potwierdzamy generowanie unikalnego ID modułu.

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/65c0e270-d86f-4e14-9a43-921e379a2e14)

Następnie w drzewie projektu klikamy PPM na License i dodajemy nowe urządzenie.

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/a3d8922e-49ce-4e1c-a282-6a497549a0ca)

Pojawi nam się nowa zakładka o nazwie Dongle 1, otwieramy ją i wybieramy wczytany moduł EL6070 lub C9900-L100:

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/81ffe3f4-c020-4761-a8ed-66aa89c434cb)

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/4b9ddc08-6621-4145-9dae-4bded45620f5)

Jeśli moduł nie posiada w sobie jeszcze żadnych licencji, to przy pytaniu o aktywację wybieramy *Nie*:

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/369a646c-02a1-41fc-9044-d325b84076b7)

Jeśli klucz i id się zgadza zobaczymy status *Valid* (może być konieczne wciśnięcie przycisku *Reload Info*):

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/de689eb0-9c26-4498-b0f4-2179186137fd)

Zaznaczamy opcję *Update license cache using dongle content on startup*.

W zakładce *License / Manage Licenses* zaznaczamy *Disable automatic detection of required licenses for project* oraz wybieramy licencje zgodne z zamówieniem (tylko te, które są na zamówieniu).

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/7ffb5261-c446-4091-a818-3d3b4ade6154)

Następnie w zakładce *Order information (Runtime)* dopasowujemy licencję do urządzenia docelowego (w tym przypadku Dongle) 

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/bf478e20-cb8d-410b-bc28-b6748104bebd)


Wybieramy urządzenie główne, dla którego generowana będzie licencja:

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/076560d1-8510-496f-8091-e24454b728c3)

Niewybrane licencje będą wyszarzone, nie biorą one udziału w dalszej części procesu:

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/a9e9bfbc-a28d-450a-93fa-a3627c96f18d)

Następnie wpisujemy numer zamówienia (tylko cyfry z numeru BADE-IN) oraz wybieramy platformę zgodną z zamówieniem.

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/7d2a314d-88c4-457b-850e-be73e5a42957)

Docelowa platforma zdefiniowana jest w nazwie licencji na zamówieniu np. TC1000-00**40**

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/43525c82-a101-447d-a62d-a5d61fea78d6)

Wybieramy *Generate File* i zapisujemy plik w dowolnym miejscu na komputerze.

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/11c5e323-be39-42df-91f3-5911feceef5a)


Jeżeli mamy skonfigurowaną pocztę to możemy automatycznie utworzyć maila wybierając:

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/40fd062b-ec3f-4c56-b096-ad1221f5b7e5)

Wygenerowany przez nas plik wysyłamy w załączniku na adres **tclicense@beckhoff.com**. Zapytanie jest automatycznie przetwarzane przez serwer. Treść maila nie ma znaczenia.  

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/08a1957f-8da1-4d22-84e8-4361374eeca3)

Odpowiedź powinna pojawić się w ciągu kilku minut.

W odpowiedzi otrzymamy plik rejestracyjny – zapisujemy go chwilowo w dowolnym miejscu na swoim komputerze.

W opisie widzimy nazwy wszystkich licencji w pakiecie.

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/74576fe2-e246-40c0-b2b5-5846fd122564)

W zakładce **Dongle 1 / License Device** wybieramy **Store License on Dongle**:

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/04e14882-4f51-49eb-b1dc-4cc965c631af)

Dodajemy otrzymany plik rejestracyjny:

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/1c0cc080-2bf4-4422-984d-3cc0e5162fc3)

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/04c3a425-842b-46b3-aced-c90a1a4c05f1)

Po prawidłowym wgraniu pliku dostaniemy komunikat z aktualną liczbą plików przechowywanych w module.

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/e50e71c4-894c-47a6-be35-2f344f9d0d27)

Aby wgrać licencję z modułu do pamięci sterownika wybieramy Cache Dongle Licenses.

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/c1bf3daa-1468-4b17-b8e4-c2c9cc603185)

Wygenerowany plik zostanie umieszczony na sterowniku w folderze C:\TwinCAT\3.1\Target\License

Aktywujemy konfigurację TwinCATa:

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/9dea9360-7c1c-4cda-a18e-e10a7cdbe3e4)

Licencje są już aktywne:

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/795b434a-0d94-49d8-9969-151f1ed998d0)











