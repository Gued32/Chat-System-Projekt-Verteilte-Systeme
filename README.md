# Chat-System – Projekt Verteilte Systeme (Projektbeschreibung)

## 📌 Projektübersicht

Dieses Projekt implementiert ein verteiltes Chat-System, in dem mehrere Clients über einen zentralen Server in Echtzeit Nachrichten austauschen. Ziel ist die Entwicklung einer robusten und skalierbaren Anwendung zur Demonstration grundlegender Kommunikationsmechanismen in verteilten Systemen.

---

## 🎯 Zielsetzung

Das Projekt dient der praktischen Umsetzung zentraler Konzepte verteilter Systeme, insbesondere:

* direkte Netzwerkkommunikation zwischen Prozessen
* parallele Verarbeitung mehrerer Client-Verbindungen
* Umsetzung einer Client-Server-Architektur

---

## 🏗️ Systemarchitektur

Die Anwendung besteht aus folgenden Komponenten:

* **Chat-Server (Python):**
  Verwaltet Client-Verbindungen, empfängt Nachrichten und verteilt diese an alle verbundenen Clients

* **Clients (Python):**
  Stellen die Benutzeroberfläche dar und ermöglichen das Senden und Empfangen von Nachrichten

* **Kommunikationsschicht:**
  Realisiert über TCP-Sockets für zuverlässige Datenübertragung

---

## 🔄 Systemablauf

1. Clients stellen eine Verbindung zum Server her
2. Ein Client sendet eine Nachricht an den Server
3. Der Server empfängt und verarbeitet die Nachricht
4. Die Nachricht wird an alle verbundenen Clients weitergeleitet (Broadcast)
5. Clients empfangen und zeigen die Nachrichten an

---

## ⚙️ Verwendete Technologien

* **TCP-Sockets** – Netzwerkkommunikation zwischen Client und Server
* **Threads** – parallele Verarbeitung mehrerer Client-Verbindungen
* **Python** – Implementierung von Server und Clients

---

## 🚀 Funktionalitäten

### Basisfunktionen

* Unterstützung mehrerer gleichzeitiger Clients
* Echtzeit-Kommunikation
* Benutzeridentifikation über Namen
* Broadcast-System zur Verteilung von Nachrichten

### Erweiterungen (optional)

* Private Nachrichten zwischen Clients
* Unterstützung von Chat-Räumen (Channels)
* Speicherung von Nachrichtenverläufen

---

## 👥 Team

Das Projekt wird im Rahmen einer Teamarbeit mit 1 Studierende umgesetzt.

---

## ▶️ Ausführung

1. Starten des Chat-Servers
2. Starten mehrerer Clients
3. Eingabe und Austausch von Nachrichten in Echtzeit

---

## 📂 Projektstruktur

```id="s9t4fz"
/server   # Implementierung des Chat-Servers
/client   # Implementierung der Chat-Clients
```


---

