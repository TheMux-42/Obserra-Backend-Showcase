# Architektur (ohne Code)

## Überblick

Erkläre die Komponenten in Worten, z. B.:
- Discord Bot Gateway
- Backend Services
- Datenbank
- Monitoring/Logging

## Datenfluss

1. Discord Event kommt rein
2. Backend verarbeitet Event
3. Persistenz/Abfrage in der Datenbank
4. Antwort/Status zurück an Discord

## Betriebsaspekte

- Error Handling (konzeptionell)
- Rate Limiting / Retries (konzeptionell)
- Observability (Logs, Metriken, Alerts)

## Was bewusst fehlt

- Klassenstrukturen
- konkrete Methoden
- interne Business-Logik
- Konfigurations-Secrets
