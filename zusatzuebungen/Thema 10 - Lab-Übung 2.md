# Thema 10 - Lab-Übung 2

Tag: Tag 9

Thema: Methoden zur Bereitstellung und zum Betrieb in der AWS Cloud

Übung: EC2-Betrieb bewusst dokumentieren

Verwendetes Go-Deploy-Lab: Lab 03

Nutze Lab 3 und unterscheide bewusst zwischen Provisioning und Betrieb. Provisioning ist der Moment, in dem du die EC2 Instance mit AMI, Instance Type, Key Pair und Netzwerk startest. Betrieb beginnt danach: Du verbindest dich per SSH, prüfst Erreichbarkeit, liest Metadata und hältst wichtige Informationen nachvollziehbar fest.

Erstelle ein kleines Betriebsblatt für die Instance. Es enthält mindestens Instance ID, Public IP oder Public DNS, Region, AMI oder Betriebssystem, Security Group und verwendetes Key Pair. Ergänze außerdem einen Satz, wofür jede Information später gebraucht wird. Beispiel: Die Security Group wird benötigt, um erlaubte Netzwerkzugriffe zu prüfen. Wenn ein Wert im Lab nicht sichtbar ist, notiere, wo du ihn normalerweise suchen würdest.
