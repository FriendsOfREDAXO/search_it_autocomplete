# WIP 🚧 Autocomplete-Erweiterung für `search_it`

Das Addon stellt das "Suggest"-jQuery-PlugIn für die Autovervollständigung bei
der Suche im Frontend zur Verfügung und generiert einen Code welcher im Template
eingebunden werden muss.

Abkapselung des Plugins für Search it als eigenes Addon.

## Requirements

* [Search it](https://github.com/alxndr-w/search_it)
* Installiertes jQuery im Frontend
* Funktionierendes Suchformular, das die HTML-Klasse "search_it-form",
  sowie ein HTML-Eingabefeld für die Suche mit dem Namen "search".

## Installation

1. Addon installieren und aktivieren
3. Konfiguration im Addon vornehmen und speichern
4. Den generierten Code für das Template herauskopieren und in das Template,
   welches für das Suchfeld verwendet wird, vor dem schließenden `</body>` Tag
   hinzufügen
5. Sollte das Suchfeld überall verwendet werden, beispielsweise im Kopf der
   Seite, muss der generierte Code in das entsprechende Template hinzugefügt
   werden
6. Optional: CSS und JS Datei in den eigenen Frontend_prozess einbauen ( z.B.
   per Minify oder im Bimmelbam )

## Lizenz

"Autocomplete" von Manétage steht unter MIT Lizenz.

## Rechtliches

Verwendung auf eigene Gefahr.

## Autor

**Manetage** - Ronny Kemmereit / Pascal Schuchmann

* <http://www.manetage.de>

**Friends Of REDAXO**

* <http://www.redaxo.org>
* <https://github.com/FriendsOfREDAXO>
