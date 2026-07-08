# Thema 6 - Lab-Übung 1

Tag: Tag 4

Thema: AWS-Modell als geteilte Verantwortung

Übung: VPC und Shared Responsibility

Verwendetes Go-Deploy-Lab: Lab 04

Baue in Lab 4 die VPC, das Subnet, das Internet Gateway, die Route Table und die EC2 Instance auf. Zeichne danach eine einfache Architektur: VPC als Rahmen, darin das Public Subnet, dazu Route Table, Internet Gateway, Security Group und EC2 Instance. Die Zeichnung darf sehr schlicht sein; wichtig ist, dass die Beziehungen erkennbar sind.

Markiere anschließend, was AWS bereitstellt und was du als Kunde konfigurierst. AWS stellt die Cloud-Infrastruktur und die verwalteten Komponenten bereit. Du entscheidest aber über CIDR-Bereich, Subnet, Routing, Security-Group-Regeln und später auch über das Gastbetriebssystem der EC2 Instance. Schreibe drei konkrete Beispiele für Kundenverantwortung und drei Beispiele für AWS-Verantwortung.
