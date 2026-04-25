# Sequence emaili — Webinar 12.05.2026

> **Grupa MailerLite:** "Webinar - 5 narzędzi AI dla agenta nieruchomości [12.05.2026]"
> **Grupa ID:** `185744275235931644`
> **Form ID:** `185744336857597496` · slug `iEKWIg`
> **Konto:** Sylwia (Nieruchomości Spod Lady), `1031130`

## Konfiguracja w MailerLite

Należy utworzyć **automation** z triggerem "Joins group" → "Webinar - 5 narzędzi AI dla agenta nieruchomości [12.05.2026]". W kolejności:

| # | Wysyłka | Temat | Plik |
|---|---------|-------|------|
| 1 | Natychmiast po potwierdzeniu (double opt-in) | Cześć, masz miejsce. Co dalej | `email-1-confirm.html` |
| 2 | 5.05.2026, 10:00 (tydzień przed) | Tydzień do webinaru. Mam pytanie | `email-2-tydzien.html` |
| 3 | 11.05.2026, 18:00 (24h przed) | Jutro o 20:00. Link do Zooma | `email-3-24h.html` |
| 4 | 12.05.2026, 19:00 (1h przed) | Za godzinę startujemy | `email-4-1h.html` |
| 5 | 13.05.2026, 10:00 (po) | Dzięki, że byłeś. Replay i zniżka 100 zł | `email-5-po.html` |

## Nadawca

- **From:** Sylwia Wróblewska (jej domyślny adres w MailerLite)
- **Reply-to:** sylwia@nieruchomoscispodlady.pl
- **Ton:** ciepły, koleżeński, "z mojego doświadczenia"

## Zmienne MailerLite

W treści emaili możesz użyć:
- `{$name}` — imię subskrybenta
- `{$unsubscribe}` — link do wypisu (wymagany!)

---

## Email 1 — POTWIERDZENIE ZAPISU

**Subject:** Cześć {$name}, masz miejsce na webinarze 12 maja
**Preheader:** 5 narzędzi AI dla agenta. Wtorek, 20:00. Co przygotować.

---

Cześć {$name},

zapisałeś się na webinar **5 narzędzi AI, których agent nieruchomości używa codziennie**. Twoje miejsce jest zarezerwowane.

**Co i kiedy:**
- Wtorek, 12 maja 2026, 20:00
- Zoom (link wyślę dzień wcześniej)
- 75 minut, plus Q&A bez ograniczenia

**Co pokażemy:** Claude, ChatGPT, Gemini, NotebookLM i Gamma. Każde narzędzie z prawdziwym przykładem z pracy pośrednika. Nie podstawy promptowania, tylko konkretne workflow, które oszczędzają godziny.

**Co warto przygotować przed webinarem:**
1. Otwarte konto Google (Gmail) jeśli jeszcze nie masz
2. Słuchawki, jeśli będziesz oglądać w pracy
3. Kartka i długopis (notatki przydadzą się bardziej niż myślisz)

Jeśli masz konkretne pytanie albo zadanie, w którym chciałbyś wykorzystać AI, odpisz mi mailem przed webinarem. Postaramy się pokazać Twój przypadek na żywo.

Do zobaczenia 12 maja,
Sylwia

P.S. Zarezerwuj sobie godzinę 20:00-21:30 w kalendarzu, żeby mieć spokój. Replay też dostaniesz, ale na żywo będziemy odpowiadać na pytania.

---
Sylwia Wróblewska
Nieruchomości Spod Lady
nieruchomoscispodlady.pl

[Wypisz się]({$unsubscribe})

---

## Email 2 — TYDZIEŃ PRZED (5.05)

**Subject:** Tydzień do webinaru, {$name}. Mam jedno pytanie
**Preheader:** Webinar 12.05 o 20:00. Co najbardziej chciałbyś usłyszeć?

---

Cześć {$name},

za tydzień, we wtorek 12 maja, robimy webinar o 5 narzędziach AI dla agenta nieruchomości. Krótka sprawa.

**Mam pytanie do Ciebie:**

Z którym narzędziem chcesz, żebyśmy spędzili najwięcej czasu? Mam 75 minut, pięć narzędzi, więc nie pokażę wszystkiego. Chcę pokazać to, co dla Ciebie konkretnie ma sens.

Masz do wyboru:
- **Claude** — analiza dokumentów (KW, akty, raporty), prompty negocjacyjne
- **ChatGPT** — opisy ofert ze zdjęć, własne GPTs do maili
- **Gemini** — Gmail, Drive, Workspace
- **NotebookLM** — research nieruchomości, transkrypcje rozmów z klientem
- **Gamma** — prezentacje ofert i materiały dla klienta w 5 minut

Odpisz mi jednym słowem (nazwa narzędzia) albo opisz krótko swoją sytuację, w której coś byś chciał poukładać. Dostosujemy program, żeby było to, co Cię najbardziej zaboli, że nie zobaczyłeś.

