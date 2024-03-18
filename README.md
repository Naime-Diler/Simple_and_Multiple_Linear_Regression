# **Verkaufsprognose mit Linearer Regression**

## **Einführung:**
Dieses Projekt zielt darauf ab, ein grundlegendes Verständnis für einfache und multiple lineare Regressionsverfahren zu entwickeln und den Unterschied zwischen diesen Ansätzen zu verdeutlichen. Der Schwerpunkt liegt auf der Anwendung dieser 
Regressionstechniken, um den Zusammenhang zwischen den Werbeausgaben in verschiedenen Kanälen (wie Fernsehen, Radio und Zeitung) und den erzielten Verkäufen zu untersuchen.

## **Einfache Lineare Regression:**
In dieser Phase verwenden wir die einfache lineare Regression, bei der nur eine unabhängige Variable, wie beispielsweise die Ausgaben für TV-Werbung, verwendet wird, um die abhängige Variable, in diesem Fall die Verkaufszahlen, vorherzusagen. 
Das Modell wird anhand von Metriken wie dem Mean Squared Error (MSE), dem Root Mean Squared Error (RMSE) und dem Mean Absolute Error (MAE) bewertet, um die Genauigkeit und Fehler des Modells bei der Vorhersage der Verkaufszahlen zu verstehen.

## **Multiple Lineare Regression:**
Im nächsten Schritt vertiefen wir unsere Analyse durch die Anwendung der multiplen linearen Regression, bei der mehrere unabhängige Variablen gleichzeitig berücksichtigt werden, wie beispielsweise die Ausgaben für TV, Radio und Zeitungswerbung. 
Wir verwenden die Holdout-Validierungsmethode, um unseren Datensatz in Trainings- und Testsets aufzuteilen, und bewerten die Leistung des Modells erneut, diesmal unter Einbeziehung verschiedener Metriken wie dem RMSE und dem R²-Wert, um die Varianz 
und die Vorhersagekraft des Modells zu beurteilen.

## **Kreuzvalidierung:**
Abschließend setzen wir die Kreuzvalidierungstechnik ein, um die Stabilität unserer Modelle zu überprüfen. Dabei wird der Datensatz in mehrere Teile aufgeteilt, und die Modelle werden mehrmals trainiert und getestet. Die Leistung der Modelle wird durch 
den durchschnittlichen RMSE über eine 10-Fold-Cross-Validation bewertet, um die Generalisierbarkeit und Zuverlässigkeit unserer Modelle über verschiedene Datensatzteilungen hinweg zu beurteilen.

## **Anwendung der Methode der gewöhnlichen kleinsten Quadrate (OLS):**
Zusätzlich verwenden wir in diesem Projekt die Methode der gewöhnlichen kleinsten Quadrate (OLS), die implizit durch die LinearRegression()-Funktion von scikit-learn angewendet wird, um die Regressionskoeffizienten zu schätzen und Vorhersagen zu machen.
