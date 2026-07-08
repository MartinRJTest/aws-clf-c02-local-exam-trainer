# Thema 11 - Lab-Übung 2

Tag: Tag 10

Thema: Globale AWS-Infrastruktur

Übung: Subnetz und Availability Zone verknüpfen

Verwendetes Go-Deploy-Lab: Lab 04

Nutze Lab 4 und achte beim Erstellen des Subnets genau auf die Availability Zone. Notiere den VPC-Namen, den CIDR-Bereich, den Subnet-Namen und die AZ, in der das Subnet liegt. Halte fest: Eine VPC gehört zu einer Region, ein Subnet liegt in genau einer Availability Zone.

Formuliere danach eine kurze Empfehlung für Produktivsysteme. Ein einzelnes Subnet in einer einzelnen AZ kann für ein Lernlab ausreichen, ist aber kein vollständiges Hochverfügbarkeitsdesign. Für produktive Systeme plant man wichtige Komponenten häufig über mehrere Availability Zones. Schreibe zwei Beispiele: Webserver hinter Load Balancer in mehreren AZs und Datenbank mit Multi-AZ-Option. Wenn das Lab nur eine AZ nutzt, beschreibe die Erweiterung als Skizze.
