# TestingTraining (Polish)
[![GitHub issues](https://img.shields.io/github/issues/przemastro/testing-training-polish)](https://github.com/przemastro/testing-training-polish/issues)
[![GitHub forks](https://img.shields.io/github/forks/przemastro/testing-training-polish)](https://github.com/przemastro/testing-training-polish/network)
[![GitHub stars](https://img.shields.io/github/stars/przemastro/testing-training-polish)](https://github.com/przemastro/testing-training-polish/stargazers)
[![Python version](https://img.shields.io/badge/Python-2.7.x-%233572A5)](https://github.com/przemastro/testing-training-polish)
[![npm version](https://img.shields.io/badge/npm-5.0.x-%233572A5)](https://github.com/przemastro/testing-training-polish)
[![TSQL version](https://img.shields.io/badge/TSQL-2012-%23ccc)](https://github.com/przemastro/testing-training-polish)
[![Java version](https://img.shields.io/badge/Java-1.8-%23b07219)](https://github.com/przemastro/testing-training-polish)

# Intro

Słowa kluczowe i technologie: Baza Relacyjna, SQL, T-SQL, SQL Server, Management Studio, podbc, Python, Flask, Funkcja, Metoda, Klasa, Obiekt, AngularJS, Bootstrap, HTML, CSS, Intellij, Selenium Webdriver, Maven, RestAssured, SoapUI, TestNG, Header, Endpoint, HTTP, Tomcat, Jenkins, Serwer Aplikacyjny, Continuous Integration, Git, Json, Java, NodeJS, Adnotacja, Klucz Główny i Klucz Obcy, Routing, Kontrolka, Port, npm, Bower, xml, COR request

Wszystkie definicje znajdują się w pliku https://github.com/przemastro/testing-glossary-polish/blob/master/zagadnienia.txt.docx

Naszym zadaniem będzie napisanie prostej aplikacji - serwisu restowego z bazą danych i UI oraz przetestowanie jej na 3 poziomach Baza, API i UI. Dodatkowym zadaniem będzie postawienie aplikacji na serwerze aplikacyjnym, umieszczenie kodu w zdalnym repozytorium oraz stworzenie builda w narzędziu CI do odpalania testów automatycznych.

1. Założenia Szkolenia

Uczestnik szkolenia dowie się jak wygląda i działa współczesna aplikacja webowa. Jaki jest przepływ danych i w jaki sposób odbywa się komunikacja pomiędzy modułami. Nauczy się testować poszczególne moduły. Nauczy się także technicznej nomenklatury, jak zarządzać kodem, jak budować automatycznie aplikację.


2. Baza Danych

| Zadanie        | Przykład (Plik)    | Liczba godzin  |
| ------------- |:-------------:| -----:|
| Zainstalowanie lokalnie MSSQL, zbudowanie bazy danych, stworzenie tabel, widoków i procedur składowanych | Baza Danych - Dev | 10 |
| Przygotowanie danych testowych. Zaprojektowanie testów weryfikujących jakość i ilość przeprocesowanych danych | Baza Danych - Test | 6 |


3. Web API

| Zadanie        | Przykład (Plik)    | Liczba godzin  |
| ------------- |:-------------:| -----:|
| Zbudowanie i postawienie lokalnego API we frameworku FLASK używając języka Python | Web API - Dev | 6 |
| Wystawienie usług (“endpointów”) dla frontendu z metodami GET i POST, spięcie backendu z bazą | Web API - Dev | 10 |
| Zaprojektowanie testów API wykorzystując jeden z dedykowanych narzędzi np. SOAPUI | Web API - Test | 10 |
| Wykorzystanie frameworka RestAssured do testów Restowego API | UI-REST-test.7z | 10 |


4. User Interface UI

| Zadanie        | Przykład (Plik)    | Liczba godzin  |
| ------------- |:-------------:| -----:|
| Zaprojektowanie interfejsu użytkownika w HTML, CSS i Bootstrap | Web UI - Dev | 6 |
| Zaprojektowanie klienta usług API w Angularjs i spięcie go z backendem | Web API - Dev | 10 |
| Wystawienie frontendu na lokalnym serwerze aplikacyjnym np. Tomcat | DevOps | 4 |
| Zaprojektowanie testów UI | Web UI - Test | 6 |
| Stworzenie prostego frameworka do testów automatycznych UI przy użyciu Java/TestNG/Selenium | UI-REST-test.7z | 10 |


5. GIT i CI

| Zadanie        | Przykład (Plik)    | Liczba godzin  |
| ------------- |:-------------:| -----:|
| Stworzenie własnego zdalnego repozytorium np. GIT i wypuszczenie zmian z lokalnego repozytorium. Podział kodu na branche | DevOps | 4 |
| Postawienie lokalnie narzędzia CI np. Jenkins i spięcie go ze zdalnym repozytorium | DevOps | 4 |
| Stworzenie builda do automatycznego odpalania testów automatycznych | DevOps | 4 |


Suma godzin: 100






