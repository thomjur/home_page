---
title: religioid
author: thomas jurczyk
layout: project
exclude: true
category: projects
link-citations: true
---

# A Quantitative Analysis of the Dissemination of Religious Notions in Contemporary English Texts

## Aim of this Research Project

The project has set itself the task of quantitatively examining central religious concepts such as sacred, ritual, purity, and religion in terms of their prevalence, use, and meaning in various social fields such as politics and art. From a theoretical perspective, the project's focus lies on (de)sacralization processes [see @krech_soziologie_2018] and the concept of the "religioid" coined by Simmel [see @tyrell_religioide_2018].

Empirically, this project will build on the religious studies text corpus ReligionML that includes documents from different social fields and annotates them to enable data-driven research in the study of religion (more details on ReligionML and the first annotation attempts can be found on the [ReligionML website](https://thomjur.github.io/home_page/projects/religionml.html)).

## Theoretical Background

The theoretical background of this project is, on the one hand, the concept of the "religioid" coined by Georg Simmel, which describes the emergence of religious semantics and of religion as a whole from (non-religious) social processes:

> Als Ausgangspunkt dient die empirische Herleitung von Religion aus sozialen Vorgängen mittels des Differenzierungsparadigmas und der daraus resultierenden Unterscheidung von Religion als autonomer Vorstellungswelt und „Religioidem“ [...], das bereits in Vergesellschaftungsprozessen vorzufinden ist. [@krech_soziologie_2018, 337][^C]

[^C]: "The starting point is the empirical derivation of religion from social processes by means of the differentiation paradigm and the resulting distinction between religion as an autonomous world of imagination and a 'religioid' \[\...\], which is already found in processes of socialization."

Complementing the concept of the religioid, the project also draws on the process of (de)sacralization, which can be seen as an extension of the concept of secularization. In a linguistic context, secularization is commonly understood as the deconstruction of the religious origin of concepts and their interpretation in a non-religious context [see @schlette_heilige_2009]. The concept of descralization, in contrast to sacralization, is understood as part of a broader phenomenon oscillating between the poles of increasing (sacralization) and decreasing (desacralization) religious interpretations [@krech_soziologie_2018, 445]. In this context, sacralization is understood as the process of a religious interpretation of "vormals religiös insignifikante Entität[en]" [@krech_soziologie_2018, 443],[^A] which is not only undertaken by religious actors (e.g. religious institutions) but can also be initiated by non-religious participants:

[^A]: "formerly religiously insignificant entity[ies]."

> Unter Sakralisierung ist in der Religionsforschung ganz allgemein zu verstehen, dass sich die kollektive Verständigung über das Heilige vom religiösen in den nicht-religiösen Bereich ausweitet oder verlagert. [@schlette_sakralisierung_2018, 437][^B]

[^B]: "In religious studies, sacralization is generally understood to mean that the collective understanding of the sacred expands or shifts from the religious to the non-religious realm."

The process of (de)sacralization can shift the meaning of concepts from the religious to the non-religious realm, but it can also take the opposite path by linking formerly non-religious phenomena to the realm of religion [see the example of civil religion in @bellah_civil_1967].

The project "A Quantitative Analysis of the Dissemination of Religious Notions in Contemporary English Texts" will attempt to quantitatively analyze these processes of religioid use cases of certain terms as well as the process of (de)sacralization  using texts from various social fields. Potential social fields that could be examined in this context are found, among others, in the section "Religion im gesellschaftlichen Kontext" in the *Handbuch Religionssoziologie* [@pollack_handbuch_2018, 657-859]. For several reasons (among others: availability, copyright issues, relevance), the project is currently limited to the three fields of politics, art, and media/internet.[^1]

[^1]: For the relation between religion and politics, see Willems [-@willems_religion_2018]. For the relation between religion and art, see Krech [-@krech_religion_2018]. For the relation between religion and media/online discourses, see Neumaier [-@neumaier_religion_2018; -@neumaier_religion_2016].

## Methodology

The methodology is based on the quantitative analysis of the textual evidence collected in the ReligionML Corpus, consisting of sentences and short documents of diverse provenance (text snippets, tweets, etc.). On the one hand, the analysis will be performed by applying machine learning algorithms [in particular from the field of unsupervised learning, see @geron_handson_2019] on the annotated documents of the ReligionML Corpus. On the other hand, established methods from the field of corpus linguistics will be applied to achieve a better understanding of the use and meaning of the terms under investigation. These include methods such as keyword analysis, collocation analysis, and word frequency lists [@brezina_statistics_2018b].

The quantitative methods will be expanded to include a qualitative level of analysis focusing on selected textual examples drawn from the quantitative analysis. The *mixed methods* approach used here builds on a procedure I developed in my dissertation [@jurczyk_notion_2022a] that will hopefully be extended during this project.

An example in this context is the analysis of (English) terms such as \"sacred\" or \"holy\" in documents of different provenance and genres (Twitter, newspaper articles, forums, art, politics, etc.), which are collected and annotated in the ReligionML Corpus and analyzed and discussed under the questions addressed in the theory section [I took a first step in this direction in my dissertation, see @jurczyk_notion_2022a].

## Data

The data, consisting of individual sentences or short sections, will be archived and processed in a structured manner in the ReligionML Corpus. Central to both the investigations in the context of this project and the ReligionML project as a whole are the annotations to be made at the document and word level, the details of which are explained on the [ReligionML Corpus website](https://thomjur.github.io/home_page/projects/religionml.html).

From a copyright and pragmatic[^2] point of view, already digitized and freely available sources (Twitter, newspapers, digitized books, Wikipedia, etc.) are to be included and supplemented with manual and anonymized excerpts from other sources. From a copyright perspective, it is advantageous that the analyses in this project are based on short text excerpts (sentences and at most paragraphs, tweets) without including the complete sources.


[^2]: The keyword here is automated acquisition of data through web scraping.

# Bibliography

---
references:
- id: bellah_civil_1967
  author:
    - family: Bellah
      given: Robert N.
  citation-key: bellah_civil_1967
  container-title: Daedalus
  issue: '1'
  issued:
    - year: 1967
  page: 1-21
  title: Civil Religion in America
  type: article-journal
  volume: '96'

- id: bender_annotation_2020a
  abstract: >-
    Annotation hat sich von einer analog geprägten Kulturtechnik, deren
    Geschichte sich bis in die Antike zurückverfolgen lässt, hin zu einer
    digitalen Praktik entwickelt, die in verschiedenen Spannungsfeldern verortet
    werden kann. Sie wird einerseits als alltagsweltliche Rezeptions-, aber auch
    Kommunikationsform vollzogen (und ist somit potenzieller Gegenstand von
    linguistischen Untersuchungen, z.B. Hashtag-Analysen), andererseits auch als
    wissenschaftliche Methode angewendet. Methodisch bildet sie eine
    Schnittstelle zwischen hermeneutischer und automatisiert-quantifizierender
    Analyse. Aus diskurslinguistischer Perspektive verbindet das Annotieren
    wissenschaftliche Metadiskursivität mit diskursiver Involviertheit. Diese
    Verortungen werden im vorliegenden Aufsatz diskutiert und anhand von
    konkreten Annotationsprojekten veranschaulicht. Im Mittelpunkt steht dabei
    das kollaborativ-diskursive Annotieren als wissenschaftliche Methode in der
    digitalen (Diskurs-)Linguistik.
  accessed:
    - year: 2022
      month: 4
      day: 6
  author:
    - family: Bender
      given: Michael
  citation-key: bender_annotation_2020a
  container-title: Diskurse – digital
  DOI: 10.25521/DISKURSE-DIGITAL.2020.140
  issued:
    - year: 2020
      month: 4
      day: 29
  language: de
  page: 1-35 Seiten
  publisher: Diskurse – digital
  source: DOI.org (Datacite)
  title: Annotation als Methode der digitalen Diskurslinguistik
  type: article-journal
  URL: https://majournals.bib.uni-mannheim.de/diskurse-digital/article/view/140
  volume: Bd. 2 Nr. 1

- id: brezina_statistics_2018b
  abstract: >-
    Do you use language corpora in your research or study, but find that you
    struggle with statistics? This practical introduction will equip you to
    understand the key principles of statistical thinking and apply these
    concepts to your own research, without the need for prior statistical
    knowledge. The book gives step-by-step guidance through the process of
    statistical analysis and provides multiple examples of how statistical
    techniques can be used to analyse and visualise linguistic data. It also
    includes a useful selection of discussion questions and exercises which you
    can use to check your understanding. The book comes with a Companion
    website, which provides additional materials (answers to exercises,
    datasets, advanced materials, teaching slides etc.) and Lancaster Stats
    Tools online (http://corpora.lancs.ac.uk/stats), a free click-and-analyse
    statistical tool for easy calculation of the statistical measures discussed
    in the book.
  accessed:
    - year: 2022
      month: 3
      day: 11
  author:
    - family: Brezina
      given: Vaclav
  citation-key: brezina_statistics_2018b
  ISBN: 978-1-316-41089-9 978-1-108-66902-3
  issued:
    - year: 2018
  language: English
  note: 'OCLC: 1055686776'
  source: Open WorldCat
  title: 'Statistics in corpus linguistics: a practical guide'
  title-short: Statistics in corpus linguistics
  type: book
  URL: >-
    https://www.cambridge.org/core/books/statistics-in-corpus-linguistics/4E530F86B328B2287681AD240796D2CF#fndtn-contents

- id: dash_language_2021
  abstract: >-
    This book addresses the research, analysis, and description of the methods
    and processes that are used in the annotation and processing of language
    corpora in advanced, semi-advanced, and non-advanced languages. It provides
    the background information and empirical data needed to understand the
    nature and depth of problems related to corpus annotation and text
    processing and shows readers how the linguistic elements found in texts are
    analyzed and applied to develop language technology systems and devices. As
    such, it offers valuable insights for researchers, educators, and students
    of linguistics and language technology.
  author:
    - family: Dash
      given: Niladri Sekhar
  citation-key: dash_language_2021
  event-place: Singapore
  ISBN: '9789811629594'
  issued:
    - year: 2021
  language: English
  note: 'OCLC: 1249070338'
  publisher: Springer
  publisher-place: Singapore
  source: Open WorldCat
  title: Language corpora annotation and processing
  type: book

- id: geron_handson_2019
  author:
    - family: Géron
      given: Aurélien
  citation-key: geron_handson_2019
  edition: Second edition
  ISBN: 978-1-4920-3264-9
  issued:
    - year: 2019
  publisher: O'Reilly
  title: >-
    Hands-on machine learning with Scikit-Learn, Keras, and TensorFlow:
    Concepts, tools, and techniques to build intelligent systems
  type: book

- id: ide_handbook_2017c
  abstract: >-
    This handbook offers a thorough treatment of the science of linguistic
    annotation. Leaders in the field guide the reader through the process of
    modeling, creating an annotation language, building a corpus and evaluating
    it for correctness. Essential reading for both computer scientists and
    linguistic researchers. Linguistic annotation is an increasingly important
    activity in the field of computational linguistics because of its critical
    role in the development of language models for natural language processing
    applications. Part one of this book covers all phases of the linguistic
    annotation process, from annotation scheme design and choice of
    representation format through both the manual and automatic annotation
    process, evaluation, and iterative improvement of annotation accuracy. The
    second part of the book includes case studies of annotation projects across
    the spectrum of linguistic annotation types, including morpho-syntactic
    tagging, syntactic analyses, a range of semantic analyses (semantic roles,
    named entities, sentiment and opinion), time and event and spatial analyses,
    and discourse level analyses including discourse structure, co-reference, et
    cetera Each case study addresses the various phases and processes discussed
    in the chapters of part one
  call-number: '410.285'
  citation-key: ide_handbook_2017c
  DOI: 10.1007/978-94-024-0881-2
  edition: 1st ed. 2017
  editor:
    - family: Ide
      given: Nancy
    - family: Pustejovsky
      given: James
  event-place: Dordrecht
  ISBN: 978-94-024-0881-2
  issued:
    - year: 2017
  number-of-pages: '1'
  publisher: 'Springer Netherlands : Imprint: Springer'
  publisher-place: Dordrecht
  source: Library of Congress ISBN
  title: Handbook of Linguistic Annotation
  type: book

- id: jurczyk_notion_2022a
  author:
    - family: Jurczyk
      given: Thomas
  citation-key: jurczyk_notion_2022a
  collection-number: '5'
  collection-title: Digital Humanities Research
  event-place: Bielefeld
  ISBN: '9783837661811'
  issued:
    - year: 2022
  language: English
  note: 'OCLC: 1285506584'
  number-of-pages: '350'
  publisher: transcript
  publisher-place: Bielefeld
  source: Open WorldCat
  title: >-
    The Notion of "holy" in Ancient Armenian Texts from the Fifth Century CE: A
    Comparative Approach Using Digital Tools and Methods
  type: book

- id: krech_dimensionen_2018
  abstract: >-
    Der Beitrag macht in prinzipieller Hinsicht vier analytisch zu
    unterscheidende Dimensionen des Religiösen aus: (1) Wahrnehmung und
    Erfahrung, (2) Körperlichkeit und Materialität, (3) Orientierung und Wissen
    sowie (4) Handeln und Regulierung. Die Erfahrungsdimension stattet religiöse
    Kommunikation mit Evidenz aus, die materielle Dimension stellt Medien für
    sie bereit, die kognitive Dimension ermöglicht spezifisch religiösen Sinn,
    und die Handlungsdimension sorgt für die Kanalisierung religiöser
    Kommunikation in institutionelle Arrangements. Während die ersten drei
    Dimensionen die religiösen Semantiken herstellen, garantiert die vierte
    Dimension ihre sozialstrukturelle Einbettung. Somit stehen die erste bis
    dritte mit der vierten Dimension in einem wissenssoziologischen Verhältnis
    der Wechselwirkung zwischen Semantik und Sozialstruktur.
  author:
    - family: Krech
      given: Volkhard
  citation-key: krech_dimensionen_2018
  container-title: Handbuch Religionssoziologie
  DOI: 10.1007/978-3-531-18924-6_3
  editor:
    - family: Pollack
      given: Detlef
    - family: Krech
      given: Volkhard
    - family: Müller
      given: Olaf
    - family: Hero
      given: Markus
  event-place: Wiesbaden
  ISBN: 978-3-531-18924-6
  issued:
    - year: 2018
  language: de
  page: 51–94
  publisher: Springer Fachmedien Wiesbaden
  publisher-place: Wiesbaden
  title: Dimensionen des Religiösen
  type: chapter
  URL: https://doi.org/10.1007/978-3-531-18924-6_3

- id: krech_religion_2018
  abstract: >-
    Der Beitrag untersucht das Verhältnis zwischen Religion und Kunst
    relational, das heißt, in wechselseitigem Bezug aufeinander. Dieses Vorgehen
    birgt den heuristischen Vorteil, Religion und Kunst nicht oder zumindest
    nicht vollständig substantiell fassen zu müssen und sich somit in die Gefahr
    der Essentialisierung zu begeben, sondern beide gesellschaftlichen
    Teilbereiche in ihren variierenden semantischen Formungen als voneinander
    abhängig bestimmen zu können. Nach kultur- und religionsgeschichtlichen
    Bruchstücken stellt der Beitrag gesellschaftsstrukturelle Überlegungen an.
    Anschließend werden anhand von kunstreligiösen Elementen im Werk von Joseph
    Beuys und in dessen Rezeption Interferenzen von Kunst und Religion erörtert.
    Im Ergebnis des religionsgeschichtlichen Durchgangs und des
    kunstgeschichtlichen Beispiels wird deutlich, dass es sich bei Kunst und
    Religion in gesellschaftsstruktureller Perspektive um keine Alternative
    handelt. Zwar lässt sich ein konkreter Sachverhalt in einem bestimmten
    Kontext nur entweder als Religion oder als Kunst verstehen. Da aber die
    moderne Gesellschaft funktional differenziert und zugleich polykontextural
    strukturiert ist, können unterschiedliche Bestimmungen gleichzeitig
    erfolgen.
  author:
    - family: Krech
      given: Volkhard
  citation-key: krech_religion_2018
  container-title: Handbuch Religionssoziologie
  DOI: 10.1007/978-3-531-18924-6_32
  editor:
    - family: Pollack
      given: Detlef
    - family: Krech
      given: Volkhard
    - family: Müller
      given: Olaf
    - family: Hero
      given: Markus
  event-place: Wiesbaden
  ISBN: 978-3-531-18924-6
  issued:
    - year: 2018
  language: de
  page: 783–807
  publisher: Springer Fachmedien Wiesbaden
  publisher-place: Wiesbaden
  title: Religion und Kunst
  type: chapter
  URL: https://doi.org/10.1007/978-3-531-18924-6_32

- id: krech_soziologie_2018
  abstract: >-
    Der Beitrag rekonstruiert wesentliche Aspekte der Religionstheorie Georg
    Simmels. Dabei wird zwischen einem soziologischen, kulturwissenschaftlichen
    und lebensphilosophischen Ansatz unterschieden. Die Argumente der
    Rekonstruktion lauten: 1) Im Zentrum der Religionstheorie Georg Simmels
    steht das Verhältnis von Teil und Ganzem, das seine soziale Konkretion in
    der Beziehung zwischen „Individuum“ und „Gesellschaft“, seine kulturelle
    Realisierung im Verhältnis von „subjektiver“ und „objektiver Kultur“ sowie
    seine lebensphilosophische Ausprägung in der Relation von „Prozess“ und
    „Form“ findet. 2) Auf der Basis von Simmels Wechselwirkungsverständnis sind
    die Glieder der genannten Begriffspaare methodische Begriffe, die sich nur
    durch den wechselseitigen Bezug aufeinander bestimmen. Die übergeordnete
    Relation ist diejenige zwischen Teil und Ganzem. 3) Simmel zufolge ist
    Religion diejenige gesellschaftliche und kulturelle Form, die das Verhältnis
    von Teil und Ganzem in seinen verschiedenen Ausprägungen auf besondere Weise
    traktiert. Ihre Emergenz ist qua Analogie aus „religioiden“ sozialen
    Prozessen heraus zu verstehen.
  author:
    - family: Krech
      given: Volkhard
  citation-key: krech_soziologie_2018
  container-title: Georg simmel und das leben in der gegenwart
  DOI: 10.1007/978-3-658-21427-2_18
  editor:
    - family: Lautmann
      given: Rüdiger
    - family: Wienold
      given: Hanns
  event-place: Wiesbaden
  ISBN: 978-3-658-21427-2
  issued:
    - year: 2018
  language: de
  page: 325–346
  publisher: Springer Fachmedien Wiesbaden
  publisher-place: Wiesbaden
  title: Die ‚Soziologie der Religion` – neu gelesen
  type: chapter
  URL: https://doi.org/10.1007/978-3-658-21427-2_18

- id: lasch_handbuch_2017
  citation-key: lasch_handbuch_2017
  collection-number: Band 18
  collection-title: Handbücher Sprachwissen
  editor:
    - family: Lasch
      given: Alexander
    - family: Liebert
      given: Wolf-Andreas
  event-place: Berlin Boston
  ISBN: 978-3-11-029629-7 978-3-11-029585-6
  issued:
    - year: 2017
  language: ger
  number-of-pages: '507'
  publisher: De Gruyter
  publisher-place: Berlin Boston
  source: K10plus ISBN
  title: Handbuch Sprache und Religion
  type: book

- id: lordick_digitale_2016a
  accessed:
    - year: 2022
      month: 4
      day: 6
  author:
    - family: Lordick
      given: Harald
    - family: Becker
      given: Rainer
    - family: Bender
      given: Michael
    - family: Borek
      given: Luise
    - family: Hastik
      given: Canan
    - family: Kollatz
      given: Thomas
    - family: Mache
      given: Beata
    - family: Rapp
      given: Andrea
    - family: Reiche
      given: Ruth
    - family: Walkowski
      given: Niels-Oliver
  citation-key: lordick_digitale_2016a
  container-title: Bibliothek Forschung und Praxis
  DOI: 10.1515/bfp-2016-0042
  ISSN: 1865-7648, 0341-4183
  issue: '2'
  issued:
    - year: 2016
      month: 1
      day: 1
  language: de
  source: DOI.org (Crossref)
  title: Digitale Annotationen in der geisteswissenschaftlichen Praxis
  type: article-journal
  URL: https://www.degruyter.com/document/doi/10.1515/bfp-2016-0042/html
  volume: '40'

- id: neumaier_religion_2016
  author:
    - family: Neumaier
      given: Anna
  citation-key: neumaier_religion_2016
  event-place: Würzburg
  ISBN: '9783956501418'
  issued:
    - year: 2016
  language: ger
  publisher: Ergon Verlag
  publisher-place: Würzburg
  source: BnF ISBN
  title: >-
    Religion@home? religionsbezogene Online-Plattformen und ihre Nutzung eine
    Untersuchung zu neuen Formen gegenwärtiger Religiosität
  title-short: Religion@home?
  type: thesis

- id: neumaier_religion_2018
  abstract: >-
    Öffentlichkeit und Medien sind zentrale Bezugsbereiche von Religion, und
    entsprechende Beziehungen sind Forschungsfelder der Religionssoziologie.
    Während im Rahmen der Säkularisierungsdebatte der Rückzug traditioneller
    Religionen in die Privatsphäre diskutiert wurde, ist Religion als Gegenstand
    massenmedialer Thematisierung längst wieder in der Öffentlichkeit präsent.
    Zugleich entstehen mediale Räume, die quer zur klassischen Unterscheidung
    von öffentlich und privat liegen. Der vorliegende Artikel widmet sich diesem
    Feld in drei Blöcken: 1) die Verortung von Religion zwischen Privatsphäre
    und Öffentlichkeit, 2) die Thematisierung von Religion in der medialen
    Öffentlichkeit sowie 3) institutionelle und individuelle Mediennutzung und
    deren Wechselwirkungen mit Religion. Dabei wird argumentiert, dass sich die
    Präsenz von Religion in Medien und Öffentlichkeit zunehmend von der
    Bedeutung religiöser Institutionen abgelöst hat: Während die Emanzipation
    einer religionsunabhängigen Medienlandschaft Religion immer wieder zum
    Objekt von Berichterstattung und Unterhaltung macht, müssen religiöse
    Institutionen sich und ihre Inhalte den Logiken von Markt und Medien
    anpassen, um weiterhin Thema oder Teilnehmer öffentlicher, medialer Diskurse
    zu sein.
  author:
    - family: Neumaier
      given: Anna
  citation-key: neumaier_religion_2018
  container-title: Handbuch Religionssoziologie
  DOI: 10.1007/978-3-531-18924-6_34
  editor:
    - family: Pollack
      given: Detlef
    - family: Krech
      given: Volkhard
    - family: Müller
      given: Olaf
    - family: Hero
      given: Markus
  event-place: Wiesbaden
  ISBN: 978-3-531-18924-6
  issued:
    - year: 2018
  language: de
  page: 833–859
  publisher: Springer Fachmedien Wiesbaden
  publisher-place: Wiesbaden
  title: Religion, Öffentlichkeit, Medien
  type: chapter
  URL: https://doi.org/10.1007/978-3-531-18924-6_34

- id: pollack_handbuch_2018
  citation-key: pollack_handbuch_2018
  collection-title: >-
    Veröffentlichungen der Sektion Religionssoziologie der Deutschen
    Gesellschaft für Soziologie
  DOI: 10.1007/978-3-531-18924-6
  editor:
    - family: Pollack
      given: Detlef
    - family: Krech
      given: Volkhard
    - family: Müller
      given: Olaf
    - family: Hero
      given: Markus
  event-place: Wiesbaden [Heidelberg]
  ISBN: 978-3-531-18924-6 978-3-531-17536-2
  issued:
    - year: 2018
  language: ger
  number-of-pages: '1067'
  publisher: Springer VS
  publisher-place: Wiesbaden [Heidelberg]
  source: K10plus ISBN
  title: Handbuch Religionssoziologie
  type: book

- id: reiter_reflektierte_2020a
  accessed:
    - year: 2022
      month: 4
      day: 6
  citation-key: reiter_reflektierte_2020a
  DOI: 10.1515/9783110693973
  editor:
    - family: Reiter
      given: Nils
    - family: Pichler
      given: Axel
    - family: Kuhn
      given: Jonas
  ISBN: 978-3-11-069397-3
  issued:
    - year: 2020
      month: 7
      day: 20
  language: de
  publisher: De Gruyter
  source: DOI.org (Crossref)
  title: >-
    Reflektierte algorithmische Textanalyse: Interdisziplinäre(s) Arbeiten in
    der CRETA-Werkstatt
  title-short: Reflektierte algorithmische Textanalyse
  type: book
  URL: https://www.degruyter.com/document/doi/10.1515/9783110693973/html

- id: schlette_heilige_2009
  author:
    - family: Schlette
      given: Magnus
  citation-key: schlette_heilige_2009
  container-author:
    - family: Thies
      given: C.
  container-title: Religiöse Erfahrung in der Moderne. William James und die Folgen
  event-place: Wiesbaden
  issued:
    - year: 2009
  language: de
  page: 109-132
  publisher: Harrassowitz
  publisher-place: Wiesbaden
  title: Das Heilige in der Moderne
  type: chapter

- id: schlette_sakralisierung_2018
  abstract: >-
    Der Artikel leistet eine Begriffsbestimmung von ‚Sakralisierung` als einer
    Prozesskategorie sozialen Wandels, die sich auf die Kommunikation des
    Heiligen in der symbolischen Selbstverständigung von Religionskollektiven
    sowie im Austausch zwischen der religiösen und den außerreligiösen sozialen
    Handlungssphären bezieht. Unter Sakralisierung ist demnach die Änderung
    einer etablierten Praxis der Zuschreibung von Heiligkeit zu verstehen,
    derzufolge neuen Entitäten im Spannungsverhältnis von Immanenz und
    Transzendenz Heiligkeit zuerkannt bzw. als heilig anerkannten Entitäten
    diese Eigenschaft abgesprochen wird. Der Sakralisierungsbegriff ist als
    Komplementärbegriff zum Begriff der Säkularisierung angelegt.
  author:
    - family: Schlette
      given: Magnus
    - family: Krech
      given: Volkhard
  citation-key: schlette_sakralisierung_2018
  container-title: Handbuch Religionssoziologie
  DOI: 10.1007/978-3-531-18924-6_17
  editor:
    - family: Pollack
      given: Detlef
    - family: Krech
      given: Volkhard
    - family: Müller
      given: Olaf
    - family: Hero
      given: Markus
  event-place: Wiesbaden
  ISBN: 978-3-531-18924-6
  issued:
    - year: 2018
  language: de
  page: 437–463
  publisher: Springer Fachmedien Wiesbaden
  publisher-place: Wiesbaden
  title: Sakralisierung
  type: chapter
  URL: https://doi.org/10.1007/978-3-531-18924-6_17

- id: stefanowitsch_corpus_2020
  abstract: >-
    Corpora are used widely in linguistics, but not always wisely. This book
    attempts to frame corpus linguistics systematically as a variant of the
    observational method. The first part introduces the reader to the general
    methodological discussions surrounding corpus data as well as the practice
    of doing corpus linguistics, including issues such as the scientific
    research cycle, research design, extraction of corpus data and statistical
    evaluation. The second part consists of a number of case studies from the
    main areas of corpus linguistics (lexical associations, morphology, grammar,
    text and metaphor), surveying the range of issues studied in corpus
    linguistics while at the same time showing how they fit into the methodology
    outlined in the first part
  author:
    - family: Stefanowitsch
      given: Anatol
  citation-key: stefanowitsch_corpus_2020
  collection-number: '7'
  collection-title: Textbooks in language sciences
  event-place: Berlin
  ISBN: 978-3-96110-224-2 978-3-96110-225-9 978-3-96110-226-6
  issued:
    - year: 2020
  language: eng
  number-of-pages: '490'
  publisher: Language Science Press
  publisher-place: Berlin
  source: K10plus ISBN
  title: 'Corpus linguistics: a guide to the methodology'
  title-short: Corpus linguistics
  type: book

- id: tyrell_religioide_2018
  abstract: >-
    Die Zeit um 1900 wird heute gern mit dem weitgreifenden Titel der „Moderne
    um 1900“ bedacht, und dass es mit dem ‚um 1900` etwas auf sich hat, lässt
    sich gerade auch in kulturell-religiöser Hinsicht aufweisen. Dies wird in
    einem ersten Gedankengang skizziert. Um 1900 war es Georg Simmel, der als
    erster nicht nur von einer „Soziologie der Religion“ gesprochen, sondern
    bereits 1898 eine solche auch gedanklich konzipiert hat. Ihr entstammt der
    1906 hinzugetretene Begriff des Religioiden. Die zweite Überlegung wendet
    sich der ‚religioiden` Begriffserfindung Simmels zu. Diese war seiner
    religionssoziologischen Leitidee verpflichtet. ‚Das Religioide` war also
    zunächst durchaus nicht auf die ‚religiöse Lage` der Zeit gemünzt; es ist
    zeitgenössisch allerdings so aufgefasst worden. Die dritte Überlegung
    bezieht sich auf den ersten der drei substantiellen Fälle, an denen Simmel
    seine religionssoziologische Konzeption verdeutlicht und expliziert hat: auf
    den religioiden Fall des Einander- bzw. Aneinanderglaubens. Es geht es um
    das bzw. den Glauben und damit um eine Begrifflichkeit, die selbst vielfach
    für das Religiöse einsteht. Simmel seinerseits trägt sein soziologisches
    Glaubensargument allerdings in einer semantischen Gestalt vor, die das
    Argument auch wieder in Schwierigkeiten bringt.
  author:
    - family: Tyrell
      given: Hartmann
  citation-key: tyrell_religioide_2018
  container-title: Georg Simmel und das Leben in der Gegenwart
  DOI: 10.1007/978-3-658-21427-2_19
  editor:
    - family: Lautmann
      given: Rüdiger
    - family: Wienold
      given: Hanns
  event-place: Wiesbaden
  ISBN: 978-3-658-21427-2
  issued:
    - year: 2018
  language: de
  page: 347–362
  publisher: Springer Fachmedien Wiesbaden
  publisher-place: Wiesbaden
  title: Das Religioide und der Glaube
  type: chapter
  URL: https://doi.org/10.1007/978-3-658-21427-2_19

- id: willems_religion_2018
  abstract: >-
    Die Anzeichen einer verstärkten Präsenz von religiösen Akteuren auf der
    politischen Bühne gegenwärtiger Gesellschaften seit den 1970er Jahren haben
    zu einem deutlichen Konjunkturaufschwung der sozialwissenschaftlichen
    Erforschung des Verhältnisses von Religion und Politik geführt. Allerdings
    sind viele der grundsätzlichen Fragen zur gegenwärtigen politischen Rolle
    der Religion nach wie vor unbeantwortet, die meisten der vorgeschlagenen
    Antworten umstritten. Das gilt etwa für die Bestimmung des Ausmaßes sowie
    der Ursachen der vermeintlichen oder wirklichen politischen Rückkehr der
    Religion. Umstritten ist auch, ob und inwieweit es sich bei dieser Rückkehr
    um eine defensive Reaktion auf Prozesse der Modernisierung und
    Globalisierung oder um produktive Selbsttransformationen religiöser
    Traditionen in einer grundlegend veränderten Umwelt handelt. Zu den offenen
    Fragen zählt zudem, ob und inwieweit Religion in gegenwärtigen
    Gesellschaften eine eigenständige politische Kraft ist oder doch nur eine zu
    politischen Zwecken ge- oder missbrauchte Ressource. Darüber hinaus wird
    kontrovers erörtert, ob und inwieweit sich die gegenwärtigen Entwicklungen
    noch mit den politischen Prognosen der klassischen Säkularisierungstheorie,
    also der Erwartung eines Rückgangs von Religion als empirischem Faktor der
    Politik, in Einklang bringen lassen oder zu einer mehr oder weniger
    grundlegenden Revision oder gar Aufgabe dieser Theorietradition nötigen?
    Schließlich ist auch nach wie vor umstritten, ob und inwieweit einzelne
    religiöse Traditionen mit den Erfordernissen demokratischer Praxis vereinbar
    sind und über ausreichende Fähigkeiten verfügen, sich auf die Existenz
    kulturell, religiös und moralisch pluraler Gesellschaften einzustellen. Der
    folgende Beitrag rekonstruiert und diskutiert diese Kontroversen vor dem
    Hintergrund der wesentlichen historischen Stationen der wechselvollen
    Geschichte des Verhältnisses von Religion und Politik.
  author:
    - family: Willems
      given: Ulrich
  citation-key: willems_religion_2018
  container-title: Handbuch Religionssoziologie
  DOI: 10.1007/978-3-531-18924-6_27
  editor:
    - family: Pollack
      given: Detlef
    - family: Krech
      given: Volkhard
    - family: Müller
      given: Olaf
    - family: Hero
      given: Markus
  event-place: Wiesbaden
  ISBN: 978-3-531-18924-6
  issued:
    - year: 2018
  language: de
  page: 659–692
  publisher: Springer Fachmedien Wiesbaden
  publisher-place: Wiesbaden
  title: Religion und Politik
  type: chapter
  URL: https://doi.org/10.1007/978-3-531-18924-6_27
...
