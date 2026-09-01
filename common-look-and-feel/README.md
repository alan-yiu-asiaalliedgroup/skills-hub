# Install Locally

Copy this entire folder to the root-level skills directory:

```text
<project-root>\.agents\skills\common-look-and-feel
```

From the repository root in PowerShell:

```powershell
New-Item -ItemType Directory -Force .\.agents\skills | Out-Null
Copy-Item -Recurse -Force .\common-look-and-feel .\.agents\skills\common-look-and-feel
```