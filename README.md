# Data ke kybernetickým incidentům

Tento repozitář obsahuje open data k kybernetickým bezpečnostním incidentům, které byly nahlášeny [Národnímu úřadu pro kybernetickou a informační bezpečnost](https://www.nukib.cz) (NÚKIB) dle § 8 zákona č. 181/2014 Sb. o kybernetické bezpečnosti.

**[data.csv](data.csv)**

Měsíční přehledy s podrobnějšími informacemi o incidentech jsou dostupné v sekci [Analýzy a Souhrnné zprávy](https://www.nukib.cz/cs/infoservis/dokumenty-a-publikace/analyzy/) na webu NÚKIB.

## Popis dat

### Rok/měsíc

Datum ve formátu YYYY-MM, kdy byl incident nalášen.

### Klasifikace incidentu

Dle [Reference Incident Classification Taxonomy](https://www.enisa.europa.eu/publications/reference-incident-classification-taxonomy) od [ENISA](https://www.enisa.europa.eu).

Možné hodnoty:
* Dostupnost - např. narušení dostupnosti způsobené DoS/DDoS útokem nebo sabotáží.
* Informační bezpečnost - např. neautorizovaný přístup k datům, neautorizovaná změna informace.
* Podvod - např. phishing, krádež identity nebo neoprávněné využití ICT.
* Pokus o průnik - např. pokus o zneužití zranitelnosti, pokus o přihlášení apod.
* Průnik - např. kompromitace aplikace nebo uživatelského účtu.
* Sběr informací - např. skenování, sniffing, sociální inženýrství.
* Škodlivý kód - např. virus, červ, trojský kůň, dialer, spyware.
* Urážlivý obsah - např. spam, kyberšikana, nevhodný obsah.
* Ostatní

### Závažnost incidentu dle § 31 odst. 2 vyhlášky č. 82/2018 Sb. o kybernetické bezpečnosti

* VELMI VÝZNAMNÝ INCIDENT - incident, při kterém je přímo a významně narušena bezpečnost poskytovaných služeb nebo aktiv. Jeho řešení vyžaduje neprodlené zásahy obsluhy s tím, že musí být všemi dostupnými prostředky zabráněno dalšímu šíření kybernetického bezpečnostního incidentu včetně minimalizace vzniklých i potenciálních škod.
* VÝZNAMNÝ INCIDENT - incident, při kterém je narušena bezpečnost poskytovaných služeb nebo aktiv. Jeho řešení vyžaduje neprodlené zásahy obsluhy s tím, že musí být vhodnými prostředky zabráněno dalšímu šíření kybernetického bezpečnostního incidentu včetně minimalizace vzniklých škod.
* MÉNĚ VÝZNAMNÝ INCIDENT - incident, při kterém dochází k méně významnému narušení bezpečnosti poskytovaných služeb nebo aktiv. Jeho řešení vyžaduje zásahy obsluhy s tím, že musí být vhodnými prostředky omezeno další šíření kybernetického bezpečnostního incidentu včetně minimalizace vzniklých škod.

## Distribuce datové sady není autorskoprávně chráněnou databází

Poskytovaná distriubuce datové sady není autorskoprávně chráněnou databází ve smyslu § 2 odst. 2 a 5 zákona č. 121/2000 Sb., o právu autorském, o právech souvisejících s právem autorským a o změně některých zákonů (autorský zákon). Strukturu poskytované distribuce datové sady (strukturu poskytované databáze) je tak možné bez dalšího převzít a opětovně užívat.
