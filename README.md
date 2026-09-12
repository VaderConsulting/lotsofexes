# lotsofexes

CSC VB6 LotsofExes (`LotsofExes.exe`) one-button batch factory. Reads server lists from `c:\temp\serv*.txt` and emits numbered `.bat` files under `c:\temp\bat\` to copy and schedule wake scripts across admin shares (`c$\temp`), then clean up `wake.exe` / `macs.csv`.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Project1` (`LotsofExes.vbp`) | VB6 | WinForms exe | Emit wake/copy/clean admin-share batch files |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `LotsofExes.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Writable `c:\temp` paths used by the sample (`serv*.txt`, `bat\` output folders)

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Old/lotsofexes`.
Company names in project files: CSC.

## License

MIT (c) 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
