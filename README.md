# Interaktive Detektivarbeit
#### (*Semesterendprojekt SoSe22 - Physical Computing*)
 &nbsp;


---
### **Konzept**
---
Schlüpfe in die Rolle des Detektiven XY und löse den Mord, der sich innerhalb eines Raum abgespielt hat. 
Alle Antworten befinden sich in diesem einen Zimmer. Suche nach Hinweisen und untersuche diese, um Tonspuren oder visuelle Effekte zu aktivieren, die auf die Aufklärung deuten könnten.
Damit der Detektiv eine logische Gedankenkette bilden kann, ist es wichtig die Komponenten in der korreten Abfolge zu untersuchen.

---
### **Welche Funktionen soll es geben?**
---

- Sensorsystem :
  z.B. Kapazitiver Sensor (Berührungsloser Schalter), Fotozelle (Lichtmesseung), Piezo Rim Sensor (Vibrationsmessung)
- Audioausgabe
  (durch Lautsprecher)
- Speichersystem
  Ablage der Audiodateien? Von Pc abrufen?
  
 &nbsp;
 
 ---
### **Vergleiche der Sensortypen**
---

**Kapazitiver Sensor**

Was ist ein kapazitiver Sensor? 
Kapazitive Annäherung Sensoren (KAS) sind berührungslose Schalter.
Sie erfassen leitende- und nichtleitende Materialien wie Metalle, Kunststoffe, Holz, Flüssigkeiten, Pasten sowie Schüttgüter. 
Selbst Messungen durch nichtleitende Materialien sind möglich.

