# CarServiceMateDeployment

## Dokumentacja Projektu Docker Compose dla CarServiceMate

Projekt CarServiceMate składa się z trzech głównych komponentów: API (Backend), Frontend i bazy danych MS SQL Server. Poniższa dokumentacja zawiera instrukcje dotyczące konfiguracji i uruchomienia projektu przy użyciu Docker Compose.

### Struktura Projektu

Projekt składa się z następujących komponentów:

- **CarServiceMateApi**: Backend aplikacji. Repozytorium: [CarServiceMateApi](https://github.com/sebastianpgab/CarServiceMateApi.git)
- **CarMateCustomerManagerFront**: Frontend aplikacji. Repozytorium: [CarMateCustomerManagerFront](https://github.com/sebastianpgab/CarMateCustomerManager---front.git)
- **CarServiceMateDb**: Baza danych Microsoft SQL Server.

### Wymagania

Aby uruchomić projekt, potrzebne będą:

- Docker
- Docker Compose
- Git

### Instrukcja Uruchomienia

#### Krok 1: Klonowanie Repozytoriów

Klonuj oba repozytoria do lokalnego systemu:

```sh
git clone https://github.com/sebastianpgab/CarServiceMateApi.git
git clone https://github.com/sebastianpgab/CarMateCustomerManager---front.git
```sh
#### Krok 2: Uruchomienie Docker Compose

W katalogu z plikiem docker-compose.yml, uruchom następujące polecenie, aby zbudować i uruchomić wszystkie usługi:

docker compose up

Podsumowanie
Po wykonaniu tych kroków, aplikacja frontendowa powinna być dostępna na http://localhost:3000, a API na http://localhost:4210.
