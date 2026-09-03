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
ROS 1b:
Innloggede brukere får tilgang til data de ikke skal ha tilgang til.
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
ROS 1a, 1d, 2d
-->

---

## Påvirker denne endringen autentisering eller autorisering?

- [ ] Nei
- [ ] Ja

Hvis ja:

- [ ] Sikkerhetsansvarlig er involvert
- [ ] Test av uautorisert tilgang er gjennomført
- [ ] Eksisterende roller og rettigheter er verifisert

Beskriv:

---

## Påvirker denne endringen dataflyt eller integrasjoner?

- [ ] Nei
- [ ] Ja

Hvis ja:

- [ ] Kryptering er verifisert
- [ ] Ingen nye åpne endepunkter eksponeres
- [ ] Integrasjonen er testet i QA

Beskriv:

<!--
ROS 2a, 2f
-->

---

## Kan endringen påvirke konfigurasjon eller infrastruktur?

- [ ] Nei
- [ ] Ja

Hvis ja:

- [ ] Endringen er dokumentert
- [ ] Endringen er testet i QA
- [ ] Rollback-plan finnes

Beskriv:

<!--
ROS 1f, 2e
-->

---

## Påvirker denne endringen Github-repositoriet eller CI/CD?

- [ ] Nei
- [ ] Ja

Hvis ja:

- [ ] Ingen nye hemmeligheter (secrets) er lagt inn i kode
- [ ] Nødvendige GitHub-rettigheter er gjennomgått
- [ ] Branch protection påvirkes ikke
- [ ] Dependabot/SAST-resultater er gjennomgått

Beskriv:

<!--
ROS 1c
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
