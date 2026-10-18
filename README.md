<div align="center">

# DockWall

### A Modular Desk-Side Organizer

A custom 3D-printed storage system that turns the side of a bookshelf into useful desk space.

**Designed in Autodesk Fusion 360 · Intended for FDM 3D printing · STEP export included**

</div>

---

## Overview

DockWall is a modular organizer designed to make better use of the vertical space beside a desk. It combines a multi-section mounting panel, separate connectors, and interchangeable accessories for everyday items such as pencils, a mouse, and headphones.

Instead of taking up more desktop area, DockWall moves storage to the side of a nearby bookshelf. Its modular layout is intended to let accessories be repositioned as needs change.

The current design is intended to attach to the broad, flat side of a wooden bookshelf without drilling. Adhesive mounting is planned, but the final adhesive setup and its holding capacity have not yet been verified.

> **Project status:** CAD design and manufacturing preparation. The design has not yet been physically validated. Fit, strength, adhesive performance, and load capacity remain unconfirmed.

## Features

- **Modular panel:** Six nominal 240 × 240 mm sections arranged in three columns and two rows.
- **Vertical storage:** Uses the side of a bookshelf instead of additional desktop space.
- **40 mm grid:** Intended 40 mm center-to-center spacing for accessory placement.
- **Interchangeable accessories:** Includes a pencil bin, shelf, mouse tray, and headphone rack.
- **Separate connectors:** Custom connector bodies are designed to align and join the panel sections.
- **3D-printable design:** Intended for fused-filament fabrication using PLA.
- **No-drill mounting goal:** Designed for adhesive attachment to a suitable flat furniture surface, pending validation.
- **CAD interchange:** Modeled in Fusion 360 and exported as a STEP file.

## Design at a Glance

| Specification | Current design |
| --- | --- |
| Project name | DockWall |
| CAD software | Autodesk Fusion 360 |
| CAD exchange format | STEP (`.step`) |
| Intended manufacturing | FDM / fused-filament 3D printing |
| Intended material | PLA |
| Panel sections | 6 |
| Nominal section size | 240 × 240 mm |
| Intended overall panel size | 720 × 480 mm |
| Intended grid spacing | 40 mm center-to-center |
| Main body shell thickness | 3 mm |
| Intended mounting surface | Flat side of a wooden bookshelf |
| Mounting approach | Adhesive; validation pending |
| Verified load capacity | Not established |
| Physical fit testing | Pending |

*Dimensions are nominal design targets. Actual assembled dimensions may vary with connector geometry, seam alignment, and manufacturing tolerances.*

## System Design

DockWall is made up of three main parts: the panel sections, panel connectors, and storage accessories.

### 1. Panel Sections

The panel provides the grid where compatible accessories attach. The intended full panel area is approximately **720 × 480 mm**, assembled from six nominal 240 × 240 mm sections.

Splitting the panel into smaller sections is intended to make manufacturing and assembly more manageable than producing one oversized part. The main body shell thickness was revised to 3 mm during design development to balance material use, weight, and rigidity. Actual strength will depend on geometry, print orientation, and slicer settings.

### 2. Connectors

Separate connector bodies are included to align and join the panel sections. Connector fit is important: too much clearance can allow movement, while too little can prevent assembly or damage the printed parts.

The connector count and fit should be confirmed against the final CAD model and assembly plan before manufacturing the full set.

### 3. Accessories

The current CAD export includes the following accessory designs:

| Accessory | Intended use |
| --- | --- |
| **Pencil Bin** | Pencils and lightweight stationery |
| **Shelf** | A small platform for compatible items |
| **Mouse Tray** | A dedicated place to store a computer mouse |
| **Headphone Rack** | Support for headphones when not in use |

These are the accessories currently represented in the design. Their final fit, usability, and load capacity have not yet been verified through physical testing.

## CAD Files

### `DockWall.step`

`DockWall.step` is the current exported CAD file. STEP is a neutral CAD interchange format that transfers solid geometry between compatible CAD applications and manufacturing workflows.

The export contains multiple separately named solid bodies, including:

- `Connector1` through `Connector10`
- `Pencil_Bin`
- `Shelf`
- `Mouse_Tray`
- `Headphone Rack`
- Panel geometry

A STEP file can preserve separate solid bodies, but manufacturing services may interpret multi-body files differently. Before ordering a print, confirm that the provider can identify and manufacture the bodies separately as intended.

### Fusion 360 Source File

Keep the editable Fusion 360 source file in the repository separately from the STEP export. The native file is the preferred version for continuing to edit the model and its design features.

Suggested repository structure:

```text
DockWall/
├── README.md
├── BOM.md
├── BOM.csv
├── CAD/
│   ├── source/
│   │   └── DockWall.f3d
│   └── exports/
│       └── DockWall.step
└── Journal/
    └── design-journal.md
```

