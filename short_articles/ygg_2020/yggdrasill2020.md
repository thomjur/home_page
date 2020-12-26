---
title: Yggdrasill Jahresrückblick 2019
author: thomas jurczyk
layout: article
exclude: true
---

<sub>**Aktueller Stand:** 26. Dezember 2020</sub>

## Einführung
Die folgenden Visualisierungen und Statistiken basieren auf Beiträgen, die während des Jahres 2020 auf der religionswissenschaftlichen Informationsliste [Yggdrasill](https://www.lists.uni-marburg.de/lists/sympa/info/yggdrasill) veröffentlicht worden sind (für die Auswertung der Beiträge aus dem Jahr 2019, klicken Sie bitte [hier]({{ site.baseurl }}{% link short_articles/ygg_2019/yggdrasill2019.md %})). Laut Beschreibung auf der offiziellen Webseite, die von der Universität Marburg gehostet wird, handelt es sich bei Yggdrasill um eine ...

>  ... religionswissenschaftliche Diskussions- und Informationsliste (...) \[Yggdrasill] ist eine Dienstleistung der Europäischen Gesellschaft für Religionswissenschaft (European Association for the Study of Religions, EASR). Die Diskussionen bei "Yggdrasill" werden hauptsächlich auf Deutsch geführt. Yggdrasill wird gegenwärtig von Sebastian Schüler (Leipzig) betreut.[^1]

Die folgenden statistischen Übersichten über die Diskussionsthemen sowie -teilnehmer/innen auf Yggdrasill verfolgen kein spezifisches Ziel. Sie sind vor allem aus dem Interesse und der Freude an der Generierung, Verarbeitung sowie Visualisierung digitaler Daten heraus entstanden.[^2]

Ein besonderes Augenmerk lag darauf, die Analysen und deren Visualisierungen so abstrakt zu halten, dass keine Rückschlüsse auf einzelne Listenmitglieder möglich bzw. sinnvoll sind. So werden weder konkrete Personen genannt noch wird auf irgendeine andere Art und Weise auf Aspekte hingewiesen, die sich leicht auf einzelne Listenmitglieder zurückführen ließen (zum Beispiel Hinweise auf Personen, die besonders häufig posten etc.). Falls sich doch jemand unbeabsichtigterweise angesprochen oder gar an den Pranger gestellt fühlt, bitte ich darum, mich zu kontaktieren, damit ich entsprechende Änderungen vornehmen kann. Das Letzte, was ich beabsichtige, ist die Diskussonskultur auf Yggdrasill zu beeinflussen oder gar zu stören. Aus diesem Grund habe ich mich ebenfalls dazu entschlossen, die Inhalte der Diskussionsbeiträge nicht zu berücksichtigen, da sich beispielsweise die Resultate textstatistischer Verfahren bei einem so kleinen Datensatz letztlich doch auf bestimmte Personen oder zumindest einen gewissen Personenkreis zurückführen ließen.

Über Feedback, Hinweise (gerne auch technischer Natur) sowie Ideen für weitere Auswertungen würde ich mich sehr freuen. Gerne können Sie mich unter meiner Mailadresse, die ich auf Yggdrasill nutze, oder aber unter <contact@thomas-jurczyk.com> erreichen.

## Die Datenbasis
Die Datenbasis besteht aus derzeit **829** Mailbeiträgen (+197 zum Vorjahr), die im Laufe des Jahres 2020 auf Yggdrasill veröffentlicht wurden.[^3] Die Beiträge wurden manuell in einem separaten Postfach in meinem Mailprogramm gespeichert und von dort in Python geladen und weiterverarbeitet. Zu der weiteren Bearbeitung gehörte neben automatisierten Auswertungen auch die manuelle Annotation der Kategorien (siehe unten). Es wurden nur Beiträge berücksichtigt, die dezidiert für Yggdrasill bestimmt waren. Beiträge, die gleichzeitig auf mehreren Listen erschienen sind und mehrere Listenkürzel in der Betreffzeile führten, sind in der Regel nicht berücksichtigt worden. Trotzdem der Versuch unternommen wurde, alle Beiträge einzubeziehen, kann es sein, dass einige Beiträge übersehen bzw. aufgrund technischer Probleme nicht angezeigt wurden. Auch sind hin und wieder Beiträge aus Cross-Listen-Postings in den Ordner gerutscht. Die folgenden absoluten Zahlen sind entsprechend mit Vorsicht zu behandeln und sollten entsprechen vorsichtig interpretiert werden.

## Yggdrasill 2020 Auswertungen
### Anzahl der Beiträge pro Monat plus die Top Themen
Der interaktive Plot unter [diesem Link](yggdrasill_2020_overview.html) zeigt die absolute Anzahl an Beiträgen pro Monat an. Wenn die Maus (oder der Finger im Falle eines Smartphones bzw. Tablets) über die Rechtecke geführt wird, wird außerdem das Top Thema des jeweiligen Monats angezeigt. Es sei angemerkt, dass sich in zahlreichen "ruhigeren" Monaten mehrere Beiträge den ersten Platz teilen. In diesem Falle wurde eines der Top Themen zufällig ausgewählt. Auch ist die Auswertung der Top-Themen nicht immer ganz korrekt, da insbesondere im Jahr 2020 viele Themenstränge unter wechselnden Titeln geführt wurden.

### Anzahl der Beiträge unterteilt nach Gender
Der *pie chart* unter [diesem Link](pie_chart_gender.html) (interaktive Version) zeigt die absolute Anzahl an Beiträgen auf Yggdrasill in 2020 geordnet nach Gender der Verfasser/innen. Das Label "unbekannt" wurde vergeben, wenn Listenbeiträge von Organisationen oder nicht identifizierbaren Personen verfasst wurden.

### Anzahl der Beiträge unterteilt nach Titeln
Der interaktive *pie chart* unter [diesem Link](pie_chart_status.html) zeigt die absolute Anzahl an Beiträgen auf Yggdrasill in 2020 geordnet nach Titeln der Verfasser/innen. Die Titel sind dabei unterteilt in:

* Professoren
* Promoviert
* Kein Titel (Studierende, PhD students usw.)

Da die Titel der einzelnen Personen nicht immer leicht zu ermitteln waren, sind die hier präsentierten Zahlen nur als vage Annäherungen zu verstehen. Habilitierte Personen, die keine feste Professur innehaben, wurden zumeist in die Gruppe "Promoviert" aufgenommen.

### Gruppierung der Beiträge

Der letzte *pie chart* unter [diesem Link](pie_chart_topics.html) (interaktive Version) zeigt die absolute Anzahl an Beiträgen auf Yggdrasill in 2020 gruppiert nach übergreifenden Themen. Hierbei wurden die folgenden Oberkategorien festgelegt (**Achtung**: Es gibt Änderungen im Vergleich zum Vorjahr 2020, da einige Kategorien wie **Preise** rausgefallen sind bzw. in **Ankündigungen** integriert wurden):

* Die Kategorie **Reflexion & Kritik** beinhaltet Beiträge, die sich mit allgemeinen Fragen und Entwicklungen der Religionswissenschaft beschäftigen. Darunter fallen beispielsweise Themen wie "Verhältnis von Religionswissenschaft und Theologie" oder die Frage nach der Relevanz von Quellensprachen in B.A. Studiengängen der Religionswissenschaft, aber auch der Umgang mit befristeten Stellen etc.
* Die Kategorien **CfP** sowie **Veranstaltungen** und **Ankündigungen** weisen gewisse Schnittsmengen auf. Unter **Veranstaltungen** werden sämtliche Versammlungsformen gefasst (Workshop, Konferenz, Arbeitskreistreffen usw.). Die Kategorie **CfP** enthält nur Beiträge, in deren Betreffzeile "CfP" oder "Call for Papers" erwähnt wurden. Andere Beiträge, die eventuell ebenfalls als CfPs gewertet werden können, dies aber in der Betreffzeile nicht erwähnen, sind eventuell in anderen Kategorien wie **Veranstaltungen** oder **Ankündigungen** untergekommen.
* Die Kategorie **Religionswissenschaft** beinhaltet Beiträge, die sich mit konkreten religionswissenschaftlichen Fragen ("Was ist Schamanismus aus rw. Perspektive?") befassen oder nach religionswissenschaftlicher Expertise fragen ("Wer arbeitet noch zu Thema XY?"). Die Kategorie **Religionswissenschaft** überschneidet sich teilweise mit **Reflexion & Kritik**, was insbesondere im Jahr 2020 anhand von Threads und Diskussionen wie der um die ZDF Doku "Juden in Japan" deutlich wurde, die ursprünglich sogar "nur" eine **Ankündigung** war. 
* Die Kategorie **Publikation** beinhaltet alles, was irgendwie als "schriftlich" festgehalten angekündigt wurde. Darunter fallen Buchpublikationen, Artikel, aber auch Blogs, (schriftliche) Interviews oder Zeitungsartikel.
* Die Kategorie **Ankündigungen** enthält Bekanntmachungen, wozu u.a. Filmvorführungen, Podiumsdiskussionen, Radiofeatures etc. gehören.
* Die anderen Kategorien wie **Stellenausschreibungen** (jetzt **CfA**), **Stipendien** oder **Studiengang** sollten selbsterklärend sein.

Über Feedback, Hinweise (gerne auch technischer Natur) sowie Ideen für weitere Auswertungen würde ich mich sehr freuen. Gerne können Sie mich unter meiner Mailadresse, die ich auf Yggdrasill nutze, oder aber unter <contact@thomas-jurczyk.com> erreichen.

## Fußnoten
***
[^1]: [Yggdrasill Beschreibung Uni Marburg](https://www.lists.uni-marburg.de/lists/sympa/info/yggdrasill) 

[^2]: Dabei wurden insbesondere die Programmiersprache [Python](https://www.python.org/) sowie die Python Bibliotheken [Bokeh](http://docs.bokeh.org/en/0.13.0/) und [pandas](https://pandas.pydata.org/) verwendet.

[^3]: Stand 26. Dezember 2020.
