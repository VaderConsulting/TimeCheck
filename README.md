# TimeCheck

VB6 Server Time Check (`TimeCheck.exe`): uses the NetHostTime component to read each listed server's clock, compares it with local time, and lists the deltas; the File menu can start a check, export results to `c:\temp\Server Times.txt`, and load or save the server list. Open `TimeCheck.vbp` in the VB6 IDE.

**Source last updated:** 2001-02-28 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `TimeCheck` (`TimeCheck.vbp`) | VB6 | WinForms exe | Compare local vs remote server times |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `TimeCheck.vbp`

## Requirements

- Visual Basic 6.0 IDE
- NetHostTime 5.0 component (sibling `NetHostTime` project)
- Common Dialog control (comdlg32.ocx)

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/TimeCheck`. Project company field: CSC.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
