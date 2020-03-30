---
title: Yggdrasill Jahresrückblick 2019
author: thomas jurczyk
layout: article
exclude: true
---

<sub>**Aktueller Stand:** 13. November 2019</sub>

## Einführung
Die folgenden Visualisierungen und Statistiken basieren auf Beiträgen, die während des Jahres 2019 auf der religionswissenschaftlichen Informationsliste [Yggdrasill](https://www.lists.uni-marburg.de/lists/sympa/info/yggdrasill) veröffentlicht worden sind. Laut Beschreibung auf der offiziellen Webseite, die von der Universität Marburg gehostet wird, handelt es sich bei Yggdrasill um eine ...

>  ... religionswissenschaftliche Diskussions- und Informationsliste (...) \[Yggdrasill] ist eine Dienstleistung der Europäischen Gesellschaft für Religionswissenschaft (European Association for the Study of Religions, EASR). Die Diskussionen bei "Yggdrasill" werden hauptsächlich auf Deutsch geführt. Yggdrasill wird gegenwärtig von Sebastian Schüler (Leipzig) betreut.[^1]

Die folgenden statistischen Übersichten über die Diskussionsthemen sowie -teilnehmer/innen auf Yggdrasill verfolgen kein spezifisches Ziel. Sie sind vor allem aus dem Interesse und der Freude an der Generierung, Verarbeitung sowie Visualisierung digitaler Daten heraus entstanden.[^2]

Ein besonderes Augenmerk lag darauf, die Analysen und deren Visualisierungen so abstrakt zu halten, dass keine Rückschlüsse auf einzelne Listenmitglieder möglich bzw. sinnvoll sind. So werden weder konkrete Personen genannt noch wird auf irgendeine andere Art und Weise auf Aspekte hingewiesen, die sich leicht auf konkrete Listenmitglieder zurückführen ließen (zum Beispiel Hinweise auf Personen, die besonders häufig posten etc.). Falls sich doch jemand unbeabsichtigterweise angesprochen oder gar an den Pranger gestellt fühlt, bitte ich darum, mich zu kontaktieren, damit ich entsprechende Änderungen vornehmen kann. Das Letzte, was ich beabsichtige, ist die Diskussonskultur auf Yggdrasill zu beeinflussen oder gar zu stören. Aus diesem Grund habe ich mich ebenfalls dazu entschlossen, die konkreten Inhalte der Diskussionsbeiträge nicht zu berücksichtigen, da sich beispielsweise die Resultate textstatistischer Verfahren bei einem so kleinen Datensatz letztlich doch auf bestimmte Personen oder zumindest einen gewissen Personenkreis zurückführen ließen.

Über Feedback, Hinweise (gerne auch technischer Natur) sowie Ideen für weitere Auswertungen würde ich mich sehr freuen. Gerne können Sie mich unter meiner Mailadresse, die ich auf Yggdrasill nutze, oder aber unter <contact@thomas-jurczyk.com> erreichen.

## Die Datenbasis
Die Datenbasis besteht aus derzeit **547** Mailbeiträgen, die im Laufe des Jahres 2019 auf Yggdrasill veröffentlicht wurden.[^3] Die Beiträge wurden manuell in einem separaten Postfach gespeichert und von dort mit der Hilfe von [pywin32](https://pypi.org/project/pywin32/) in Python geladen und weiterverarbeitet. Es wurden nur Beiträge berücksichtigt, die dezidiert für Yggdrasill bestimmt waren. Beiträge, die gleichzeitig auf mehreren Listen erschienen sind und mehrere Listenkürzel in der Betreffzeile führten, sind nicht berücksichtigt worden. Trotzdem der Versuch unternommen wurde, alle Beiträge einzubeziehen, kann es sein, dass einige Beiträge übersehen bzw. aufgrund technischer Probleme nicht angezeigt wurden. Die folgenden absoluten Zahlen sind entsprechend mit Vorsicht zu behandeln und sollten nicht zu streng interpretiert werden.

## Yggdrasill 2019 Auswertungen
### Anzahl der Beiträge pro Monat plus die Top Themen
Der interaktive Plot unter [diesem Link](yggdrasill_2019_overview.html) zeigt die absolute Anzahl an Beiträgen pro Monat an. Wenn die Maus (oder der Finger im Falle eines Smartphones bzw. Tablets) über die Rechtecke geführt wird, wird außerdem das Top Thema des jeweiligen Monats angezeigt. Es sei angemerkt, dass sich in zahlreichen "ruhigeren" Monaten mehrere Beiträge den ersten Platz teilen. In diesem Falle wurde eines der Top Themen zufällig ausgewählt.

### Anzahl der Beiträge unterteilt nach Gender
Der *pie chart* unter [diesem Link](pie_chart_gender.html) (interaktive Version) zeigt die absolute Anzahl an Beiträgen auf Yggdrasill in 2019 geordnet nach Gender der Verfasser/innen. Das Label "unbekannt" wurde vergeben, wenn Listenbeiträge von Organisationen oder nicht identifizierbaren Personen verfasst wurden.

### Anzahl der Beiträge unterteilt nach Titeln
Der interaktive *pie chart* unter [diesem Link](pie_chart_status.html) zeigt die absolute Anzahl an Beiträgen auf Yggdrasill in 2019 geordnet nach Titeln der Verfasser/innen. Die Titel sind dabei unterteilt in:

* Professoren
* Promoviert
* Kein Titel (Studierende, PhD Students, usw.)
* unbekannt

Da die Titel der einzelnen Personen nicht immer leicht zu ermitteln waren, sind die hier präsentierten Zahlen nur als vage Annäherungen zu verstehen. Habilitierte Personen, die keine feste Professur innehaben, wurden zumeist in die Gruppe "Promoviert" aufgenommen.

### Gruppierung der Beiträge
Der letzte *pie chart* unter [diesem Link](pie_chart_groups.html) (interaktive Version) zeigt die absolute Anzahl an Beiträgen auf Yggdrasill in 2019 gruppiert nach übergreifenden Themen. Hierbei wurden die folgenden Oberkategorien festgelegt:

* Die Kategorie **Reflektion & Kritik** beinhaltet Beiträge, die sich mit allgemeinen Fragen und Entwicklungen der Religionswissenschaft beschäftigen. Darunter fallen beispielsweise Themen wie "Verhältnis von Religionswissenschaft und Theologie" oder die Frage nach der Relevanz von Quellensprachen in B.A. Studiengängen der Religionswissenschaft.
*  Die beiden Kategorien **CfP** sowie **Veranstaltungen** weisen gewisse Schnittsmengen auf. Unter **Veranstaltungen** werden sämtliche Versammlungsformen gefasst (Workshop, Konferenz, Arbeitskreistreffen, Filmvorführungen usw.). Die Kategorie **CfP** enthält nur Beiträge, in deren Betreffzeile "CfP" oder "Call for Papers" erwähnt wurden. Andere Beiträge, die eventuell ebenfalls als CfPs gewertet werden können, dies aber in der Betreffzeile nicht erwähnen, sind eventuell in anderen Kategorien untergekommen.
*  Die Kategorie **Religionswissenschaft** beinhaltet Beiträge, die sich mit konkreten religionswissenschaftlichen Fragen ("Was ist Schamanismus aus rw. Perspektive?") befassen oder nach religionswissenschaftlicher Expertise fragen ("Wer arbeitet noch zu Thema XY?").
*  Die Kategorie **Publikation** beinhaltet alles, was irgendwie als "schriftlich" festgehalten angekündigt wurde. Darunter fallen Buchpublikationen, Artikel, aber auch Blogs, Interviews oder Zeitungsartikel.
*  Die anderen Kategorien wie **Stellenausschreibungen** oder **Preise** sollten selbsterklärend sein.

Die hier festgehaltenen Ergebnisse sind vorläufig und werden in unregelmäßigen Abständen aktualisiert. Über Feedback, Hinweise (gerne auch technischer Natur) sowie Ideen für weitere Auswertungen würde ich mich sehr freuen. Gerne können Sie mich unter meiner Mailadresse, die ich auf Yggdrasill nutze, oder aber unter <contact@thomas-jurczyk.com> erreichen.

## Fußnoten
***
[^1]: [Yggdrasill Beschreibung Uni Marburg](https://www.lists.uni-marburg.de/lists/sympa/info/yggdrasill) 

[^2]: Dabei wurden insbesondere die Programmiersprache [Python](https://www.python.org/) sowie die Python Bibliotheken [Bokeh](http://docs.bokeh.org/en/0.13.0/) und [pandas](https://pandas.pydata.org/) verwendet.

[^3]: Stand 13. November 2019.
