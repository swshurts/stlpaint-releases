<img width="1087" height="809" alt="STLPaint Main Screen" src="https://github.com/user-attachments/assets/d94388e7-c8cb-4706-9b11-92bd07268e11" />
# STLPaint downloads

Installers for STLPaint, a desktop tool for painting 3D models that are going to be
printed, then exporting them with the colours intact.

User Guides: PDF File  - [stlpaint-user-manual.pdf](https://github.com/user-attachments/files/34995443/stlpaint-user-manual.pdf)
             Docx File - [stlpaint-user-manual.docx](https://github.com/user-attachments/files/34995442/stlpaint-user-manual.docx)

This repository holds **downloads only**. The source code is not published here.

## Get the app

Open the [latest release](https://github.com/swshurts/stlpaint-releases/releases/latest)
and download the file for your system:

| System | File | Notes |
|---|---|---|
| Windows 10/11 (64-bit) | `STLPaint-Setup-<version>.exe` | Run the installer. Windows may show a SmartScreen prompt the first time. |
| Linux (x86-64) | `STLPaint-<version>.AppImage` | Mark it executable (`chmod +x`) and run it. |

There is no macOS build.

## If Windows warns you

The installer is signed with a code-signing certificate issued to the publisher, but a
new certificate has no reputation with SmartScreen yet, so the "Windows protected your
PC" prompt can still appear. Choose **More info → Run anyway**. You can confirm the
signature yourself before running it:

```powershell
Get-AuthenticodeSignature .\STLPaint-Setup-*.exe | Format-List Status, SignerCertificate
```

`Status` should be `Valid`.

## Reporting a problem

Open an issue here with your system, the version, and what you were doing.