Genaue Funktionsweise:
[Kapazitiver Sensor](//www.baumer.com/ch/de/service-support/funktionsweise/funktionsweise-und-technologie-von-kapazitiven-sensoren/a/Know-how_Function_Capacitive-sensors)

**Fotozelle**

Was macht eine Fotozelle?
Fällt Licht in die Fotozelle, dann löst es aus der Oberfläche der Katode infolge Fotoemission Elektronen heraus (lichtelektrischer Effekt, Fotoeffekt). Diese wandern zur positiv geladenen Anode und werden von ihr aus der Röhre abgesaugt.

Genaue Funktionsweise:
[Fotozelle](https://www.lernhelfer.de/schuelerlexikon/physik/artikel/fotozelle)


**Vibrationssensor**

Ein Vibrationssensor ist ein piezoelektrischer Sensor, der Schwingungen erfasst. Sie setzen ihn ein, um damit Beschleunigungen, Geschwindigkeiten oder reguläre Schwingungen zu messen. Vibrationssensoren zeigen Ihnen an, wann Sie Ihre Maschinen warten lassen müssen.

Genaue Funktionsweise:
[Vibrationsmesser](https://www.youtube.com/watch?v=Z0wZv8aDwlY)

 &nbsp;
---
# Ähnliche Projekte
 &nbsp;
---
### **Silence Breaker: One Survivors Story** (*Audiovisuelles Storytelling Projekt von Min Kwak*)
---

![Gespannter Stoff mit eingenähtem Leitfähigen Faden](https://images.squarespace-cdn.com/content/v1/5c36db7296e76f097022a8db/1547368627605-WBVDC0X0UY6A8ILRA00L/IMG_1538.JPG?format=750w)

---
### **Konzept**
---
Silence Breaker : One Survivor’s Story is an immersive, interactive audiovisual experience based on a true story of one survivor of domestic abuse. The story has 4 sections, and each section is narrated in 4 visual, virtual spaces of the survivor’s house, which was built based on the place where domestic abuse was actually happened. Audio of each section of story will be played through installed fabric speaker by touching woman’s silhouette in order. The voice is a real voice of this survivor, and it was recorded directly. Sound contains ordinary domestic noise in order to give realistic sense. Audience can experience this story though multiple senses, and follow how the survivor has been suffered and finally received freedom.

---
### **Ähnlichkeiten & Unterschiede im Vergleich meines Konzeptes**
---

**Unterschiede**

In diesem Projekt hat die Kreatorin nicht nur das interaktive Storytelling in Form von Knopfaktvierung und Ausgabe über Lautsprecher programmiert, sondern einen kompletten 3-D Space, bestehend aus vier Räumen kreiert, die die Geschichte zusätzlich visuell wiedergibt. Diese Setup ist in meinem Vorhaben nicht notwendig und würde Rahmen sprengen.


**Übereinstimmungen**

Trotz offensichtlichen Aufwandsunterschied ist das Projekt dennoch interessant für mich, da die Kreatorin ein interaktives Audiosystem eingebunden hat. Durch die Aktivierung von Schaltern, welche repräsentativ für die Kapitel der Geschichte stehen, kann der User entscheiden, welche Tonspuren wann abgespielt werden.

---
### **Dokumentation - Gut & Schlecht**
---

Die Kreatorin Min Kwak hat sowohl ein paar Videos der Nutzung, sowie eine Vorstellungswebsite des Projektes veröffentlicht. 
Allerdings werden in den Videos lediglich die Nutzung veranschaulicht und die Website dokumentiert das technische Vorgehen sehr oberflächlich und dient wohl eher nur um Interessenten auf das Projekt aufmerksam zu machen. 
Eine technische Dokumentation, wie zum Beispiel die Zusammensätzung und Verbindung der verwendeten Komponenten, sowie die Programmierung werden komplett ausgelassen.


---
### **Umsetzbarkeit des Projektes**
---

Da ich vorhabe den 3-D Teil komplett außer Acht zu lassen, scheint das interaktive Soundsystem recht gut umsetzbar zu sein. Die einzelnen Kapitel werden zudem (scheinbar) nicht mit Sensor, sondern durch simplen Knopfdruck gesteuert. Lediglich die Einbindung des gespannten Stoffstückes und des eingenähten Leitfadens stellt mich noch vor ein Rätsel. Als Referenzprojekt scheint dies dennoch interessant zu sein.

[Projektwebsite](https://minkwak.com/silence-breaker-one-survivors-story#:~:text=Silence%20Breaker%20%3A%20One%20Survivor's%20Story%20is%20an%20immersive%2C%20interactive%20audiovisual,one%20survivor%20of%20domestic%20abuse.)

[Projektvideos](https://www.youtube.com/watch?v=uJUv6X8mDUM)

---
### **Nutzung des Tiptoi-Systems** (*Hobbyrecherche auf Github*)
---

---
### **Konzept/Funtkion**
---
Tiptoi ist ein interaktives Lernspiel bestehend aus einem Digitalstift und einem Spielbrett, Buch oder Puzzle mit digitalem Papier. Der Stift wird auf verschiedene Stellen der bedruckten Oberfläche gehalten und erkennt am Punktraster des OID, welche Stelle angetippt wurde.
Das Projekt befasst sich mit einer Analyse des Tiptoi-Stiftes, wie die Zusammensetzung des einzelenen Elemente und die Programmierung dieser.
Beschreibung der Projektbeteiligten :"The current status is that we understood most of the file format (see the GME file format specification). We provide a tool that allows you to dissect these files. The tool can also be used to generate completely new files from scratch; see below for details."

---
### **Ähnlichkeiten & Unterschiede im Vergleich meines Konzeptes**
---

**Unterschiede**

Auf der einen Seite wird das Output der Story versimpelt, da diese primär durch das Berühren durch Stellen eines Bilderbuches stattfinden.

**Übereinstimmungen**

Das Grundprinzip ist jedoch das gleiche, da es durch die Aktivierung von Sensoren eine Tonspur abspielt.
---
### **Dokumentation - Gut & Schlecht**
---

Dank der Dokumentation einer Hobby-Enthusiasten kann ich mich auch mit der Zusammensetzung des Codes befassen. 
Der einzige Nachteil ist, dass dies keine offiziellen Daten der Firma Ravensburger sind und diese eventuell unklar sein könnten oder in der Funktion abweichen.


---
### **Umsetzbarkeit des Projektes**
---

Die Umsetzung scheint mir mit diesem Prinzip sehr machbar und somit realistisch zu sein. Ich werde ich höchstwarscheinlich sehr viel mit dem öffentlich zur Verfügung gestellten Codes auf Git-Hub auseinandersetzen.



[Git-Hub Dokumentation](https://github.com/entropia/tip-toi-reveng)
