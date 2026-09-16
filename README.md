Benötigtes Wissen/Skills für die Benutzung von AR.js


HTML- Programmiersprache für die Erstellung von Websites.

	->Gutes youtube Tutorial https://www.youtube.com/watch?v=HfTXHrWMGVY&list=PLZlA0Gpn_vH-cEDOofOujFIknfZZpIk3a 


Hosting der Website- Hier gibt es einige möglichkeiten (Muss eine Https sein, Http reicht nicht aus):

	->Node.js: hosting eines lokalen servers (so hab ich es gemacht)
		->Gutes youtube Tutorial https://www.youtube.com/watch?v=VShtPwEkDD0 

	->Xampp: hosting eines lokalen servers

	->github: hosting einer static Website 
		->Gutes youtube Tutorial https://www.youtube.com/watch?v=e5AwNU3Y2es

    ->Wenn du einen Anderen Service oder Weg benutzen willst die Website zu hosten ist das auch völlig in ordnung.

A-Frame Webframework zum Bau von 3D/AR/VR erlebnissen:
	
	->A-Frame Website https://aframe.io/docs/1.8.0/introduction/

	->A-Frame youtube tutorial https://www.youtube.com/watch?v=ktjMCanKNLk&list=PL8MkBHej75fJD-HveDzm4xKrciC5VfYuV
		-> Videos 1-6 erklären die einfachsten Grundlagen die benötigt werden

Kleine Tipps:

	-> STRG+ALT+I öffnet den A-Frame Inspector, damit kann man herausfinden ob Marker erkannt werden
	-> Was auch immer man in AR zeigen will ist ein child-Entity zu dem entsprechenden Marker
	-> Die 3D modelle müssen mit <a-entity> aufgerufen werden, <a-obj-model> funktioniert nicht
	-> Die X-Y-Z-Ausrichtung mit dem "position-component" ist objektbezogen und nicht global,
	   d.h wenn das 3D-Modell mit dem "rotation-component" gedreht wird drehen sich die Achsen auch mit.
