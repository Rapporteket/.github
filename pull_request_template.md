# Beskrivelse

## Hva er endret?
Beskriv endringen kort.

## Hvorfor er endringen nødvendig?
Beskriv behovet eller problemet som løses.

## Relaterte saker
- Closes #
- Related to #

---

# Sikkerhetsvurdering

## Påvirker denne endringen tilgang til data?

- [ ] Nei
- [ ] Ja, og tilgangsstyring er gjennomgått

Hvis ja, beskriv:

<!--
Innloggede brukere skal ikke få tilgang til data de ikke skal ha tilgang til.
-->

---

## Påvirker denne endringen håndtering eller visning av sensitive data?

- [ ] Nei
- [ ] Ja

Hvis ja:

- [ ] Sensitive data eksponeres ikke i logger
- [ ] Sensitive data eksponeres ikke i feilmeldinger
- [ ] Sensitive data eksponeres ikke i e-post
- [ ] Sensitive data eksponeres ikke i klientkode/browser

Beskriv vurderingen:

<!--
ROS 1a
Rapporter og resultater som sendes automatisk ut på epost inneholder sensitive data
-->

---

# Testing

## Gjennomført testing

- [ ] Enhetstester
- [ ] Integrasjonstester
- [ ] QA-test
- [ ] Manuell sikkerhetstest
- [ ] Ingen tester nødvendig

Beskriv utført testing:

---

# Sjekkliste før merge

- [ ] Koden er gjennomgått av minst én annen utvikler
- [ ] Ingen sensitive data er lagt inn i kode, tester eller dokumentasjon
- [ ] Logging er gjennomgått
- [ ] Feilhåndtering er vurdert
- [ ] Dokumentasjon er oppdatert
- [ ] Risiko er vurdert opp mot ROS for Rapporteket

## Risikonivå

- [ ] Lav
- [ ] Middels
- [ ] Høy

Hvis middels eller høy, beskriv kompenserende tiltak:

---

# Kommentar til reviewer

Spesielle forhold reviewer bør være oppmerksom på:
