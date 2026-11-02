# Beszélj Angolul (saját verzió)

Saját angol beszélgetésgyakorló app telefonra. Böngészőben fut (Chrome ajánlott), kiteheted a kezdőképernyőre, és van benne mikrofon.

## Mit tud

- Beszélgetés Emmával, az AI tanárral: hétköznapi és építész szakmai témák, tárgyalás
- Hangos beszélgetés: mikrofon gomb, vagy „Folyamatos hangos beszélgetés” mód a Beállításokban
- Javítás magyar magyarázattal, kiejtési tipp beszédnél
- Szókártyák ismétléssel, szövegértés (Olvasás), autós hanglecke mód

## Beállítás

1. Nyisd meg az app címét Chrome-ban a telefonodon.
2. Beállítások → Claude API-kulcs: illeszd be a kulcsot, és nyomd meg a „Kulcs mentése” gombot. A kulcs csak a telefonodon tárolódik.
3. Chrome menü (⋮) → „Hozzáadás a kezdőképernyőhöz”.

## API-kulcs és költség

- Kulcs: https://console.anthropic.com → API Keys. Tölts fel egyenleget, és állíts be havi költségkorlátot (Limits).
- Hozzávetőleges költség napi 20 üzenetnél: Opus 5.5 kb. 8–10 USD/hó, Sonnet 5.5 kb. 4–5 USD/hó, Haiku 5.5 1 USD alatt/hó. A modellt a Beállításokban választhatod.
- A kulcsot senkinek ne küldd el. Ha kiszivárgott, töröld a console-ban, és hozz létre újat.

## Fájlok

- `index.html` – maga az app
- `manifest.webmanifest`, `icon-*.png` – telepíthető ikon
- `sw.js` – offline héj (az AI-hoz internet kell)
