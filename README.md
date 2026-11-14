# Web de Pit Reflex

Web pública del juego Pit Reflex, servida con GitHub Pages en
https://danielrubioruizseo-beep.github.io/

| Archivo | Qué es |
|---|---|
| `index.html` | Portada del juego. |
| `pit-reflex/privacy-policy.html` | Política de privacidad (español e inglés). Se genera desde el juego con `node scripts/make-privacy.mjs`; no la edites a mano. |
| `pit-reflex/jugar/` | Versión jugable en el navegador. Se genera desde el juego con `npm run web:publish`; no la edites a mano. |
| `404.html` | Página de error. Si se recarga dentro de la versión jugable, vuelve a su inicio. |
| `app-ads.txt` | Lo exige AdMob. Se añade cuando AdMob dé la línea con el ID de editor (`pub-…`). |

El código del juego está en un repositorio privado aparte.
