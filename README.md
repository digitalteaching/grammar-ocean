# Grammar Ocean

Übungsseite Englisch für Klasse 6: simple present, Satzbau (Subjekt – Verb – Objekt – Ort – Zeit, at/in/on), simple past mit was/were, unregelmäßige Verben, Verneinung und Fragen im simple past, present progressive, gemischte Zeiten und eine Ferien-E-Mail mit typischen Fehlern.

Sieben „Inseln“ mit je drei bis vier Stufen. Jede Stufe hat einen animierten Erklärteil in Klick-Schritten (Wortkacheln bauen den Satz um) und endlose Übungsrunden zu zehn Aufgaben: Auswahl, Eintippen, Satz bauen, Fehler finden, Verb-Karten. Die Aufgaben werden aus Satzbausteinen zufällig erzeugt, die Antwortposition ist zufällig.

Motivation: Tagesziel 12 Minuten (die Anzeige zählt nur aktive Zeit), Serie ab 5 Minuten pro Tag, Muscheln als Punkte, Sterne je Stufe (ab 9 von 10 beim ersten Versuch), Abzeichen, Finn der Delfin.

Alles auf Englisch; der Schalter „DE“ oben rechts blendet deutsche Hilfezeilen ein.

## Code für die Lehrkraft

„My code for my teacher“ erzeugt einen Code ohne Namen. Die Lehrkraft fügt ihn unter `index.html#teacher` ein und sieht: Übungsminuten je Tag, Runden und Sterne je Stufe, Fehlerquoten je Bereich, gelernte und unsichere unregelmäßige Verben, die letzten 30 Fehler (geschrieben → richtig). Derselbe Code lädt den Stand auf einem anderen Gerät.

Der Fortschritt liegt nur im Browser (localStorage), es gibt keinen Server.

## Technik

Eine Datei, keine Abhängigkeiten, läuft offline. Test der Aufgabengeneratoren: `node test.mjs`. Veröffentlichen über GitHub Pages (Konto digitalteaching): `sh veroeffentlichen.sh`.
