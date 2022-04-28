# Analyse der Anfälligkeit für Hangrutschungen in Vietnam

Dieses Projekt wurde im Rahmen des Moduls Geo 403 - Geoinformatikprojekt an der Friedrich-Schiller-Universität Jena von *Felix Fest*, *Tim Grünemay*, *Max Markhardt*, *Justin Volkert* und *Lei Wang* erstellt und basiert auf den Arbeiten des Betreuers des Moduls, *Markus Meinhardt*.

Ziel des Projektes war es, aus verschiedenen räumlichen Parametern die Anfälligkeit für Hangrutschungen eines vorgegebenen Untersuchungsgebietes in Vietnam zu ermitteln. Dies Sollte auf Basis von zwei verschiedenen statistischen Methoden geschehen und mithilfe eines Modelbuilders automatisiert werden. 

Das hier vorgestellte Modell ermöglicht es nach Eingabe der erforderlichen Parameter, die Anfälligkeit für Hangrutschungen eines Gebietes automatisch auf Grundlage der beiden statistischen Indices, Statistical Index (SI) und Weighting Factor (WF) zu bewerten.

Die für die Berechnung verwendeten Parameter setzen sich aus folgenden zusammen:

* Slope
* Aspect
* Curvature
* Curvature_plan
* Curvature_prof
* Distance to Roads
* Landuse
* Lithosphere
* Topographic Wetness Index (TWI)
* Stream Power Index (SPI)
* Precipitation
* Soil

Die für die Berechnung benötigten Eingabeparameter, aus denen auch alle sonstigen benötigten Parameter errechnet werden, sind ein DGM, ein Viewshed des Untersuchungsgebietes, ein Straßenlayer, ein Lithographielayer, ein Landnutzungslayer und ein Bodenartenlayer. 
Als Ergebnis erhält man für jeden Parameter zwei Tabellen aus denen jeweils für jede Klasse des Parameters die SI-Werte und der WF-Wert abegelesen werden können und somit für weitere Analysen genutzt werden können.

Das Modell wurde mit ArcMap 10.8.1 erstellt.
