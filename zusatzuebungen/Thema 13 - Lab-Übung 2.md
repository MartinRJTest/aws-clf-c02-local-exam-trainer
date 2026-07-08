# Thema 13 - Lab-Übung 2

Tag: Tag 12

Thema: AWS-Services für künstliche Intelligenz und maschinelles Lernen sowie Analytik-Services

Übung: S3 als Landing Zone für Daten

Verwendetes Go-Deploy-Lab: Lab 11

Nutze Lab 11 und betrachte den S3 Bucket als einfache Landing Zone für Rohdaten. Lade ein Objekt hoch und notiere Bucket-Name, Objektname und Zweck der Datei. Das Objekt kann im Lab eine einfache Datei sein; wichtig ist die Denkweise: Daten landen zuerst dauerhaft und kostengünstig in S3.

Beschreibe danach eine serverlose Analyse-Pipeline in vier Schritten. Schritt 1: S3 speichert Rohdaten. Schritt 2: AWS Glue katalogisiert oder bereitet Daten vor. Schritt 3: Amazon Athena fragt Daten per SQL direkt aus S3 ab. Schritt 4: Amazon QuickSight visualisiert Ergebnisse in Dashboards. Markiere klar, welche Teile du im Lab wirklich klickst und welche Teile du als Architektur-Erklärung ergänzt. Verwende landing zone, data lake, Glue, Athena und QuickSight.
