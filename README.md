# M777 Status Monitor Module · Unsorted

Ward-Beck Systems M777, 1982|15. Wiki page: [M777 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M777.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 9 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 6 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 1 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 1 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 4 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 3 |

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

Not on Google Drive yet: `1982 - 777-03-005 - BACK PLANE MTG. ANGLES - DRN P. Mahoney - ENG MRW - ISS 3.jpg`

## 3-D model

[`MECHANICAL/M777.stl`](MECHANICAL/M777.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M777)

- **Size:** 41 × 178 mm panel, 165 mm deep, 3.2 mm plate (assumed: 1.6" x 7" x 6.5", the common module)
- **From the drawing:** 0 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M777 - front panel.svg`)
- no drawing of the front panel: the panel is blank
- Made by `tools/module_models.py` (→ `MECHANICAL/M777.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

Not on Google Drive yet: `19xx - 777-01-002 - M777A STATUS MONITOR MODULE FUNCTIONAL - ISS 1.jpg`, `19xx - 777-02-002 - M777A STATUS MONITOR MODULE SCHEMATIC - ISS 1.jpg`

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [19xx - 777-01-002 - M777A STATUS MONITOR MODULE FUNCTIONAL - ISS 1.kicad_sch](KICAD/19xx%20-%20777-01-002%20-%20M777A%20STATUS%20MONITOR%20MODULE%20FUNCTIONAL%20-%20ISS%201.kicad_sch)
- [19xx - 777-02-002 - M777A STATUS MONITOR MODULE SCHEMATIC - ISS 1.kicad_sch](KICAD/19xx%20-%20777-02-002%20-%20M777A%20STATUS%20MONITOR%20MODULE%20SCHEMATIC%20-%20ISS%201.kicad_sch)
- [M777.kicad_sym](KICAD/M777.kicad_sym)
- [index.html](KICAD/index.html)

## Software

- [index.html](SOFTWARE/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
