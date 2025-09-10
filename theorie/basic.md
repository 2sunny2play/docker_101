# Docker 101

## Image vs. Container

+ Docker-Image **statische Datei, alle notwendigen Anweisungen, um eine Anwendung auszuführen**. wie eine Vorlage eines Dateisystems und der darin enthaltenen Software. Ein **Image ist unveränderlich** wird verwendet, um Container zu erstellen.

+ Docker-Container **laufende Instanz eines Images**. Es ist eine isolierte Umgebung, in der die Anwendung ausgeführt wird. Container sind **flüchtig** und können gestartet, gestoppt, gelöscht und neu erstellt werden. 
Container = Image + writable Layer + laufender Prozess (meist ein „PID 1“). Wenn der Hauptprozess endet, endet der Container

