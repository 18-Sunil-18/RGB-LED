# RGB-LED

Eine RGB-LED ansteuern
Aufgabe: Eine RGB LED soll in verschiedenen Farben leuchten.

Material: Arduino / eine RGB-LED / 3x Widerstand mit 200 Ohm / Breadboard / Kabel

Was ist eine RGB-LED? Eine RGB-LED ist eine LED die in verschiedenen Farben leuchten kann. Hinter der Bezeichnung RGB verbergen sich die Farbei „Rot“, „Grün“ und „Blau“. Die LED besteht im Inneren aus drei einzeln ansteuerbaren LEDS, die in den drei Farben leuchten. Deswegen hat eine RGB-LED auch so viele Beinchen, nämlich genau vier. Das längste der vier Beinchen ist je nach Version die gemeinsame Anode (+) bzw. Kathode (-). Mit den drei kürzeren Beinchen werden die einzelnen Farben der RGB-LED angesteuert.

Version a: „Common cathode“ – Das längste Beinchen der LED ist „-“ und die drei kürzeren Beinchen werden über „+“ (Spannung) angesteuert.

Version b) „Common anode“ – Das längste Beinchen der LED ist „+“ und die drei kürzeren Beinchen werden über „-“ (GND) angesteuert.

Durch eine Mischung der Farben können noch sehr viele weitere Farben erzeugt werden. Zum Beispiel entsteht durch die Ansteuerung der Farben „Blau“ und „Grün“ die Farbe „Türkis“.

Welche Version man selber hat, findet man durch einfaches umstecken von „+“ und „-“ an der LED heraus (Info: Eine LED leuchtet nur bei richtigem Anschluss).
