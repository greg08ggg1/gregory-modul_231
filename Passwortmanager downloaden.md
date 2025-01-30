# **1. Diskussion: Kriterien für die Wahl eines Passwortmanagers**  
1. **Sicherheit**: Der Passwortmanager muss eine starke Verschlüsselung wie AES-256 haben.  
2. **Benutzerfreundlichkeit**: Die Bedienung soll einfach und übersichtlich sein.  
3. **Plattformen**: Der Passwortmanager muss auf verschiedenen Geräten laufen.  

## **2. Vergleich der Kriterien**  
- Die Kriterien passen grösstenteils.  
- **Open-Source** ist neu dazugekommen, weil ein offener Quellcode hilft, Sicherheitslücken zu finden.  
- **Backup-Möglichkeiten** sind wichtig, um Passwörter nicht zu verlieren.  

## **3. Auswahl des Passwortmanagers**  
### **Gewählte Kriterien:**  
1. **Verschlüsselung**: Starker Algorithmus (z. B. AES-256).  
2. **Open-Source**: Quellcode kann überprüft werden.  
3. **Plattformen**: Windows, Mac, Linux, Android, iOS.  
4. **Cloud-Synchronisation**: Passwörter sicher auf mehreren Geräten verfügbar.  

### **Vergleich:**  

| Passwortmanager | Verschlüsselung  | Open Source | Plattformen                       | Cloud-Synchronisation  | Offline-Nutzung |
|----------------|-----------------|-------------|-----------------------------------|------------------------|----------------|
| **KeePass**    | AES-256         | ✓ Ja        | Windows                           | ✗ Nein                 | ✓ Ja           |
| **KeePassXC**  | AES-256         | ✓ Ja        | Windows, Mac, Linux               | ✗ Nein                 | ✓ Ja           |
| **Bitwarden**  | AES-256         | ✓ Ja        | Windows, Mac, Linux, iOS, Android | ✓ Ja                   | ✓ Ja (lokal)   |
| **LastPass**   | AES-256         | ✗ Nein      | Windows, Mac, Linux, iOS, Android | ✓ Ja                   | ✗ Nein        |

### **Entscheidung: Bitwarden**  
- Bitwarden erfüllt alle Kriterien und kann Passwörter sicher synchronisieren.  

## **4. Überlegungen zur Nutzung von Bitwarden**  
### **Master-Passwort vergessen:**  
- Master-Passwort sicher aufbewahren (z. B. Safe oder Vertrauensperson).  
- Notfall-Zugriff einrichten, falls das Passwort vergessen wird.  

### **Backup der Passwortdatenbank:**  
- Bitwarden kann die Datenbank exportieren und lokal speichern.  
- Sicheres Backup auf externem Laufwerk oder verschlüsseltem Cloud-Speicher machen.  

### **Cloud-Dienstausfall:**  
- Bitwarden kann auch ohne Internet genutzt werden.  
- Möglichkeit, Bitwarden auf einem eigenen Server zu hosten.  
