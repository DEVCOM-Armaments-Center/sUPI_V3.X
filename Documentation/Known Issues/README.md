# sUPI v3.3 Known Issues

> **DISTRIBUTION STATEMENT A. APPROVED FOR PUBLIC RELEASE; DISTRIBUTION IS UNLIMITED.**

These are the errata for the v3.3 technical data package. Each issue has its own file. If a document
does not agree with itself, the issue tells you which source is correct. To report a new issue on
GitHub, refer to [`CONTRIBUTING.md`](../../CONTRIBUTING.md).

## Read before you order or assemble boards

| Issue | Card |
| --- | --- |
| [The BOM and pick-and-place still include parts that the MFR notes remove](platform-bom-includes-removed-parts.md) | Platform |
| [The released BOMs still use Murata capacitors](murata-capacitors-in-bom.md) | Both |
| [The inverter MPN does not agree with the value and footprint](inverter-mpn-mismatch.md) | Both |
| [The BOM lists R14 (DNP) and does not list R1](payload-bom-r1-r14.md) | Payload |
| [Title-block comments and helper files carry pre-release part numbers](kicad-stale-part-numbers.md) | Both |

## Read before you machine parts

| Issue | Part |
| --- | --- |
| [The latch notch does not align with the button, and the halves do not seat fully](13122514-13122515-13122518-latch-misalignment.md) | `13122514`, `13122515`, `13122518` |
| [The model hole positions are different from 100064665 V3](13122518-hole-spacing-issue.md) | `13122518` |
| [Note 5 names a superseded design model](13122514-13122517-note-5-stale-design-model.md) | `13122514`, `13122517` |
| [The hard anodize finish cannot apply to the polymer material option](13122514-13122517-material-finish-conflict.md) | `13122514`, `13122517` |
