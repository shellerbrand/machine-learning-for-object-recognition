# Objekterkennung und Transfer-Lernen

<img src="https://github.com/shellerbrand/machine-learning-for-object-recognition/blob/master/resources/training-picture-grid.png?raw=true" width="500px"/>

In diesem Repository findet sich ein Beispiel dafür, wie Bilderkennung mit neuronalen Netzen funktioniert.

Dieses Beispiel wird im Rahmen der Veranstaltung [Lernen, wie Maschinen lernen](https://www.mzl.uni-muenchen.de/zusatzqualifikationen/lehramtpro/kurse-lehramtpro-2020-21/kurse-digitalisierung/kmbd_10_lernen_maschinen/index.html) an der [LMU München](https://www.uni-muenchen.de/) verwendet.

Das Beispiel soll die Bedeutung der Auswahl geeigneter Trainingsdaten vermitteln. Außerdem soll es den Studenten zeigen, wie einfach es ist, mit frei verfügbaren Mitteln ein eigenes Bilderkennungssystem zu trainieren. 

In der Regel bauen wir im Kurs einen Detektor, der Gummibärchen von Lakritz-Produkten unterscheiden kann. Dieses Beispiel hat den angenehmen Nebeneffekt, dass im Nachgang der Versuchsaufbau aufgegessen werden kann. Denkbar sind jedoch auch andere Beispiele, in denen zwei verschiedene Arten von Objekten unterschieden werden sollen.

Wesentlicher Bestandteil dieses Beispiels ist ein [Jupyter-Notebook](machine_learning_object_recognition_transfer_learning.ipynb), das für die Ausführung auf 
[Google Colaborary](https://colab.research.google.com) entwickelt wurde. Dadurch kann das Beispiel von jedem, der ein Google-Konto besitzt, einfach im Browser durchgeführt werden. Das Notebook ist jedoch auch ohne große Modifikation in einer lokalen Umgebung für Jupyter-Notebooks lauffähig.

## Benutzung

Das Notebook kann mit diesem Link in Google Colaboratory geöffnet werden:

https://colab.research.google.com/github/shellerbrand/machine-learning-for-object-recognition/blob/master/machine_learning_object_recognition_transfer_learning.ipynb

Wenn man eigene Trainings- und Evaluierungsdaten benutzen will, dann muss man dafür ein Konto auf der [Bilder Upload-Seite](https://imageupload.hellerbit.com/images) anlegen.

__Bitte beachten__: Alle Konten und die dazugehörigen Daten werden täglich um Mitternacht deutscher Zeit gelöscht. Der Code für die Upload-Seite wird zu einem späteren Zeitpunkt ebenfalls hier veröffentlicht für diejenigen, die die Upload-Seite auf Ihrem eigenen Server betreiben wollen.