Do wtorku!
Sylwia

P.S. Jeśli pojawi się ktoś z Twoich znajomych z branży, kto też mógłby skorzystać, podeślij mu link: akademia-ai-nieruchomosci.pl/webinar-narzedzia-ai

---
Sylwia Wróblewska
Nieruchomości Spod Lady

[Wypisz się]({$unsubscribe})

---

## Email 3 — 24 GODZINY PRZED (11.05, 18:00)

**Subject:** Jutro o 20:00. Tu masz link do Zooma
**Preheader:** Webinar AI dla agenta nieruchomości. 12 maja, 75 minut konkretu.

---

Cześć {$name},

jutro, wtorek 12 maja, o **20:00** spotykamy się na webinarze.

**Twój link do Zooma:**
👉 [WSTAW TUTAJ LINK ZOOM]

(zachowaj tego maila, jutro też wyślę przypomnienie godzinę przed)

**Krótka ściągawka:**
- Start: 20:00, koniec około 21:15 (plus Q&A)
- Co weź: kartka, długopis, ewentualnie słuchawki
- Co pokażemy: Claude, ChatGPT, Gemini, NotebookLM, Gamma — z prawdziwymi przykładami z pracy agenta

**Jeśli czegoś nie zdążysz:** dostaniesz nagranie (replay 7 dni). Ale najwięcej dostaniesz na żywo, bo Q&A na czacie zostawiamy bez ograniczenia.

Do jutra!
Sylwia & Darek

---
Sylwia Wróblewska
Nieruchomości Spod Lady

[Wypisz się]({$unsubscribe})

---

## Email 4 — 1 GODZINA PRZED (12.05, 19:00)

**Subject:** Za godzinę startujemy, {$name}
**Preheader:** Link do Zooma jest tu. Zaczynamy o 20:00.

---

Cześć {$name},

za godzinę startujemy webinar **5 narzędzi AI dla agenta nieruchomości**.

👉 **[KLIKNIJ I DOŁĄCZ DO ZOOMA](LINK_ZOOM)**

Wszystko mam już przygotowane. Sylwia o 20:00 zaczyna powitanie, ja od 20:10 lecę z narzędziami. Plan:

- 20:00 powitanie (Sylwia)
- 20:10 pięć narzędzi, pięć przykładów (Darek)
- 21:00 codzienny workflow
- 21:10 Q&A

Bądź 5 minut wcześniej, żeby spokojnie wejść.

Do zobaczenia,
Darek

---
ai-team.pl

[Wypisz się]({$unsubscribe})

---

## Email 5 — DZIEŃ PO WEBINARZE (13.05, 10:00)

**Subject:** {$name}, dzięki, że byłeś wczoraj. Replay + zniżka 100 zł
**Preheader:** Nagranie webinaru na 7 dni + warsztaty Akademii AI w cenie startowej.

---

Cześć {$name},

dzięki, że byłeś wczoraj na webinarze. Mam nadzieję, że choć jedna z pokazanych rzeczy realnie zmieni Ci jutrzejszy dzień pracy.

**Replay (7 dni):**
👉 [LINK DO NAGRANIA]
Możesz wrócić, przewinąć do konkretnego narzędzia, podlinkować koleżance z biura.

**Materiały podsumowujące:**
👉 [LINK DO PDFa]
Lista narzędzi, gotowe prompty do skopiowania, schemat workflow.

---

**A teraz konkret:**

Pokazałem Ci 5 narzędzi. Webinar pokazuje, co JEST. **Warsztaty Akademii AI** uczą, JAK tego używać codziennie w Twojej pracy.

Format: środa online, czwartek-piątek stacjonarnie w Sopocie, sobota Q&A. Wychodzisz z **10+ agentami AI skonfigurowanymi pod Twoją pracę pośrednika** + roczny dostęp do platformy z aktualizacjami.

**Twoja zniżka 100 zł** (jako uczestnik webinaru) — kod: **WEBINAR12MAJA**

| Pakiet | Cena standard | Twoja cena |
|--------|---------------|------------|
| Część I (1 dzień stacjonarnie) | 750 zł | **650 zł** |
| Części I + II (2 dni stacjonarnie + certyfikat KW-NSL-AI) | 1 399 zł | **1 299 zł** |

👉 **Zapisuję się:** [LINK DO SKLEPU NSL]

Zniżka ważna do **niedzieli 17.05** włącznie. Jak będzie 10-12 osób, ruszamy z najbliższym terminem warsztatów. Jak będzie więcej, otwieramy kolejny.

Pytania? Odpisz na tego maila albo zadzwoń: 571 309 209.

Do zobaczenia w Akademii,
Sylwia & Darek

---
Sylwia Wróblewska
Nieruchomości Spod Lady · ai-team.pl

[Wypisz się]({$unsubscribe})
