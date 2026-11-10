<!-- This page is maintained in the Owble repository under .github/release-repo/README.md and copied here with every release. -->
<p align="center">
  <img src="owble.png" width="112" alt="Owble Logo" />
</p>

<h1 align="center">Owble</h1>

<p align="center">
  Ein moderner Client für <a href="https://www.mumble.info">Mumble</a>-Server – für Windows, macOS und Linux.
</p>

<p align="center">
  <img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FAntaresPURE%2FOwble-Releases%2Fbadges%2Ftests.json" alt="Tests" />
</p>

<p align="center">
  <b>⬇ Herunterladen:</b>
  <a href="https://github.com/AntaresPURE/Owble-Releases/releases/latest/download/Owble-win-x64.zip">Windows</a> ·
  <a href="https://github.com/AntaresPURE/Owble-Releases/releases/latest/download/Owble-osx-arm64.zip">macOS (Apple-Chip)</a> ·
  <a href="https://github.com/AntaresPURE/Owble-Releases/releases/latest/download/Owble-osx-x64.zip">macOS (Intel)</a> ·
  <a href="https://github.com/AntaresPURE/Owble-Releases/releases/latest/download/Owble-linux-x64.tar.gz">Linux</a>
</p>

---

## Installation

.NET ist jeweils enthalten, es muss nichts anderes installiert werden.

**Windows 10/11 (64 Bit):** ZIP entpacken und `Owble.exe` starten. Beim ersten Start bietet Owble an, sich für dein Benutzerkonto zu installieren (ohne Adminrechte); was eingerichtet wird, wählst du selbst: Startmenü, Desktop, App-Liste, Autostart, `mumble://`-Links. Nichts ausgewählt heißt portabel. Meldet Windows „Der Computer wurde durch Windows geschützt“ (die Datei ist nicht signiert): *Weitere Informationen → Trotzdem ausführen*.

**macOS 13 oder neuer:** ZIP öffnen und `Owble.app` in den Ordner *Programme* ziehen. Beim ersten Start meldet macOS, dass die App von einem nicht verifizierten Entwickler stammt: Rechtsklick auf Owble → *Öffnen* (oder *Systemeinstellungen → Datenschutz & Sicherheit → Trotzdem öffnen*). Owble fragt dann nach dem Mikrofon; für Push-to-Talk mit einer Taste außerhalb des Fensters braucht es die Freigabe unter *Eingabeüberwachung*.

**Linux (64 Bit):** Archiv entpacken (`tar -xzf Owble-linux-x64.tar.gz`) und `Owble` im Ordner starten. Wie unter Windows bietet Owble an, sich zu installieren (nach `~/.local/share/Owble`, mit Eintrag im Anwendungsmenü, Autostart und `mumble://`-Links). Benötigt werden die üblichen Desktop-Bibliotheken (X11 bzw. XWayland, `libicu`, `libasound2`, `libice6`, `libsm6`, `fontconfig`), die auf Desktop-Systemen vorhanden sind.

**Update:** Ein installiertes Owble (unter macOS: in *Programme*) zeigt neue Versionen oben im Fenster an und aktualisiert sich mit einem Klick. Sonst: neue Version herunterladen und wie oben starten. Einstellungen, Server und Zertifikat bleiben erhalten. **Deinstallieren** (Einstellungen, unter Windows auch die App-Liste) entfernt Owble restlos. Die eigene Version steht unten links in den Einstellungen, alle Versionen unter [Releases](https://github.com/AntaresPURE/Owble-Releases/releases).

## Lizenz

© 2026 Marco Josef Lehmer – alle Rechte vorbehalten, siehe [`LICENSE`](LICENSE). Vervielfältigen, Verändern und Weitergeben nur mit schriftlicher Zustimmung. Komponenten Dritter: [`THIRD-PARTY-NOTICES.md`](THIRD-PARTY-NOTICES.md).

Dieses Repository enthält nur die fertigen Versionen. Die Einträge „Source code“ bei den Releases fügt GitHub automatisch hinzu; sie enthalten nur diese Seite und die Lizenz.
