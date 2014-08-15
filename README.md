# Contao form-scr-default

Mit der Erweiterung "e-spin_form-scr-default" k�nnen Standardauswahlen f�r die Formularelemente Selectbox, Checkbox und Radiobutton dynamisch vorgegeben werden.

Die Standardwerte f�r die drei Elemente k�nnen bisher nur fest bzw. statisch vorgebenen werden - bei Elementen wie Textfelder ist es aber m�glich, ein Standardwert �ber ein Insert-Tag dynamisch einzubinden.

Mit der Erweiterung wird die dynamische Vorbelegung auch auf die o.g. Formularfeldtypen erweitert und so kann z.B. bei einer Auswahl an Anreden (Frau | Herr) beim erneuten Aufruf des Formulares erneut gesetzt werden.

F�r den Zugriff auf Werte der Selectbox gibt es zwei Inserttags:

    {{form_rawvalue::<feldname>}} - zieht die Werte aus dem FORM_DATA-Array der aktuellen Session
    {{form_rawvalue_get::<feldname>}} - zieht die Werte aus dem entsprechenden GET-Parameter

Bei dem Einsatz des GET-Parameters sollten Sonderzeichen und Umlaute vermieden werden. Mehrere Werte f�r "multiselect" k�nnen per "Komma separierter Liste" angegeben werden - siehe Beispiel.

Die Vorbelegung ist auch �ber andere geeignete Inserttags m�glich.


Mehr zu Installation und Beispielen f�r form-scr-default unter http://www.e-spin.de/form-scr-default.html