# Scene Director — Free Distribution

Public distribution repository for **Scene Director**, a Foundry VTT module that shows cinematic screens to every player when combat starts and ends.

![A Rebel start screen: ransom-note title, the enemy leader and the number of foes](media/screen-rebel-encounter-start.png)

## Install

In Foundry, open **Add-on Modules → Install Module** and paste this manifest URL:

```text
https://github.com/LucasChlz/Scene-Director-Distribution/releases/latest/download/module.json
```

Requires Foundry VTT v13 (verified 13.351). Works with any game system.

Release assets contain only the Foundry runtime (`scripts`, `styles`, `lang`, `fonts`), `module.json`, `LICENSE`, `README.md` and `CHANGELOG.md`. Development files, tests and internal documentation are not included.

## Free features

- Encounter start and end screens in two art styles, **Rebel** and **Chronicle**, shown to the whole table at the same time.
- The combat fills them in: enemy leader, party members, names, enemy count and rounds. Hidden combatants never show; actors with no art get the style's silhouette.
- **Cast:** right-click a combatant to make it the leader, or open the Cast window to order the party and leave someone out.
- Every color of every style is editable, with saved palettes, a default palette per style and a contrast warning.
- Editable texts (`{leader}`, `{enemies}`, `{roundsRoman}`…), fixed images for any slot, and a sound per scene.
- A GM window that dresses in the style of the scene being edited, with a live preview.
- Plays automatically when combat starts and ends, or on demand, from key bindings or the API.
- Screens last 2 to 4 seconds and can be skipped; each player can turn off flashes and camera shake.
- English and Brazilian Portuguese. Public API for new art styles, text treatments and kinds of screens.

![The Scene Director window in the Rebel theme](media/window-rebel.png)

![The Chronicle end screen: the party in medallions and the rounds in Roman numerals](media/screen-chronicle-encounter-end.png)

![The two start screens playing](media/clip-start-screens.gif)

## Editions

- **Free:** the public package published here, complete on its own.
- **Patreon:** a separate companion module in development, which uses the Free module as its required base.

Issues for the distributed module can be reported in this repository.

## Release integrity

Each release includes:

- `module.json`
- `scene-director-VERSION.zip`
- `scene-director-VERSION.zip.sha256`

The checksum can be used to verify that the downloaded ZIP matches the validated build.

## Credits and license

MIT. The bundled fonts (Anton, Archivo Black, Abril Fatface, Rubik Mono One, Cinzel, Cormorant Garamond) are under the SIL Open Font License. The screenshots show the module's own screens and built-in silhouettes.
