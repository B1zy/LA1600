# Lern-Bericht
Gruppenname: Date (Aeschlimann, Bashiri, Bielski)
## Einleitung

Im Rahmen unseres Projektes haben wir eine benutzerfreundliche Vergleichs-Website entwickelt, auf der Nutzer bis zu drei verschiedene Handys vergleichen können.

## Was habe ich gelernt?

Im Zuge dieses Projekts haben wir gelernt, wie man eine Sprachwechsel-Funktion in einer Website implementiert.

## Beschreibung

Die Implementierung einer Sprachwechsel-Funktion war eine interessante Aufgabe, die sowohl unsere Kenntnisse in HTML und CSS vertiefte, als auch unser Verständnis für die Erstellung von interaktiven und benutzerfreundlichen Webseiten erweiterte. Es war eine bereichernde Erfahrung, da wir sowohl technische Fähigkeiten als auch eine sinnvolle Benutzerfunktionalität entwickeln konnten, die in realen Webanwendungen häufig vorkommt.

Insbesondere fiel es uns schwer, zu entscheiden, wie der Benutzer die Sprache wechseln sollte. Wir wollten eine Methode, die sowohl intuitiv als auch einfach zu verwenden ist. Nach einigem Nachdenken und Experimentieren entschieden wir uns schliesslich dafür, den Namen der Sprache klickbar zu machen.
Wenn ein Benutzer auf den Namen der Sprache klickt, ändert die Website ihre Sprache entsprechend. Um die Benutzerfreundlichkeit zu erhöhen und Verwirrung zu vermeiden, habe ich es so eingerichtet, dass der Benutzer durch erneutes Klicken auf den gleichen Button zur ursprünglichen Sprache der Website zurückkehren kann.
![image](https://github.com/Entlino/LA1600/assets/111045708/66e0ff47-6fea-4b36-aa14-6d6b197c1925)

Der bereitgestellte Code bietet eine Funktion für die Sprachumschaltung auf unserer Website. Der HTML-Teil enthält einen Hyperlink, der auf die englische Version der Samsung-Seite verweist und über die ID "language-checkbox" gesteuert wird.
```
<a href="samsung eng.html" id="language-checkbox">English</a>
```
Dieser Codeabschnitt steuert das Design und das Verhalten eines Sprachumschalt-Links auf einer Website. Der Link ist absolut positioniert und erscheint in der oberen rechten Ecke der Seite. Beim Überfahren mit der Maus wird der Link unterstrichen, um zu signalisieren, dass er klickbar ist.
```
.language-checkbox {
  position: absolute;
  top: 10px;
  right: 10px;
  font-size: 14px;
  color: #2196f3;
  text-decoration: none;
  cursor: pointer;
}

.language-checkbox-label {
  display: inline-block;
}

.language-checkbox-label:hover {
  text-decoration: underline;
}

#language-checkbox:checked + .language-checkbox-label::before {
  content: "\2713";
}
```


## Verifikation

Die verwendeten Medien, darunter Code-Snippets und schriftliche Beschreibungen, demonstrieren konkret die Fähigkeiten, die wir im Rahmen dieses Projekts erworben haben. Sie illustrieren, wie wir eine Sprachumschaltungsfunktion auf einer Website implementiert haben, indem wie sowohl den funktionalen Code als auch das dazugehörige Styling erstellt haben. Diese Materialien bieten einen eindeutigen Nachweis meiner neu erworbenen Fähigkeiten und meines erweiterten Verständnisses von Webentwicklung und Benutzerinteraktion.

# Reflexion zum Arbeitsprozess

Die Erstellung der Website war für uns alle drei eine Menge Spass und eine grosse Lernerfahrung. Es hat uns geholfen, uns intensiver mit HTML und CSS vertraut zu machen, was zu einer Steigerung unseres technischen Wissens und unserer Fähigkeiten geführt hat. 

Was nicht gut gelaufen ist, war unsere ursprüngliche Zielsetzung für das Projekt. Aufgrund unserer mangelnden Erfahrung mit HTML und CSS waren einige unserer Ziele überambitioniert. Wir planten Funktionen wie ein Filtersystem und 3D-Modelle der Handys einzubauen, mussten diese Ideen aber aufgrund technischer Einschränkungen aufgeben. Wir erkannten, dass solche Funktionen nur mit der Verwendung von Javascript möglich sind. Dies führte zu Anpassungen unserer ursprünglichen Planung und zu einer Neuausrichtung unserer Projektziele.

**VBV**: Für zukünftige Projekte wäre es hilfreich, unsere Ziele und Erwartungen besser an unsere technischen Fähigkeiten und Kenntnisse anzupassen. Vor Beginn des Projekts könnten wir eine gründlichere Recherche und Planung durchführen, um ein besseres Verständnis der technischen Anforderungen und Möglichkeiten zu erlangen.
