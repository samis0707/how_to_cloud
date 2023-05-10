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

##### Kostenmatrix Root-Server
| Anbieter | Jährliche Kosten | Technsicher Support |  Arbeitsspeicher | CPU-Leistung | Datenträger | Datenmenge | Datenschutz | Geo-Location | Zusätzliche Funktionen
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| Hetzner | 70,57€ x 12: 893,88€ | E-Mail, Telefon | 64GB DDR4 RAM | 6 cores / 12 threads @ 3.6 GHz | SATA HDD / NVMe SSD | 2 x 512GB NVMe SSD 2 x 2TB SATA HDD (5TB) | Deutscher Standort, DSGVO Konform | Deutschland | Control panel |
| NetCup | 79,34€ x 12: 952,8€ | E-Mail, Telefon | 64GB DDR4 RAM | 14 cores |SSD | 2TB | keine Informationen | Deutschland | keine komplett dedizierte Einheit |
| IONOS (1&1) | 129 x 12: 1.560€ | E-Mail |64GB DDR4 RAM | 8 cores  | SSD | 1920GB | ? | Deutschland | Mangaged Backups |
| Starto | 82€ x 12: 984€  | E-Mail, Telefon | 64GB DDR4 RAM | 8 cores | SSD | 960GB | ? | Deutschland | Managed Backups | managed Backups

Ergebnis und schriftliche Begründung: 

Die Wahl fällt auf den Anbieter Hetzner. Er überzeugt nicht nur durch seine Konfigurationsmöglichkeiten, sondern auch durch den deutschen Standort die Datenschutz-Richtlinien und ein sehr gutes Preis/Leistungsverhältnis. Er bietet als einziger Anbieter die Anforderungen, die wir an die verfügbare Datenmenge haben. Die Wahl fiel auf einen dedizierten Server, da dieser voll umfänglich in unserer Kontrolle liegt. Die Gefahr, dass durch Virtualisierung in verschiedener Weise Perfomance einbußen auftreten können, wie bei manchen viruellen Server, ist so nicht gegeben.
Das Angebot:
![Hetzner Angebot](https://github.com/samis0707/how_to_cloud/assets/83206717/af2aa6fe-0087-4533-af27-37aaf45b0eea)
![2023-05-10 15_06_55-Hetzner Online GmbH - Robot — Mullvad Browser](https://github.com/samis0707/how_to_cloud/assets/83206717/b4a8a25c-0174-4894-83f8-a2da5f1f1c72)


#### Kosten für Domain-Hosting
Domain-Name: dualshare.de
##### Kostenmatrix Domain-Hosting
| Anbieter | Jährliche Kosten | Technischer Support |  Geo-Location |
| ----------- | ----------- | ----------- | ----------- |
| Strato | 0,6€ (Jahr 2: 12€) | E-Mail, Telefon | Deutschland |
| NetCup | 5,04€ | E-Mail, Telefon | ? | 
| IONOS | 0,96€ (Jahr 2: 15,6€) | E-Mail, Telefon | Deutschland |
Ergebnis und schriftliche Begründung:
Die Wahl fällt auf den Anbieter Strato. Er überzeugt durch ein gutes Preis/Leistungsverhältnis.

### Termin 2
---
#### Kosten für einen CoTurn-Server
#### Kosten für Back-Ups
#### SSO-Service
