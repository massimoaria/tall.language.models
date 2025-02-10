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

This repository, `tall.language.models`, provides updated pre-trained
NLP language models, trained on gold standard annotated corpora from the
[Universal Dependencies](https://universaldependencies.org/) (UD)
project, version 2.15, using the `udpipe` R package ([CRAN
link](https://CRAN.R-project.org/package=udpipe)).

Additionally, the repository now includes:

- Example datasets in the sample.data folder, which can be used to test
  and explore TALL functionalities.
- Lexicon datasets in the lexicon.data folder, providing additional
  resources for linguistic analysis and enrichment of textual data in
  TALL.

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
- To enrich TALL’s text analysis capabilities by providing example and
  lexicon datasets for hands-on testing and experimentation.

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
| Afrikaans | AfriBooms | Peter Dirix, Liesbeth Augustinus, Daniel van Niekerk | UD Afrikaans-AfriBooms is a conversion of the AfriBooms Dependency Treebank, originally annotated with a simplified PoS set and dependency relations according to a subset of the Stanford tag set. The corpus consists of public government documents. | af_afribooms-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/af_afribooms/index.html> |
| Ancient Greek | PROIEL | Dag Haug | UD_Ancient_Greek-PROIEL is converted from the Ancient Greek data in the PROIEL treebank, and consists of the New Testament plus selections from Herodotus. | grc_proiel-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/grc_proiel/index.html> |
| Ancient Greek | Perseus | Giuseppe G. A. Celano, Daniel Zeman | This Universal Dependencies Ancient Greek Treebank consists of an automatic conversion of a selection of passages from the Ancient Greek and Latin Dependency Treebank 2.1. | grc_perseus-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/grc_perseus/index.html> |
| Arabic | PADT | Daniel Zeman, Zdeněk Žabokrtský, Shadi Saleh | The Arabic-PADT UD treebank is based on the | ar_padt-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/ar_padt/index.html> |
| Armenian | ArmTDP | Marat M. Yavrumyan | A Universal Dependencies treebank for Eastern Armenian developed for UD originally by the ArmTDP team led by Marat M. Yavrumyan at the Yerevan State University. | hy_armtdp-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/hy_armtdp/index.html> |
| Basque | BDT | Maria Jesus Aranzabe, Aitziber Atutxa, Kepa Bengoetxea, Arantza Diaz de Ilarraza, Iakes Goenaga, Koldo Gojenola, Larraitz Uria | The Basque UD treebank is based on a automatic conversion from part of the Basque Dependency Treebank (BDT), created at the University of of the Basque Country by the IXA NLP research group. The treebank consists of 8.993 sentences (121.443 tokens) and covers mainly literary and journalistic texts. | eu_bdt-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/eu_bdt/index.html> |
| Belarusian | HSE | Olga Lyashevskaya, Angelika Peljak-Łapińska, Daria Petrova, Yana Shishkina | The Belarusian UD treebank is based on a sample of the news texts included in the Belarusian-Russian parallel subcorpus of the Russian National Corpus, | be_hse-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/be_hse/index.html> |
| Bulgarian | BTB | Kiril Simov, Petya Osenova, Martin Popel | UD_Bulgarian-BTB is based on the HPSG-based BulTreeBank. | bg_btb-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/bg_btb/index.html> |
| Catalan | AnCora | Héctor Martínez Alonso, Elena Pascual, Daniel Zeman | Catalan data from the [AnCora](http://clic.ub.edu/corpus/) corpus. | ca_ancora-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/ca_ancora/index.html> |
| Chinese | GSD | Mo Shen, Ryan McDonald, Daniel Zeman, Peng Qi | Traditional Chinese Universal Dependencies Treebank annotated and converted by Google. | zh_gsd-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/zh_gsd/index.html> |
| Chinese | GSDSimp | Peng Qi, Koichi Yasuoka | Simplified Chinese Universal Dependencies dataset converted from the GSD (traditional) dataset with manual corrections. | zh_gsdsimp-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/zh_gsdsimp/index.html> |
| Classical Chinese | Kyoto | Koichi Yasuoka, Christian Wittern, Tomohiko Morioka, Takumi Ikeda, Naoki Yamazaki, Yoshihiro Nikaido, Shingo Suzuki, Shigeki Moro, Yuan Li, Hiroyuki Shirasu, Kazunori Fujita | Classical Chinese Universal Dependencies Treebank annotated and converted by Institute for Research in Humanities, Kyoto University. | lzh_kyoto-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/lzh_kyoto/index.html> |
| Coptic | Scriptorium | Mitchell Abrams, Elizabeth Davidson, Amir Zeldes | UD Coptic contains manually annotated Sahidic Coptic texts, including Biblical texts, sermons, letters, and hagiography. | cop_scriptorium-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/cop_scriptorium/index.html> |
| Croatian | SET | Željko Agić, Nikola Ljubešić, Daniel Zeman | The Croatian UD treebank is based on the extension of the SETimes-HR corpus, the [hr500k](http://hdl.handle.net/11356/1183) corpus. | hr_set-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/hr_set/index.html> |
| Czech | CAC | Barbora Hladká, Daniel Zeman | The UD_Czech-CAC treebank is based on the Czech Academic Corpus 2.0 (CAC) created at Charles University in Prague. | cs_cac-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/cs_cac/index.html> |
| Czech | CLTT | Barbora Hladká, Daniel Zeman, Martin Popel | The UD_Czech-CLTT treebank is based on the Czech Legal Text Treebank 2.0, | cs_cltt-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/cs_cltt/index.html> |
| Czech | FicTree | Tomáš Jelínek, Daniel Zeman | FicTree is a treebank of Czech fiction, automatically converted into the UD format. The treebank was built at Charles University in Prague. | cs_fictree-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/cs_fictree/index.html> |
| Czech | PDT | Daniel Zeman, Jan Hajič | The Czech-PDT UD treebank is based on the Prague Dependency Treebank – Consolidated 1.0, created at the Charles University in Prague. | cs_pdt-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/cs_pdt/index.html> |
| Danish | DDT | Anders Johannsen, Héctor Martínez Alonso, Barbara Plank | The Danish UD treebank is a conversion of the Danish Dependency Treebank. | da_ddt-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/da_ddt/index.html> |
| Dutch | Alpino | Daniel Zeman, Zdeněk Žabokrtský, Gosse Bouma, Gertjan van Noord | This corpus consists of samples from various treebanks annotated at the University of Groningen using the Alpino annotation tools and guidelines. | nl_alpino-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/nl_alpino/index.html> |
| Dutch | LassySmall | Gosse Bouma, Gertjan van Noord | This corpus contains sentences from the Wikipedia section of the Lassy Small Treebank. | nl_lassysmall-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/nl_lassysmall/index.html> |
| English | EWT | Natalia Silveira, Timothy Dozat, Christopher Manning, Sebastian Schuster, Ethan Chi, John Bauer, Miriam Connor, Marie-Catherine de Marneffe, Nathan Schneider, Sam Bowman, Hanzhi Zhu, Daniel Galbraith, John Bauer | A Gold Standard Universal Dependencies Corpus for English, built over the source material of the English Web Treebank LDC2012T13 (<https://catalog.ldc.upenn.edu/LDC2012T13>). | en_ewt-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/en_ewt/index.html> |
| English | GUM | Siyao Peng, Amir Zeldes | Universal Dependencies syntax annotations from the GUM corpus (<https://gucorpling.org/gum/>) | en_gum-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/en_gum/index.html> |
| English | LinES | Lars Ahrenberg | UD English_LinES is the English half of the LinES Parallel Treebank with the original dependency annotation first automatically converted into Universal Dependencies and then partially reviewed. Its contents cover literature, an online manual and Europarl data. | en_lines-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/en_lines/index.html> |
| English | ParTUT | Cristina Bosco, Manuela Sanguinetti | UD_English-ParTUT is a conversion of a multilingual parallel treebank developed at the University of Turin, and consisting of a variety of text genres, including talks, legal texts and Wikipedia articles, among others. | en_partut-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/en_partut/index.html> |
| Estonian | EDT | Kadri Muischnek, Kaili Müürisep, Tiina Puolakainen, Andriela Rääbis, Liisi Torga | UD Estonian is a converted version of the Estonian Dependency Treebank (EDT), originally annotated in the Constraint Grammar (CG) annotation scheme, and consisting of genres of fiction, newspaper texts and scientific texts. The treebank contains 30,972 trees, 437,769 tokens. | et_edt-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/et_edt/index.html> |
| Estonian | EWT | Kadri Muischnek, Kaili Müürisep, Tiina Puolakainen, Dage Särg, Sandra Eiche, Andriela Rääbis | UD EWT treebank consists of different genres of new media. The treebank contains 7,190 trees, 90,585 tokens. | et_ewt-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/et_ewt/index.html> |
| Finnish | FTB | Jussi Piitulainen, Hanna Nurmi, Jack Rueter | FinnTreeBank 1 consists of manually annotated grammatical examples from VISK. The UD version of FinnTreeBank 1 was converted from a native annotation model with a script and later manually revised. | fi_ftb-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/fi_ftb/index.html> |
| Finnish | TDT | Filip Ginter, Jenna Kanerva, Veronika Laippala, Niko Miekka, Anna Missilä, Stina Ojala, Sampo Pyysalo | UD_Finnish-TDT is based on the Turku Dependency Treebank (TDT), a broad-coverage dependency treebank of general Finnish covering numerous genres. The conversion to UD was followed by extensive manual checks and corrections, and the treebank closely adheres to the UD guidelines. | fi_tdt-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/fi_tdt/index.html> |
| French | GSD | Marie-Catherine de Marneffe, Bruno Guillaume, Ryan McDonald, Alane Suhr, Joakim Nivre, Matias Grioni, Carly Dickerson, Guy Perrier | The UD_French-GSD was converted in 2015 from the content head version of the universal dependency treebank v2.0 (<https://github.com/ryanmcd/uni-dep-tb>). It is updated since 2015 independently from the previous source. | fr_gsd-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/fr_gsd/index.html> |
| French | ParTUT | Cristina Bosco, Manuela Sanguinetti | UD_French-ParTUT is a conversion of a multilingual parallel treebank developed at the University of Turin, and consisting of a variety of text genres, including talks, legal texts and Wikipedia articles, among others. | fr_partut-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/fr_partut/index.html> |
| French | Sequoia | Marie Candito, Djamé Seddah, Guy Perrier, Bruno Guillaume | **UD_French-Sequoia** is an automatic conversion of the [SUD_French-Sequoia](https://github.com/surfacesyntacticud/SUD_French-Sequoia) treebank, which comes from the former corpus [French Sequoia corpus](http://deep-sequoia.inria.fr). | fr_sequoia-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/fr_sequoia/index.html> |
| Galician | CTG | Xavier Gómez Guinovart | The Galician UD treebank is based on the automatic parsing of the Galician Technical Corpus (<http://sli.uvigo.gal/CTG>) created at the University of Vigo by the the TALG NLP research group. | gl_ctg-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/gl_ctg/index.html> |
| German | GSD | Slav Petrov, Wolfgang Seeker, Ryan McDonald, Joakim Nivre, Daniel Zeman, Adriane Boyd | The German UD is converted from the content head version of the [universal dependency treebank v2.0 (legacy)](https://github.com/ryanmcd/uni-dep-tb). | de_gsd-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/de_gsd/index.html> |
| German | HDT | Emanuel Borges Völker, Felix Hennig, Arne Köhn, Maximilan Wendt, Verena Blaschke, Nina Böbel, Leonie Weissweiler | UD German-HDT is a conversion of the Hamburg Dependency Treebank, created at the University of Hamburg through manual annotation in conjunction with a standard for morphologically and syntactically annotating sentences as well as a constraint-based parser. | de_hdt-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/de_hdt/index.html> |
| Gothic | PROIEL | Dag Haug | The UD Gothic treebank is based on the Gothic data from the PROIEL treebank, and consists of Wulfila’s Bible translation. | got_proiel-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/got_proiel/index.html> |
| Greek | GDT | Prokopis Prokopidis | The Greek UD treebank (UD_Greek-GDT) is derived from the Greek Dependency Treebank. | el_gdt-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/el_gdt/index.html> |
| Hebrew | HTB | Yoav Goldberg, Reut Tsarfaty, Amir More, Shoval Sadde, Victoria Basmov, Yuval Pinter | A Universal Dependencies Corpus for Hebrew. | he_htb-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/he_htb/index.html> |
| Hindi | HDTB | Riyaz Ahmad Bhat, Daniel Zeman | The Hindi UD treebank is based on the Hindi Dependency Treebank (HDTB), created at IIIT Hyderabad, India. | hi_hdtb-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/hi_hdtb/index.html> |
| Hungarian | Szeged | Richárd Farkas, Katalin Simkó, Zsolt Szántó, Viktor Varga, Veronika Vincze | The Hungarian UD treebank is derived from the Szeged Dependency Treebank (Vincze et al. 2010). | hu_szeged-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/hu_szeged/index.html> |
| Indonesian | GSD | Ryan McDonald, Joakim Nivre, Daniel Zeman, Septina Dian Larasati, Ika Alfina | The Indonesian-GSD treebank was originally converted from the content head version of the [universal dependency treebank v2.0 (legacy)](https://github.com/ryanmcd/uni-dep-tb) in 2015. In order to comply with the latest Indonesian annotation guidelines, the treebank has undergone a major revision between UD releases v2.8 and v2.9 (2021). | id_gsd-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/id_gsd/index.html> |
| Irish | IDT | Teresa Lynn, Jennifer Foster, Sarah McGuinness, Abigail Walsh, Jason Phelan, Kevin Scannell | A Universal Dependencies 4910-sentence treebank for modern Irish. | ga_idt-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/ga_idt/index.html> |
| Italian | ISDT | Cristina Bosco, Alessandro Lenci, Simonetta Montemagni, Maria Simi | The Italian corpus annotated according to the UD annotation scheme was obtained by conversion from ISDT (Italian Stanford Dependency Treebank), released for the dependency parsing shared task of Evalita-2014 (Bosco et al. 2014). | it_isdt-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/it_isdt/index.html> |
| Italian | ParTUT | Cristina Bosco, Manuela Sanguinetti | UD_Italian-ParTUT is a conversion of a multilingual parallel treebank developed at the University of Turin, and consisting of a variety of text genres, including talks, legal texts and Wikipedia articles, among others. | it_partut-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/it_partut/index.html> |
| Italian | PoSTWITA | Cristina Bosco, Manuela Sanguinetti | PoSTWITA-UD is a collection of Italian tweets annotated in Universal Dependencies that can be exploited for the training of NLP systems to enhance their performance on social media texts. | it_postwita-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/it_postwita/index.html> |
| Italian | TWITTIRO | Alessandra T. Cignarella, Cristina Bosco, Manuela Sanguinetti | TWITTIRÒ-UD is a collection of ironic Italian tweets annotated in Universal Dependencies. The treebank can be exploited for the training of NLP systems to enhance their performance on social media texts, and in particular, for irony detection purposes. | it_twittiro-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/it_twittiro/index.html> |
| Italian | VIT | Fabio Tamburini, Maria Simi, Cristina Bosco | The UD_Italian-VIT corpus was obtained by conversion from VIT (Venice Italian Treebank), developed at the Laboratory of Computational Linguistics of the Università Ca’ Foscari in Venice (Delmonte et al. 2007; Delmonte 2009; <http://rondelmo.it/resource/VIT/Browser-VIT/index.htm>). | it_vit-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/it_vit/index.html> |
| Japanese | GSD | Mai Omura, Yusuke Miyao, Hiroshi Kanayama, Hiroshi Matsuda, Aya Wakasa, Kayo Yamashita, Masayuki Asahara, Takaaki Tanaka, Yugo Murawaki, Yuji Matsumoto, Shinsuke Mori, Sumire Uematsu, Ryan McDonald, Joakim Nivre, Daniel Zeman | This Universal Dependencies (UD) Japanese treebank is based on the definition of UD Japanese convention described in the UD documentation. The original sentences are from Google UDT 2.0. | ja_gsd-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/ja_gsd/index.html> |
| Korean | GSD | Ryan McDonald, Joakim Nivre, Daniel Zeman, Jinho Choi, Na-Rae Han, Jena Hwang, Jayeol Chun | The Google Korean Universal Dependency Treebank is first converted from the [Universal Dependency Treebank v2.0 (legacy)](https://github.com/ryanmcd/uni-dep-tb), and then enhanced by Chun et al., 2018. | ko_gsd-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/ko_gsd/index.html> |
| Korean | Kaist | Jinho Choi, Na-Rae Han, Jena Hwang, Jayeol Chun | The KAIST Korean Universal Dependency Treebank is generated by Chun et al., 2018 from the constituency trees in the [KAIST Tree-Tagging Corpus](http://semanticweb.kaist.ac.kr/home/index.php/Corpus4). | ko_kaist-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/ko_kaist/index.html> |
| Latin | ITTB | Marco Passarotti, Marinella Testori, Daniel Zeman, Berta González Saavedra, Flavio Massimiliano Cecchini | Latin data from the *Index Thomisticus* Treebank. Data are taken from the *Index Thomisticus* corpus by Roberto Busa SJ, which contains the complete work by Thomas Aquinas (1225–1274; Medieval Latin) and by 61 other authors related to Thomas. | la_ittb-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/la_ittb/index.html> |
| Latin | PROIEL | Dag Haug | The Latin PROIEL treebank is based on the Latin data from the PROIEL treebank, and contains most of the Vulgate New Testament translations plus selections from Caesar’s Gallic War, Cicero’s Letters to Atticus, Palladius’ Opus Agriculturae and the first book of Cicero’s De officiis. | la_proiel-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/la_proiel/index.html> |
| Latvian | LVTB | Lauma Pretkalniņa, Laura Rituma, Gunta Nešpore-Bērzkalne, Baiba Saulīte, Artūrs Znotiņš, Normunds Grūzītis | Latvian UD Treebank is based on Latvian Treebank ([LVTB](http://sintakse.korpuss.lv)), being created at University of Latvia, Institute of Mathematics and Computer Science, [Artificial Intelligence Laboratory](http://ailab.lv). | lv_lvtb-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/lv_lvtb/index.html> |
| Lithuanian | ALKSNIS | Andrius Utka, Erika Rimkutė, Agnė Bielinskienė, Jolanta Kovalevskaitė, Loïc Boizou, Gabrielė Aleksandravičiūtė, Kristina Brokaitė, Daniel Zeman, Natalia Perkova, Bernadeta Griciūtė | The Lithuanian dependency treebank ALKSNIS v3.0 (Vytautas Magnus University). | lt_alksnis-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/lt_alksnis/index.html> |
| Lithuanian | HSE | Olga Lyashevskaya, Dmitri Sitchinava | Lithuanian treebank annotated manually (dependencies) using the Morphological Annotator by CCL, Vytautas Magnus University (<http://tekstynas.vdu.lt/>) and manual disambiguation. | lt_hse-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/lt_hse/index.html> |
| Maltese | MUDT | Slavomír Čéplö, Daniel Zeman | MUDT (Maltese Universal Dependencies Treebank) is a manually annotated treebank of Maltese, a Semitic language of Malta descended from North African Arabic with a significant amount of Italo-Romance influence. | mt_mudt-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/mt_mudt/index.html> |
| Marathi | UFAL | Vinit Ravishankar | UD Marathi is a manually annotated treebank consisting primarily of stories from Wikisource, and parts of an article on Wikipedia. | mr_ufal-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/mr_ufal/index.html> |
| Norwegian | Bokmaal | Lilja Øvrelid, Fredrik Jørgensen, Petter Hohle, Ingerid Løyning Dale, Per Erik Solberg, Andre Kåsen | The Norwegian UD treebank is based on the Bokmål section of the Norwegian Dependency Treebank (NDT), which is a syntactic treebank of Norwegian. The current version of NDT has been automatically converted to the UD scheme by Ingerid Løyning Dale, Per Erik Solberg and Andre Kåsen at the Norwegian Language Bank at the National Library of Norway. This conversion builds to a large extent on previous conversions by Lilja Øvrelid at the University of Oslo. | no_bokmaal-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/no_bokmaal/index.html> |
| Norwegian | Nynorsk | Lilja Øvrelid, Fredrik Jørgensen, Petter Hohle, Ingerid Løyning Dale, Per Erik Solberg, Andre Kåsen | The Norwegian UD treebank is based on the Nynorsk section of the Norwegian Dependency Treebank (NDT), which is a syntactic treebank of Norwegian. NDT has been automatically converted to the UD scheme by Lilja Øvrelid at the University of Oslo. | no_nynorsk-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/no_nynorsk/index.html> |
| Old Church Slavonic | PROIEL | Dag Haug | The Old Church Slavonic (OCS) UD treebank is based on canonical Old Church Slavonic data from the PROIEL and TOROT treebanks. | cu_proiel-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/cu_proiel/index.html> |
| Persian | Seraji | Mojgan Seraji, Filip Ginter, Joakim Nivre, Martin Popel, Daniel Zeman | The Persian Universal Dependency Treebank (Seraji) is based on Uppsala Persian Dependency Treebank (UPDT). | fa_seraji-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/fa_seraji/index.html> |
| Polish | LFG | Agnieszka Patejuk, Adam Przepiórkowski | The LFG Enhanced UD treebank of Polish is based on a corpus of LFG (Lexical Functional Grammar) syntactic structures generated by an LFG grammar of Polish, POLFIE, and manually disambiguated by human annotators. | pl_lfg-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/pl_lfg/index.html> |
| Polish | PDB | Alina Wróblewska, Daniel Zeman, Jan Mašek, Rudolf Rosa | The Polish PDB-UD treebank is automatically converted from the Polish Dependency Bank 2.0 (PDB 2.0). Both treebanks were created at the [Institute of Computer Science, Polish Academy of Sciences](https://ipipan.waw.pl/en/) in Warsaw (Poland). | pl_pdb-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/pl_pdb/index.html> |
| Portuguese | Bosque | Alexandre Rademaker, Cláudia Freitas, Elvis de Souza, Aline Silveira, Tatiana Cavalcanti, Wograine Evelyn, Luisa Rocha, Isabela Soares-Bastos, Eckhard Bick, Fabricio Chalub, Guilherme Paulino-Passos, Livy Real, Valeria de Paiva, Daniel Zeman, Martin Popel, David Mareček, Natalia Silveira, André Martins | This Universal Dependencies (UD) Portuguese treebank is based on the Constraint Grammar converted version of the Bosque, which is part of the Floresta Sintá(c)tica treebank. It contains both European (CETEMPúblico) and Brazilian (CETENFolha) variants. | pt_bosque-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/pt_bosque/index.html> |
| Portuguese | GSD | Alexandre Rademaker, Ryan McDonald, Joakim Nivre, Daniel Zeman, Fabricio Chalub, Carlos Ramisch, Juan Belieni, Vanessa Berwanger Wille, Rodrigo Pintucci | The Brazilian Portuguese UD is converted from the \[Google Universal Dependency | pt_gsd-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/pt_gsd/index.html> |
| Romanian | Nonstandard | Cătălina Mărănduc, Cenel-Augusto Perez, Victoria Bobicev, Cătălin Mititelu, Florinel Hociung, Valentin Roșca, Roman Untilov, Petru Rebeja | The Romanian Non-standard UD treebank (called UAIC-RoDia) is based on UAIC-RoDia Treebank. UAIC-RoDia = ISLRN 156-635-615-024-0 | ro_nonstandard-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/ro_nonstandard/index.html> |
| Romanian | RRT | Verginica Barbu Mititelu, Elena Irimia, Cenel-Augusto Perez, Radu Ion, Radu Simionescu, Martin Popel | The Romanian UD treebank (called RoRefTrees) (Barbu Mititelu et al., 2016) is the reference treebank in UD format for standard Romanian. | ro_rrt-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/ro_rrt/index.html> |
| Russian | GSD | Ryan McDonald, Vitaly Nikolaev, Olga Lyashevskaya | Russian Universal Dependencies Treebank annotated and converted by Google. | ru_gsd-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/ru_gsd/index.html> |
| Russian | SynTagRus | Kira Droganova, Olga Lyashevskaya, Daniel Zeman | Russian data from the SynTagRus corpus. | ru_syntagrus-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/ru_syntagrus/index.html> |
| Russian | Taiga | Olga Lyashevskaya, Olga Rudina, Natalia Vlasova, Anna Zhuravleva | Universal Dependencies treebank is based on data samples extracted from Taiga Corpus and MorphoRuEval-2017 and GramEval-2020 shared tasks collections. | ru_taiga-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/ru_taiga/index.html> |
| Scottish Gaelic | ARCOSG | Colin Batchelor | A treebank of Scottish Gaelic based on the [Annotated Reference Corpus Of Scottish Gaelic (ARCOSG)](https://github.com/Gaelic-Algorithmic-Research-Group/ARCOSG). | gd_arcosg-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/gd_arcosg/index.html> |
| Serbian | SET | Tanja Samardžić, Nikola Ljubešić | The Serbian UD treebank is based on the [SETimes-SR](http://hdl.handle.net/11356/1200) corpus and additional news documents from the Serbian web. | sr_set-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/sr_set/index.html> |
| Slovak | SNK | Katarína Gajdošová, Mária Šimková, Daniel Zeman | The Slovak UD treebank is based on data originally annotated as part of the Slovak National Corpus, following the annotation style of the Prague Dependency Treebank. | sk_snk-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/sk_snk/index.html> |
| Slovenian | SSJ | Kaja Dobrovoljc, Tomaž Erjavec, Simon Krek | The SSJ treebank is the reference UD treebank for Slovenian, consisting of approximately 13,000 sentences and 267,097 tokens from fiction, non-fiction, periodical and Wikipedia texts in standard modern Slovenian. As of UD release 2.10 in May 2022, the original version of the SSJ UD treebank has been partially manually revised and extended with new manually annotated data. | sl_ssj-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/sl_ssj/index.html> |
| Slovenian | SST | Kaja Dobrovoljc, Joakim Nivre | The Spoken Slovenian Treebank (SST) is a manually annotated collection of transcribed audio recordings featuring spontaneous speech in various everyday situations. It includes 344 unique speech events (documents) amounting to approximately 10 hours of speech, encompassing a total of 6,108 utterances and 98,396 tokens. | sl_sst-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/sl_sst/index.html> |
| Spanish | AnCora | Héctor Martínez Alonso, Daniel Zeman | Spanish data from the [AnCora](http://clic.ub.edu/corpus/) corpus. | es_ancora-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/es_ancora/index.html> |
| Spanish | GSD | Miguel Ballesteros, Héctor Martínez Alonso, Ryan McDonald, Elena Pascual, Natalia Silveira, Daniel Zeman, Joakim Nivre | The Spanish UD is converted from the content head version of the [universal dependency treebank v2.0 (legacy)](https://github.com/ryanmcd/uni-dep-tb). | es_gsd-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/es_gsd/index.html> |
| Swedish | LinES | Lars Ahrenberg | UD Swedish_LinES is the Swedish half of the LinES Parallel Treebank with UD annotations. All segments are translations from English and the sources cover literary genres, online manuals and Europarl data. | sv_lines-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/sv_lines/index.html> |
| Swedish | Talbanken | Joakim Nivre, Aaron Smith, Victor Norrman | The Swedish-Talbanken treebank is based on Talbanken, a treebank developed at Lund University in the 1970s. | sv_talbanken-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/sv_talbanken/index.html> |
| Tamil | TTB | Loganathan Ramasamy, Daniel Zeman | The UD Tamil treebank is based on the Tamil Dependency Treebank created at the Charles University in Prague by Loganathan Ramasamy. | ta_ttb-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/ta_ttb/index.html> |
| Telugu | MTG | Taraka Rama, Sowmya Vajjala | The Telugu UD treebank is created in UD based on manual annotations of sentences from a grammar book. | te_mtg-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/te_mtg/index.html> |
| Turkish | IMST | Utku Türk, Şaziye Betül Özateş, Büşra Marşan, Salih Furkan Akkurt, Çağrı Çöltekin, Gülşen Cebiroğlu Eryiğit, Memduh Gökırmak, Hüner Kaşıkara, Umut Sulubacak, Francis Tyers | The UD Turkish Treebank, also called the IMST-UD Treebank, is a semi-automatic conversion of the IMST Treebank (Sulubacak&Eryiğit, 2018; Sulubacak et al., 2016). | tr_imst-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/tr_imst/index.html> |
| Ukrainian | IU | Natalia Kotsyba, Bohdan Moskalevskyi, Mykhailo Romanenko | Gold standard Universal Dependencies corpus for Ukrainian, developed for UD originally, by [Institute for Ukrainian](https://mova.institute), NGO. \[[українською](https://mova.institute/золотий_стандарт)\] | uk_iu-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/uk_iu/index.html> |
| Urdu | UDTB | Riyaz Ahmad Bhat, Daniel Zeman | The Urdu Universal Dependency Treebank was automatically converted from Urdu Dependency Treebank (UDTB) which is part of an ongoing effort of creating multi-layered treebanks for Hindi and Urdu. | ur_udtb-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/ur_udtb/index.html> |
| Uyghur | UDT | Marhaba Eli, Daniel Zeman, Francis Tyers | The Uyghur UD treebank is based on the Uyghur Dependency Treebank (UDT), created at the Xinjiang University, China. | ug_udt-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/ug_udt/index.html> |
| Vietnamese | VTB | Lương Nguyễn Thị, Linh Hà Mỹ, Phương Lê Hồng, Huyền Nguyễn Thị Minh | The Vietnamese UD treebank is a conversion of the constituent treebank created in the VLSP project (<https://vlsp.hpda.vn/>). | vi_vtb-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/vi_vtb/index.html> |
| Wolof | WTB | Bamba Dione | UD_Wolof-WTB is a natively manual developed treebank for Wolof. Sentences were collected from encyclopedic, fictional, biographical, religious texts and news. | wo_wtb-ud-2.15.udpipe | <https://universaldependencies.org/treebanks/wo_wtb/index.html> |

## Model Accuracy

We present the tokenizer, tagger, lemmatizer and parser performance,
measured on the testing portion of the data, evaluated on the raw text.
The results are F1 scores.

| Language | Treebank | Words | Sentences | UPOS | XPOS | UFeats | AllTags | Lemma | UAS | LAS |
|:---|:---|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| Afrikaans | AfriBooms | 99.93 | 99.65 | 95.79 | 91.39 | 93.67 | 91.26 | 96.40 | 82.55 | 77.97 |
| Ancient Greek | PROIEL | 100.00 | 45.89 | 95.34 | 95.65 | 87.71 | 86.28 | 90.77 | 68.94 | 63.73 |
| Ancient Greek | Perseus | 99.98 | 98.73 | 81.44 | 71.34 | 84.62 | 71.24 | 79.90 | 58.70 | 51.74 |
| Arabic | PADT | 94.51 | 81.43 | 88.91 | 82.35 | 82.44 | 82.16 | 87.36 | 67.64 | 62.60 |
| Armenian | ArmTDP | 99.38 | 97.28 | 92.39 | 99.38 | 83.70 | 82.79 | 90.83 | 75.17 | 67.58 |
| Basque | BDT | 99.98 | 99.42 | 92.43 | 99.98 | 87.17 | 84.68 | 91.09 | 74.57 | 69.35 |
| Belarusian | HSE | 99.28 | 84.80 | 96.07 | 95.40 | 88.30 | 87.69 | 88.77 | 77.08 | 73.45 |
| Bulgarian | BTB | 99.92 | 94.67 | 98.01 | 94.72 | 95.77 | 94.39 | 92.88 | 87.98 | 83.52 |
| Catalan | AnCora | 99.94 | 99.08 | 98.22 | 95.04 | 97.68 | 94.83 | 98.19 | 86.97 | 83.75 |
| Chinese | GSD | 89.89 | 98.80 | 82.84 | 83.56 | 88.57 | 82.30 | 89.83 | 58.96 | 55.27 |
| Chinese | GSDSimp | 89.05 | 98.80 | 82.28 | 82.98 | 87.79 | 81.76 | 89.00 | 58.27 | 54.47 |
| Classical Chinese | Kyoto | 97.70 | 42.03 | 87.70 | 87.29 | 88.09 | 84.79 | 97.46 | 65.90 | 60.15 |
| Coptic | Scriptorium | 75.38 | 30.20 | 72.69 | 72.55 | 72.88 | 71.87 | 73.30 | 50.32 | 48.26 |
| Croatian | SET | 99.91 | 93.54 | 96.67 | 89.99 | 90.59 | 89.95 | 93.30 | 82.08 | 77.39 |
| Czech | CAC | 99.96 | 99.76 | 98.56 | 90.88 | 89.58 | 89.45 | 96.24 | 84.81 | 81.13 |
| Czech | CLTT | 99.37 | 93.79 | 94.87 | 82.33 | 82.64 | 82.23 | 92.93 | 72.06 | 67.99 |
| Czech | FicTree | 99.99 | 97.56 | 97.60 | 90.26 | 90.96 | 90.14 | 95.60 | 84.95 | 80.79 |
| Czech | PDT | 99.91 | 91.91 | 98.63 | 93.12 | 93.21 | 92.83 | 97.50 | 83.49 | 80.18 |
| Danish | DDT | 99.93 | 89.92 | 95.24 | 99.92 | 94.48 | 93.22 | 94.46 | 77.57 | 73.77 |
| Dutch | Alpino | 99.59 | 89.99 | 94.18 | 91.51 | 93.28 | 90.78 | 90.82 | 78.21 | 73.20 |
| Dutch | LassySmall | 99.83 | 81.93 | 94.79 | 92.21 | 93.95 | 91.41 | 92.16 | 80.11 | 75.79 |
| English | EWT | 99.14 | 86.17 | 94.10 | 93.23 | 94.37 | 91.61 | 95.15 | 81.03 | 77.64 |
| English | GUM | 99.57 | 95.07 | 95.77 | 95.32 | 95.10 | 93.69 | 96.55 | 81.52 | 78.18 |
| English | LinES | 99.94 | 87.88 | 95.07 | 94.08 | 94.94 | 91.84 | 95.78 | 81.11 | 76.60 |
| English | ParTUT | 99.78 | 99.02 | 94.30 | 93.86 | 94.21 | 92.45 | 94.76 | 82.15 | 78.75 |
| Estonian | EDT | 99.88 | 89.81 | 95.45 | 96.80 | 93.71 | 92.15 | 87.93 | 77.08 | 73.13 |
| Estonian | EWT | 98.95 | 75.16 | 88.85 | 91.47 | 86.94 | 83.72 | 84.30 | 66.96 | 60.45 |
| Finnish | FTB | 99.99 | 86.93 | 92.01 | 90.74 | 92.21 | 89.00 | 85.76 | 77.89 | 72.65 |
| Finnish | TDT | 99.68 | 85.59 | 94.28 | 95.43 | 90.54 | 89.50 | 84.52 | 76.79 | 72.74 |
| French | GSD | 98.89 | 93.45 | 96.24 | 98.89 | 95.34 | 94.51 | 96.78 | 86.39 | 83.00 |
| French | ParTUT | 99.41 | 98.64 | 95.26 | 94.69 | 92.58 | 91.12 | 95.84 | 85.33 | 82.11 |
| French | Sequoia | 99.09 | 85.01 | 96.42 | 99.09 | 94.91 | 94.17 | 96.60 | 84.69 | 81.63 |
| Galician | CTG | 99.14 | 94.80 | 96.23 | 95.80 | 98.92 | 95.38 | 95.18 | 75.72 | 72.53 |
| German | GSD | 99.56 | 78.69 | 64.12 | 64.29 | 53.65 | 50.34 | 86.07 | 71.43 | 65.53 |
| German | HDT | 99.90 | 92.60 | 97.80 | 97.40 | 91.40 | 91.00 | 92.30 | 77.00 | 81.40 |
| Gothic | PROIEL | 100.00 | 28.25 | 93.73 | 94.20 | 86.76 | 84.55 | 89.51 | 70.88 | 63.47 |
| Greek | GDT | 99.89 | 89.51 | 95.13 | 95.13 | 89.96 | 88.75 | 92.74 | 83.36 | 79.58 |
| Hebrew | HTB | 85.08 | 99.69 | 80.84 | 80.84 | 78.57 | 77.75 | 79.01 | 59.74 | 56.38 |
| Hindi | HDTB | 99.99 | 97.69 | 95.84 | 94.91 | 90.17 | 87.68 | 98.05 | 90.44 | 85.86 |
| Hungarian | Szeged | 99.69 | 94.48 | 90.96 | 99.69 | 87.20 | 85.84 | 87.29 | 70.59 | 64.95 |
| Indonesian | GSD | 99.45 | 90.47 | 93.22 | 91.90 | 94.17 | 86.65 | 87.32 | 80.88 | 74.29 |
| Irish | IDT | 99.67 | 97.57 | 93.43 | 92.20 | 84.15 | 81.76 | 91.96 | 80.52 | 72.83 |
| Italian | ISDT | 99.80 | 96.59 | 97.24 | 97.11 | 97.12 | 96.33 | 96.98 | 87.46 | 84.47 |
| Italian | ParTUT | 99.70 | 99.02 | 96.73 | 96.37 | 96.40 | 95.19 | 96.35 | 86.26 | 83.08 |
| Italian | PoSTWITA | 99.36 | 24.37 | 94.25 | 93.88 | 94.26 | 92.50 | 93.84 | 72.70 | 67.74 |
| Italian | TWITTIRO | 99.02 | 28.57 | 90.37 | 89.60 | 90.00 | 87.00 | 89.43 | 70.77 | 64.11 |
| Italian | VIT | 99.75 | 96.73 | 96.38 | 95.37 | 96.33 | 94.18 | 96.52 | 81.76 | 77.58 |
| Japanese | GSD | 95.77 | 99.45 | 93.50 | 92.80 | 95.75 | 92.30 | 94.21 | 84.20 | 82.36 |
| Korean | GSD | 99.85 | 93.63 | 91.40 | 81.07 | 99.50 | 78.74 | 86.96 | 60.94 | 51.64 |
| Korean | Kaist | 99.99 | 100.00 | 92.95 | 80.41 | 99.99 | 80.41 | 88.12 | 72.96 | 61.60 |
| Latin | ITTB | 99.97 | 92.53 | 98.42 | 93.26 | 93.98 | 92.63 | 98.04 | 79.31 | 75.58 |
| Latin | PROIEL | 99.99 | 28.48 | 94.53 | 94.73 | 86.89 | 85.59 | 91.73 | 63.36 | 57.80 |
| Latvian | LVTB | 99.23 | 99.06 | 95.23 | 87.53 | 91.82 | 87.48 | 93.35 | 78.23 | 73.52 |
| Lithuanian | ALKSNIS | 99.95 | 87.75 | 90.37 | 81.26 | 82.42 | 80.88 | 86.89 | 65.80 | 59.65 |
| Lithuanian | HSE | 97.65 | 92.04 | 71.39 | 70.36 | 66.42 | 60.98 | 68.95 | 43.34 | 31.05 |
| Maltese | MUDT | 99.79 | 82.32 | 93.79 | 93.49 | 99.79 | 93.20 | 99.79 | 75.31 | 68.95 |
| Marathi | UFAL | 95.27 | 81.19 | 78.79 | 95.27 | 70.06 | 67.88 | 83.15 | 62.55 | 51.15 |
| Norwegian | Bokmaal | 99.82 | 97.34 | 96.39 | 97.70 | 95.06 | 93.74 | 96.04 | 85.36 | 82.30 |
| Norwegian | Nynorsk | 99.90 | 92.74 | 95.92 | 97.30 | 94.93 | 93.29 | 95.47 | 83.85 | 80.62 |
| Old Church Slavonic | PROIEL | 100.00 | 34.43 | 91.36 | 91.63 | 82.50 | 80.73 | 81.73 | 66.17 | 59.74 |
| Persian | Seraji | 99.65 | 98.00 | 96.02 | 95.78 | 95.92 | 95.31 | 92.74 | 79.98 | 75.19 |
| Polish | LFG | 99.86 | 99.83 | 96.86 | 87.18 | 87.48 | 86.56 | 92.56 | 90.64 | 86.73 |
| Polish | PDB | 99.85 | 96.06 | 97.30 | 88.49 | 88.84 | 87.88 | 94.28 | 84.74 | 80.83 |
| Portuguese | Bosque | 99.67 | 89.56 | 96.12 | 99.67 | 94.07 | 92.66 | 96.50 | 83.83 | 79.97 |
| Portuguese | GSD | 99.27 | 87.99 | 95.58 | 82.76 | 91.78 | 82.58 | 91.72 | 82.18 | 78.52 |
| Romanian | Nonstandard | 98.88 | 96.92 | 94.94 | 90.06 | 88.31 | 87.67 | 91.61 | 81.26 | 75.55 |
| Romanian | RRT | 99.68 | 94.01 | 96.91 | 95.94 | 96.09 | 95.83 | 95.16 | 82.69 | 77.96 |
| Russian | GSD | 99.53 | 97.41 | 95.00 | 94.74 | 85.57 | 84.50 | 89.90 | 81.58 | 76.41 |
| Russian | SynTagRus | 99.57 | 97.55 | 97.42 | 99.57 | 90.50 | 90.11 | 95.24 | 83.19 | 79.37 |
| Russian | Taiga | 98.74 | 84.37 | 93.42 | 98.74 | 86.33 | 85.42 | 89.54 | 72.77 | 67.12 |
| Scottish Gaelic | ARCOSG | 97.39 | 56.07 | 91.38 | 83.27 | 85.18 | 82.49 | 91.33 | 74.56 | 68.31 |
| Serbian | SET | 100.00 | 93.84 | 97.36 | 90.76 | 91.10 | 90.73 | 93.40 | 84.90 | 80.63 |
| Slovak | SNK | 100.00 | 77.73 | 92.98 | 77.04 | 79.32 | 76.77 | 83.32 | 78.84 | 74.61 |
| Slovenian | SSJ | 99.89 | 99.07 | 96.78 | 90.26 | 90.53 | 89.80 | 95.04 | 84.17 | 80.51 |
| Slovenian | SST | 100.00 | 93.73 | 94.83 | 88.51 | 88.67 | 87.49 | 94.84 | 70.58 | 65.41 |
| Spanish | AnCora | 99.94 | 97.92 | 98.25 | 94.92 | 97.94 | 94.54 | 98.17 | 85.23 | 81.52 |
| Spanish | GSD | 99.72 | 94.54 | 95.49 | 99.72 | 95.97 | 93.55 | 94.08 | 83.40 | 79.41 |
| Swedish | LinES | 99.96 | 86.83 | 94.67 | 91.95 | 90.11 | 86.66 | 94.50 | 81.31 | 76.54 |
| Swedish | Talbanken | 99.91 | 94.20 | 95.71 | 93.90 | 94.18 | 92.43 | 95.13 | 81.51 | 77.23 |
| Tamil | TTB | 94.93 | 95.08 | 78.41 | 76.99 | 79.37 | 72.93 | 82.41 | 59.66 | 49.62 |
| Telugu | MTG | 100.00 | 98.98 | 90.29 | 90.29 | 98.89 | 90.29 | 100.00 | 87.93 | 75.45 |
| Turkish | IMST | 97.60 | 97.51 | 88.85 | 88.54 | 84.31 | 81.58 | 85.77 | 61.37 | 52.36 |
| Ukrainian | IU | 99.71 | 96.71 | 94.85 | 84.03 | 83.67 | 82.86 | 91.39 | 77.54 | 72.78 |
| Urdu | UDTB | 99.99 | 97.12 | 91.53 | 89.00 | 80.26 | 75.43 | 91.47 | 81.25 | 74.23 |
| Uyghur | UDT | 99.74 | 82.17 | 88.80 | 90.12 | 83.63 | 76.78 | 83.47 | 67.06 | 53.01 |
| Vietnamese | VTB | 85.11 | 97.02 | 76.10 | 75.07 | 85.11 | 75.04 | 83.66 | 47.83 | 40.71 |
| Wolof | WTB | 99.16 | 90.27 | 91.73 | 91.42 | 90.89 | 88.62 | 92.81 | 75.18 | 69.40 |

## Acknowledgements

The models were trained using [UDpipe R
package](https://CRAN.R-project.org/package=udpipe) on [Universal
Dependencies 2.15 treebanks](https://universaldependencies.org/).

## Structure

The repository is organized as follows:

- **`2.15/`**: Contains pre-trained `udpipe` models for individual
  languages. Each model file is named according to the corresponding
  language and the version of the Universal Dependencies data used.
- **`data/`**: Contains rdata files to build up tables in README.
- **`sample.data/`**: Contains example datasets that can be used to test
  and explore TALL functionalities.
- **`lexicon.data/`**: Contains lexicon datasets for linguistic analysis
  and text enrichment tasks in TALL.
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
