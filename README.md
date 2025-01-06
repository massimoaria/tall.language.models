Pre-Trained Annotation Models for TALL
================

## Overview

**TALL - *Text Analysis for ALL***
(<https://github.com/massimoaria/tall>) is an R Shiny application that
provides a comprehensive suite of methodologies for various text
analysis tasks. It is designed to meet the needs of researchers who may
lack extensive programming skills, offering a versatile and
user-friendly tool for analyzing textual data. With TALL, users can
apply a wide range of text analysis techniques, making it easier to
extract valuable insights from textual data in an efficient and
accessible manner.

**TALL** leverages the `udpipe` library for preprocessing, tokenization,
lemmatization, and parsing of raw texts. The `udpipe` R package allows
users to easily tokenize, tag, lemmatize, and perform dependency parsing
on texts in multiple languages by providing convenient access to
pre-trained annotation models. Built-in udpipe models are based on
Universal Dependencies (UD) version 2.5 and had not been updated in some
time.

This repository, `udpipe.models`, provides updated pre-trained NLP
language models, trained on gold standard annotated corpora from the
[Universal Dependencies](https://universaldependencies.org/) (UD)
project, version 2.15, using the `udpipe` R package ([CRAN
link](https://CRAN.R-project.org/package=udpipe)).

The models are intended for use in Natural Language Processing (NLP)
tasks, including tokenization, parsing, and tagging. This repository
serves as a resource for researchers and developers working with TALL
([Tall GitHub repository](https://github.com/massimoaria/tall)).

## Purpose

The primary objectives of this repository are:

- To provide updated pre-trained `udpipe` models for a wide range of
  languages, aligned with the latest version of the UD corpora (2.15).
- To facilitate reproducible NLP research and applications by making
  these models readily available.
- To support projects that use Universal Dependencies data for
  tokenization, parsing, and tagging tasks in R and other environments.

## Data Source

The gold standard annotated corpora used to train these models are
sourced from the Universal Dependencies project ([Universal Dependencies
GitHub repository](https://github.com/UniversalDependencies)).

Universal Dependencies is a community-driven initiative that offers
high-quality annotated corpora in the standardized CoNLL-U format for
many languages. The models in this repository are trained specifically
on data from version 2.15.

## Available Pre-Trained Models

| Language | Treebank | Contributors | Description | File | Link |
|:---|:---|:---|:---|:---|:---|
| English | EWT | Natalia Silveira, Timothy Dozat, Christopher Manning, Sebastian Schuster, Ethan Chi, John Bauer, Miriam Connor, Marie-Catherine de Marneffe, Nathan Schneider, Sam Bowman, Hanzhi Zhu, Daniel Galbraith, John Bauer | A Gold Standard Universal Dependencies Corpus for English, | en_ewt-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/en_ewt/index.html" target="_blank">Link</a> |
| English | GUM | Siyao Peng, Amir Zeldes | Universal Dependencies syntax annotations from the GUM corpus (<https://gucorpling.org/gum/>) | en_gum-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/en_gum/index.html" target="_blank">Link</a> |
| English | LinES | Lars Ahrenberg | UD English_LinES is the English half of the LinES Parallel Treebank | en_lines-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/en_lines/index.html" target="_blank">Link</a> |
| English | ParTUT | Cristina Bosco, Manuela Sanguinetti | UD_English-ParTUT is a conversion of a multilingual parallel treebank developed at the University of Turin, | en_partut-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/en_partut/index.html" target="_blank">Link</a> |
| Italian | ISDT | Cristina Bosco, Alessandro Lenci, Simonetta Montemagni, Maria Simi | The Italian corpus annotated according to the UD annotation scheme was obtained by conversion from ISDT (Italian Stanford Dependency Treebank), released for the dependency parsing shared task of Evalita-2014 (Bosco et al. 2014). | it_isdt-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/it_isdt/index.html" target="_blank">Link</a> |
| Italian | ParTUT | Cristina Bosco, Manuela Sanguinetti | UD_Italian-ParTUT is a conversion of a multilingual parallel treebank developed at the University of Turin, | it_partut-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/it_partut/index.html" target="_blank">Link</a> |
| Italian | PoSTWITA | Cristina Bosco, Manuela Sanguinetti | PoSTWITA-UD is a collection of Italian tweets annotated in Universal Dependencies that can be exploited for the training of NLP systems to enhance their performance on social media texts. | it_postwita-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/it_postwita/index.html" target="_blank">Link</a> |
| Italian | TWITTIRO | Alessandra T. Cignarella, Cristina Bosco, Manuela Sanguinetti | TWITTIRÒ-UD is a collection of ironic Italian tweets annotated in Universal Dependencies. | it_twittiro-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/it_twittiro/index.html" target="_blank">Link</a> |
| Italian | VIT | Fabio Tamburini, Maria Simi, Cristina Bosco | The UD_Italian-VIT corpus was obtained by conversion from VIT (Venice Italian Treebank), developed at the Laboratory of Computational Linguistics of the Università Ca’ Foscari in Venice (Delmonte et al. 2007; Delmonte 2009; <http://rondelmo.it/resource/VIT/Browser-VIT/index.htm>). | it_vit-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/it_vit/index.html" target="_blank">Link</a> |
| Spanish | AnCora | Héctor Martínez Alonso, Daniel Zeman | Spanish data from the [AnCora](http://clic.ub.edu/corpus/) corpus. | es_ancora-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/es_ancora/index.html" target="_blank">Link</a> |
| Spanish | GSD | Miguel Ballesteros, Héctor Martínez Alonso, Ryan McDonald, Elena Pascual, Natalia Silveira, Daniel Zeman, Joakim Nivre | The Spanish UD is converted from the content head version of the \[universal | es_gsd-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/es_gsd/index.html" target="_blank">Link</a> |
| French | GSD | Marie-Catherine de Marneffe, Bruno Guillaume, Ryan McDonald, Alane Suhr, Joakim Nivre, Matias Grioni, Carly Dickerson, Guy Perrier | The **UD_French-GSD** was converted in 2015 from the content head version of the universal | fr_gsd-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/fr_gsd/index.html" target="_blank">Link</a> |
| French | ParTUT | Cristina Bosco, Manuela Sanguinetti | UD_French-ParTUT is a conversion of a multilingual parallel treebank developed at the University of Turin, | fr_partut-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/fr_partut/index.html" target="_blank">Link</a> |
| French | Sequoia | Marie Candito, Djamé Seddah, Guy Perrier, Bruno Guillaume | **UD_French-Sequoia** is an automatic conversion of the [SUD_French-Sequoia](https://github.com/surfacesyntacticud/SUD_French-Sequoia) treebank, which comes from the former corpus [French Sequoia corpus](http://deep-sequoia.inria.fr). | fr_sequoia-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/fr_sequoia/index.html" target="_blank">Link</a> |
| German | GSD | Slav Petrov, Wolfgang Seeker, Ryan McDonald, Joakim Nivre, Daniel Zeman, Adriane Boyd | The German UD is converted from the content head version of the \[universal | de_gsd-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/de_gsd/index.html" target="_blank">Link</a> |
| German | HDT | Emanuel Borges Völker, Felix Hennig, Arne Köhn, Maximilan Wendt, Verena Blaschke, Nina Böbel, Leonie Weissweiler | UD German-HDT is a conversion of the Hamburg Dependency Treebank, created at the University of Hamburg through manual annotation in conjunction with a standard for morphologically and syntactically annotating sentences as well as a constraint-based parser. | de_hdt-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/de_hdt/index.html" target="_blank">Link</a> |
| Chinese | GSD | Mo Shen, Ryan McDonald, Daniel Zeman, Peng Qi | Traditional Chinese Universal Dependencies Treebank annotated and converted by | zh_gsd-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/zh_gsd/index.html" target="_blank">Link</a> |
| Chinese | GSDSimp | Peng Qi, Koichi Yasuoka | Simplified Chinese Universal Dependencies dataset converted from the GSD (traditional) dataset with manual corrections. | zh_gsdsimp-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/zh_gsdsimp/index.html" target="_blank">Link</a> |
| Afrikaans | AfriBooms | Peter Dirix, Liesbeth Augustinus, Daniel van Niekerk | UD Afrikaans-AfriBooms is a conversion of the AfriBooms Dependency Treebank, originally annotated with a simplified PoS set and dependency relations according to a subset of the Stanford tag set. The corpus consists of public government documents. | af_afribooms-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/af_afribooms/index.html" target="_blank">Link</a> |
| Ancient Greek | Perseus | Giuseppe G. A. Celano, Daniel Zeman | This Universal Dependencies Ancient Greek Treebank consists of an automatic conversion of a selection of passages from the Ancient Greek and Latin Dependency Treebank 2.1 | grc_perseus-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/grc_perseus/index.html" target="_blank">Link</a> |
| Ancient Greek | PROIEL | Dag Haug | UD_Ancient_Greek-PROIEL is converted from the Ancient Greek data in the PROIEL treebank, and consists of the New Testament plus selections from Herodotus. | grc_proiel-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/grc_proiel/index.html" target="_blank">Link</a> |
| Arabic | PADT | Daniel Zeman, Zdeněk Žabokrtský, Shadi Saleh | The Arabic-PADT UD treebank is based on the | ar_padt-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/ar_padt/index.html" target="_blank">Link</a> |
| Armenian | ArmTDP | Marat M. Yavrumyan | A Universal Dependencies treebank for Eastern Armenian developed for UD originally by the ArmTDP team led by Marat M. Yavrumyan at the Yerevan State University. | hy_armtdp-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/hy_armtdp/index.html" target="_blank">Link</a> |
| Basque | BDT | Maria Jesus Aranzabe, Aitziber Atutxa, Kepa Bengoetxea, Arantza Diaz de Ilarraza, Iakes Goenaga, Koldo Gojenola, Larraitz Uria | The Basque UD treebank is based on a automatic conversion from part of the Basque Dependency Treebank (BDT), created at the University of of the Basque Country by the IXA NLP research group. The treebank consists of 8.993 sentences (121.443 tokens) and covers mainly literary and journalistic texts. | eu_bdt-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/eu_bdt/index.html" target="_blank">Link</a> |
| Belarusian | HSE | Olga Lyashevskaya, Angelika Peljak-Łapińska, Daria Petrova, Yana Shishkina | The Belarusian UD treebank is based on a sample of the news texts included in the Belarusian-Russian parallel subcorpus of the Russian National Corpus, | be_hse-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/be_hse/index.html" target="_blank">Link</a> |
| Bulgarian | BTB | Kiril Simov, Petya Osenova, Martin Popel | UD_Bulgarian-BTB is based on the HPSG-based BulTreeBank, | bg_btb-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/bg_btb/index.html" target="_blank">Link</a> |
| Catalan | AnCora | Héctor Martínez Alonso, Elena Pascual, Daniel Zeman | Catalan data from the [AnCora](http://clic.ub.edu/corpus/) corpus. | ca_ancora-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/ca_ancora/index.html" target="_blank">Link</a> |
| Classical Chinese | Kyoto | Koichi Yasuoka, Christian Wittern, Tomohiko Morioka, Takumi Ikeda, Naoki Yamazaki, Yoshihiro Nikaido, Shingo Suzuki, Shigeki Moro, Yuan Li, Hiroyuki Shirasu, Kazunori Fujita | Classical Chinese Universal Dependencies Treebank annotated and converted by Institute for Research in Humanities, Kyoto University. | lzh_kyoto-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/lzh_kyoto/index.html" target="_blank">Link</a> |
| Coptic | Scriptorium | Mitchell Abrams, Elizabeth Davidson, Amir Zeldes | UD Coptic contains manually annotated Sahidic Coptic texts, including Biblical texts, sermons, letters, and hagiography. | cop_scriptorium-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/cop_scriptorium/index.html" target="_blank">Link</a> |
| Croatian | SET | Željko Agić, Nikola Ljubešić, Daniel Zeman | The Croatian UD treebank is based on the extension of the SETimes-HR corpus, the [hr500k](http://hdl.handle.net/11356/1183) corpus. | hr_set-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/hr_set/index.html" target="_blank">Link</a> |
| Czech | CAC | Barbora Hladká, Daniel Zeman | The UD_Czech-CAC treebank is based on the Czech Academic Corpus 2.0 (CAC; | cs_cac-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/cs_cac/index.html" target="_blank">Link</a> |
| Czech | CLTT | Barbora Hladká, Daniel Zeman, Martin Popel | The UD_Czech-CLTT treebank is based on the Czech Legal Text Treebank 2.0, | cs_cltt-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/cs_cltt/index.html" target="_blank">Link</a> |
| Czech | FicTree | Tomáš Jelínek, Daniel Zeman | FicTree is a treebank of Czech fiction, automatically converted into the UD | cs_fictree-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/cs_fictree/index.html" target="_blank">Link</a> |
| Czech | PDT | Daniel Zeman, Jan Hajič | The Czech-PDT UD treebank is based on the Prague Dependency Treebank – Consolidated 1.0 | cs_pdt-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/cs_pdt/index.html" target="_blank">Link</a> |
| Danish | DDT | Anders Johannsen, Héctor Martínez Alonso, Barbara Plank | The Danish UD treebank is a conversion of the Danish Dependency Treebank. | da_ddt-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/da_ddt/index.html" target="_blank">Link</a> |
| Dutch | Alpino | Daniel Zeman, Zdeněk Žabokrtský, Gosse Bouma, Gertjan van Noord | This corpus consists of samples from various treebanks annotated at the University of Groningen using the Alpino annotation tools and guidelines. | nl_alpino-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/nl_alpino/index.html" target="_blank">Link</a> |
| Dutch | LassySmall | Gosse Bouma, Gertjan van Noord | This corpus contains sentences from the Wikipedia section of the Lassy Small Treebank. | nl_lassysmall-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/nl_lassysmall/index.html" target="_blank">Link</a> |
| Estonian | EDT | Kadri Muischnek, Kaili Müürisep, Tiina Puolakainen, Andriela Rääbis, Liisi Torga | UD Estonian is a converted version of the Estonian Dependency Treebank (EDT), originally annotated in the Constraint Grammar (CG) annotation scheme, and consisting of genres of fiction, newspaper texts and scientific texts. The treebank contains 30,972 trees, 437,769 tokens. | et_edt-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/et_edt/index.html" target="_blank">Link</a> |
| Estonian | EWT | Kadri Muischnek, Kaili Müürisep, Tiina Puolakainen, Dage Särg, Sandra Eiche, Andriela Rääbis | UD EWT treebank consists of different genres of new media. The treebank contains 7,190 trees, 90,585 tokens. | et_ewt-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/et_ewt/index.html" target="_blank">Link</a> |
| Finnish | FTB | Jussi Piitulainen, Hanna Nurmi, Jack Rueter | FinnTreeBank 1 consists of manually annotated grammatical examples | fi_ftb-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/fi_ftb/index.html" target="_blank">Link</a> |
| Finnish | TDT | Filip Ginter, Jenna Kanerva, Veronika Laippala, Niko Miekka, Anna Missilä, Stina Ojala, Sampo Pyysalo | UD_Finnish-TDT is based on the Turku Dependency Treebank (TDT), a broad-coverage dependency treebank of general Finnish covering numerous genres. The conversion to UD was followed by extensive manual checks and corrections, and the treebank closely adheres to the UD guidelines. | fi_tdt-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/fi_tdt/index.html" target="_blank">Link</a> |
| Galician | CTG | Xavier Gómez Guinovart | The Galician UD treebank is based on the automatic parsing of the Galician Technical Corpus (<http://sli.uvigo.gal/CTG>) created at the University of Vigo by the the TALG NLP research group. | gl_ctg-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/gl_ctg/index.html" target="_blank">Link</a> |
| Galician | TreeGal | Marcos Garcia, Xulia Sánchez-Rodríguez | The Galician-TreeGal is a treebank for Galician developed at LyS Group (Universidade da Coruña) and at CiTIUS (Universidade de Santiago de Compostela). | gl_treegal-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/gl_treegal/index.html" target="_blank">Link</a> |
| Gothic | PROIEL | Dag Haug | The UD Gothic treebank is based on the Gothic data from the PROIEL treebank, and consists of Wulfila’s Bible translation. | got_proiel-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/got_proiel/index.html" target="_blank">Link</a> |
| Greek | GDT | Prokopis Prokopidis | The Greek UD treebank (UD_Greek-GDT) is derived from the Greek Dependency Treebank | el_gdt-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/el_gdt/index.html" target="_blank">Link</a> |
| Hebrew | HTB | Yoav Goldberg, Reut Tsarfaty, Amir More, Shoval Sadde, Victoria Basmov, Yuval Pinter | A Universal Dependencies Corpus for Hebrew. | he_htb-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/he_htb/index.html" target="_blank">Link</a> |
| Hindi | HDTB | Riyaz Ahmad Bhat, Daniel Zeman | The Hindi UD treebank is based on the Hindi Dependency Treebank (HDTB), | hi_hdtb-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/hi_hdtb/index.html" target="_blank">Link</a> |
| Hungarian | Szeged | Richárd Farkas, Katalin Simkó, Zsolt Szántó, Viktor Varga, Veronika Vincze | The Hungarian UD treebank is derived from the Szeged Dependency Treebank (Vincze et al. 2010). | hu_szeged-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/hu_szeged/index.html" target="_blank">Link</a> |
| Indonesian | GSD | Ryan McDonald, Joakim Nivre, Daniel Zeman, Septina Dian Larasati, Ika Alfina | The Indonesian-GSD treebank was originally converted from the content head version of the [universal dependency treebank v2.0 (legacy)](https://github.com/ryanmcd/uni-dep-tb) in 2015. In order to comply with the latest Indonesian annotation guidelines, the treebank has undergone a major revision between UD releases v2.8 and v2.9 (2021). | id_gsd-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/id_gsd/index.html" target="_blank">Link</a> |
| Irish | IDT | Teresa Lynn, Jennifer Foster, Sarah McGuinness, Abigail Walsh, Jason Phelan, Kevin Scannell | A Universal Dependencies 4910-sentence treebank for modern Irish. | ga_idt-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/ga_idt/index.html" target="_blank">Link</a> |
| Japanese | GSD | Mai Omura, Yusuke Miyao, Hiroshi Kanayama, Hiroshi Matsuda, Aya Wakasa, Kayo Yamashita, Masayuki Asahara, Takaaki Tanaka, Yugo Murawaki, Yuji Matsumoto, Shinsuke Mori, Sumire Uematsu, Ryan McDonald, Joakim Nivre, Daniel Zeman | This Universal Dependencies (UD) Japanese treebank is based on the definition of UD Japanese convention described in the UD documentation. The original sentences are from Google UDT 2.0. | ja_gsd-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/ja_gsd/index.html" target="_blank">Link</a> |
| Korean | GSD | Ryan McDonald, Joakim Nivre, Daniel Zeman, Jinho Choi, Na-Rae Han, Jena Hwang, Jayeol Chun | The Google Korean Universal Dependency Treebank is first converted from the \[Universal | ko_gsd-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/ko_gsd/index.html" target="_blank">Link</a> |
| Korean | Kaist | Jinho Choi, Na-Rae Han, Jena Hwang, Jayeol Chun | The KAIST Korean Universal Dependency Treebank is generated by Chun et al., 2018 from the constituency trees in the [KAIST Tree-Tagging Corpus](http://semanticweb.kaist.ac.kr/home/index.php/Corpus4). | ko_kaist-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/ko_kaist/index.html" target="_blank">Link</a> |
| Latin | ITTB | Marco Passarotti, Marinella Testori, Daniel Zeman, Berta González Saavedra, Flavio Massimiliano Cecchini | Latin data from the *Index Thomisticus* Treebank. Data are taken from the *Index Thomisticus* corpus by Roberto Busa SJ, which contains the complete work by Thomas Aquinas (1225–1274; Medieval Latin) and by 61 other authors related to Thomas. | la_ittb-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/la_ittb/index.html" target="_blank">Link</a> |
| Latin | Perseus | Giuseppe G. A. Celano, Daniel Zeman, Federica Gamba | This Universal Dependencies Latin Treebank consists of an automatic conversion of a selection of passages from the Ancient Greek and Latin Dependency Treebank 2.1 | la_perseus-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/la_perseus/index.html" target="_blank">Link</a> |
| Latin | PROIEL | Dag Haug | The Latin PROIEL treebank is based on the Latin data from the PROIEL treebank, and contains most of the Vulgate New Testament translations plus selections from Caesar’s Gallic War, Cicero’s Letters to Atticus, Palladius’ Opus Agriculturae and the first book of Cicero’s De officiis. | la_proiel-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/la_proiel/index.html" target="_blank">Link</a> |
| Latvian | LVTB | Lauma Pretkalniņa, Laura Rituma, Gunta Nešpore-Bērzkalne, Baiba Saulīte, Artūrs Znotiņš, Normunds Grūzītis | Latvian UD Treebank is based on Latvian Treebank ([LVTB](http://sintakse.korpuss.lv)), being created at University of Latvia, Institute of Mathematics and Computer Science, [Artificial Intelligence Laboratory](http://ailab.lv). | lv_lvtb-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/lv_lvtb/index.html" target="_blank">Link</a> |
| Lithuanian | ALKSNIS | Andrius Utka, Erika Rimkutė, Agnė Bielinskienė, Jolanta Kovalevskaitė, Loïc Boizou, Gabrielė Aleksandravičiūtė, Kristina Brokaitė, Daniel Zeman, Natalia Perkova, Bernadeta Griciūtė | The Lithuanian dependency treebank ALKSNIS v3.0 (Vytautas Magnus University). | lt_alksnis-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/lt_alksnis/index.html" target="_blank">Link</a> |
| Lithuanian | HSE | Olga Lyashevskaya, Dmitri Sitchinava | Lithuanian treebank annotated manually (dependencies) using the Morphological Annotator by CCL, Vytautas Magnus University (<http://tekstynas.vdu.lt/>) and manual disambiguation. | lt_hse-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/lt_hse/index.html" target="_blank">Link</a> |
| Maltese | MUDT | Slavomír Čéplö, Daniel Zeman | MUDT (Maltese Universal Dependencies Treebank) is a manually annotated treebank of Maltese, a Semitic language of Malta descended from North African Arabic with a significant amount of Italo-Romance influence. | mt_mudt-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/mt_mudt/index.html" target="_blank">Link</a> |
| Marathi | UFAL | Vinit Ravishankar | UD Marathi is a manually annotated treebank consisting primarily of stories from Wikisource, and parts of an article on Wikipedia. | mr_ufal-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/mr_ufal/index.html" target="_blank">Link</a> |
| Norwegian | Bokmaal | Lilja Øvrelid, Fredrik Jørgensen, Petter Hohle, Ingerid Løyning Dale, Per Erik Solberg, Andre Kåsen | The Norwegian UD treebank is based on the Bokmål section of the Norwegian | no_bokmaal-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/no_bokmaal/index.html" target="_blank">Link</a> |
| Norwegian | Nynorsk | Lilja Øvrelid, Fredrik Jørgensen, Petter Hohle, Ingerid Løyning Dale, Per Erik Solberg, Andre Kåsen | The Norwegian UD treebank is based on the Nynorsk section of the Norwegian | no_nynorsk-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/no_nynorsk/index.html" target="_blank">Link</a> |
| Old Church Slavonic | PROIEL | Dag Haug | The Old Church Slavonic (OCS) UD treebank is based on canonical Old Church Slavonic data from the PROIEL and TOROT treebanks. | cu_proiel-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/cu_proiel/index.html" target="_blank">Link</a> |
| Persian | Seraji | Mojgan Seraji, Filip Ginter, Joakim Nivre, Martin Popel, Daniel Zeman | The Persian Universal Dependency Treebank (Seraji) is based on Uppsala Persian Dependency Treebank (UPDT). | fa_seraji-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/fa_seraji/index.html" target="_blank">Link</a> |
| Polish | LFG | Agnieszka Patejuk, Adam Przepiórkowski | The LFG Enhanced UD treebank of Polish is based on a corpus of LFG (Lexical Functional Grammar) syntactic structures generated by an LFG grammar of Polish, POLFIE, and manually disambiguated by human annotators. | pl_lfg-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/pl_lfg/index.html" target="_blank">Link</a> |
| Polish | PDB | Alina Wróblewska, Daniel Zeman, Jan Mašek, Rudolf Rosa | The Polish PDB-UD treebank is automatically converted from the Polish Dependency Bank 2.0 (PDB 2.0). Both treebanks were created at the [Institute of Computer Science, Polish Academy of Sciences](https://ipipan.waw.pl/en/) in Warsaw (Poland). | pl_pdb-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/pl_pdb/index.html" target="_blank">Link</a> |
| Portuguese | Bosque | Alexandre Rademaker, Cláudia Freitas, Elvis de Souza, Aline Silveira, Tatiana Cavalcanti, Wograine Evelyn, Luisa Rocha, Isabela Soares-Bastos, Eckhard Bick, Fabricio Chalub, Guilherme Paulino-Passos, Livy Real, Valeria de Paiva, Daniel Zeman, Martin Popel, David Mareček, Natalia Silveira, André Martins | This Universal Dependencies (UD) Portuguese treebank is based on the | pt_bosque-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/pt_bosque/index.html" target="_blank">Link</a> |
| Portuguese | GSD | Alexandre Rademaker, Ryan McDonald, Joakim Nivre, Daniel Zeman, Fabricio Chalub, Carlos Ramisch, Juan Belieni, Vanessa Berwanger Wille, Rodrigo Pintucci | The Brazilian Portuguese UD is converted from the \[Google Universal Dependency | pt_gsd-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/pt_gsd/index.html" target="_blank">Link</a> |
| Romanian | Nonstandard | Cătălina Mărănduc, Cenel-Augusto Perez, Victoria Bobicev, Cătălin Mititelu, Florinel Hociung, Valentin Roșca, Roman Untilov, Petru Rebeja | The Romanian Non-standard UD treebank (called UAIC-RoDia) is based on UAIC-RoDia Treebank. UAIC-RoDia = ISLRN 156-635-615-024-0 | ro_nonstandard-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/ro_nonstandard/index.html" target="_blank">Link</a> |
| Romanian | RRT | Verginica Barbu Mititelu, Elena Irimia, Cenel-Augusto Perez, Radu Ion, Radu Simionescu, Martin Popel | The Romanian UD treebank (called RoRefTrees) (Barbu Mititelu et al., 2016) is the reference treebank in UD format for standard Romanian. | ro_rrt-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/ro_rrt/index.html" target="_blank">Link</a> |
| Russian | GSD | Ryan McDonald, Vitaly Nikolaev, Olga Lyashevskaya | Russian Universal Dependencies Treebank annotated and converted by Google. | ru_gsd-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/ru_gsd/index.html" target="_blank">Link</a> |
| Russian | SynTagRus | Kira Droganova, Olga Lyashevskaya, Daniel Zeman | Russian data from the SynTagRus corpus. | ru_syntagrus-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/ru_syntagrus/index.html" target="_blank">Link</a> |
| Russian | Taiga | Olga Lyashevskaya, Olga Rudina, Natalia Vlasova, Anna Zhuravleva | Universal Dependencies treebank is based on data samples extracted from Taiga Corpus and MorphoRuEval-2017 and GramEval-2020 shared tasks collections. | ru_taiga-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/ru_taiga/index.html" target="_blank">Link</a> |
| Scottish Gaelic | ARCOSG | Colin Batchelor | A treebank of Scottish Gaelic based on the [Annotated Reference Corpus Of Scottish Gaelic (ARCOSG)](https://github.com/Gaelic-Algorithmic-Research-Group/ARCOSG). | gd_arcosg-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/gd_arcosg/index.html" target="_blank">Link</a> |
| Serbian | SET | Tanja Samardžić, Nikola Ljubešić | The Serbian UD treebank is based on the [SETimes-SR](http://hdl.handle.net/11356/1200) corpus and | sr_set-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/sr_set/index.html" target="_blank">Link</a> |
| Slovak | SNK | Katarína Gajdošová, Mária Šimková, Daniel Zeman | The Slovak UD treebank is based on data originally annotated as part of the | sk_snk-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/sk_snk/index.html" target="_blank">Link</a> |
| Slovenian | SSJ | Kaja Dobrovoljc, Tomaž Erjavec, Simon Krek | The SSJ treebank is the reference UD treebank for Slovenian, consisting of approximately 13,000 sentences and 267,097 tokens from fiction, non-fiction, periodical and Wikipedia texts in standard modern Slovenian. As of UD release 2.10 in May 2022, the original version of the SSJ UD treebank has been partially manually revised and extended with new manually annotated data. | sl_ssj-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/sl_ssj/index.html" target="_blank">Link</a> |
| Slovenian | SST | Kaja Dobrovoljc, Joakim Nivre | The Spoken Slovenian Treebank (SST) is a manually annotated collection of transcribed audio recordings featuring spontaneous speech in various everyday situations. It includes 344 unique speech events (documents) amounting to approximately 10 hours of speech, encompassing a total of 6,108 utterances and 98,396 tokens. | sl_sst-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/sl_sst/index.html" target="_blank">Link</a> |
| Swedish | LinES | Lars Ahrenberg | UD Swedish_LinES is the Swedish half of the LinES Parallel Treebank with UD annotations. | sv_lines-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/sv_lines/index.html" target="_blank">Link</a> |
| Swedish | Talbanken | Joakim Nivre, Aaron Smith, Victor Norrman | The Swedish-Talbanken treebank is based on Talbanken, a treebank developed at Lund University | sv_talbanken-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/sv_talbanken/index.html" target="_blank">Link</a> |
| Tamil | TTB | Loganathan Ramasamy, Daniel Zeman | The UD Tamil treebank is based on the Tamil Dependency Treebank created at the | ta_ttb-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/ta_ttb/index.html" target="_blank">Link</a> |
| Telugu | MTG | Taraka Rama, Sowmya Vajjala | The Telugu UD treebank is created in UD based on manual annotations of sentences from a grammar book. | te_mtg-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/te_mtg/index.html" target="_blank">Link</a> |
| Turkish | IMST | Utku Türk, Şaziye Betül Özateş, Büşra Marşan, Salih Furkan Akkurt, Çağrı Çöltekin, Gülşen Cebiroğlu Eryiğit, Memduh Gökırmak, Hüner Kaşıkara, Umut Sulubacak, Francis Tyers | The UD Turkish Treebank, also called the IMST-UD Treebank, is a semi-automatic conversion of the IMST Treebank (Sulubacak&Eryiğit, 2018; Sulubacak et al., 2016). | tr_imst-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/tr_imst/index.html" target="_blank">Link</a> |
| Ukrainian | IU | Natalia Kotsyba, Bohdan Moskalevskyi, Mykhailo Romanenko | Gold standard Universal Dependencies corpus for Ukrainian, developed for UD originally, by [Institute for Ukrainian](https://mova.institute), NGO. \[[українською](https://mova.institute/золотий_стандарт)\] | uk_iu-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/uk_iu/index.html" target="_blank">Link</a> |
| Urdu | UDTB | Riyaz Ahmad Bhat, Daniel Zeman | The Urdu Universal Dependency Treebank was automatically converted from Urdu Dependency Treebank (UDTB) which is part of an ongoing effort of creating multi-layered treebanks for Hindi and Urdu. | ur_udtb-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/ur_udtb/index.html" target="_blank">Link</a> |
| Uyghur | UDT | Marhaba Eli, Daniel Zeman, Francis Tyers | The Uyghur UD treebank is based on the Uyghur Dependency Treebank (UDT), | ug_udt-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/ug_udt/index.html" target="_blank">Link</a> |
| Vietnamese | VTB | Lương Nguyễn Thị, Linh Hà Mỹ, Phương Lê Hồng, Huyền Nguyễn Thị Minh | The Vietnamese UD treebank is a conversion of the constituent treebank created in the VLSP project | vi_vtb-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/vi_vtb/index.html" target="_blank">Link</a> |
| Wolof | WTB | Bamba Dione | UD_Wolof-WTB is a natively manual developed treebank for Wolof. Sentences were collected from encyclopedic, fictional, biographical, religious texts and news. | wo_wtb-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/wo_wtb/index.html" target="_blank">Link</a> |

## Acknowledgements

The models were trained using [UDpipe R
package](https://CRAN.R-project.org/package=udpipe) on [Universal
Dependencies 2.15 treebanks](https://universaldependencies.org/).

## Structure

The repository is organized as follows:

- **`2.15/`**: Contains pre-trained `udpipe` models for individual
  languages. Each model file is named according to the corresponding
  language and the version of the Universal Dependencies data used.
- **`README.rmd`**: This document provides an overview of the
  repository’s contents and purpose (rmarkdown format).
- **`README.md`**: This document provides an overview of the
  repository’s contents and purpose (github format).
- **`README.html`**: This document provides an overview of the
  repository’s contents and purpose (html format).

## Using the Models

To use these models, simply install **TALL**, which will automatically
handle the downloading of the pre-trained model required for analyzing
your corpus.

``` r
# Install the remotes package if not already installed (uncomment the next line removing #)
# install.packages("remotes")

remotes::install_github("massimoaria/tall")

library(tall)

tall()
```
