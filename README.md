# Ueberwachungskamera
Überwachungskamera mit Bewegungserkennung

Das File stream.py läuft auf einem RPi Zero, welcher per Kabel an das Netzwerk angeschlossen ist.
Eine IR-Cam ist ebenfalls kabelgebunden am RPi. Ein zusätzlicher IR-Scheinwerfer sorgt nachts für ausreichend Licht für die Kamera. 
Dieser zusätzliche Scheinwerfer besitzt ein Fotowiderstand, so dass dieser bei ausreichendem Tageslicht nicht unnötig Strom verbraucht. 

Im Haus läuft auf einem weiteren RPi mit der Software "MotionEye", welche bei Bewegungen automatisch 20 Sek. lang ein Video aufzeichnet. Konfigurationsdatei folgt 

Zum Zwecke der Speicherschonung wird demnächst bzw sobald ausreichend Bildmaterial vorhanden ist, eine zusätzliche Gesichterkennung dafür sorgen, dass bestimmte
Gesichter nicht mehr gespeichert werden.
