# TimeCheck

VB6 server time checker (`TimeCheck.exe`): uses NetHostTime to fetch each listed server’s clock, compares to local time, and can export deltas to `c:\temp\Server Times.txt`. Open `TimeCheck.vbp` in the VB6 IDE (needs NetHostTime.dll).

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `TimeCheck` (`TimeCheck.vbp`) | VB6 | WinForms exe | Compare local vs remote server times |
