## Samenvatting

TechITEasy bv wil een applicatie met de volgende punten erin;

- ze hebben 4 soorten producten, TV's , afstandbedienings, muurbeugels en CI-modules.
- onderscheid in rechten binnen app. Hella, Paulus en Robin alles mogelijk. Rest beperkt.
- volgende (voor alle) productkenmerken; naam, merk, type, prijs en mogelijkheden.
- voor tv nog extra; schermtype, formaat, schermkwaliteit
    - ja/nee feiten; wifi, smart tv, voice controle en hdr compatible.
- voor afstandbediening extra; batterijtype, smart remote is ja/nee.
- voor muurbeugels extra; formaat en bevestigingsmethode.
- voor CI-module extra; provider, encoding.
- bijhouden wat de voorraad is en daarvan verkocht is en wanneer.
- 'wordt vaak samen gekocht met' sectie.

Relaties tussen diverse producten:

- voor elke tv maar 1 afstandsbediening
- ook 1 afstandsbediening per tv
- een soort ci-module past op meerdere tv's
- 1 tv kan maar 1 ci-module hebben
- beugels die voor meerdere tv's beschikbaar zijn
- een tv meerdere beugels hebben

## User stories

1. Als verkoper wil ik de huidige voorraad kunnen zien zodat ik reclame kan maken met modellen die wij uit voorraad
   leverbaar hebben.
2. Als eigenaar wil ik een rechtenscheiding in de applicatie zodat niet elke medewerker gevoelige gegevens kan aanpassen
   of inzien.
3. Als magazijnbeheerder wil ik de huidige voorraad kunnen zien zodat 