---
title: religionml
author: thomas jurczyk
layout: project
exclude: true
category: projects
---

<h2
id="religionml-corpus-annotation-project-for-machine-learning-april-14-2022">ReligionML:
Corpus Annotation Project for Machine Learning (May 21, 2022)</h2>
<h3 id="description">Description</h3>
<p>The ReligionML project has set itself the task of creating an
annotated text corpus for the study of religion. The corpus data
consists of smaller text units (sentences, short paragraphs, tweets,
etc.) which include central religious notions. These religious word
fields and their syntactic/semantic embedding will be annotated on a
word and sentence level. The final corpus should enable conducting
research questions dealing with the use and meaning of central religious
notions on both a qualitative and quantitative level (see the project <a
href="{{ site.baseurl }}{% link projects/religioid.md %}">A
Quantitative Analysis of the Dissemination of Religious Notions in
Contemporary English Texts</a>).</p>
<div id="fig:figure1" class="fignos">
<figure>
<img
src="{{ site.baseurl }}{% link assets/images/corpus_structure.png %}"
alt="Figure 1: Corpus structure." />
<figcaption aria-hidden="true"><span>Figure 1:</span> Corpus
structure.</figcaption>
</figure>
</div>
<p>A group of five religious studies’ scholars working at the <a
href="">Center for Religious Studies</a> at the Ruhr-Universität Bochum
conducted a pilot-project of ReligionML between 2019 and 2020. Yet, due
to COVID and other circumstances, the initial project stopped but should
again be taken up in the near future based on the previously made
experiences.</p>
<h3 id="corpus">Corpus</h3>
<p>The final corpus should consist of (annotated) sentences and
paragraphs deriving from both historical and contemporary texts that
include religious and religion-related notions, such as holy, pure,
religion, etc. The corpus and the annotation workflow focus on rather
small text units such as sentences due to the project's emphasis on
central religious notions and their syntactic/semantic embedding
(independent of the full document in which they appear in).</p>
<p>The data for the ReligionML corpus is currently collected by
searching for sentences in larger documents that include
religious/religioid words (mostly by using web scrapers or a Twitter
streamer). The words that are currently included in the search are:</p>
<ol type="a">
<li><p> Words related to the word field of holiness (“sacred,” “holy,”
“holiness,” etc.) and their <em>pendants</em> in other languages (for
instance, “heilig” in German).</p></li>
<li><p> Words related to religion (“religion,” “religious”) and their
<em>pendants</em> in other languages (for instance, “Religion” in
German).</p></li>
<li><p> Words related to ritual (“ritual,” “cult,” etc.) and their
<em>pendants</em> in other languages (for instance, “Ritual” in
German).</p></li>
<li><p> Words related to purity (“purity,” “pure”) and their
<em>pendants</em> in other languages (for instance, “rein” in
German).</p></li>
</ol>
<p>The collected sentences during the automatized scraping process are
categorized by their a) historical or contemporary background, b)
language, c) religion, d) societal field, and e) text genre (see also
figure <a href="#fig:figure1">1</a>).</p>
<p>Currently, the corpus consists of English <strong>tweets</strong>
(158,747), sentences from the English <strong>Wikipedia</strong>
(7,593), and sentences from <strong>newspaper articles</strong> from
several German and English websites that explicitly mention words
related to the above-mentioned terms.</p>
<p>The corpus and the subcorpora will continuously be expanded and
updated.</p>
<h3
id="annotation-scheme-annotation-process-annotation-platform">Annotation
Scheme &amp; Annotation Process (Annotation Platform)</h3>
<p>The initial annotation workflow conducted at the <a
href="https://ceres.rub.de/en/">Center for Religious Studies</a> between
2019 and 2020 was based on an in-house solution written in Python (using
Flask as a web framework). Even though this initial platform produced
promising first results, it yet had several flaws. One goal of the
current research project is to establish a new annotation platform
(using Django) that can be used by both the annotators and a wider
audience to annotate and discuss the corpus texts. The major ideas
behind the new annotation workflow are:</p>
<ol type="1">
<li>Using an in-house web application to annotate the texts on the macro
layer (see below).</li>
<li>Combining the in-house solution with existing software solutions for
the qualitative analysis (such as CATMA or existing JavaScript
frameworks for text annotation, which should ideally be implemented on
the website).</li>
<li>Creating an annotation scheme using SKOS and RDF with the potential
to embed the annotation results within a broader context (linked open
data).</li>
</ol>
<h3 id="macro-annotation-quantitative-annotation">Macro Annotation
(Quantitative Annotation)</h3>
<p>During the macro annotation workflow on the project website, the
annotator is shown a tweet, sentence, or paragraph (called document in
the following part) from the ReligionML corpus (according to the
subcorpus selected by the annotator). Among others, the annotation
options should include the following aspects:</p>
<ol type="a">
<li><p>(Optional) Users may leave a comment for the selected
document.</p></li>
<li><p>(Obligatory) Users must estimate the sentiment of the document
(positive, neutral, or negative).</p></li>
<li><p>(Obligatory) Users should annotate specific religions relevant to
the document (Christianity, Islam, Hinduism, no religion,
etc.).</p></li>
<li><p>(Optional) Users are encouraged to proceed with the document’s
micro annotation, which occurs on a separate site (see below).</p></li>
<li><p>(Obligatory) Users need to select the societal spheres prevailing
in this document (religion, politics, economics, art, etc.).</p></li>
<li><p>(Obligatory) Finally, users are asked to qualify the tweet or
sentence with the help of (currently) five different categories to
estimate the religious, religioid, or irreligious character of the
selected document.</p></li>
</ol>
<p>The five categories in the final step are:</p>
<p><em>Inner-religion</em> means that the selected document has a
religious meaning and was stated from within religion. A typical example
would be a Christian or Muslim writing/saying something about their
belief.</p>
<p><em>Religion-transcendence</em> means that although the document does
not come from an inner-religious sphere, the overall context is still
referring to religion as a social system dealing with the
immanence/transcendence distinction. A typical example are two
non-religious persons talking about religion as a worldview and
religious truth claims compared to, for instance, philosophical
ones. This category also includes religious polemics and mockery.</p>
<p><em>Religion-immanence</em> means that the document still uses
religious semantics but more in the sense of a general distinction
marker. A good example is "religion" as an ethnic/political
category. The boundaries between <em>Religion-transcendence</em> and <em>Religion-immanence</em> are particularly blurry when dealing with religiously motivated extremism or 'theocratic' governments. The attribution to either of these categories has to be decided on a case to case basis.</p>
<p><em>Metaphorical-use</em> means that the religious terminology in the
document is no longer directly referring to "religion" but uses the
"religion" domain in another context. A typical example are sentences
such as "Electronic music is my religion."</p>
<p><em>No-religion</em> means that the document is not related to
religion or has no religious or religioid meaning.</p>
<h3 id="micro-annotation-qualitative-annotation">Micro Annotation
(Qualitative Annotation)</h3>
<p>The micro annotation page should be reachable from the page of the
macro annotation and enable the annotators to add annotations on a word
level. Potential tags should indicate the sentiment
(positive/negative) and include tags from the <em>Semantic Domain
Annotation System</em> (SDAS).</p>
<p>The <em>Semantic Domain Annotation System</em> (SDAS) is currently
based on three top domains: "Society," "World," and "Mind." The current
subdivision of these domains is shown in figure <a
href="#fig:figure3">3</a>. The SDAS is mainly developed from an
inductive perspective, meaning that the users annotating the documents
add and discuss candidates for new categories based on their needs.</p>
<p>However, the integration of the new categories into the SDAS
hierarchy should also consider existing semantic hierarchies and
literature on the development of annotation schemes <span
class="citation"
data-cites="reiter_reflektierte_2020a bender_annotation_2020a dash_language_2021 ide_handbook_2017c lordick_digitale_2016a">(<a
href="#ref-reiter_reflektierte_2020a" role="doc-biblioref">Reiter,
Pichler, and Kuhn 2020</a>; <a href="#ref-bender_annotation_2020a"
role="doc-biblioref">Bender 2020</a>; <a href="#ref-dash_language_2021"
role="doc-biblioref">Dash 2021</a>; <a href="#ref-ide_handbook_2017c"
role="doc-biblioref">Ide and Pustejovsky 2017</a>; <a
href="#ref-lordick_digitale_2016a" role="doc-biblioref">Lordick et al.
2016</a>)</span>. It should also facilitate the integration into other
hierarchies and ontologies via RDF and LOD. The inductive approach helps
avoiding bloated hierarchies that include semantic fields never
mentioned in the data by simultaneously remaining open for new
categories.</p>
<p>A helpful feature that was already part of the initial web
application was the "Pre-Annotation" option that allowed pre-annotating
the currently selected documents based on previous annotations. It makes
the annotation process much faster, while also enabling to reflect
previous annotations in view of new data.</p>
<p>Both schemes presented here are part of an iterative evaluation
process and will be further developed in the future.</p>
<div id="fig:figure2" class="fignos">
<figure>
<img
src="{{ site.baseurl }}{% link assets/images/qualitative_annotation.png %}"
alt="Figure 2: Micro annotation." />
<figcaption aria-hidden="true"><span>Figure 2:</span> Micro
annotation.</figcaption>
</figure>
</div>
<h3 id="collaborative-parts-of-the-annotation-workflow">Collaborative
Parts of the Annotation Workflow</h3>
<p>The annotation workflow is accompanied by the comparison and
discussion of the annotations made by the users.</p>
<p>The initial ReligionML group consisted of five scholars with diverse
academic backgrounds who all ended up working in religious studies. The
overall annotation workflow can be characterized as iterative. After
several weeks or months when the group members individually annotated
the corpus data via the web application, the annotation scheme was
discussed and evaluated during regular meetings. Afterward, potential
changes to both the annotation scheme and the website were
implemented.</p>
<p>The group did not agree on a pre-defined "gold standard" of the
annotation scheme, which was a deliberate decision. Yet, this procedure
might change once a more or less fixed annotation scheme has been
established. Even though a high inter-annotator agreement is generally
desirable in some instances (for example, in the context of sentiment or
syntax tagging), accepting potentially ambiguous semantic tagging by
different annotators might in the case of ReligionML also be regarded as
a necessary part of the workflow that helps to better understand the use
and meaning of religious notions in various contexts.</p>
<h3 id="querying-the-corpus-retrieving-data">Querying the Corpus &amp;
Retrieving Data</h3>
<p>The new web application should offer possibilities to query and
retrieve the (annotated) corpus data. The users should be able to
download both the corpus and the (meta) data deriving from the
annotations via a structured REST API or as simple CSV files. This step
underlines the necessity to use anonymized and licence-free data
only.</p>
<h3
id="machine-learning-other-use-cases-of-the-religionml-corpus">Machine
Learning &amp; Other Use Cases of the ReligionML Corpus</h3>
<p>At present, the corpus annotation is still too preliminary to train
machine learning algorithms. However, the use cases of the annotated
corpus data are not restricted to machine learning approaches. Instead,
the annotated ReligionML corpus can be used to accomplish a great
variety of different tasks.</p>
<div id="fig:figure3" class="fignos">
<figure>
<img
src="{{ site.baseurl }}{% link assets/images/approaches.png %}"
alt="Figure 3: Possible automated and manual analytical approaches." />
<figcaption aria-hidden="true"><span>Figure 3:</span> Possible automated
and manual analytical approaches.</figcaption>
</figure>
</div>
<p>The following parts will outline some potential future use cases of
the ReligionML corpus. For a more concrete example, see the already
mentioned <a
href="{{ site.baseurl }}{% link projects/religioid.md %}">A
Quantitative Analysis of the Dissemination of Religious Notions in
Contemporary English Texts</a>.</p>
<h3
id="use-case-i-querying-and-filtering-the-annotated-religionml-corpus">Use
Case I: Querying and Filtering the Annotated ReligionML Corpus</h3>
<p>The first use case is most likely the most intuitive one. The corpus
will provide documents with religious notions that can be queried and
filtered using the annotations. The ReligionML corpus should provide an
easy-to-use resource to look for specific examples of the application of
religious notions in different contexts. For instance, users interested
in words and documents related to "holiness" in different religions
between past and present should have the opportunity to query the
ReligionML corpus to obtain a representative and annotated data sample
that they can then further use in their research. Of course, the users
can apply the annotated data in whatever context they wish and are not
restricted to specific qualitative or automated approaches.</p>
<h3 id="use-case-ii-predicting-and-filtering-unknown-data">Use Case II:
Predicting and Filtering Unknown Data</h3>
<p>The training of machine learning models with the annotated data
should enable the automated classification and annotation of unknown
data. Of course, the unknown data must have approximately the same
format as the corpus data on which the models were trained. This means
that at least according to the current structure of the ReligionML
corpus, the machine learning models will not predict and annotate long
documents, but only relatively short phrases or sentences. An excellent
example in this context is the pre-annotation and pre-filtering of newly
collected tweets from a Twitter streamer if the user is only interested
in certain topics related to religious terminologies, such as "religion
and politics." In this example, the users could apply the trained
machine learning algorithms to filter the the Twitter data for their
specific needs.</p>
<h3 id="use-case-iii-new-perspectives-on-current-research-questions">Use
Case III: New Perspectives on Current Research Questions</h3>
<p>The training of machine learning models and the annotation of
the data also grant new insights into the use of religious terminology.
Firstly, the annotations' statistics contribute exciting insights into
the data, for example, by providing an overview of the distribution of
certain word-groups or sentiments. To give an example of potential
questions in this context: Are inner-religious tweets or sentences more
positive than political communication about religion? Are there any
specific semantics or word-groups that allow the identification of
religious polemics? Secondly, a look at the machine learning models'
trained parameters offers a detailed insight into the classifiers'
decision-making process, thereby contributing to the question of
specific use cases of religious language as well.</p>

