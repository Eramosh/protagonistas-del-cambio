# Protagonistas del Cambio · Protagonists of Change

**Prototype v0.1 · October 2026** · [Español abajo](#español)

A community board game and a pilot web tool for just energy transitions in rural Latin America. Pilot territory: Yucatán, Mexico.

Most energy projects follow *technology → deployment → community*. We reverse it: *community → capacity → governance → technology*. Communities play through five stations (needs, options, actors, funding, upkeep), write their own Community Plan, and only then connect with actors who can help.

## What is in this repository

| File | What it is |
|---|---|
| `index.html` | Bilingual pilot page (ES/EN): project overview, kit downloads, facilitator tool to upload a Community Plan and match it with actors, aggregate MEL panel |
| `kit/Protagonistas_del_Cambio_Kit_v0.1.pdf` | Print-and-play kit in Spanish (18 US Letter pages) |
| `kit/Protagonists_of_Change_Kit_v0.1_EN.pdf` | Same kit in English, for reviewers |
| `*.jpg` | Board and cover images used by the page |

## How it works

1. **Physical game**: played on paper, no internet needed. Tokens can be corn, beans and pumpkin seeds.
2. **Community Plan sheet**: the group writes its agreements, including the actor types it matched with in the game.
3. **Plan upload**: the facilitator enters the Plan on the page after recording the group's consent. No personal names.
4. **Match**: only actors of the types chosen in the game appear. The community decides “Yes, let’s talk” or “Not for now”.
5. **Contact route and follow-up**: a list of chosen actors, what each asks for, and a ready message. The page sends nothing; the community makes contact.

## Pilot limitations

- **Simulated database.** Uploaded Plans are stored only in the browser of the device used (localStorage). The MEL panel adds up those Plans plus three clearly marked example Plans. A secure, shared database with access control is planned for the funded phase.
- **Example actors.** The actor list is a sample built from public sources to demonstrate the Match. We have no relationship with any of these organisations.
- **Language.** A Yucatec Maya (maaya t'aan) version is in preparation with speakers from the pilot community.
- **Starting values.** Game prices, events and number of months will be adjusted after playtests.

## Run it

Open `index.html` in any browser, or visit the GitHub Pages link of this repository. Keep the `kit` folder next to `index.html` so the PDF downloads work.

---

## Español

Un juego de mesa comunitario y una página piloto para una transición energética justa en comunidades rurales de América Latina. Territorio piloto: Yucatán, México.

La comunidad juega 5 estaciones, escribe su Hoja de Plan y quien facilita la carga en la página. Ahí la comunidad hace Match con actores de los tipos que eligió en el juego y obtiene una ruta de contacto.

**Limitaciones del piloto:** la base de datos está simulada; los Planes se guardan solo en el dispositivo. Los actores son ejemplos de fuentes públicas, sin relación con ninguno. La versión en maya está en preparación.

**Para verla:** abre `index.html` en cualquier navegador o entra al enlace de GitHub Pages del repositorio.
