# Thema 8 - Lab-Übung 1

Tag: Tag 5/7

Thema: AWS Access Management-Funktionen

Übung: IAM Least Privilege Evidence

Verwendetes Go-Deploy-Lab: Lab 05

Bearbeite Lab 5 und erstelle anschließend eine IAM-Matrix für user-1, user-2 und user-3. Die Spalten heißen: IAM User, Group, erlaubter Service, erwartete Grenze und beobachtetes Ergebnis. Trage die vorhandenen Gruppen S3-Support, EC2-Support und EC2-Admin ein und lies die zugehörigen Policies aufmerksam.

Teste mindestens einen erlaubten Zugriff und einen verweigerten Zugriff in einem privaten Browserfenster. Beispiel: user-1 soll S3 sehen können, aber keinen passenden EC2-Zugriff haben. Schreibe die Beobachtung als technischen Nachweis: "Erlaubt: ..., verweigert: ..., Grund laut Gruppe oder Policy: ...". Wenn ein Zugriff anders aussieht als erwartet, dokumentiere zuerst ruhig die sichtbare Meldung und prüfe dann Gruppe und Policy erneut. Verwende die Begriffe IAM User, IAM Group, Policy, Allow, Access Denied und least privilege.
