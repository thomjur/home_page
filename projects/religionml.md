---
title: religionml
author: thomas jurczyk
layout: article
exclude: true
---

## ReligionML Corpus Annotation Project for Machine Learning (1.1.8 / 17.12.2020)

### Link
[Link to the *ReligionML Corpus Annotation Project for Machine Learning* (currently password protected)](https://python.thomas-jurczyk.com/){:target="_blank"}

**Note that this site is currently password protected!**

If you wish to participate or access the page, please send an email to [contact@thomas-jurczyk.com](mailto:contact@thomas-jurczyk.com)

### Description
The *ReligionML* project has set itself the task of creating an
annotated corpus for the study of religion. The corpus data consists of
smaller text units (tweets, sentences, short paragraphs, etc.) and their
annotation on a word and sentence level. The annotation process focuses
on religious semantics and their syntactical as well as semantic
embedding. The annotated corpus data can be further used for automated
examinations with machine learning algorithms or analysis via classical
hermeneutical approaches.

A group of annotators at the Center for Religious Studies (CERES) in
Bochum is responsible for the annotation process. Since it is often
difficult to unambiguously assign semantic annotations, it is crucial
that as many people as possible take part in the annotation process.
There are currently five scholars from the field of religious studies
working on the text corpora\'s annotations.

Even though the annotations concentrate on aspects related to research
interests in the study of religion (such as the interrelation between
religion and other societal fields), they are not associated with a
particular research question. Instead, the annotations should be kept as
general as possible to apply to a great variety of research questions
ranging from applications in machine learning or corpus linguistics to
qualitative-hermeneutic approaches.

![Corpus structure]({{ site.baseurl }} {% link assets/images/corpus_structure.png %})

The *ReligionML* project is a Python web application created with [Flask](https://palletsprojects.com/p/flask/){:target="_blank"}.

### Corpus

The final corpus should represent a broad spectrum of religious and
religion-related sentences, paragraphs, and expressions deriving from
texts of historical and contemporary religions and other societal
fields. The corpus and the annotation process focus on sentences due to
the project\'s emphasis on religious semantics and their syntactic and
semantic embedding. Furthermore, the annotation of short paragraphs,
sentences, and words builds the basis for the classification and
annotation of larger documents. Thus, even though the corpus texts and
the annotation currently concentrate on the meso (paragraphs/sentences)
and micro (words) level, a later integration of larger documents remains
an option.

The data for the ReligionML corpus is currently collected by searching
for sentences in larger documents that include specific words hinting at
a potential religious context. The words that are currently searched
are:

a)  Words related to holiness (sacred, holy, holiness, etc.) and their
    *pendants* in other languages (for instance, *heilig* in German).

b)  Words related to religion (religion, religious) and their *pendants*
    in other languages (for instance, *Religion* in German).

c)  Words related to ritual (ritual, cult, etc.) and their *pendants* in
    other languages (for instance, Ritual in German).

d)  Words related to purity (purity, pure) and their *pendants* in other
    languages (for instance, *rein* in German).

The collected sentences are then further categorized by their a)
historical or contemporary background, b) language, c) religion, and
d) text genre (see also figure 1). The text genre should not be
understood in an exclusively literary sense. In this context, \"genre\"
refers to texts deriving from a common and shared context, which can
include stylistics, societal background, as well as \"Gattung.\"

Currently, the corpus only consists of English **tweets** (158,747),
sentences from the English **Wikipedia** (7,593), and sentences from
**newspaper articles** from several German and English news websites
that explicitly mention words related to:

a)  Holiness (e.g., holy, sacred, holiness)

b)  Religion (e.g., religion, religious)

c)  Ritual (e.g., ritual, cult)

d)  Purity (e.g., purity, pure)

These subcorpora are continually being expanded and updated. The
Wikipedia and the newspaper corpora have not been added to the
website\'s database yet. The current size of those corpora that have
already been integrated can be viewed under the menu item \"Corpus
Selection\" on the website. The annotation and corpus creation starts
with Twitter and Wikipedia data due to its accessibility and diverse use
cases of religious semantics. For instance, religious communication and
communication about religion on Twitter is often related to different
religions (Hinduism, Islam, Christianity, etc.) and stems from diverse
backgrounds (religion and politics, economy, art, polemics, etc.).

