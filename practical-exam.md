# Praktische Prüfung


### Checkliste für den Prüfungstag
- Ausweisdokument
- Präsentation
- Plan B, falls die Technik nicht funktioniert…z.B. Präsentation ausgedruckt 
- Notebook, Beamer, Netzteil, sowie sämtliche Adapter
- Presenter 
- Zettel und Stift
- Exemplar eurer Dokumentation
- Ausbildungsnachweise!


# allgemeine fragen zum docu

### Was ist eine API? 
Eine API (Application Programming Interface) ist ein Satz von Befehlen, Funktionen, Protokollen und Objekten, die Programmierer verwenden können, um eine Software zu erstellen oder mit einem externen System zu interagieren. Sie stellt Entwicklern Standardbefehle für die Ausführung allgemeiner Operationen zur Verfügung, so dass Codes nicht von Grund auf neu geschrieben werden müssen.

Die API – auch Programmierstelle genannt- ermöglicht es demnach Anwendungen miteinander zu kommunizieren. Die API ist nicht die Datenbank oder gar der Server, sondern der Code, der die Zugangspunkte für den Server regelt und die Kommunikation ermöglicht.

Somit wird der Datenaustausch zwischen verschiedenen Systemen um ein Vielfaches beschleunigt und vereinfacht.

### Was ist ein REST-API?
steht für „Representational State Transfer - Application Programming Interface“. Sie macht den Austausch von Informationen möglich, wenn diese sich auf unterschiedlichen Systemen befinden. Im Zeitalter von Desktop-PCs und mobilen Geräten wie Tablets oder Smartphones trifft man oft auf solche unterschiedlichen Systeme, die den Einsatz von REST-API notwendig machen. Man spricht bei REST-API auch von der Maschine-Maschine-Kommunikation, da die verschiedenen Systeme und Geräte zusammengebracht werden und gewissermaßen die „gleiche Sprache“ sprechen. Dank REST-API ist es möglich, Informationen und Aufgaben auf verschiedene Server zu verteilen und mit Hilfe eines HTTP-Requests anzufordern. Der HTTP-Request setzt sich aus dem Endpoint und den entsprechenden Parametern zusammen
 
### Was ist ein FRAMEWORK?
In der Softwareentwicklung ist ein Framework ein Entwicklungsrahmen, der dem Anwendungsprogrammierer zur Verfügung steht, um die grundlegende Architektur der Software zu bestimmen. 

### Library vs FRAMEWORK?
Bei einer Library ruft der Entwickler innerhalb seines Codes die Klassen und Funktionen der Bibliothek direkt auf. Hingegen ruft das Framework, eine bestimme Form der Library, vorgesehene Funktionen wenn nötig selbständig auf. Damit folgt es dem Paradigma „Inversion of Control“.

### Was ist Docker?
Docker legt Programme samt ihrer Abhängigkeiten in Images ab. Diese bilden die Basis für virtualisierte Container, die auf nahezu jedem Betriebssystem lauffähig sind. So werden Anwendungen portabel und unkompliziert, sei es während der Entwicklung oder beim Skalieren von SaaS-Clustern.

### was ist Kafka?
Kafka wird häufig in Echtzeit-Streaming-Datenarchitekturen verwendet, um Echtzeitanalysen bereitzustellen. Laut Entwickler wurde die Software nach dem Autor Franz Kafka benannt, weil sie ein für das Schreiben optimiertes System darstellt. Die Software bietet den Anwendern hauptsächlich drei Funktionen:
Veröffentlichung und Abonnement von Datenströmen
Effektives Speichern von Datenströmen
Verarbeiten von Streams in Echtzeit
("Apache Kafka ist Pub-Sub-Messaging, das als verteiltes Commit-Log neu gedacht ist.
Kafka ist ein verteilter, partitionierter, replizierter Commit-Log-Dienst.)

### Was sind die verschiedenen Komponenten in Kafka?
Topic, Producer, Consumer, Broker

### Was ist ein Topic?
Ein Datenstrom, der einer Tabelle in einer Datenbank ähnlich ist (ohne alle Beschränkungen)

### Was ist ein producer?
Producer geben Mitteilungen aus und veröffentlichen Nachrichten in einem Kafka-Topic

