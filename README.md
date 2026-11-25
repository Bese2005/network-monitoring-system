\# Network Monitoring System



\## Project Description

A Raspberry Pi-based network monitoring system that allows an administrator to monitor computers on a network.



\## Project Goals

\- Register computers using their IP addresses.

\- Check whether registered computers respond to network checks.

\- Display monitoring status.

\- Show response time and last successful check.



\## Technologies

\- Raspberry Pi

\- Python

\- Flask

\- MariaDB

\- HTML and CSS

\- Git and GitHub



\## Project Status

Currently in the planning and preparation phase.



\## Developers

VG2 Information Technology Project




# Network Monitoring System

## Hva vi har gjort så langt

### 1. Oppsett av prosjektet
- Opprettet prosjektmappen på Raspberry Pi.
- Opprettet et virtuelt Python-miljø (`venv`).
- Aktivert det virtuelle miljøet.
- Installert Flask.

### 2. Git og GitHub
- Opprettet et GitHub-repositorium.
- Koblet prosjektmappen på Raspberry Pi til GitHub.
- Opprettet `.gitignore` for å unngå å laste opp unødvendige filer.
- Opprettet README-fil for dokumentasjon.

### 3. Utvikling med Flask
- Opprettet hovedfilen `app.py`.
- Opprettet en Flask-applikasjon.
- Laget hjemmesiden med en egen rute (`/`).
- Opprettet en rute for `/about`.
- Konfigurert Flask til å kjøre på port 5001.
- Testet nettsiden fra en annen enhet på nettverket.

### 4. HTML
- Opprettet mappen `templates`.
- Opprettet filen `index.html`.
- Laget grunnleggende HTML-struktur.
- Brukt `<header>` og `<main>` for å organisere innholdet.
- Koblet HTML-siden til Flask ved hjelp av `render_template()`.

## Hva vi arbeider med nå
- Videreutvikling av dashbordet.
- Lære og bruke CSS for å forbedre utseendet på nettsiden.

## Hva som gjenstår
- Utvikle designet med CSS.
- Opprette og konfigurere MariaDB-databasen.
- Lage funksjon for registrering av datamaskiner.
- Utvikle nettverksovervåking med Python.
- Vise status og responstid på dashbordet.
- Lagre overvåkingsresultater i databasen.
- Teste systemet.
- Lage brukerveiledning og installasjonsveiledning.

## Teknologier
- Raspberry Pi
- Linux
- Python
- Flask
- HTML
- CSS
- MariaDB
- Git og GitHub

## Prosjektstatus
Prosjektet er under utvikling. Grunnleggende oppsett av Raspberry Pi, Flask og HTML er gjennomført. Neste steg er å videreutvikle dashbordet med CSS.