In the future, other text corpora will also be made available for
annotation, provided that they represent relevant examples of religious
communication for the study of religion. Suggestions for corpora can be
sent to [this mail address](mailto:contact@thomas-jurczyk.com). There must be no legal problems with
the provision of corpora.

### Annotation Scheme & Annotation Process

The annotation process is currently based on an in-house solution. We
use a web application available under python.thomas-jurczyk.com/ to
host, annotate, and store our data. The entire site is password
protected and thus only accessible to the group members.

If you want to test the website and the annotation, please send an email
to <contact@thomas-jurczyk.com>, and I will grant you access to the
annotation page.

The current registration methods are straightforward. To start the
annotation process, users must register a username and password
(providing an optional email address). After registration, users can log
in directly with their username and password (there is no need to accept
or confirm anything). If the login process was successful, the user
should select the desired corpus under the menu item \"Corpus
Selection.\" By default, the \"Twitter (Holy)\" corpus is selected.
Afterward, the annotation can be started under the menu item
\"Annotation.\"

The annotation process consists of two steps. The first step includes
the macrolayer, meaning the annotation of the full tweet or sentence.
The second step focuses on the microlayer and allows annotating single
words or word-groups in the tweet or sentence.

### Macro Annotation (Quantitative Annotation)

On the page for the macro annotation, the user is shown a tweet or
sentence, depending on the selected corpus. The users are given several
options to annotate the tweet/sentence:

a)  They may leave an optional comment for each tweet.

b)  Users can estimate the overall sentiment (positive, neutral, or
    negative) of the text.

c)  There is also an option to annotate specific religions relevant to
    the tweet or sentence (Christianity, Islam, Hinduism, etc.).

d)  Users are encouraged to proceed with the tweet/sentence\'s micro
    annotation, which occurs on a separate site (see below).

e)  Finally, users are asked to qualify the tweet or sentence with the
    help of (currently) five different categories (see also figure 2).
    Clicking one of these categories also functions as a \"submit\"
    button to the rest of the formula.

The five categories are:

*Inner-religion* means that the text has a religious meaning and was
stated from within religion. A typical example would be a Christian or
Muslim saying something about their belief.

*Religion-transcendence* means that although the text does not come from
an inner-religious sphere, the overall context is still referring to
religion as a social system dealing with the immanence/transcendence
distinction. A typical example are two non-religious persons talking
about religion as a worldview and religious truth claims compared to,
for instance, philosophical ones.

*Religion-immanence* means that the text still uses religious semantics
but more in the sense of a general distinction marker. A good example is
\"religion\" as an ethnic/political category.

*Metaphorical-use* means that the terminology is no longer directly
referring to \"religion\" but uses the \"religion\" domain in another
context. A typical example are sentences such as \"Electronic music is
my religion.\"

*No-religion* means that the text has nothing to do with religion at
all.

![ Quantitative Annotation (Macro)]({{ site.baseurl }} {% link assets/images/quantitative_annotation.png %})


### Micro Annotation (Qualitative Annotation)

The micro annotation page can be accessed via the button \'Qualitative
Annotation\' on the macro annotation page. Currently, the users can tag
single words and word-groups with:

a)  Sentiment (positive/negative)

b)  Semantic Domain Annotation System (SDAS)

The \"Semantic Domain Annotation System\" (SDAS) is currently based on
the three top domains: \"Society,\" \"World,\" and \"Mind.\" The current
subdivision of these domains is shown in figure 3. The SDAS is mainly
developed from an inductive perspective, meaning that the group members
add and discuss candidates for new categories based on their needs.
However, the integration of the new categories into the SDAS hierarchy
then also considers existing semantic hierarchies and other literature
on the development of annotation schemes (Bender 2020; Ide and
Pustejovsky 2017; Lordick et al. 2016; Pustejovsky, Bunt, and Zaenen
2017a; Reiter, Pichler, and Kuhn 2020). The inductive approach helps
avoid bloated hierarchies that include semantic fields never mentioned
in the data. However, we remain open to adding new categories whenever
we need.

