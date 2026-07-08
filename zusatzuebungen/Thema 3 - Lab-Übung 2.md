# Thema 3 - Lab-Übung 2

Tag: Tag 2

Thema: Prinzipien des AWS Cloud-Designs

Übung: Design for Failure mit Load Balancer

Verwendetes Go-Deploy-Lab: Lab 13

Führe Lab 13 bis zum Application Load Balancer und zur Target Group durch. Zeichne danach eine einfache Skizze: Client oder Browser, Application Load Balancer, Target Group und zwei EC2 Instances. Markiere, dass der Load Balancer HTTP-Traffic auf gesunde Ziele verteilt und selbst keine Anwendung oder Datenbank enthält.

Stoppe wie im Lab eine der EC2 Instances und beobachte danach den Health Status in der Target Group. Dokumentiere, welche Instance noch verwendet wird und welche nicht mehr als gesundes Ziel zählt. Schreibe anschließend drei Sätze mit den Begriffen high availability, health check und single point of failure. Wichtig ist die Begründung: Warum ist eine Architektur mit mehreren gesunden Targets robuster als eine einzelne Instance?