### Was ist ein consumer?
Ein consumer abonniert ein oder mehrere Topics und liest und verarbeitet auch Nachrichten aus dem Topic

### Was ist ein consumer group?
Ein oder mehrere consumers, die gemeinsam einen Satz von abonnierten topics konsumieren.

### Was ist ein broker?
Ein Kafka-Broker verwaltet die Speicherung von Nachrichten in einem oder mehreren Topic(s). Er wird auch als Kafka-Server oder -Knoten bezeichnet

### Was ist die Rolle des Offsets?
Eine fortlaufende ID-Nummer, die den Nachrichten in den Partitionen zugewiesen wird, um jede Nachricht in der Partition eindeutig zu identifizieren

### Was ist die Aufgabe von ZooKeeper?
Die Hauptaufgabe von Zookeeper besteht hier darin, die Koordination zwischen verschiedenen Knoten in einem Cluster herzustellen. Zookeeper wird auch für die Wiederherstellung eines zuvor festgelegten Offsets verwendet, wenn ein Knoten ausfällt.

### Auflistung einiger Kafka-Benutzerfälle ?
Messaging-System, Aktivitätsverfolgung, Sammeln von Metriken von vielen verschiedenen Orten, Sammeln von Anwendungsprotokollen, Entkopplung von Systemabhängigkeiten

### Wie wird ein Topic identifiziert?
Durch seinen Namen

### Was ist ein partition?
Ein Abschnitt eines topic, in dem Datensätze gespeichert werden. Er ermöglicht die Skalierung eines topics über viele Server und erlaubt parallele Verbraucher.

### Sind die Daten geordnet, sobald sie in einem topic veröffentlicht wurden?
Ordnung wird nur innerhalb einer Partition garantiert, nicht über Partitionen hinweg

### Was ist ein Cluster?
Ein Cluster besteht aus mehreren Brokern (Servern)

### Wie wird ein Broker identifiziert?
Ein Broker wird durch seine ID identifiziert

### Wie stellt man eine Verbindung zu einem Kafka-Cluster her?
Wenn Sie sich mit einem beliebigen Broker verbinden, werden Sie mit dem gesamten Cluster verbunden

### Was ist die empfohlene Mindestanzahl an Brokern, mit der man beginnen sollte?
3

# design-patterns

### Abstract Factory?
Bereitstellen einer Schnittstelle zum Erstellen von Familien verwandter oder abhängiger Objekte ohne Angabe ihrer konkreten Klassen