A helpful feature on the \"Qualitative Annotation Page\" is the option
to pre-annotate the current tweet/sentence. If the users click
\"Pre-Annotate,\" the current tweet/sentence will be annotated based on
already existing word and word-group annotations by the user (in the
selected corpus). After annotating the words and word-groups, the users
may return to the macro annotation site to finish the annotation of the
current tweet or sentence.

Both schemes presented here are part of an iterative evaluation process
and will be further developed in the future.

If you encounter any problems or have suggestions, please send them to
<contact@thomas-jurczyk.com>.

![Micro Annotation]({{ site.baseurl }} {% link assets/images/qualitative_annotation.png %})

### Annotation Process

The annotation process is based on the comparison and discussion of
annotations made by different scholars in the study of religion.
Currently, the *ReligionML* group consists of five scholars with diverse
academic backgrounds who now work in religious studies. The overall
annotation process can be characterized as iterative. After several
weeks or months where the group members individually annotate the corpus
data via the web application, the annotation scheme is discussed and
evaluated during regular meetings. Afterward, potential changes to both
the annotation scheme and the website are implemented, and the
annotation process starts again. Besides discussing the annotation
scheme and the technical aspects, the meetings are also used to examine
the actual texts and think of potential use cases.

At the moment, the group does neither have a pre-defined \"gold
standard\" of the annotation scheme, nor do we intend to implement one
in the near future. Even though a high inter-annotator agreement is
desirable in some instances (for example, in the context of sentiment or
syntax tagging), we have decided to allow potentially ambiguous semantic
tagging by different annotators and accept it as part of the phenomenon
description of often ambiguous texts. However, the question remains in
how far this semantic ambiguity can and should also be reflected in the
automated filtering and classification of the data (see below).

### Querying the Corpus & Retrieving Data

The web application offers several options to query and retrieve the
(annotated) corpus data. Currently, the users can download their macro
annotations plus the corresponding tweets as .csv files. Additionally,
users can download an overview of all tweets/sentences in a corpus that
have been annotated at least once on the macro-level (including all
existing annotations). Further options to query and retrieve the corpus
data will be gradually implemented in the future.

### Machine Learning & Other Use Cases for the ReligionML Corpus

At present, the corpus annotation is still too preliminary to train
machine learning algorithms. However, the use cases of the annotated
corpus data are not restricted to machine learning approaches. Instead,
the annotated *ReligionML* corpus can be used to accomplish a great
variety of different tasks.

![Possible automated and manual analytical approaches]({{ site.baseurl }} {% link assets/images/approaches.png %})

### Querying and filtering the annotated corpus

The first use case is most likely the most intuitive one. The annotated
corpus will provide texts concerned with religion that can be queried
and selected with the existing annotations\' help. The *ReligionML*
corpus should provide an easy-to-use resource to look for specific
examples of religious communication when examining particular research
questions in the study of religion. For instance, users interested in
semantics related to \"holiness\" in different religions between past
and present should have the opportunity to query the *ReligionML* corpus
to obtain a representative and annotated data sample that they can then
further use in their research. Of course, the users can apply the
annotated data in whatever context they wish and are not restricted to
specific qualitative or automated approaches.

### Prediction and filtering of unknown data

The training of machine learning models with the annotated data should
enable the automated classification and annotation of unknown data. Of
course, the new data must have approximately the same format as the
corpus data on which the models were trained. This means that at least
according to the current structure of the *ReligionML* corpus, the
machine learning models will not predict and annotate long documents,
but only relatively short phrases or sentences. An excellent example in
this context is the pre-annotation and pre-filtering of newly collected
tweets from a Twitter streamer if the user is only interested in certain
topics related to religion, such as \"religion and politics.\" Here, the
users could apply the trained machine learning algorithms to filter the
newly received tweets for their specific needs.

### New perspectives on current research questions

The training of machine learning models and the general annotation of
the data also grant new insights into the use of religious terminology.
Firstly, the annotations\' statistics contribute exciting insights into
the data, for example, by providing an overview of the distribution of
certain word-groups or sentiments. To give an example of potential
questions in this context: Are inner-religious tweets or sentences more
positive than political communication about religion? Are there any
specific semantics or word-groups that allow the identification of
religious polemics? Secondly, a look at the machine learning models\'
trained parameters offers a detailed insight into the classifiers\'
decision-making process, thereby contributing to the question of
specific use cases of religious language as well.

