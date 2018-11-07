# DICOM

**D**igital **I**maging and **CO**mmunications in **M**edicine

DICOM jest standardem wymiany i zarządzania danymi obrazowania medycznego oraz powiązanymi. Standard pozwala na integrację pomiędzy urządzeniami diagnostyki obrazowej (modalnościami), systemami archiwizacji (PACS), przeglądarkami obrazów jak i każdym innym oprogramowaniem realizującym standard.

Standard składa się z dwóch głównych części: pliku oraz protokołu sieciowego.

Plik DICOM to format zapisu danych obrazowania medycznego. Oprócz obrazu medycznego zawiera on także informacje o pacjencie (imię, nazwisko, id, płeć, data urodzenia, etc.), dane akwizycji (typ urządzenia i jego ustawienia), a także kontekst badania w jakim obraz został wytworzony.

Protokół sieciowy DICOM pozwala na wykonywanie zapytań o dane obrazowania medycznego (oraz powiązne) oraz realizuje żadania wysyłki tych danych.

Za sukcesem standardu stoi przede wszystkim umożliwienie zewnętrznym dostawcom oprogramowania integracji ze wszystkimi składowymi działającego systemu szpitalnego. Tak jak podłączając drukarkę do komputera spodziewamy się możliwości skorzystania z jej funkcjonalności w stosunkowo krótkim czasie tak realizacja standardu pozwala na uzyskanie rozsądnego czasu, po którym możliwe jest korzystanie z nowo zakupionego oprogramowania.

# PACS

**P**icture **A**rchiving and **C**ommunication **S**ystem

System składowania danych obrazowania medycznego i powiązanych. Pozwala na przechowanie danych pochodzących z różnych modalności i zapewnia szybki dostęp do tych danych.

# RIS

**R**adiological **I**nformation **S**ystem

System zarządzania dla pracowni diagnostyki obrazowej. Do jego głównych funkcjonalności należy ustalanie kalendarza badań, 

# Interakcja

1.  Pacjent pojawia się w rejestracji
2.  Data badania jest wyznacza dla pacjenta w systemie RIS
3.  Pacjent pojawia się w rejestracji zgodnie z wyznaczoną datą badania
4.  System RIS zakłada zlecenie wykonania badania dla pacjenta w systemie PACS (worklista)
5.  Pacjent udaje się do pracowni diagnostyki obrazowej
6.  Technik wyszukuje pacjenta na worklist systemu PACS
7.  Technik przeprowadza badanie
8.  Przeprowadzone badanie jest utrwalne w pamięci modalności
9.  Kopia badania skojarzona z pacjentem jest wysyłana do systemu PACS
10.


is the core system for the electronic management of imaging departments. The major functions of the RIS can include patient scheduling, resource management, examination performance tracking, examination interpretation, results distribution, and procedure billing.[2] RIS complements HIS (hospital information systems) and PACS (picture archiving and communication system), and is critical to efficient workflow to radiology practices.

Tak jak każda przeglądarka internetowa jest w stanie wyświetlić dla użytkownika plik obrazowy przechowywany na serwerze, tak samo 
## Core

DICOM comprises of two main parts - file format and network protocol.

DICOM file format 


DICOM file format 
