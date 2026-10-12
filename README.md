# Amateurfußball in Deutschland 2024–2026 – Power-BI-Dashboard

Analyse der DFB-Mitgliederstatistik für alle 21 Landesverbände über drei Jahre.

**Bericht ansehen:** [Dashboard als PDF](DFB_Amateurfussball_Dashboard_Qussai_Elbackoush.pdf)

## Fragestellung
Wächst der organisierte Amateurfußball nur bei den Mitgliedern, oder auch im Spielbetrieb? Und wo gelingen die Übergänge im Jugend- und Frauenfußball?

## Datenquelle
DFB-Mitgliederstatistik, Ausgaben 2024, 2025 und 2026 (dfb.de). Werte je Jahr wie in der jeweiligen Ausgabe veröffentlicht; alle Summen gegen die DFB-Gesamtwerte geprüft.

## Methode
- **Power Query (M):** wiederverwendbare Funktion, die jede Jahrestabelle entpivotiert und zu einer Faktentabelle zusammenführt. Ein neues Jahr erfordert nur ein zusätzliches Tabellenblatt.
- **Datenmodell:** Sternschema mit Dimensionstabelle der Landesverbände (Regionalverband) und Faktentabelle.
- **DAX:** Kennzahlen wie Mitglieder pro Mannschaft, Übergangsquote (A-/B- zu C- bis G-Junioren-Teams) und Veränderung seit 2024.

## Zentrale Erkenntnisse
1. **Mitglieder wachsen schneller als Mannschaften:** +7,4 % Mitglieder, +3,6 % Mannschaften seit 2024.
2. **Mehr Mitglieder, weniger Teams, außer bei Kindern und Mädchen:** Bei Frauen kommen 242 statt 213 Mitglieder auf eine Mannschaft.
3. **Übergänge als Frühindikator:** Die Übergangsquote sinkt in vier von fünf Regionen, am stärksten im Norden (17,6 % → 14,7 %). Auf ein Mädchen-Team kommen nur noch 0,60 Frauen-Teams statt 0,76.

## Hinweise
Mitglieder umfassen auch passive Mitglieder. Die Mannschaftszahlen im Kinderfußball sind durch neue Spielformen beeinflusst. Die Übergangsquote vergleicht Teams, nicht einzelne Spieler*innen, und ist daher ein Indikator.

## Tools
Power BI Desktop · Power Query (M) · DAX · Excel

Erstellt von Qussai Elbackoush
