Open the downloaded dooms-day.md file, copy everything, and paste it into the GitHub editor.

The write-up records the following verified findings from the provided evidence and attached write-up:

PHP version: 8.4.26
Earliest anomalous request: 2026-10-28 08:42:52
Initial multipart boundary: ZZZZZZZZZZ
Occupied Apache workers: 149
CVEs: CVE-2026-109618 and CVE-2026-109619
PHP memory limit: 134217728 bytes
Leaked cookie: PHPSESSID
Leaked cookie size: 773518 bytes
RCE time: 2026-10-28 08:43:02
Reverse-shell port: 4444
Second worker crash: 2026-10-28 08:47:42
Database-file discovery command
