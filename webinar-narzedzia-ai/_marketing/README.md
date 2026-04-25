# Webinar 12.05.2026 — Marketing Pack

> **Lejek:** Sylwia (społeczność NSL) → webinar bezpłatny → warsztaty Akademii AI
> **Cel:** zebrać 10-12 osób na warsztaty (Część I 750 zł lub I+II 1399 zł)

## Stan techniczny

| Element | Status | Detale |
|---------|--------|--------|
| Landing | ✅ LIVE (po push) | `/webinar-narzedzia-ai/index.html` |
| URL | ✅ | `akademia-ai-nieruchomosci.pl/webinar-narzedzia-ai` |
| Grupa MailerLite | ✅ utworzona | ID: `185744275235931644` |
| Form MailerLite | ✅ utworzony | ID: `185744336857597496`, slug: `iEKWIg` |
| Konto MailerLite | ✅ Sylwia | Account ID: `1031130` |
| Formularz na landingu | ✅ podpięty | POST do MailerLite JSONP, double opt-in |
| Sequence emaili (5) | ✅ drafty | `emails.md` |
| Posty social (8) | ✅ drafty | `social-posts.md` |

## Co Darek/Sylwia musi zrobić w MailerLite GUI

1. **Sprawdzić formularz** — Forms → Embedded → "Zapis - Webinar 12.05.2026" → potwierdzić ustawienia (double opt-in, content emaila aktywacyjnego po polsku)

2. **Skonfigurować email aktywacyjny (double opt-in)** — Forms → ten formularz → Confirmation email → spersonalizować (Sylwia w nadawcy, ciepły ton)

3. **Utworzyć Automation** z triggerem "Joins group: Webinar - 5 narzędzi AI dla agenta nieruchomości [12.05.2026]":
   - Email 1: natychmiast po confirm (treść z `emails.md`)
   - Email 2: 5.05 o 10:00
   - Email 3: 11.05 o 18:00 (Z LINKIEM ZOOM!)
   - Email 4: 12.05 o 19:00 (Z LINKIEM ZOOM!)
   - Email 5: 13.05 o 10:00 (Z REPLAYEM + ZNIŻKA)

4. **Ustawić Zoom**:
   - Stworzyć Zoom Meeting "Webinar 12.05.2026 — 5 narzędzi AI" z registracją (Required)
   - Ustawienia: Waiting Room ON, recording ON (cloud)
   - Skopiować link do Joina i wstawić w emaile #3 i #4 (LINK_ZOOM placeholder)

5. **Po webinarze**:
   - Pobrać nagranie z Zooma → wgrać na YouTube (unlisted) lub Vimeo
   - Wstawić link do nagrania w email #5
   - Wygenerować PDF z materiałami (lista narzędzi, prompty) i wstawić w email #5
   - Wygenerować Stripe link / kupon `WEBINAR12MAJA` w sklepie NSL z ceną o 100 zł niższą i wstawić w email #5

## Promocja — TIMELINE

| Data | Akcja | Plik referencyjny |
|------|-------|-------------------|
| **27.04** Pon 20:00 | Sylwia: post #1 w grupie NSL FB + IG | social-posts.md `#1` |
| **28.04** Wt 18:00 | Darek: post #2 FB + LinkedIn | social-posts.md `#2` |
| **30.04** Czw 12:00 | Sylwia: post #3 (przegląd narzędzi) FB + IG story | social-posts.md `#3` |
| **02.05** Sob 11:00 | Sylwia: post #4 (case story) grupa NSL | social-posts.md `#4` |
| **05.05** Wt 18:00 | Sylwia + Darek: post #5 (tydzień przed) | social-posts.md `#5` |
| **05.05** Wt 10:00 | Email #2 wychodzi automatycznie | emails.md |
| **08.05** Pt | Sylwia: rolka IG | social-posts.md `#6` |
| **11.05** Pn 9:00 | Sylwia + Darek: post #7 (jutro!) | social-posts.md `#7` |
| **11.05** Pn 18:00 | Email #3 wychodzi automatycznie | emails.md |
| **12.05** Wt 9:00 | Sylwia + Darek: post #8 (dziś!) | social-posts.md `#8` |
| **12.05** Wt 19:00 | Email #4 wychodzi automatycznie | emails.md |
| **12.05** Wt 20:00 | **WEBINAR LIVE** | — |
| **13.05** Śr 10:00 | Email #5 wychodzi automatycznie + post FB z replayem | emails.md |
| **17.05** Nd 23:59 | Koniec ważności zniżki 100 zł | — |

## URL repo / deploy

- **Repo:** `dariuszszuca-lang/akademia-ai-strona`
- **Folder:** `STRONY/akademia-ai-strona/webinar-narzedzia-ai/`
- **Vercel:** projekt `akademia-ai-strona`, auto-deploy na `git push`
- **Live URL:** https://akademia-ai-nieruchomosci.pl/webinar-narzedzia-ai

## Pomiar sukcesu

| Metryka | Cel | Gdzie sprawdzić |
|---------|-----|-----------------|
| Zapisy na webinar | 80+ | MailerLite grupa |
| Confirm rate (double opt-in) | 70%+ | MailerLite |
| Show-up na żywo | 50% | Zoom raport |
| Zapisy na warsztaty | 10-12+ | sklep NSL |
| Konwersja webinar → warsztat | 5-10% | własna kalkulacja |

## Kontakt techniczny

- **Landing:** Darek (jeśli błąd, wrzuć w iCloud, ja naprawię i pushnę)
- **MailerLite:** Sylwia (jej konto, jej kontrola)
- **Zoom:** Darek (jego płatne konto)
- **Sklep NSL / Stripe:** Sylwia
