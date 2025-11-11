# Arbeitsauftrag
Beobachte das Objektspiel zum *second hand shop* und beantworte folgende Fragen:
1. Wie entwickelt sich die Länge der Datenstruktur? Spielt die Länge der Datenstruktur eine Rolle zur Verwaltung der Elemente?
Personen stellen sich in der Warteschlange an und bekommen ihre Produkte nacheinander. Die Länge der Datenstruktur spielt dabei eine große Rolle, da die Länge der Warteschlange sich immer ändert, je nachdem wie viele Personen anstehen. 

2. Wie werden neue Elemente hinzugefügt?
Eine Person stellt sich in die Warteschlange um ihr Produkt abzuholen.

3. Auf welche Elemente wird Zugegriffen?
Auf die Personen in der Warteschlange und auf die Produkte.

4. Welche Beziehungen der Elemente gibt es untereinander?
Personen haben ihre Bestellbestätigung und kennen die Produkte. Jedes Element muss seinen Nachfolger kennen. 

5. Welche Elemente müsste ein Verwaltungselement kennen?
Ein Verwaltungselement müsste die Warteschlange und die Produkte kennen. 

6. Nach welchem Prinzip arbeitet die Datenstruktur? Wie nennt man eine solche Datenstruktur?
Die Person an vorderster Stelle wird bedient, bekommt ihr Produkt und verlässt die Warteschlange. FIFO-Prinzip  

6. Welche (Verwaltungs)Operationen sind für diese Datenstruktur sinnvoll?
- aufrücken
- entfernen
- hinzufügen

