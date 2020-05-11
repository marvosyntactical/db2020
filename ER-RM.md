# Entity-Relationship Model vs. Relationship Model:

1. Entity-Relationship (**ER**) ist das Flowchart Modell aus Foliensaetzen 3 und 4;
es basiert hauptsaechlich auf Entities, zwischen denen dann unterschiedlich stellige Beziehungen mit unterschiedlicher Kardinalitaet bestehen.
2. Das **RM** wird in Foliensatz 4 eingeführt und hat als strukturelle Darstellungseinheit nur noch Relationships; Entities aus **ER** werden ebenfalls auf relationships gemappt. Jede relationship hat Attribute gemaess dem **ER** Modell, wobei eine untermenge hiervon die Schluesselmenge ist, die aus den Schluesseln der entsprechenden Entitaeten direkt uebernommen wird (bei Relation die einer Entity entspricht) bzw. sich nach entsprechend der Kardinalitaet eindeutig aus den Schluesselmengen der teilnehmenden Entities ergibt (bei Relation die einer Relation entspricht).
2. Hier ist der Algo: ![alt text][ertorm]




3. Frage: Es gibt also eine Funktion **ER** -> **RM** ... gibt es auch eine Funktion **RM** -> **ER**?
  * Sieht so aus als ob die Funktion bijektiv ist; aus dem **RM** laesst sich eindeutig ein **ER**-``flowchart" rekonstruieren 



---
Resources:


[ertorm]: https://github.com/marvosyntactical/db2020/blob/master/er-to-rm.png  "ER to RM Table"

