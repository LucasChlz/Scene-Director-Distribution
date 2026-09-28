# Scene Director — Free Distribution

Public distribution repository for **Scene Director**, a Foundry VTT module that shows cinematic screens to every player when combat starts and ends.

No release has been published yet. When the first version is out, install it from Foundry's package browser or with this manifest URL in **Add-on Modules → Install Module → Manifest URL**:

```text
https://github.com/LucasChlz/Scene-Director-Distribution/releases/latest/download/module.json
```

Release assets contain only the Foundry runtime (`scripts`, `styles`, `lang`, `fonts`, `module.json` and `LICENSE`). Development files, tests and internal documentation are not included.

## Free features

- two art styles, each with an encounter start and an encounter end screen;
- every color of every style editable, with saved palettes and a default palette per style;
- enemy leader, party members, names, enemy count and rounds filled in from the combat;
- editable texts and images, optional sound;
- automatic play when combat starts and ends, or on demand for the whole table;
- skip with a click or Esc, and a per-player option to turn off flashes and camera shake;
- scene import and export as JSON;
- public API for new art styles, text treatments and kinds of screens.

## Editions

- **Free:** the public package published here.
- **Patreon:** a separate companion module, developed in a private repository, that uses the Free module as its required base.

Issues for the distributed module can be reported in this repository.

## Release integrity

Each release includes:

- `module.json`
- `scene-director-VERSION.zip`
- `scene-director-VERSION.zip.sha256`

The checksum can be used to verify that the downloaded ZIP matches the validated build.