<h2>Bibliography</h2>

<div id="refs" class="references csl-bib-body hanging-indent"
role="doc-bibliography">
<div id="ref-bender_annotation_2020a" class="csl-entry"
role="doc-biblioentry">
Bender, Michael. 2020. <span>“Annotation als Methode der digitalen
Diskurslinguistik.”</span> <em>Diskurse – digital</em> Bd. 2 Nr. 1
(April): 1–35 Seiten. <a
href="https://doi.org/10.25521/DISKURSE-DIGITAL.2020.140">https://doi.org/10.25521/DISKURSE-DIGITAL.2020.140</a>.
</div>
<div id="ref-dash_language_2021" class="csl-entry"
role="doc-biblioentry">
Dash, Niladri Sekhar. 2021. <em>Language corpora annotation and
processing</em>. Singapore: Springer.
</div>
<div id="ref-ide_handbook_2017c" class="csl-entry"
role="doc-biblioentry">
Ide, Nancy, and James Pustejovsky, eds. 2017. <em>Handbook of Linguistic
Annotation</em>. 1st ed. 2017. Dordrecht: Springer Netherlands :
Imprint: Springer. <a
href="https://doi.org/10.1007/978-94-024-0881-2">https://doi.org/10.1007/978-94-024-0881-2</a>.
</div>
<div id="ref-lordick_digitale_2016a" class="csl-entry"
role="doc-biblioentry">
Lordick, Harald, Rainer Becker, Michael Bender, Luise Borek, Canan
Hastik, Thomas Kollatz, Beata Mache, Andrea Rapp, Ruth Reiche, and
Niels-Oliver Walkowski. 2016. <span>“Digitale Annotationen in Der
Geisteswissenschaftlichen Praxis.”</span> <em>Bibliothek Forschung Und
Praxis</em> 40 (2). <a
href="https://doi.org/10.1515/bfp-2016-0042">https://doi.org/10.1515/bfp-2016-0042</a>.
</div>
<div id="ref-reiter_reflektierte_2020a" class="csl-entry"
role="doc-biblioentry">
Reiter, Nils, Axel Pichler, and Jonas Kuhn, eds. 2020. <em>Reflektierte
Algorithmische Textanalyse: Interdisziplinäre(s) Arbeiten in Der
CRETA-Werkstatt</em>. De Gruyter. <a
href="https://doi.org/10.1515/9783110693973">https://doi.org/10.1515/9783110693973</a>.
</div>
</div>
