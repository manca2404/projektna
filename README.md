# Projektna Naloga: Analiza Študentskih Del

**Predmet:** Uvod v Programiranje  
**Avtor:** Manca Kavčič

## Opis Projekta

Ta projektna naloga vsebuje analizo študentskih del, pridobljenih iz e-študentskega servisa. Podatki so bili zbrani s spletne strani [E-Študentski Servis](https://www.studentski-servis.com/studenti) in so shranjeni v datoteki `dela.csv`. Pri zbiranju podatkov so bili vključeni naslednji atributi:

- ID dela
- Naziv dela
- Lokacija
- Neto plača
- Bruto plača
- Prosta mesta
- Trajanje
- Delovnik

Podatki so bili pridobljeni 28. junija 2024, kar pomeni, da so lahko ob branju te naloge že zastareli, saj se spletna stran nenehno posodablja. Kljub temu verjamem, da podatki še vedno nudijo vpogled v ponudbo študentskih del, saj so bili zbrani v času poletnega izpitnega obdobja, ko študentje najbolj iščejo delo in je ponudba običajno največja.

## Cilji Analize

Vse podatke sem analizirala v datoteki UrejanjePodatkov, ki pa sem jih razdelila na več sklopov. Glavni cilj analize je bil proučiti neto plače, saj se mi zdi ta podatek najbolj zanimiv. V analizo pa so bili vključeni tudi vsi ostali zbrani podatki.

## Tehnološki Sklop

Za pridobivanje podatkov in njihovo analizo so bile uporabljene naslednje tehnologije:

- **Pridobivanje podatkov:** Za pridobivanje podatkov iz spletne strani sem uporabila knjižnico `scrapy`.
- **Analiza podatkov:** Vsi podatki so bili analizirani v obliki Jupyter Notebooka.

Obe datoteki, tako za pridobivanje podatkov kot za analizo, sta vključeni v tem repozitoriju.

## Zaključek

Kljub temu da so podatki morda zastareli, menim, da analiza ponuja koristen vpogled v trg študentskega dela v Sloveniji v specifičnem obdobju.
