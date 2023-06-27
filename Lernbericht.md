# Lern-Bericht

### Gruppe: Lychee

- Sacher (Gruppenleiter)
- Marku
- Burlet

## Einleitung

Wir haben uns entschieden, eine Website für Restaurants zu entwickeln, die den Benutzern bei der schnelleren Entscheidungsfindung für ein Restaurant helfen soll.

## Was habe ich gelernt?

Wir haben gelernt, wie man mit HTML und CSS Filter programmiert und verwendet.

## Beschreibung


https://github.com/robinsacher/LA1600/assets/110892985/1ba7b218-9ad9-4f77-bfdb-13a171f31215

In diesem Video sieht man im ersten markierten Code, den Gesamtcode für unseren Filter.
Danach wird der Code markiert, der für die Änderung der Farbe zuständig ist und danach, für das Ausblenden.
Am Schluss wird noch markiert, wie man das Einblendet.

```css
.Burger,
.Doener,
.Pizza {
  display: none;
}

#burgerfilter:checked ~ .restaurants .Burger,
#doenerfilter:checked ~ .restaurants .Doener,
#pizzafilter:checked ~ .restaurants .Pizza {
  display: block;
}
```
Hier sieht man noch den CSS code ohne den Teil, der dafür zuständig ist, die Elemente schön zu machen.
Dabei sieht man, dass nur zwei Befehle wichtig sind.

1: `display: block;`, welches die Elemente anzeigen lässt nachdem einer der Filter checked ist.

2: `display: none;`, welches die Elemente ausblendet. Dieser Teil ist die Ausgangsposition der Elemente (wenn Checkboxen unchecked).

### Generelle Beschreibung:
Anwendung:
Filter sollte man immer dann anwenden, wenn man zu viele Elemente hat, welche dazu führen können, dass es unübersichtlich wird. Auch für Shops und vorlieben (in unserem Fall beim Essen) sind Filter praktisch, da man nicht die Restaurants ansehen muss, welche man sowieso nicht besuchen möchte.

Funkion:
Grundsätzlich hat man im HTML nur die Labels mit den input Checkboxen und den Elementen die man ein/ausblenden Möchte. Man gibt den filtern verschiedene klassen und den Elementen ihre zugehörigen Klassen wie Pizza und/oder Burger, danach kann man eine CSS Pseudoklasse machen, welche dann Burger ein/ausblendet, wenn die Checkbox checked ist. Das wäre dann zum einblenden `display: block;` und zum ausblenden `display: none;`

## Verifikation

1: Es zeigt, dass wir gelernt haben diese Ein- und Ausblend Funktion in eine Webseite einzufügen.

2: Es zeigt, dass wir gelernt haben wie wir generell mit diesem Ein- und Ausblenden umgehen sollen / wie es generell funktioniert.

3: Es zeigt, dass wir gelernt haben in welchen Fällen man diese Filter einbauen kann/sollte und wie das Grundkonzept funktioniert.

## Reflexion zum Arbeitsprozess

**Was gut an unserer Arbeit lief:**
- An unserer Arbeit hat besonders das Zusammenarbeiten gut funktioniert. Auch zu dritt konnten wir produktiv an unseren Aufgaben arbeiten. Die Arbeitspakete haben wir gut unter uns aufgeteilt, wodurch wir einen klaren Überblick halten konnten.


**Was nicht gut an unserer Arbeit lief:**
- Wir hatten häufig Interesse an denselben Arbeitspaketen, was dazu führte, dass wir öfter abstimmen mussten, wer welches Arbeitspaket übernehmen würde.

**VBV**: Sich zum Beginn des Projektes eine klare Struktur zu den Arbeitspaketen ausdenken, so dass alle schon am Anfang ein klares Bild von ihren Areitspaketen haben und somit keine Zeit verschwendet wird.
