# Passwort-Generator (lokal & datenschutzfreundlich)

🔗 **Live-Version:**  
https://sicherheits-tools.de/werkzeuge/passwort/

## Kurzbeschreibung
Dieser Passwort-Generator läuft vollständig lokal im Browser.
Die Passworterzeugung erfolgt clientseitig, ohne Datenübertragung
an Server oder Drittanbieter.

Das Tool richtet sich an Privatpersonen und Freelancer,
die einfache Sicherheitswerkzeuge ohne Cloud-Abhängigkeit nutzen möchten.

## Technische Funktionsweise
- Clientseitige Ausführung (JavaScript im Browser)
- Nutzung der Web Crypto API (`window.crypto.getRandomValues`)
- Keine externen Skripte
- Keine Netzwerk-Requests
- Offline nutzbar (nach Seitenaufruf)

## Datenschutz
- Keine Speicherung
- Kein Tracking
- Keine Analyse-Tools
- Keine Datenübertragung

## Quellcode & Offenlegung

Der vollständige produktive Quellcode dieses Tools ist bewusst
nicht öffentlich verfügbar.

**Gründe:**
- Schutz vor ungeprüfter Weiterverbreitung
- Vermeidung manipulierter Kopien
- Sicherstellung, dass Nutzer stets die Originalversion verwenden

Die technische Funktionsweise ist oben beschrieben und kann
direkt in den Browser-Entwicklertools überprüft werden
(Netzwerk-Tab bleibt leer).

## Beispiel (vereinfachtes Prinzip)

```js
const array = new Uint32Array(1);
window.crypto.getRandomValues(array);

```

## Rechtlicher Hinweis

© 2026 [sicherheits-tools.de](https://sicherheits-tools.de)  
Alle Rechte vorbehalten.

Dieses Repository dient ausschließlich der technischen
Dokumentation und Referenz.
