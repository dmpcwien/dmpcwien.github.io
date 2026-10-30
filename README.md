# Dean Teamplaner – öffentliche OAuth-Informationsseite

Statische Projektwebsite für den Google-OAuth-Zustimmungsbildschirm.

**Wichtig:** Dieses öffentliche Repository darf keine E-Mails, Kalender, Arbeits-PDFs, Mitarbeiterinformationen, API-Schlüssel oder OAuth-Tokens enthalten. Der eigentliche VZA7-Arbeitsassistent befindet sich in einem getrennten privaten Repository.

## GitHub Pages

Repository: `dmpcwien/dmpcwien.github.io`

In den Repository-Einstellungen unter **Settings → Pages → Build and deployment**
- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/(root)**
- **Save**

Nach erfolgreicher Veröffentlichung:
- Startseite: https://dmpcwien.github.io/
- Datenschutz: https://dmpcwien.github.io/datenschutz.html
- Nutzung: https://dmpcwien.github.io/nutzung.html

## Google Auth Platform → Branding

Nur öffentlich erreichbare Links eintragen. Für die Autorisierung der Domain ggf. eine Verifizierung in Google Search Console durchführen. GitHub Pages garantiert keine Anerkennung durch Googles OAuth-Verifizierung; je nach Prüfung kann eine eigene Domain erforderlich sein.

Ein Wechsel der OAuth-App von **Testing** auf **In production** erzeugt keinen neuen Token. Danach muss die Gmail-Zustimmung mit Offlinezugriff erneuert und der neue `VZA7_GMAIL_REFRESH_TOKEN` als GitHub Actions Secret im **privaten** VZA7-Repository hinterlegt werden.

Die Datenschutzhinweise müssen mit der tatsächlich betriebenen App und den geltenden rechtlichen Anforderungen übereinstimmen, bevor die Seite in einer öffentlichen OAuth-Freigabe verwendet wird.