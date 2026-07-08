# Thema 6 - Lab-Übung 2

Tag: Tag 4

Thema: AWS-Modell als geteilte Verantwortung

Übung: Gastbetriebssystem und Kundenpflichten

Verwendetes Go-Deploy-Lab: Lab 02

Nutze die Windows EC2 Instance aus Lab 2 und betrachte sie aus Sicht des Shared Responsibility Model. Verbinde dich per RDP und notiere, was du in der Instanz selbst beeinflussen kannst: Betriebssystemoberfläche, installierte Software, lokale Konfigurationen und Login-Verfahren. Ergänze die Security Group aus der AWS Console als Netzwerkschutz vor der Instanz.

Erstelle danach eine zweispaltige Liste: AWS responsibility und customer responsibility. Bei AWS gehören physische Rechenzentren, Hardware, Strom, Netzwerkgrundlage und Hypervisor in die Liste. Beim Kunden stehen Gastbetriebssystem, Benutzerzugriff, Anwendungen, Daten und Security-Group-Regeln. Schreibe zusätzlich einen Satz, warum EC2 mehr eigene Verantwortung bedeutet als ein vollständig verwalteter Service wie RDS.
