# dns

Öffentliche Allow-Liste für einen Technitium-DNS-Server mit Advanced Blocking.

| Datei | Inhalt |
|---|---|
| `tdns_whitelist.txt` | Domains, die trotz Blocklisten auflösen sollen. Eine Domain pro Zeile, `#` leitet Kommentare ein, gruppiert nach Dienst. Ursprünglich aus einer AdGuard-Allowlist übernommen. |

Technitium lädt die Datei über ihre Raw-URL auf dem Branch `main` (Einstellung `allowListUrls`). Eine Änderung wirkt nach dem nächsten Abruf durch den Server.

Das Repo ist öffentlich, deshalb gehören hier nur Domains hinein: keine internen Hostnamen, IPs oder Zugangsdaten.
