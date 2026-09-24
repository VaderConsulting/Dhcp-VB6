# Dhcp

CSC VB6 DHCP client extractor (`DHCPExtract.exe`) that shells `dhcpcmd` (4.00+) against a chosen DHCP server. It lists scopes, enumerates clients (IP, hostname, MAC), and exports selected or all scopes to CSV under `c:\temp`. UI caption is "DHCP Clients".

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `DHCP` (`Dhcp.vbp`) | VB6 | WinForms exe | Scope/client extract via dhcpcmd |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Dhcp.vbp`

## Requirements

- Visual Basic 6.0 IDE
- `dhcpcmd.exe` 4.00 or later on PATH (Windows Resource Kit / DHCP tools)

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/Dhcp`.
Company names in project files: CSC.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
