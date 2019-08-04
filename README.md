# FirstApproachNLP

## Einleitung
Es wurde ein Datensatz gewählt, welcher unterschiedliche Interpreten und die dazugehörigen Songtexte beinhaltet. Aus diesem Datensatz soll ein Lerner generiert werden, welcher im Stande ist, Songtexte dem Interpreten zu zuweisen.

Big Data besteht zu einem Grossteil aus Textdaten, diese sind stark unstrukturiert. Um signifikante Ergebnisse bei der Analyse zu erzielen, müssen die Daten zuerst prozessiert werden. Als Werkzeug dient das Natural Language Processing, kurz NLP.

NLP unterstützt den Benutzer mit verschiedenen Tasks, unteranderem der Feature-Generierung und der Klassifizierung der Texte. NLP ist eine weit verbreitete Art der Datenanalyse und wird  für verschiedenste Anwendungen verwendet, wie Rechtschreibprüfung, personalisierte Werbung, oder Schlüsselwortsuche. Die Werkzeuge befinden sich in der verwendeten Python Natural Language Toolkit Library (NLTK).



## Zielsetzung
Ziel ist es eine möglichst hohe Genauigkeit bei der Ermittlung von Künstlern aus gegebenen Songtexten zu erreichen. 


## Vorgehensweise

Zu Beginn werden die Daten vorbereitet (Preprocessing), dass heisst es werden unnötige Wörter und Textteile entfernt, welche keine brauchbaren Angaben zur Eigenschaft des Textes bieten.

NLP beinhaltet zwei Arten der Sprachprozessierung, Natural Language Understanding und Natural Language Generation. In diesem Projekt wird aussschliesslich der Teil der Natural Language Understanding verwendet.

Unterteilt wird die NLP in die Tasks 
- Preprocessing
- Feature-Generierung
- Klassifikation.

Diese Tasks werden sequentiell in einer Pipeline abgearbeitet mittels einem geeigneten Klassifikator.
Zum Schluss werden verschiedene Klassifikatoren gegeneinander kreuzvalidiert.
