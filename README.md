Dies ist die Simulation einer Torsteuerung mit CoDeSYS 3.5.20

![Torsteuerung](https://user-images.githubusercontent.com/76168072/144604168-7d970285-196c-42fd-b6a5-02a4e0cba64d.jpg)

Die Datei Torsteuerung.projekt enthält die Visualisierung und deren Logik.

Das SPS Programm zur auswertung der Taster und zur Ansteuerung des Torantriebs soll erarbeitet werden,
als EIN/AUSgänge sind die Globalen Variablen definiert.

	// Tor_öffnen     	Q1: BOOL;
	// Tor_schliesen  	Q2: BOOL;
	// End_auf      	B0: BOOL;
	// End_zu       	B1: BOOL;
	// NOT_AUS        	S0: BOOL := TRUE;
	// Taster_Auf    	S1: BOOL;
	// Taster_Zu    	S2: BOOL;
	// Taster_Aus   	S3: BOOL := TRUE;


Video der Steuerung
https://www.youtube.com/watch?v=_owyrw4OeZ8
