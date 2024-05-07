Projekty Laboratorium Kryptografii

Projekt 1: Szyfrowanie hybrydowe. Funkcje skrótu
1. Zagadnienie

Szyfrowanie hybrydowe. Funkcje skrótu.
2. Cel

Celem zajęć laboratoryjnych jest zapoznanie się z szyfrowaniem hybrydowym oraz funkcjami skrótu, w tym standardami SHA-2 i SHA-3.
3. Zadania do realizacji w sprawozdaniu

    Szyfrowanie hybrydowe
        Opracowanie modelu umożliwiającego uzgodnienie klucza asymetrycznego i wykorzystanie go do szyfrowania i deszyfrowania za pomocą szyfru symetrycznego.
        Wykonanie szyfrowania i deszyfrowania wiadomości utworzonej z imienia i nazwiska.
        Realizacja szyfrowania i deszyfrowania hybrydowego przy użyciu schematów AES i RSA.

    Standardowe funkcje skrótu SHA-2 i SHA-3 (Keccak)
        Opracowanie modelu wyznaczającego skrót dowolnej wiadomości funkcją skrótu SHA-2 i SHA-3.
        Porównanie skrótów wiadomości utworzonych przez modyfikację poprzedniej i pierwotnej wiadomości.

    Ataki na funkcje skrótu
        Wyznaczenie par różnych wiadomości o jednakowych skrótach dla funkcji MD5 i SHA-1.
        Znalezienie wiadomości, których pierwszy bajt skrótu jest równy 00.
        Znalezienie dwóch różnych wiadomości o tym samym pierwszym bajcie skrótu.

    Funkcja HMAC
        Opracowanie modelu funkcji skrótu z kluczem (HMAC) na bazie funkcji skrótu SHA-2 lub SHA-3.
        Wyznaczenie skrótu wiadomości utworzonej z imienia i nazwiska.

Projekt 2: Podpis cyfrowy
1. Zagadnienie

Podpis cyfrowy.
2. Cel

Celem zajęć laboratoryjnych jest zapoznanie się z podstawowymi schematami podpisu cyfrowego: RSA, ElGamal i DSA oraz ich bezpieczeństwem.
3. Zadania do realizacji w sprawozdaniu

    Podpis cyfrowy: schemat RSA
        Generowanie i weryfikacja podpisu cyfrowego schematem RSA.
        Weryfikacja podpisu dla danych z pliku.

    Podpis cyfrowy: schemat ElGamal
        Generowanie i weryfikacja podpisu cyfrowego schematem ElGamal.
        Weryfikacja podpisu dla danych z pliku.

    Podpis cyfrowy DSA
        Generowanie i weryfikacja podpisu cyfrowego algorytmem DSA.
        Weryfikacja podpisu dla danych z pliku.

Projekt 3: Szyfry blokowe
1. Zagadnienie

Szyfry blokowe.
2. Cel

Celem zajęć laboratoryjnych jest zapoznanie się z szyframi blokowymi, w tym z aktualnym standardem AES, trybami pracy szyfrów blokowych i ich własnościami.
3. Zadania do realizacji w sprawozdaniu

    Standard AES (Advanced Encryption Standard)
        Szyfrowanie i deszyfrowanie za pomocą AES w trybie ECB.
        Szyfrowanie różnych plików i analiza ich szyfrogramów.

    Metody dopełniania wiadomości
        Szyfrowanie z różnymi metodami dopełniania i ich analiza.

    Podstawowe tryby pracy i ich własności
        Szyfrowanie bloku danych algorytmem AES w różnych trybach pracy.
        Badanie wpływu zmian w tekście jawnym na szyfrogram.
        Analiza propagacji błędów transmisji.

    Inne szyfry blokowe
        Wypisanie nazw innych szyfrów blokowych dostępnych w programie CryptTool 2.1.
