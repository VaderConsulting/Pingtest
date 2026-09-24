# Pingtest

CSC VB6 Ping Test host (`PingTest.exe` / `Pingtest.vbp`): demo/harness for `ctlPing.ocx` — pick servers from ADO, Start/Loop/Stop ping with progress bars, optional CSV of round-trip times. Open `Pingtest.vbp` in the VB6 IDE (needs `ctlPing.ocx`).

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `PingTest` (`Pingtest.vbp`) | VB6 | WinForms exe | PingTest |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Pingtest.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `MSADODC.OCX`
  - `MSCOMCTL.OCX`
  - `ctlPing.ocx`

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/Pingtest`.
Company names in project files: CSC.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