![alt text](https://o.quizlet.com/oEI.1Revehh7tMKMVZig7Q.png)


### Chain of Responsibility?
Das Chain of Responsibility-Muster ist ein Entwurfsmuster, das aus einer Quelle von Befehlsobjekten und einer Reihe von Verarbeitungsobjekten besteht. Jedes Verarbeitungsobjekt enthält eine Logik, die die Typen von Befehlsobjekten definiert, die es verarbeiten kann; der Rest wird an das nächste Verarbeitungsobjekt in der Kette weitergegeben. Es gibt auch einen Mechanismus zum Hinzufügen neuer Verarbeitungsobjekte am Ende dieser Kette.

![alt text](https://o.quizlet.com/9gDvx4iF3f0iD3hzMCRN8Q.png)


### Adapter?
Das Adapter-Muster ist ein Software-Entwurfsmuster (auch bekannt als Wrapper, eine alternative Bezeichnung, die mit dem Decorator-Muster geteilt wird), das es ermöglicht, die Schnittstelle einer bestehenden Klasse als eine andere Schnittstelle zu verwenden. Es wird oft verwendet, um bestehende Klassen mit anderen zusammenarbeiten zu lassen, ohne ihren Quellcode zu verändern.

![alt text](https://o.quizlet.com/lQCc9wt.4pGuGCmOz9e5gA.jpg)


### Memento?
Das Memento-Pattern ist ein Software-Entwurfsmuster, das die Möglichkeit bietet, den vorherigen Zustand eines Objekts wiederherzustellen (Rückgängigmachen über Rollback).
Das Memento-Pattern wird mit drei Objekten implementiert: dem Originator, einem Caretaker und einem Memento.

![alt text](https://o.quizlet.com/44JQkR10.9VGpDxZd4D75A.png)


### Bridge pattern?
Das Bridge-Pattern ist ein Entwurfsmuster in der Softwaretechnik, das dazu dient, "eine Abstraktion von ihrer Implementierung zu entkoppeln, so dass beide unabhängig voneinander variieren können", eingeführt von der Gang of Four (GoF). Die Brücke verwendet Kapselung, Aggregation und kann Vererbung verwenden, um Verantwortlichkeiten in verschiedene Klassen zu trennen.

![alt text](https://o.quizlet.com/SyJ4lvDiCHgRBvfS8cMM9A.png)


### Singleton pattern?
In der Softwaretechnik ist das Singleton-Pattern ein Software-Entwurfsmuster, das die Instanziierung einer Klasse auf ein Objekt einschränkt. Dies ist nützlich, wenn genau ein Objekt benötigt wird, um Aktionen im gesamten System zu koordinieren. Das Konzept wird manchmal auf Systeme verallgemeinert, die effizienter arbeiten, wenn nur ein Objekt existiert, oder die die Instanziierung auf eine bestimmte Anzahl von Objekten beschränken. Der Begriff stammt aus dem mathematischen Konzept des Singletons.

![alt text](https://o.quizlet.com/VE0srKpNDQ7tU6b.wvCUvA.png)


# von schriftlichen Prüfungen 2021


### Level-Support als mehrstufiges System
First-Level-Support
- Der First-Level-Support ist die erste Anlaufstelle für alle eingehenden Unterstützungsfragen. Der Mitarbeiter ist für deren vollständige Erfassung inklusive aller erforderlichen Zusatzinformationen zuständig und bearbeitet sie nach seinem Kenntnisstand weitestgehend selbstständig.

Second-Level-Support
- Der Second-Level-Support unterstützt den First-Level-Support durch Übernahme komplexerer Anfragen und durch Weiterbildung am Arbeitsplatz. Neu erarbeitete Lösungen werden in Wissensdatenbanken eingepflegt, um das Wissen für den First-Level-Support nutzbar zu machen.

Third-Level-Support
- Der Third-Level-Support setzt sich aus Spezialisten einzelner Fachabteilungen und/oder des Herstellers zusammen und stellt so die höchste fachliche Ebene innerhalb einer Support-Organisation dar.


### Argumente für ein Ticketsystem
– Nachvollziehbarkeit aller Anfragen
– Systematische Bearbeitung von Anfragen
– Einhaltung von Service-Level-Agreements
– Automatisierung von Antworten und Statusmeldungen
– Kostenüberwachung für die Bearbeitung von Anfragen
– Steuerung von Technikereinsätzen und Helpdesk-Personal


### Raid 5 und 6
- Bei einem RAID-6-Verbund werden im Vergleich zu einem RAID-5-Verbund zusätzliche (über den Plattenverbund verteilte) Parity Informationen angelegt. Diese zusätzlichen Parity Informationen bieten den Vorteil, dass auch beim zeitgleichen Ausfall von zwei Festplatten dennoch ein verlustfreies Rebuild aller Daten möglich ist.

- In einem RAID-5-Verbund darf zeitgleich immer nur eine Festplatte ausfallen, um alle Daten verlustfrei wiederherstellen zu können.


### Ergonomischen Raid
– Bestimmte, energieoptimierte Festplatten wählen
– RAID-Level mit günstigem Verhältnis von Nettospeicherkapazität zu Bruttospeicherkapazität wählen
– Festplatten mit niedriger Drehzahl wählen (5.400 U/min statt 7.200 U/min)
– 2,5‘‘ statt 3,5“ Festplatten verwenden
– Festplatten im Energiesparmodus betreiben bzw. Energieoptionen anpassen
– Festplatten mit native command queuing einsetzen
– Verwendung von SSDs


### Warum VLAN
– Einrichtung logischer Gruppen innerhalb der physikalischen Topologie möglich
– Bessere Lastverteilung möglich
– Höhere Flexibilität durch einfache Änderung von Gruppenzugehörigkeiten
– Einfachere Softwarekonfiguration durch Software für die Gruppen
– Erhöhte Sicherheit durch Gruppierung (Subnetze)
– Weniger Kollisionsbereiche (Broadcastdomänen)
– Priorisierung des Datenverkehrs möglich

### ADSL/VDSL vs SDSL
– Asymmetrie der Bandbreite zwischen Up und Download

– Für die Videotelefonie werden gleichermaßen hohe Bandbreiten für Up- und Download benötigt, da es sich um Echtzeitdatenübertragung handelt.


### Bedrohungen die da gegen ein echt zeit schutz gibt

– Phishing
– Spyware
– Malware
– Network Intrusion


### VPN Verbindungsarten
– site-to-site
– client-to-site (end-to-side)


### Klasse
Klasse: Definiert eine Kategorie von Objekten mit gleichen Attributen und Methoden. Sie stellt einen Bauplan für Objekte dar. 


### Objekt
Objekt: Ein Exemplar (lnstanz) einer Klasse


### Aggregation
Eine Aggregation ist eine Teil-Ganze-Beziehung, bei der die Teile auch unabhängig vom Ganzen existieren können.


### Personenbezogene Daten Betroffenenrechte
– Recht auf Auskunft
– Recht auf Berichtigung
– Recht auf Löschung
– Recht auf Datenübertragbarkeit
– Recht auf Widerspruch und Widerruf
– Recht auf Einschränkung der Verarbeitung


### Social Engineering
Der Begriff Social Engineering bezeichnet eine Vorgehensweise, bei der die Schwachstelle Mensch ausgenutzt wird. Oft werden dabei Mitarbeiter eines Unternehmens mit einem Trick überredet, die normalen Sicherheitsvorkehrungen zu umgehen und sensible Informationen preiszugeben.


### Aufgabe von Antivirenprogramme
Antivirenprogramme erkennen Computerviren anhand bekannter Muster im Programmcode die in sogenannten Virensignaturen hinterlegt sind oder anhand typischer Verhaltensmuster. Sie informieren den Benutzer, isolieren befallene Programme (Quarantäne) oder löschen befallene Programme. Der Einsatz eines Antivirusprogramms bedeutet keine 100%ige Sicherheit und muss durch umsichtiges Verhalten ergänzt werden.


### Daten verlust Ursachen 
– Fehlbedienung
– Elementarschaden, Wasserschaden, Brand
– Technischer Defekt, Stromausfall beim Schreiben, Festplattendefekt


### Differentielles Back up
– Voll-Back-up
– Des Weiteren Sicherung aller Dateien, die seit dem letzten Voll-Back-up geändert oder neu angelegt wurden


### Inkrementelles back up
– Voll-Back-up
– Des Weiteren Sicherung der Dateien, die nach der jeweils letzten Sicherung geändert oder neu angelegt wurden


### Asymmetrischen Verschlüsselung privaten und offentlichen schlüssel aufgabe
– Der öffentliche Schlüssel ermöglicht es jedem, Daten für den Besitzer des privaten Schlüssels zu verschlüsseln. 
– Der private Schlüssel ermöglicht es seinem Besitzer, mit dem öffentlichen Schlüssel verschlüsselte Daten zu entschlüsseln.
### links
- [Fachinformatiker - Allgemein](https://quizlet.com/de/195203566/fiae-fachinformatiker-anwendungsentwicklung-flash-cards/).
- [Fachinformatiker - Allgemein2](https://quizlet.com/de/529531857/prufungsvorbereitung-fachinformatiker-anwendungsentwicklung-flash-cards/).
- [Fachinformatiker - Allgemein3](https://www.repetico.de/cardset-cards-580931-GH1_-Fachinformatiker-Anwendungsentwicklung).
- [Fachinformatiker - Fachbegriffe](https://www.repetico.de/cardset-cards-619243-Fachinformatiker---Fachbegriffe).
- [OSI-Schichten](https://www.repetico.de/cardset-cards-1371219-OSI-Schichten).
- [Datenschutz](https://www.karteikarte.com/lesson/121897/datenschutz).
- [Sicherheit](https://www.karteikarte.com/lesson/73762/sicherheit-informatik).
- [Rechtsformen](https://www.aachen.ihk.de/blueprint/servlet/resource/blob/605672/ab60155705a7ae93efac23472fabee8a/rechtsformen-uebersichtstabelle-data.pdf).
- [Fragen aus dem Fachgespräch Fachinformatiker Anwendungsentwicklung](https://kiloherz.info/2016/05/fragen-aus-dem-fachgespraech-fachinformatiker-anwendungsentwicklung/).

