

**1. S1 - Wybierz produkt**

**S1.1. Opis**

Funkcja umożliwia przegląd aktualnych produktów. Po podjęciu decyzji o kupnie

towaru, klient dodaje wybrany produkt do koszyka i składa zamówienie.

**S1.2. Aktorzy**

Klient.

**S1.3 Przepływ zdarzeń**

**S1.3-1** System umożliwia przegląd aktualnej oferty sklepu, udostępnionej w

postaci listy towarów (nazwa, zdjęcie, cena, opis).

**S1.3-2** Klient przegląda listę towarów.

**S1.3-3** Po kliknięciu nazwy produktu z listy Klient ma możliwośc zapoznania się z

jego opisem.

**S1.3-4** Gdy klient chce kupic wybrany produkt, musi kliknąc na opcję Dodaj do

koszyka .

**S1.4 Przepływy alternatywne**

Brak.

**S1.5 Warunki początkowe**

W systemie utrwalone są dane o cenach towarów – z chwili uruchomienia

systemu. Koszyk jest pusty.

**S1.6 Warunki końcowe**

W koszyku znajduje się wybrany produkt.

**2. S2 - Aktualizacja danych produktu**

**S2.1 Opis**

W panelu towarów Administrator zmienia dane o produktach (zdjęcie, cena,

nazwa, opis).

**S2.2 Aktorzy**

Administrator.

**S2.3 Przepływ zdarzeń**

**S2.3-1** Administrator zmienia dane produktu.

**S2.3-2** Administrator akceptuje zmiany.

**S2.3-3** System zapisuje zmiany.





**S2.4 Przepływy alternatywne**

**PA2-2** Administrator odrzuca zmiany.

**PA2-3** System anuluje wprowadzone zmiany.

**S2.5 Warunki początkowe**

W systemie utrwalone są dane o produktach.

**S2.6 Warnki końcowe**

W systemie są dane o produktach zostały aktualizowane.

**3. S3 - Zarządzanie koszykiem**

**S3.1 Opis**

Klient ma możliwośc przeglądania kwoty łącznej do zapłaty, usuwania produktów,

zmiany liczby zakupionych produktów.

**S3.2 Aktorzy**

Klient.

**S3.3 Przepływ zdarzeń**

**S3.3-1** Klient wybiera opcję Koszyk zakupów.

**S3.3-2** System wyświetla listę uprzednio wybranych produktow.

**S3.3-3** Klient wybiera opcję *Złoż zam*ówienie .

**S3.4 Przepływy alternatywne**

**PA3-2** System wyświetla informację Brak produktów w koszyku zakupów.

**PA3-3a** Klient zmienia liczbę wybranych produktów poprzez kliknięcie na

przyciskach *zmniejsz oraz zwiększ* liczbę produktów.

**PA3-3b** Klient wybiera opcję usunięcia produktu.

**PA3-3c** System aktualizuje listę produktów oraz wartośc całego zamówienia.

**S3.5 Warunki początkowe**

Musi byc wybrany co najmniej jeden produkt.

**S3.6 Warunki końcowe**

Przejście do składania zamówienia.

