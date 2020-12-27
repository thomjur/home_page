---
title: Yggdrasill Jahresrückblick 2020
author: thomas jurczyk
layout: article
exclude: true
---

<sub>**Aktueller Stand:** 26. Dezember 2020</sub>

## Einführung
Die folgenden Visualisierungen und Statistiken basieren auf Beiträgen, die während des Jahres 2020 auf der religionswissenschaftlichen Informationsliste [Yggdrasill](https://www.lists.uni-marburg.de/lists/sympa/info/yggdrasill) veröffentlicht worden sind (für die Auswertung der Beiträge aus dem Jahr 2019 klicken Sie bitte [hier]({{ site.baseurl }}{% link short_articles/ygg_2019/yggdrasill2019.md %})). Laut Beschreibung auf der offiziellen Webseite, die von der Universität Marburg gehostet wird, handelt es sich bei Yggdrasill um eine ...

>  ... religionswissenschaftliche Diskussions- und Informationsliste (...) \[Yggdrasill] ist eine Dienstleistung der Europäischen Gesellschaft für Religionswissenschaft (European Association for the Study of Religions, EASR). Die Diskussionen bei "Yggdrasill" werden hauptsächlich auf Deutsch geführt. Yggdrasill wird gegenwärtig von Sebastian Schüler (Leipzig) betreut.[^1]

Die folgenden statistischen Übersichten über die Diskussionsthemen sowie -teilnehmer/innen auf Yggdrasill verfolgen kein spezifisches Ziel. Sie sind vor allem aus dem Interesse und der Freude an der Generierung, Verarbeitung sowie Visualisierung digitaler Daten heraus entstanden.[^2]

Ein besonderes Augenmerk lag darauf, die Analysen und deren Visualisierungen so abstrakt zu halten, dass keine Rückschlüsse auf einzelne Listenmitglieder möglich bzw. sinnvoll sind. So werden weder konkrete Personen genannt noch wird auf irgendeine andere Art und Weise auf Aspekte hingewiesen, die sich leicht auf einzelne Listenmitglieder zurückführen ließen (zum Beispiel Hinweise auf Personen, die besonders häufig posten etc.). Falls sich doch jemand unbeabsichtigterweise angesprochen oder gar an den Pranger gestellt fühlt, bitte ich darum, mich zu kontaktieren, damit ich entsprechende Änderungen vornehmen kann. Das Letzte, was ich beabsichtige, ist die Diskussonskultur auf Yggdrasill zu beeinflussen oder gar zu stören. Aus diesem Grund habe ich mich ebenfalls dazu entschlossen, die Inhalte der Diskussionsbeiträge nicht zu berücksichtigen, da sich beispielsweise die Resultate textstatistischer Verfahren bei einem so kleinen Datensatz letztlich doch auf bestimmte Personen oder zumindest einen gewissen Personenkreis zurückführen ließen.

Über Feedback, Hinweise (gerne auch technischer Natur) sowie Ideen für weitere Auswertungen würde ich mich sehr freuen. Gerne können Sie mich unter meiner Mailadresse, die ich auf Yggdrasill nutze, oder aber unter <contact@thomas-jurczyk.com> erreichen.

## Die Datenbasis
Die Datenbasis besteht aus derzeit **829** Mailbeiträgen (+197 zum Vorjahr), die im Laufe des Jahres 2020 auf Yggdrasill veröffentlicht wurden.[^3] Die Beiträge wurden manuell in einem separaten Postfach in meinem Mailprogramm gespeichert und von dort in Python geladen und weiterverarbeitet. Zu der weiteren Bearbeitung gehörte neben automatisierten Auswertungen auch die manuelle Annotation der Kategorien (siehe unten). Es wurden nur Beiträge berücksichtigt, die dezidiert für Yggdrasill bestimmt waren. Beiträge, die gleichzeitig auf mehreren Listen erschienen sind und mehrere Listenkürzel in der Betreffzeile führten, sind in der Regel nicht berücksichtigt worden. Trotzdem der Versuch unternommen wurde, alle Beiträge einzubeziehen, kann es sein, dass einige Beiträge übersehen bzw. aufgrund technischer Probleme nicht angezeigt wurden. Auch sind hin und wieder Beiträge aus Cross-Listen-Postings in den Ordner gerutscht. Die folgenden sind entsprechend mit Vorsicht zu interpretieren.

## Yggdrasill 2020 Auswertungen
### Anzahl der Beiträge pro Monat plus die Top-Themen
Der interaktive Plot unter [diesem Link](yggdrasill_2020_overview.html) zeigt die absolute Anzahl an Beiträgen pro Monat an. Wenn die Maus (oder der Finger im Falle eines Smartphones bzw. Tablets) über die Rechtecke geführt wird, wird außerdem das Top-Thema des jeweiligen Monats angezeigt. Die Auswertung der Top-Themen ist nicht immer ganz korrekt, da insbesondere im Jahr 2020 viele Themenstränge unter wechselnden Titeln geführt wurden.

### Top 3 Themen jedes Monats

Die folgende Tabelle zeigt die drei meistdiskutierten Themen eines jeden Monats und bietet damit eine Ergänzung zu der Übersicht über die Top-Themen (siehe erster Plot). Sie weist außerdem auf noch bestehende Schwierigkeiten hin, Themen, die eigentlich zusammengehören, aber unter unterschiedlichen Titeln bzw. leicht abgeänderten Betreffzeilen diskutiert werden (siehe März 2020 in der Tabelle), automatisiert zusammenzufassen.

|                             MONTH                                                  |    TOPIC                                                                                                                                           |    |
|:-----------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------:|-------------:|
| JAN 20|  [Ygg] Religion und Tattoos                                                                                                                                                             |            6 |
| | [Ygg] Hinweis auf Tagung "Public: Religion & Sapce" und Call of Papers                                                                                                                 |            2 |
| | [Ygg] Islamische Interpretationen religiöser Vielfalt                                                                                                                                  |            2 |
| FEB 20 | [Ygg] Rassismus inkl. Antisemitismus                                                                                                                                                   |           27 |
| | [Ygg] Thüringen                                                                                                                                                                        |            8 |
| | [Ygg] In memoriam Adolf Holl (1930-2020)                                                                                                                                               |            6 |
| MAR 20 | [Ygg] Anfrage MDR: Was sage die großen Weltreligionen?                                                                                                                                 |            7 |
| | [Ygg] Anfrage MDR: Was sage(n) die großen Weltreligionen?                                                                                                                              |            6 |
| | [Ygg] Frage und Gruß                                                                                                                                                                   |            5 |
| APR 20 | [Ygg] Hinweis / Frage zur Ausschreibungsliste "Theologie" #03/20                                                                                                                     |           13 |
| | [Ygg] Anfrage: Die Verbindung zwischen der gegenwärigen Forschung zu "UMF" und dem Nationalsozialismus                                                                                 |            5 |
| | [Ygg] Fw: letter to our European friends                                                                                                                                               |            5 |
| MAI 20 | [Ygg] Nochmals grundsätzlich                                                                                                                                                           |           39 |
| | [Ygg] Corona-Auswirkungen auf Wissenschaftler_innen mit Kindern                                                                                                                        |           17 |
| | [Ygg] Nochmals grundsätzlich zum "Mittelbau"                                                                                                                                           |           12 |
|  JUN 20 | [Ygg] Nochmals grundsätzlich zum "Mittelbau"                                                                                                                                           |            2 |
| | [Ygg] AAR Statement on Racism and George Floyd Murder, June 4, 2020                                                                                                                    |            1 |
| | [Ygg] Ausschreibung Dissertationspreis der DVRW 2021 (Einreichfrist: 30. September 2020)                                                                                             |            1 |
| JUL 20 | [Ygg] Misstrauensvotum gegenüber ANONYMISIERT                                                                                                                                 |            4 |
| | [Ygg] Antwort: Misstrauensvotum gegenüber ANONYMISIERT                                                                                                                        |            3 |
| | [Ygg] local encounters                                                                                                                                                                 |            3 |
| AUG 20 | [Ygg] Tag für Tag - die sonstigen Religionen                                                                                                                                           |            8 |
| | [Ygg] Historisches und systematisches Proseminar                                                                                                                                       |            7 |
| | [Ygg] Ausschreibung Koordinatorenstelle im Forschungskolleg NRW "Regionale Regulierung Religiöser Pluralität im Vergleich"                                                             |            2 |
| SEP 20 | [Ygg] Religionswissenschaftliche Kirchengeschichte?                                                                                                                                    |           11 |
| | [Ygg] Grundsatzbeitrag zur Rolle der Religionswissenschaft                                                                                                                             |            9 |
| | [Ygg] Neuerscheinung "Religion in der Schule" -- Download OPEN ACCESS                                                                                                                |            8 |
| OKT 20 | [Ygg] Online-Lehrveranstaltungen - Interesse an wechselseitigen Öffnungen?                                                                                                             |            3 |
| | [Ygg] Resistance to Order and Authority in Religion. Religious Studies Doctoral Conference, Budapest, October 15-17, 2020.                                                         |            2 |
| | [Ygg] Åke Ström                                                                                                                                                                        |            2 |
| NOV 20 | [Ygg] Literatur zu "deskriptivem, wertneutralem Schreiben"                                                                                                                             |           21 |
| | [Ygg] Antwort: Literatur zu "deskriptivem, wertneutralem Schreiben"                                                                                                                  |           17 |
| | [Ygg] Literaturtipp Beziehung Buddhismus und Hinduismus                                                                                                                                |           13 |
| DEZ 20 | [Ygg] Nochmals zu Thema "Leitfaden" fürTheologiestudierende zum religionswissenschaftlichen Spracherwerb                                                                               |           47 |
| | [Ygg] ZDF Info "Japan und die Juden"                                                                                                                                                   |           22 |
| | [Ygg] Religionsunterricht versus Ethikunterricht oder versus pluralistischer Religionsunterricht?                                                                                    |            7 |

### Anzahl der Beiträge unterteilt nach Gender
Der *pie chart* unter [diesem Link](pie_chart_gender.html) (interaktive Version) zeigt die absolute Anzahl an Beiträgen auf Yggdrasill in 2020 geordnet nach Gender der Verfasser/innen. Das Label "unbekannt" wurde vergeben, wenn Listenbeiträge von Organisationen oder nicht identifizierbaren Personen verfasst wurden.

### Anzahl der Beiträge unterteilt nach Titeln
Der interaktive *pie chart* unter [diesem Link](pie_chart_status.html) zeigt die absolute Anzahl an Beiträgen auf Yggdrasill in 2020 geordnet nach Titeln der Verfasser/innen. Die Titel sind dabei unterteilt in:

* Professoren
* Promoviert
* Kein Titel (Studierende, PhD students usw.)

Da die Titel der einzelnen Personen nicht immer leicht zu ermitteln waren, sind die hier präsentierten Zahlen nur als vage Annäherungen zu verstehen. Habilitierte Personen, die keine feste Professur innehaben, wurden zumeist in die Gruppe "Promoviert" aufgenommen.

### Genderanteil an Statusgruppen
Die folgende Tabelle bietet eine Übersicht über den prozentualen Anteil der Geschlechter innerhalb der jeweiligen Statusgruppen. **Aufgrund der wackligen Datenbasis bitte mit Vorsicht zu interpretieren!** Auch muss die folgende Auswertung nicht zwingnd repräsentativ für die Gesamtsituation der Religionwissenschaft in Deutschland sein, da sie lediglich auf der an den Diskussionen auf Yggdrasill beteiligten Personen basiert.

|      STATUS   |     GENDER               |   % |
|:------------|----------------:|---------:|
| Dr. | m                  | 52 |
|  | w                  | 48 |
| Kein Titel | m         | 44  |
| | w         | 44  |
| | unbekannt | 12 |
| Prof. | m |                80      |
| | w               | 20      |

### Gruppierung der Beiträge

Der letzte *pie chart* unter [diesem Link](pie_chart_topics.html) (interaktive Version) zeigt die absolute Anzahl an Beiträgen auf Yggdrasill in 2020 gruppiert nach übergreifenden Themen. Hierbei wurden die folgenden Oberkategorien festgelegt (**Achtung**: Es gibt Änderungen im Vergleich zum Vorjahr 2019, da einige Kategorien wie **Preise** rausgefallen sind bzw. in **Ankündigungen** integriert wurden):

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
