# Thema 12 - Lab-Übung 1

Tag: Tag 11

Thema: AWS-Computing-Services, -Datenbank-Services, -Netzwerkservices und -Speicherservices

Übung: Compute und Networking zusammendenken

Verwendetes Go-Deploy-Lab: Lab 13

Nutze Lab 13 und dokumentiere die Beziehung zwischen EC2 Instances, Security Group, Target Group und Application Load Balancer. Erstelle eine kleine Tabelle mit den Spalten Baustein, Kategorie und Aufgabe. EC2 gehört zu Compute, Security Groups und Load Balancing gehören zum Netzwerk- und Zugriffskontext, die Target Group verbindet den Load Balancer mit konkreten Zielen.

Teste wie im Lab den Zugriff über den Load Balancer und beobachte die registrierten Targets. Schreibe anschließend einen Absatz, der die Zuständigkeiten sauber trennt: Die EC2 Instances führen die Anwendung aus, die Security Group kontrolliert erlaubte Verbindungen, die Target Group sammelt Ziele, und der Application Load Balancer verteilt HTTP-Traffic. Verwende die Begriffe Compute, Networking, target group und health check.
