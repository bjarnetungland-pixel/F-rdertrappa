# 🏥 Færder Ressursfinner – Fastlegeverktøy

> KI-drevet verktøy for fastleger og helsepersonell i Færder kommune. Matcher pasientbehov mot kommunale tjenester i Færdertrappa og genererer et praktisk ressursark på sekunder.

---

## Hva er dette?

Som fastlege er det vanskelig å ha full oversikt over alle kommunale tjenester som finnes for pasientene dine. **Færder Ressursfinner** løser dette ved å la deg skrive inn et fritt pasientsammendrag – diagnoser, sosial situasjon, funksjonsnivå, pårørendebelastning – og så bruker verktøyet kunstig intelligens til å finne frem til de mest relevante tjenestene.

Resultatet er et kortfattet, utskriftsvennlig informasjonsark organisert etter:

- 🟢 **Biologisk / Helsetjenester**
- 🟣 **Psykologisk / Psykisk helse**
- 🟠 **Sosialt / Praktisk støtte**

...med konkrete handlingspunkter for deg som fastlege nederst.

---

## Funksjoner

- **Fritekstinnskriving** – skriv pasientsammendrag akkurat slik du ville skrevet det til en kollega
- **Hurtigvalg-tagger** – trykk på vanlige behov som *Demens*, *Fallrisiko*, *Depresjon*, *Pårørendebelastning* osv.
- **Basert på Færdertrappa** – alle 12 trinn og 80+ kommunale tjenester er innebygd i verktøyet
- **Biopsykososial struktur** – resultatet er organisert etter biologiske, psykologiske og sosiale faktorer
- **Utskriftsvennlig** – ett klikk for å skrive ut eller kopiere ressursarket
- **Ingen installasjon** – åpnes direkte i nettleseren, fungerer på PC, nettbrett og mobil

---

## Slik bruker du det

1. Åpne `gp_tool_artifact.html` i en nettleser (eller bruk lenken fra GitHub Pages)
2. Fyll inn alder, kjønn og bosituasjon (valgfritt)
3. Skriv inn pasientens historikk og behov i tekstfeltet
4. Velg eventuelle hurtigvalg-tagger
5. Trykk **"Generer ressursark"**
6. Les gjennom resultatet, skriv ut eller kopier til journalsystemet

> **Tips:** Du kan trykke `Ctrl + Enter` for å generere raskt uten å bruke musen.

---

## Personvern og datasikkerhet

- ❌ Ingen pasientdata lagres i verktøyet
- ❌ Ingen data sendes til eksterne servere utover selve KI-spørringen
- ✅ KI-spørringen inneholder kun det du selv skriver inn – ikke navn, fødselsnummer eller andre identifiserende opplysninger
- ✅ Verktøyet kjører lokalt i nettleseren

> **Viktig:** Bruk aldri pasientens navn, fødselsnummer eller andre direkte identifiserende opplysninger i tekstfeltet. Beskriv pasienten med alder, kjønn og klinisk informasjon.

---

## Teknisk

Verktøyet er én enkelt HTML-fil med innebygd CSS og JavaScript. Det bruker [Claude API](https://www.anthropic.com) fra Anthropic for KI-genereringen. Ingen rammeverk, ingen avhengigheter, ingen backend.

```
gp_tool_artifact.html   ← hele verktøyet i én fil
README.md               ← denne filen
```

---

## Ressursdatabasen

Verktøyet inneholder informasjon om alle tjenester i **Færdertrappa** – Færder kommunes modell for tjenestetildeling fordelt på 12 trinn:

| Trinn | Navn |
|-------|------|
| 1 | Attraktiv og inkluderende kommune |
| 2 | Helsefremmende hverdagsliv |
| 3 | Helsefremmende og forebyggende tjenester |
| 4 | Samlokaliserte boliger uten personalbase |
| 5 | Meningsfull og inkluderende hverdag |
| 6 | Kommunalt disponerte boliger |
| 7 | Leve godt i eget hjem |
| 8 | Helsehjelp til hjemmeboende |
| 9 | Tidsbegrenset opphold |
| 10 | Boliger med mulighet for døgntjenester |
| 11 | Langtidsopphold i sykehjem og helsehus |
| 12 | Boliger og institusjon – spesialiserte plasser |

Mer informasjon: [faerder.kommune.no/fardertrappa](https://faerder.kommune.no/tjenester/om-farder-kommune/organisasjonen/fardertrappa/)

---

## Kontakt

**Færder kommune**
📞 33 39 00 00
✉️ postmottak@faerder.kommune.no
🌐 [faerder.kommune.no](https://faerder.kommune.no)

---

*Verktøyet er laget for å støtte klinisk skjønn – ikke erstatte det. Resultatene er forslag basert på tilgjengelig informasjon i Færdertrappa og bør alltid vurderes av helsepersonell.*
