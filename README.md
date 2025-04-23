# LB_259_Machinelearning

## Beschreibung
Dieser Datensatz enthält Fahrzeugverkaufsdaten, einschließlich Informationen zu Automodellen, technischen Spezifikationen, Preisen, Verkaufsstatus und Vertriebsdetails. Ziel ist es, Vorhersagen über Verkaufspreise, Margen oder Verkaufswahrscheinlichkeit zu treffen. Die Daten eignen sich gut für Regressions- oder Klassifikationsaufgaben im Bereich Data Science und maschinelles Lernen.

## Datenschutz

Der Datensatz scheint keine personenbezogenen Daten wie Namen, Adressen oder Kontaktinformationen zu enthalten. Alle enthaltenen Angaben betreffen Fahrzeuge oder Verkaufsmetriken und lassen keine Rückschlüsse auf Einzelpersonen zu. Falls die Daten aus öffentlich zugänglichen Quellen stammen, ist davon auszugehen, dass keine zusätzlichen Datenschutzmaßnahmen erforderlich sind.

## Entscheidung
Ich habe Lineare Regression gewählt, da es sich bei der Aufgabenstellung um ein Regressionsproblem handelt, bei dem ein numerischer Zielwert („Sold Price-$“) vorhergesagt werden soll. Das Modell ist leicht verständlich, schnell trainierbar und ermöglicht eine gute erste Einschätzung. Es eignet sich besonders gut für lineare Zusammenhänge und liefert solide Ergebnisse, die eine gute Grundlage für weiterführende Modellvergleiche bilden.


## Ergebniss
Das Modell wurde mit den Merkmalen „Baujahr“, „Kilometerstand“, „Motorleistung“, „Einkaufspreis“ und „Sales Rating“ trainiert, um den Verkaufspreis vorherzusagen. Das Lineare Regressionsmodell erreichte ein MAE von 740.68 und einen R²-Wert von 0.58, was eine akzeptable Genauigkeit bedeutet. Eine manuelle Überprüfung einzelner Vorhersagen ergab realistische Ergebnisse. Weitere Modelle könnten getestet werden, um die Genauigkeit zu verbessern.
