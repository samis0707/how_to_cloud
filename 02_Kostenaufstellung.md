## Warum eine Kostenmatrix?
Zur Wahl des richtigen Anbieters muss eine begründete Auswahl stattfinden --> hier mit Hilfe einer Kostenmatrix
Die Auswahl des richtigen IT-Dienstleisters für das Hosting eines Root-Servers ist eine wichtige Entscheidung, die langfristige Auswirkungen auf die Leistung und Zuverlässigkeit des Servers haben kann.
### Wo fallen Kosten an?
- Domain
- E-Mail Provider --> Admin Account
- CoTurn-Server --> Nextcloud App "Talk"
- SSO-Service
- Back-Ups

### Kick-Off
---
#### Kosten für einen Root-Servers 
Anforderungen an den Server:
- Für 1500 Nutzer mit à 512MB persönlichem Speicher
- Für 60 Gruppen mit à 20GB geteiltem Speicher
--> 6-8 Cores für die CPU, 32GB Arbeitsspeicher, 2TB Speicher

##### Kostenmatrix
| Anbieter | Jährliche Kosten | Technsicher Support |  Arbeitsspeicher | CPU-Leistung | Datenträger | Datenmenge | Datenschutz | Geo-Location | Zusätzliche Funktionen
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| Hetzner | 70,57€ x 12: 893,88€ | E-Mail, Telefon | 64GB DDR4 RAM | 6 cores / 12 threads @ 3.6 GHz | SATA HDD / NVMe SSD | 2 x 512 GB NVMe SSD 2 x 1 TB SATA SSD (3TB) | Deutscher Standort, DSGVO Konform | Deutschland | Control panel |
| NetCup | 79,34€ x 12: 952,8€ | E-Mail, Telefon | 64GB DDR4 RAM | 14 cores |SSD | 2TB | keine Informationen | Deutschland | keine komplett dedizierte Einheit |
| IONOS (1&1) | 129 x 12: 1.560€ | E-Mail |64GB DDR4 RAM | 8 cores  | SSD | 1920GB | ? | Deutschland | Mangaged Backups |
| Starto | 82€ x 12: 984€  | Telefon, E-Mail | 64GB DDR4 RAM | 8 cores | SSD | 960GB | ? | Deutschland | Managed Backups | managed Backups

Ergebnis und schriftliche Begründung: 

Die Wahl fällt auf den Anbieter Hetzner. Er überzeugt nicht nur durch seine Konfigurationsmöglichkeiten, sondern auch durch den deutschen Standort die Datenschutz-Richtilinien und ein sehr gutes Preisleistungsverhältnis. Er bietet als einziger Anbieter die Anforderungen, die wir an die verfügbare Datenmenge haben. Die Wahl fiel auf einen dedizierten Server, da dieser voll umfänglich in unserer Kontrolle liegt. Die Gefahr, dass durch Virtualisierung in verschiedener Weise Perfomance einbußen auftreten können, wie es bei einem viruellen Server sein könnte ist so nicht gegeben.
Das Angebot:
![Hetzner Angebot](https://github.com/samis0707/how_to_cloud/assets/83206717/af2aa6fe-0087-4533-af27-37aaf45b0eea)



#### Kosten für Domain-Hosting
Domain-Name: dualshare.de

| Anbieter | Jährliche Kosten | Technischer Support | Uptime-Garantie | Reputation | Datenschutz | Geo-Location | Zusätzliche Funktionen
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | 
| Anbieter A |
| Anbieter B |
| Anbieter C |
| Anbieter D |

Ergebnis und schriftliche Begründung:


Gesamtpreis: 1.067,28€


### Termin 2
---
#### Kosten für einen CoTurn-Server
#### Kosten für Back-Ups
#### SSO-Service
