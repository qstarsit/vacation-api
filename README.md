# Opdracht: Vacation Booking API

## Scenario

Je werkt aan een systeem voor een reisorganisatie die groepsreizen aanbiedt. Klanten kunnen zich inschrijven op beschikbare reizen. De organisatie wil een interne API waarmee medewerkers:

- Nieuwe reizen kunnen aanmaken
- Personen kunnen inschrijven voor een reis
- Beschikbaarheid kunnen beheren
- Overboekingen worden voorkomen

Je taak is om een eenvoudige REST API te bouwen die dit ondersteunt.

---

## Vereisten (MVP)

### API Functionaliteit

- Lijst opvragen van alle beschikbare reizen
- Nieuwe reis aanmaken, inclusief details zoals bestemming, startdatum, einddatum en maximaal aantal deelnemers
- Inschrijven van een persoon voor een reis
- Lijst van deelnemers voor een specifieke reis opvragen
- Beschikbaarheid van een reis updaten (max. aantal deelnemers)
- Annuleren van een inschrijving voor een reis

---

## Business Logica

- Een reis mag niet overboekt worden
- Een deelnemer mag zich niet twee keer inschrijven op dezelfde reis
- Je mag geen reizen boeken die in het verleden starten

---

## Technische eisen

- Gebruik **Django** of **FastAPI**
- Gebruik een ORM (**Django ORM** of **SQLAlchemy**)
- Gebruik een relationele database (**PostgreSQL** of **MariaDB**)
- Structuur van de code in meerdere modules
- Voeg een korte instructie toe over hoe je de app runt en test
- Voeg enkele voorbeeld-requests toe (curl, HTTPie of Postman)
- Zorg dat er tests zijn
- Een goede .gitignore
- Een werkend image (bijvoorbeeld via Docker)

---

## Bonuspunten

- API-authenticatie
- Kloppende Swagger / OpenAPI documentatie
- Gebruik in het geval **SQLAlchemy** Alembic voor database migraties
- Pagination bij `GET /trips`
- E-mail validatie
- Gebruik van async endpoints
- Het opgeleverde image is veilig en draait als een non-root gebruiker

---

## Aanlevering

Graag ontvangen:
- Source code (via GitHub of zip)
- README met installatie-instructies, uitleg en voorbeeld requests

---

## Beoordelingscriteria

- Begrip van relationele datamodellen
- Correct en veilig toepassen van business logica
- RESTful API ontwerp
- Netheid en modulariteit van de code
- Documentatie en bruikbaarheid
