# Perspektiv

Dansk React-prototype til en sociologisk undersøgelse.

## Kør lokalt

```sh
npm install
npm run dev
```

`npm run build` bygger produktionen.

## Prototype

Introduktion → generelle spørgsmål → én af fire cases → afslutning. Ingen svar sendes til en server eller mail. En besvarelse kan downloades som JSON. Svar eksisterer kun i React-hukommelsen og forsvinder ved genindlæsning. Casevalget fastholdes ved tilbage-navigation i flowet.

Casefordeling bruger en lokal browser-tæller i localStorage. Den er kun en demonstration, ikke en fælles respondenttæller. Genindlæsning starter en ny demo. Der er ingen analytics. Skrifttyper bruger browserens lokale fallback; der hentes ingen eksterne skrifttyper.

## Før rigtig brug

Tilføj backend med atomisk casefordeling, kvoter for gennemførte svar, håndtering af frafald og samtidige deltagere, validering, lagring og mailnotifikation. Undgå at lagre IP-adresser, og gennemgå hostinglogs, dataminimering og kombinationer af baggrundsspørgsmål før en påstand om fuld anonymitet. Erstat eksempelindhold og tidsestimat med undersøgelsens endelige indhold.

