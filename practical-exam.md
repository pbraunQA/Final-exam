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

### was ist Kafka?
Kafka wird häufig in Echtzeit-Streaming-Datenarchitekturen verwendet, um Echtzeitanalysen bereitzustellen. Laut Entwickler wurde die Software nach dem Autor Franz Kafka benannt, weil sie ein für das Schreiben optimiertes System darstellt. Die Software bietet den Anwendern hauptsächlich drei Funktionen:
Veröffentlichung und Abonnement von Datenströmen
Effektives Speichern von Datenströmen
Verarbeiten von Streams in Echtzeit

### Was ist Docker?
Docker legt Programme samt ihrer Abhängigkeiten in Images ab. Diese bilden die Basis für virtualisierte Container, die auf nahezu jedem Betriebssystem lauffähig sind. So werden Anwendungen portabel und unkompliziert, sei es während der Entwicklung oder beim Skalieren von SaaS-Clustern.

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

