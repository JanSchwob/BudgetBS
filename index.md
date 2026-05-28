<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Budget – Datenschutzerklärung</title>
  <style>
    :root {
      --bg: #f5f5f7;
      --card: #ffffff;
      --accent: #007AFF;
      --text: #1d1d1f;
      --muted: #6e6e73;
      --border: #d2d2d7;
    }
    @media (prefers-color-scheme: dark) {
      :root {
        --bg: #000000;
        --card: #1c1c1e;
        --text: #f5f5f7;
        --muted: #98989d;
        --border: #3a3a3c;
      }
    }
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: -apple-system, BlinkMacSystemFont, "SF Pro Text", "Helvetica Neue", sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
      -webkit-font-smoothing: antialiased;
    }
    header {
      background: var(--card);
      border-bottom: 1px solid var(--border);
      padding: 24px 20px;
      text-align: center;
    }
    .app-icon {
      width: 72px;
      height: 72px;
      border-radius: 16px;
      background: linear-gradient(135deg, #007AFF, #34C759);
      display: inline-flex;
      align-items: center;
      justify-content: center;
      margin-bottom: 12px;
    }
    header h1 { font-size: 22px; font-weight: 700; }
    header p { font-size: 15px; color: var(--muted); margin-top: 4px; }
    main {
      max-width: 680px;
      margin: 0 auto;
      padding: 32px 20px 64px;
    }
    .card {
      background: var(--card);
      border-radius: 16px;
      padding: 24px;
      margin-bottom: 16px;
      border: 1px solid var(--border);
    }
    .card h2 {
      font-size: 17px;
      font-weight: 600;
      margin-bottom: 12px;
      color: var(--accent);
    }
    .card p, .card li {
      font-size: 15px;
      color: var(--text);
      margin-bottom: 8px;
    }
    .card ul { padding-left: 20px; }
    .card li { margin-bottom: 6px; }
    .badge {
      display: inline-block;
      background: #34C75920;
      color: #34C759;
      border-radius: 8px;
      padding: 2px 10px;
      font-size: 13px;
      font-weight: 600;
      margin-bottom: 12px;
    }
    .highlight {
      background: #007AFF12;
      border-left: 3px solid var(--accent);
      border-radius: 0 8px 8px 0;
      padding: 12px 16px;
      margin-top: 8px;
      font-size: 14px;
    }
    footer {
      text-align: center;
      padding: 32px 20px;
      font-size: 13px;
      color: var(--muted);
      border-top: 1px solid var(--border);
    }
    footer a { color: var(--accent); text-decoration: none; }
    .date { font-size: 13px; color: var(--muted); margin-bottom: 24px; }
  </style>
</head>
<body>

<header>
  <div class="app-icon"></div>
  <h1>Budget</h1>
  <p>Monatsbudget &amp; Steuerberechnung für die Schweiz</p>
</header>

<main>
  <p class="date">Datenschutzerklärung · Stand: Mai 2026</p>

  <div class="card">
    <div class="badge">Keine Datensammlung</div>
    <h2>Kurz und klar</h2>
    <p>Budget sammelt, überträgt oder verkauft keinerlei persönliche Daten an Dritte. Alle von dir erfassten Informationen verbleiben ausschliesslich auf deinem Gerät und – falls du iCloud aktiviert hast – in deinem eigenen persönlichen iCloud-Konto.</p>
  </div>

  <div class="card">
    <h2>Welche Daten werden gespeichert?</h2>
    <p>Die App speichert ausschliesslich die Daten, die du selbst eingibst:</p>
    <ul>
      <li>Budgetname und Steuerjahr</li>
      <li>Einkommensdaten (Bruttolohn, Sozialabgaben, Pensum)</li>
      <li>Rückstellungen, Sparpläne, Ausgaben und Abonnements</li>
      <li>Steuerparameter (Zivilstand, Kinder, Religionszugehörigkeit, Abzüge)</li>
    </ul>
    <div class="highlight">
      Es werden keine Gerätedaten, keine Standortdaten, keine Nutzungsstatistiken und keine Absturzberichte erfasst.
    </div>
  </div>

  <div class="card">
    <h2>Lokale Speicherung</h2>
    <p>Alle Daten werden mit <strong>SwiftData</strong> direkt auf deinem iPhone gespeichert. Kein externer Server des Entwicklers ist involviert.</p>
  </div>

  <div class="card">
    <h2>iCloud-Synchronisation (optional)</h2>
    <p>Falls du auf deinem Gerät bei iCloud angemeldet bist, synchronisiert die App deine Budgetdaten über <strong>Apple CloudKit</strong> automatisch zwischen deinen Apple-Geräten.</p>
    <ul>
      <li>Die Synchronisation erfolgt ausschliesslich über dein persönliches iCloud-Konto.</li>
      <li>Apple verarbeitet diese Daten gemäss der <a href="https://www.apple.com/de/legal/privacy/" target="_blank">Apple-Datenschutzrichtlinie</a>.</li>
      <li>Der Entwickler hat zu keinem Zeitpunkt Zugriff auf deine iCloud-Daten.</li>
      <li>Du kannst die iCloud-Synchronisation jederzeit in den iPhone-Einstellungen unter <em>Apple-ID → iCloud → App anzeigen</em> deaktivieren.</li>
    </ul>
  </div>

  <div class="card">
    <h2>Analyse &amp; Tracking</h2>
    <p>Budget enthält:</p>
    <ul>
      <li>Keine Analyse-SDKs (kein Firebase, kein Crashlytics, kein Amplitude u.Ä.)</li>
      <li>Keine Werbung</li>
      <li>Kein Cross-App-Tracking</li>
      <li>Keine Drittanbieter-Bibliotheken ausser den von Apple bereitgestellten Frameworks</li>
    </ul>
  </div>

  <div class="card">
    <h2>Kinder</h2>
    <p>Budget richtet sich an Erwachsene. Die App ist nicht für Kinder unter 13 Jahren konzipiert und erfasst wissentlich keine Daten von Minderjährigen.</p>
  </div>

  <div class="card">
    <h2>Datenexport &amp; Löschung</h2>
    <p>Alle deine Daten gehören dir. Du kannst:</p>
    <ul>
      <li><strong>Exportieren</strong>: Über die Teilen-Funktion in der App als CSV oder PDF.</li>
      <li><strong>Löschen</strong>: Einzelne Budgets direkt in der App, alle Daten durch Deinstallation der App. iCloud-Daten werden durch Deinstallation ebenfalls entfernt.</li>
    </ul>
  </div>

  <div class="card">
    <h2>Änderungen dieser Erklärung</h2>
    <p>Bei wesentlichen Änderungen an der Datenschutzpraxis wird diese Seite aktualisiert. Das Datum oben («Stand») zeigt die letzte Änderung an.</p>
  </div>

  <div class="card">
    <h2>Kontakt</h2>
    <p>Bei Fragen zur Datenschutzerklärung:</p>
    <p><a href="mailto:jan.schwob@yahoo.com">jan.schwob@yahoo.com</a></p>
  </div>
</main>

<footer>
  <p>© 2026 Jan Schwob · <a href="mailto:jan.schwob@yahoo.com">Kontakt</a></p>
  <p style="margin-top:8px;">Budget ist eine unabhängige App und steht in keiner Verbindung zu Banken, Finanzinstituten oder Behörden.</p>
</footer>

</body>
</html>
