# Cybersecurity Projects — GitHub Pages

This is a ready-to-upload static website. No lab reruns are needed.

## Files
- `index.html` — project overview
- `smb.html`, `linux-hardening.html`, `database.html`, `bash.html` — individual project pages
- `style.css` — styling
- `screenshots/` — screenshot locations and SVG placeholders

## Insert original screenshots
Export/crop screenshots from the original assignment documents, redact sensitive data, and save them in `screenshots/` with these exact names:

### Windows SMB Exploitation & Password Analysis
- `smb-options.png` — Exploit and payload options; CYBR430 M7 Lab, page 5
- `smb-session.png` — Successful Meterpreter session; CYBR430 M7 Lab, page 6
- `smb-hash-analysis.png` — John the Ripper analysis (redact passwords and hashes); CYBR430 M7 Lab, page 8

### Linux System Hardening & Firewall Configuration
- `linux-users.png` — User creation and wheel group membership; CYBR340 Module 9, page 1
- `linux-firewall.png` — Firewall DMZ, HTTPS and MySQL rules; CYBR340 Module 9, page 3
- `linux-logs.png` — SSH status and security event log; CYBR340 Module 9, pages 3–4

### SQL Database Administration, Permissions & JSON
- `sql-crud.png` — INSERT, UPDATE and DELETE results; CYBR309 Module 3, pages 1–2
- `sql-permissions.png` — CREATE LOGIN, CREATE USER and GRANT (redact passwords); CYBR309 Module 6, pages 1–2
- `sql-json.png` — OPENJSON import and FOR JSON PATH output; CYBR309 Module 12, pages 1–2

### Linux Command Line & Bash Script Fundamentals
- `bash-files.png` — Navigation, file operations and history; CYBR340 Module 8, pages 1–2
- `bash-script.png` — Bash system information script in editor; CYBR340 Module 8, page 4
- `bash-permission.png` — Permission-denied result and troubleshooting lesson; CYBR340 Module 8, page 4

**Important:** Redact recovered passwords, hashes, login passwords, and any sensitive IPs or personal information. Avoid posting instructor-authored lab instructions verbatim. Do not misrepresent the Bash script as successfully executed: the submitted screenshot shows permission denied.

## Publish on your existing GitHub Pages website
1. Open your `cybersecurity-portfolio` repository.
2. Create a folder called `projects` in the repository root.
3. Upload all files and the `screenshots` folder contents into `projects/`.
4. Add a link on your current homepage: `<a href="projects/index.html">View Detailed Projects</a>`.
5. Commit changes and visit `https://simplyjuice.github.io/cybersecurity-portfolio/projects/`.

If you instead create a separate repository named `cybersecurity-projects`, enable GitHub Pages in Settings → Pages and select the main branch root. The link will normally be `https://simplyjuice.github.io/cybersecurity-projects/`.
