# Reading Journal – webová aplikace

Toto je připravený balíček PWA (Progressive Web App) pro nasazení na HTTPS webhosting.

## Co obsahuje
- `index.html` – aplikace
- `manifest.webmanifest` – název, ikona a nastavení přidání na plochu
- `service-worker.js` – základní cache pro opakované spuštění i při výpadku připojení
- `icons/` – ikony aplikace

## Důležité
Aplikace musí být hostovaná přes HTTPS, aby šla spolehlivě přidat na plochu a používat jako webová aplikace. Data knihovny jsou lokálně v prohlížeči daného zařízení; automaticky se nesynchronizují mezi zařízeními. Před vymazáním dat Safari se doporučuje mít zálohu, pokud ji aplikace nabízí.
