# Bijdragen aan LD ICT

Fijn dat je wilt meewerken. Deze richtlijnen gelden voor alle repositories van [LD-ICT](https://github.com/LD-ICT), tenzij een repository een eigen `CONTRIBUTING.md`, `README.md`, `CLAUDE.md` of `AGENTS.md` heeft: die gaan voor.

## Talen

- **Interface in het Nederlands.** Alles wat een klant of gebruiker ziet, schrijven we in helder Nederlands. Engelse vertalingen komen daarna.
- **Code in het Engels.** Identifiers, comments, commit messages, branches, issues en pull requests schrijven we in het Engels.

## Werkwijze

1. **Begin bij een issue.** Kijk of er al een issue is, of open er een met een van de sjablonen. Overleg bij grotere wijzigingen eerst de aanpak.
2. **Werk op een feature branch.** Nooit direct op `main`. Gebruik een korte, beschrijvende naam, zoals `fix/safari-export` of `feat/dns-import`.
3. **Houd wijzigingen klein.** Eén onderwerp per pull request is makkelijker te reviewen en terug te draaien.
4. **Volg de bestaande conventies.** Kijk hoe vergelijkbare code al is opgezet, en upgrade grote dependencies (zoals `next`, `react` of `tailwindcss`) niet zonder overleg.
5. **Test je werk.** Draai de checks van de repository lokaal (bijvoorbeeld `pnpm test`, `pnpm lint` en `pnpm typecheck`) en controleer zichtbare wijzigingen op de preview deployment, op desktop en mobiel, in licht en donker thema.
6. **Open een pull request.** Vul het sjabloon in, koppel het issue (`Closes #123`) en voeg schermafbeeldingen toe bij UI-wijzigingen.

## Commits

Schrijf korte, beschrijvende commit messages in de gebiedende wijs, zoals `Add DNS import for Plesk zones` of `Fix Safari export button`. Gebruik de body om uit te leggen _waarom_ iets verandert, als dat niet vanzelf spreekt.

## Beveiliging en privacy

- **Geen geheimen in de code.** API-sleutels en tokens horen in environment variables, nooit in commits, logs, issues of schermafbeeldingen.
- **Geen klantgegevens.** Gebruik voorbeeldgegevens (`jan@voorbeeld.nl`, `voorbeeld.nl`) in tests, issues en documentatie.
- **Kwetsbaarheden meld je vertrouwelijk**, volgens het [beveiligingsbeleid](SECURITY.md), nooit in een openbaar issue.

## Gedrag

Door bij te dragen ga je akkoord met onze [gedragscode](CODE_OF_CONDUCT.md).

---

_In English: UI copy is Dutch, everything else (code, commits, issues, PRs) is English. Work on a feature branch, keep pull requests small, run the repository's checks, test on the preview deployment, never commit secrets or customer data, and report vulnerabilities privately as described in [SECURITY.md](SECURITY.md)._
