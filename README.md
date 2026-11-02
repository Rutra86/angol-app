# Beszélj Angolul (saját verzió)

Saját angol beszélgetésgyakorló app. Böngészőben fut gépen és telefonon (Chrome ajánlott), kiteheted a kezdőképernyőre, és van benne mikrofon.

## Mit tud

- Beszélgetés Emmával, az AI tanárral: hétköznapi és építész szakmai témák, tárgyalás
- Hangos beszélgetés: mikrofon gomb, vagy „Folyamatos hangos beszélgetés” mód a Beállításokban
- Javítás magyar magyarázattal, kiejtési tipp beszédnél
- Szókártyák ismétléssel, szövegértés (Olvasás), autós hanglecke mód

## Cím

https://rutra86.github.io/angol-app/

## Beállítás

1. Nyisd meg a fenti címet Chrome-ban (gépen vagy telefonon).
2. Beállítások → AI szolgáltató: **OpenAI** (vagy Anthropic, ha Claude-kulcsod van).
3. Illeszd be az API-kulcsot, és nyomd meg a „Kulcs mentése” gombot. A kulcs csak abban a böngészőben tárolódik, ahol beírtad.
4. AI modell: ajánlott a **gpt-6.1-terra**.
5. Telefonon: Chrome menü (⋮) → „Hozzáadás a kezdőképernyőhöz”.

## API-kulcs és költség

**OpenAI**
- Kulcs: https://platform.openai.com → API keys. Egyenleg és havi korlát: Settings → Billing / Limits.
- Hozzávetőleges költség napi 20 üzenetnél: gpt-6.1-terra kb. 2 USD/hó, gpt-6.1-sol kb. 4 USD/hó, gpt-6-luna néhány tíz cent/hó.

**Anthropic (Claude)**
- Kulcs: https://console.anthropic.com → API Keys.
- Hozzávetőleges költség napi 20 üzenetnél: Opus 5.5 kb. 8–10 USD/hó, Sonnet 5.5 kb. 4–5 USD/hó, Haiku 5.5 1 USD alatt/hó.

A kulcsot senkinek ne küldd el. Ha kiszivárgott, töröld a szolgáltató oldalán, és hozz létre újat.

## Fájlok

- `index.html` – maga az app
- `manifest.webmanifest`, `icon-*.png` – telepíthető ikon
- `sw.js` – offline héj (az AI-hoz internet kell)
