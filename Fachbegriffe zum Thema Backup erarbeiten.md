# 1. Datensicherungsziele, Datenkompression
- **Backup-Ziele**: Externe Festplatten, Netzwerk-Speicher, Cloud-Dienste.
- **Kompressionsverfahren**: ZIP, RAR, deduplizierte Datenkompression.
- **Wichtigkeit der Kompression**: Besonders bei Image-Backups wichtig, da die Kompression den benötigten Speicherplatz reduziert und das Backup schneller macht.

# 2. Vollsicherung, Differenzielle Sicherung, Inkrementelle Sicherung
- **Vollsicherung**: Sichert alle Daten vollständig.
- **Differenzielle Sicherung**: Sichert nur die Änderungen seit der letzten Vollsicherung.
- **Inkrementelle Sicherung**: Sichert nur die Änderungen seit der letzten Sicherung (egal ob Voll- oder Inkrementell).
- **Grafik**: Du kannst eine Grafik erstellen, die zeigt, wie diese Sicherungen im Vergleich zueinander arbeiten.
- **Benötigt Vollbackup?**: Ja, für differenzielle und inkrementelle Sicherung ist ein Vollbackup als Grundlage erforderlich.
- **Vor- und Nachteile**: 
  - **Vollsicherung**: Langsame Sicherung, aber einfach zu wiederherstellen.
  - **Differenzielle Sicherung**: Schnellere Wiederherstellung als inkrementell, benötigt aber mehr Speicher als inkrementell.
  - **Inkrementelle Sicherung**: Sehr schnell und spart Speicher, aber langsamere Wiederherstellung.

# 3. Block-Level vs. File-Level Backup
- **Block-Level**: Sichert Daten blockweise, ideal für komplette Festplattenabbilder.
- **File-Level**: Sichert einzelne Dateien, ideal für spezifische Ordner wie den Home-Ordner.
- **Besseres Verfahren für Image-Backup**: Block-Level eignet sich besser, weil es die Festplatte auf Blockebene abbildet.
- **Besseres Verfahren für Home-Ordner**: File-Level ist besser, da nur Dateien gesichert werden.

# 4. Hot Backup vs. Cold Backup
- **Hot Backup**: Wird während des Betriebs erstellt, ohne den Server herunterzufahren. Wird z.B. bei Cloud-Diensten verwendet.
- **Cold Backup**: Das System muss heruntergefahren werden. Wird z.B. bei sehr kritischen Systemen genutzt, die nicht ständig laufen müssen.

# 5. Datensicherungsstrategie
- **Häufigkeit**: Jeden Tag, jede Woche oder nach wichtigen Änderungen.
- **Mehrere Datenträger**: 3-2-1 Regel: 3 Kopien der Daten, 2 verschiedene Medien, 1 Kopie offline oder in der Cloud.
- **Turm von Hanoi**: Eine Methode, um Daten auf verschiedenen Medien zu sichern.