This is a suggested structure; adjust the names and folders to match the actual repository.

## How It Works

1. Manufacture the panel sections, connectors, and selected accessories.
2. Inspect the printed parts for defects and dimensional issues.
3. Join and align the panel sections using the connectors.
4. Check that each accessory attaches and detaches without excessive force.
5. Prepare the bookshelf surface according to the selected adhesive manufacturer's instructions.
6. Mount the panel and allow the adhesive to cure for the specified period.
7. Introduce lightweight items cautiously and inspect the assembly for movement before normal use.

This is the planned assembly workflow. It should be updated after the first physical assembly reveals any necessary changes.

## Manufacturing and Fit Considerations

### Material: PLA

PLA is the intended material because it is commonly used for detailed FDM prints. However, it can become brittle under some conditions and may soften or deform at elevated temperatures. Printed strength also depends on part geometry, print orientation, wall count, infill, and print quality.

Avoid high-temperature environments and do not assume the organizer can support a particular load until it has been validated.

### Clearance and Tolerances

Nominal CAD dimensions may not exactly match printed dimensions.

- **Too little clearance:** a hook or connector may not fit.
- **Too much clearance:** an accessory may wobble or fail to stay in place.
- **Actual fit:** depends on the print service, material, orientation, and geometry.

Because the design has not been test-printed, final fit cannot be guaranteed. Check the manufacturing provider's stated dimensional tolerances when available.

### Panel and Connector Strength

The panel openings, connector locations, and accessory hooks are important areas to inspect. Narrow sections and sharp internal corners can concentrate stress. Accessories that extend outward from the panel can create leverage at their attachment points.

A thicker shell alone does not guarantee a strong finished part. Print orientation and the shape of the remaining material also matter.

## Installation and Mounting

DockWall is intended to mount to the flat side of a wooden bookshelf without drilling. Adhesive mounting remains unvalidated.

Before installation:

1. Confirm that the adhesive is compatible with both the bookshelf finish and the organizer's contact surface.
2. Clean and prepare the surface according to the adhesive manufacturer's instructions.
3. Apply the adhesive as directed.
4. Follow the specified application pressure and curing time.
5. Do not load the organizer before the adhesive has fully cured.

The combined weight of the panel, connectors, accessories, and stored items affects the mounting system. Shelves and racks that extend away from the panel create leverage and may pull the upper edge away from the bookshelf.

Published adhesive ratings depend on their test conditions and should not automatically be treated as a safe working load for this custom assembly. Removing adhesive may also damage some furniture finishes.

## Bill of Materials

The BOM should record exact quantities, prices, suppliers, and the final adhesive selection once confirmed.

- [`BOM.md`](BOM.md) — human-readable parts list, if included in the repository.
- [`BOM.csv`](BOM.csv) — spreadsheet-friendly parts list, if included in the repository.

Update these links or filenames if the repository uses a different structure. Do not treat unconfirmed quantities or costs as final.

## Testing and Validation

The current design is still at the CAD and manufacturing-preparation stage. The following checks remain:

- [ ] Confirm the STEP export opens correctly in the manufacturing workflow.
- [ ] Confirm separate bodies are recognized as intended.
- [ ] Verify panel-to-panel connector fit.
- [ ] Verify accessory fit and retention on the grid.
- [ ] Inspect printed parts for defects and weak areas.
- [ ] Validate adhesive compatibility with the bookshelf finish and printed surface.
- [ ] Check mounting stability with lightweight items before regular use.
- [ ] Record any changes made after physical assembly.

**No verified load rating is available yet.** Until the design has been manufactured and tested, use lightweight items only and do not rely on it to support fragile, heavy, or valuable objects.

## Software and Tools

- **Autodesk Fusion 360** — CAD modeling and design revisions
- **STEP** — neutral CAD exchange format for manufacturing preparation
- **FDM 3D printing** — intended fabrication method
- **PLA filament** — intended printed material
- **GitHub** — project files, documentation, and version history

## Development Journal

Use the project journal to record design changes, manufacturing decisions, fit issues, and validation results as the project develops.

Suggested location: [`Journal/design-journal.md`](Journal/design-journal.md)

## Limitations and Future Improvements

Known limitations:

- Physical fit and strength have not yet been tested.
- Adhesive choice, surface compatibility, and long-term holding performance are not yet confirmed.
- Final assembly dimensions may vary because of print tolerances.
- Manufacturing-service handling of multiple bodies in one STEP file must be confirmed.

Potential next steps:

- Manufacture and inspect the first set of parts.
- Adjust connector and accessory clearances based on actual fit.
- Validate the adhesive mounting method before adding more than lightweight items.
- Update the BOM and journal with final quantities, costs, and test results.

---

<div align="center">

**DockWall** · A modular approach to keeping everyday desk essentials organized.

</div>
