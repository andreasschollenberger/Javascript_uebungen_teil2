# Java Script übungen Teil 2

## index.html
Schreiben Sie eine Funktion mit dem Namen „GreaterNum“, die:
braucht 2 Argumente, beide Zahlen.
Gibt die Zahl zurück, die größer (höher) ist.
Rufen Sie diese Funktion zweimal mit unterschiedlichen Zahlenpaaren auf und protokollieren Sie die Ausgabe, um sicherzustellen, dass sie funktioniert (z. B. „Die größere Zahl von 5 und 10 ist 10.“).

## 01.html
Schreiben Sie eine Funktion namens helloWorld, die:
benötigt 1 Argument, einen Sprachcode (z. B. „es“, „de“, „en“)
gibt „Hello, World“ für die angegebene Sprache zurück, für mindestens 3 Sprachen. Standardmäßig sollte Englisch zurückgegeben werden.
Rufen Sie diese Funktion für jede der unterstützten Sprachen auf und protokollieren Sie das Ergebnis, um sicherzustellen, dass es funktioniert.

## 02.html
Schreiben Sie eine Funktion namens „assignGrade“, die:
braucht 1 Argument, eine Zahlenpunktzahl.
gibt eine Note für die Punktzahl zurück, entweder „A“, „B“, „C“, „D“ oder „F“.
Rufen Sie diese Funktion für einige verschiedene Ergebnisse auf und protokollieren Sie das Ergebnis, um sicherzustellen, dass es funktioniert.

## 03.html
Schreiben Sie eine Funktion namens pluralize, die:
benötigt zwei Argumente, ein Substantiv und eine Zahl.
gibt die Zahl und die Pluralform zurück, etwa „5 Katzen“ oder „1 Hund“.
Rufen Sie diese Funktion für einige verschiedene Ergebnisse auf und protokollieren Sie das Ergebnis, um sicherzustellen, dass es funktioniert.
Bonus: Lassen Sie ein paar Sammelbegriffe wie „Schafe“ und „Gänse“ verarbeiten.

## 04.html
Schreiben Sie eine for-Schleife, die von 0 bis 20 iteriert. Bei jeder Iteration prüft sie, ob die aktuelle Zahl gerade oder ungerade ist, und meldet dies auf dem Bildschirm (z. B. „2 ist gerade“).

## 05.html
Schreiben Sie eine for-Schleife, die von 0 bis 10 iteriert. Bei jeder Iteration der for-Schleife wird die Zahl mit 9 multipliziert und das Ergebnis protokolliert (z. B. „2 * 9 = 18“).

Bonus: Verwenden Sie eine verschachtelte for-Schleife, um die Tabellen für jeden Multiplikator von 1 bis 10 anzuzeigen (insgesamt 100 Ergebnisse).

## 06.html
Überprüfen Sie die Ergebnisse Ihrer Funktion „assignGrade“ aus der Bedingungsübung, indem Sie jeden Wert von 60 bis 100 protokollieren: Ihr Protokoll sollte Folgendes anzeigen: „Für 88 haben Sie eine Zwei erhalten. Für 89 haben Sie eine Zwei erhalten. Für 90 haben Sie eine Eins erhalten. Für.“ 91, du hast eine Eins, usw., wobei jeder Notenpunkt im Bereich protokolliert wird.

## 07.html
Erstellen Sie ein Array für Ihre Top-Auswahl (Farben, Präsidenten usw.).
Geben Sie für jede Auswahl eine Zeichenfolge wie „Meine erste Auswahl ist blau“ auf dem Bildschirm ein.
Bonus: Ändern Sie es in „Meine 1. Wahl“, „Meine 2. Wahl“, „Meine 3. Wahl“ und wählen Sie das richtige Suffix für die Nummer basierend auf dem aus, was es ist.

## 08.html
Hausaufgabe: Der Wortschätzer
Sie erstellen ein einfaches Wort-Ratespiel, bei dem der Benutzer unendlich viele Versuche hat, das Wort zu erraten (wie „Hangman“ ohne Henker oder „Wheel of Fortune“ ohne Rad und Glück).

Erstellen Sie zwei globale Arrays: eines für die Buchstaben des Worts (z. B. „F“, „O“, „X“) und eines für die aktuell erratenen Buchstaben (z. B. würde es mit „_“, „_“ beginnen). '_' und enden mit 'F', 'O', 'X').
Schreiben Sie eine Funktion namens „gueLetter“, die Folgendes bewirkt:
Nehmen Sie ein Argument, den erratenen Buchstaben.
Gehen Sie die Wortbuchstaben durch und prüfen Sie, ob der erratene Buchstabe darin enthalten ist.
Wenn der erratene Buchstabe mit einem Wortbuchstaben übereinstimmt, wird das Array der erratenen Buchstaben geändert, um dies widerzuspiegeln.
Wenn die Iteration abgeschlossen ist, sollten die aktuell erratenen Buchstaben („F__“) protokolliert werden.
und gratulieren dem Benutzer, wenn er einen neuen Brief gefunden hat.
Es sollte auch herausfinden, ob es noch weitere Buchstaben gibt, die erraten werden müssen,
und wenn nicht, sollte es dem Benutzer zum Gewinn des Spiels gratulieren.
Tun Sie so, als ob Sie das Wort nicht kennen, und rufen Sie „gueseLetter“ mehrmals mit verschiedenen Buchstaben auf, um zu überprüfen, ob Ihr Programm funktioniert.
Bonus: Machen Sie es eher wie „Wheel of Fortune“:
Beginnen Sie mit einem Prämienbetrag von 0 $
Generieren Sie jedes Mal, wenn ein Buchstabe erraten wird, einen zufälligen Betrag und belohnen Sie den Benutzer, wenn er einen Buchstaben gefunden hat (multiplizieren Sie die Belohnung, wenn mehrere Buchstaben gefunden werden), andernfalls subtrahieren Sie ihn von seiner Belohnung.
Wenn sie das Wort erraten haben, protokollieren Sie den endgültigen Belohnungsbetrag.
Bonus: Machen Sie es wie Hangman:
Behalten Sie den Überblick über alle erratenen Buchstaben (richtig und falsch) und lassen Sie den Benutzer einen Buchstaben nur einmal erraten. Wenn sie einen Buchstaben zweimal erraten, tun Sie nichts.
Verfolgen Sie den Zustand des Henkers als Zahl (beginnend bei 0) und subtrahieren oder addieren Sie diese Zahl jedes Mal, wenn er eine falsche Schätzung macht.
Sobald die Zahl 6 erreicht (eine angemessene Anzahl an Körperteilen für einen Henker), informieren Sie den Benutzer über den Verlust und zeigen Sie einen Henker im Protokoll an.