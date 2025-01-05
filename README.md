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
| Afrikaans | afribooms | Peter Dirix, Liesbeth Augustinus, Daniel van Niekerk | UD Afrikaans-AfriBooms is a conversion of the AfriBooms Dependency Treebank, originally annotated with a simplified PoS set and dependency relations according to a subset of the Stanford tag set. The corpus consists of public government documents. | af_afribooms-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/af_afribooms/index.html" target="_blank">Link</a> |
| Ancient Greek | perseus | Giuseppe G. A. Celano, Daniel Zeman | This Universal Dependencies Ancient Greek Treebank consists of an automatic | grc_perseus-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/grc_perseus/index.html" target="_blank">Link</a> |
| Arabic | padt | Daniel Zeman, Zdeněk Žabokrtský, Shadi Saleh | The Arabic-PADT UD treebank is based on the | ar_padt-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/ar_padt/index.html" target="_blank">Link</a> |
| Armenian | armtdp | Marat M. Yavrumyan | A Universal Dependencies treebank for Eastern Armenian developed for UD originally by the ArmTDP team led by Marat M. Yavrumyan at the Yerevan State University. | hy_armtdp-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/hy_armtdp/index.html" target="_blank">Link</a> |
| Basque | bdt | Maria Jesus Aranzabe, Aitziber Atutxa, Kepa Bengoetxea, Arantza Diaz de Ilarraza, Iakes Goenaga, Koldo Gojenola, Larraitz Uria | The Basque UD treebank is based on an automatic conversion from part of the Basque Dependency Treebank (BDT), created at the University of the Basque Country by the IXA NLP research group. The treebank consists of 8,993 sentences (121,443 tokens) and covers mainly literary and journalistic texts. | eu_bdt-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/eu_bdt/index.html" target="_blank">Link</a> |
| Belarusian | hse | Olga Lyashevskaya, Angelika Peljak-Łapińska, Daria Petrova, Yana Shishkina | The Belarusian UD treebank is based on a sample of the news texts included in the Belarusian-Russian parallel subcorpus of the Russian National Corpus. | be_hse-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/be_hse/index.html" target="_blank">Link</a> |
| Bulgarian | btb | Kiril Simov, Petya Osenova, Martin Popel | UD_Bulgarian-BTB is based on the HPSG-based BulTreeBank. | bg_btb-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/bg_btb/index.html" target="_blank">Link</a> |
| Catalan | ancora | Héctor Martínez Alonso, Elena Pascual, Daniel Zeman | Catalan data from the [AnCora](http://clic.ub.edu/corpus/) corpus. | ca_ancora-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/ca_ancora/index.html" target="_blank">Link</a> |
| Chinese | gsdsimp | Peng Qi, Koichi Yasuoka | Simplified Chinese Universal Dependencies dataset converted from the GSD (traditional) dataset with manual corrections. | zh_gsdsimp-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/zh_gsdsimp/index.html" target="_blank">Link</a> |
| Croatian | set | Željko Agić, Nikola Ljubešić, Daniel Zeman | The Croatian UD treebank is based on the extension of the SETimes-HR corpus, the [hr500k](http://hdl.handle.net/11356/1183) corpus. | hr_set-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/hr_set/index.html" target="_blank">Link</a> |
| Czech | cac | Barbora Hladká, Daniel Zeman | The UD_Czech-CAC treebank is based on the Czech Academic Corpus 2.0 (CAC). | cs_cac-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/cs_cac/index.html" target="_blank">Link</a> |
| Danish | ddt | Anders Johannsen, Héctor Martínez Alonso, Barbara Plank | The Danish UD treebank is a conversion of the Danish Dependency Treebank. | da_ddt-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/da_ddt/index.html" target="_blank">Link</a> |
| Dutch | lassysmall | Gosse Bouma, Gertjan van Noord | This corpus contains sentences from the Wikipedia section of the Lassy Small Treebank. | nl_lassysmall-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/nl_lassysmall/index.html" target="_blank">Link</a> |
| English | ewt | Natalia Silveira, Timothy Dozat, Christopher Manning, Sebastian Schuster, Ethan Chi, John Bauer, Miriam Connor, Marie-Catherine de Marneffe, Nathan Schneider, Sam Bowman, Hanzhi Zhu, Daniel Galbraith, John Bauer | A Gold Standard Universal Dependencies Corpus for English. | en_ewt-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/en_ewt/index.html" target="_blank">Link</a> |
| English | gum | Siyao Peng, Amir Zeldes | Universal Dependencies syntax annotations from the GUM corpus (<https://gucorpling.org/gum/>). | en_gum-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/en_gum/index.html" target="_blank">Link</a> |
| English | lines | Lars Ahrenberg | UD English_LinES is the English half of the LinES Parallel Treebank. | en_lines-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/en_lines/index.html" target="_blank">Link</a> |
| English | partut | Cristina Bosco, Manuela Sanguinetti | UD_English-ParTUT is a conversion of a multilingual parallel treebank developed at the University of Turin. | en_partut-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/en_partut/index.html" target="_blank">Link</a> |
| Estonian | edt | Kadri Muischnek, Kaili Müürisep, Tiina Puolakainen, Andriela Rääbis, Liisi Torga | UD Estonian is a converted version of the Estonian Dependency Treebank (EDT), originally annotated in the Constraint Grammar (CG) annotation scheme, and consisting of genres of fiction, newspaper texts and scientific texts. The treebank contains 30,972 trees, 437,769 tokens. | et_edt-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/et_edt/index.html" target="_blank">Link</a> |
| Finnish | tdt | Filip Ginter, Jenna Kanerva, Veronika Laippala, Niko Miekka, Anna Missilä, Stina Ojala, Sampo Pyysalo | UD_Finnish-TDT is based on the Turku Dependency Treebank (TDT), a broad-coverage dependency treebank of general Finnish covering numerous genres. | fi_tdt-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/fi_tdt/index.html" target="_blank">Link</a> |
| French | gsd | Marie-Catherine de Marneffe, Bruno Guillaume, Ryan McDonald, Alane Suhr, Joakim Nivre, Matias Grioni, Carly Dickerson, Guy Perrier | The **UD_French-GSD** was converted in 2015 from the content head version of the universal. | fr_gsd-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/fr_gsd/index.html" target="_blank">Link</a> |
| Galician | ctg | Xavier Gómez Guinovart | The Galician UD treebank is based on the automatic parsing of the Galician Technical Corpus (<http://sli.uvigo.gal/CTG>) created at the University of Vigo by the TALG NLP research group. | gl_ctg-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/gl_ctg/index.html" target="_blank">Link</a> |
| German | gsd | Slav Petrov, Wolfgang Seeker, Ryan McDonald, Joakim Nivre, Daniel Zeman, Adriane Boyd | The German UD is converted from the content head version of the universal. | de_gsd-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/de_gsd/index.html" target="_blank">Link</a> |
| Greek | gdt | Prokopis Prokopidis | The Greek UD treebank (UD_Greek-GDT) is derived from the Greek Dependency Treebank. | el_gdt-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/el_gdt/index.html" target="_blank">Link</a> |
| Hebrew | htb | Yoav Goldberg, Reut Tsarfaty, Amir More, Shoval Sadde, Victoria Basmov, Yuval Pinter | A Universal Dependencies Corpus for Hebrew. | he_htb-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/he_htb/index.html" target="_blank">Link</a> |
| Hindi | hdtb | Riyaz Ahmad Bhat, Daniel Zeman | The Hindi UD treebank is based on the Hindi Dependency Treebank (HDTB). | hi_hdtb-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/hi_hdtb/index.html" target="_blank">Link</a> |
| Hungarian | szeged | Richárd Farkas, Katalin Simkó, Zsolt Szántó, Viktor Varga, Veronika Vincze | The Hungarian UD treebank is derived from the Szeged Dependency Treebank (Vincze et al. 2010). | hu_szeged-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/hu_szeged/index.html" target="_blank">Link</a> |
| Indonesian | gsd | Ryan McDonald, Joakim Nivre, Daniel Zeman, Septina Dian Larasati, Ika Alfina | The Indonesian-GSD treebank was originally converted from the content head version of the universal dependency treebank v2.0. | id_gsd-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/id_gsd/index.html" target="_blank">Link</a> |
| Irish | idt | Teresa Lynn, Jennifer Foster, Sarah McGuinness, Abigail Walsh, Jason Phelan, Kevin Scannell | A Universal Dependencies 4910-sentence treebank for modern Irish. | ga_idt-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/ga_idt/index.html" target="_blank">Link</a> |
| Italian | isdt | Cristina Bosco, Alessandro Lenci, Simonetta Montemagni, Maria Simi | The Italian corpus annotated according to the UD annotation scheme was obtained by conversion from ISDT. | it_isdt-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/it_isdt/index.html" target="_blank">Link</a> |
| Italian | postwita | Cristina Bosco, Manuela Sanguinetti | PoSTWITA-UD is a collection of Italian tweets annotated in Universal Dependencies that can be exploited for the training of NLP systems to enhance their performance on social media texts. | it_postwita-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/it_postwita/index.html" target="_blank">Link</a> |
| Korean | kaist | Jinho Choi, Na-Rae Han, Jena Hwang, Jayeol Chun | The KAIST Korean Universal Dependency Treebank is generated by Chun et al., 2018. | ko_kaist-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/ko_kaist/index.html" target="_blank">Link</a> |
| Latin | ittb | Marco Passarotti, Marinella Testori, Daniel Zeman, Berta González Saavedra, Flavio Massimiliano Cecchini | Latin data from the *Index Thomisticus* Treebank. | la_ittb-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/la_ittb/index.html" target="_blank">Link</a> |
| Latvian | lvtb | Lauma Pretkalniņa, Laura Rituma, Gunta Nešpore-Bērzkalne, Baiba Saulīte, Artūrs Znotiņš, Normunds Grūzītis | Latvian UD Treebank is based on Latvian Treebank (LVTB). | lv_lvtb-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/lv_lvtb/index.html" target="_blank">Link</a> |
| Lithuanian | alksnis | Andrius Utka, Erika Rimkutė, Agnė Bielinskienė, Jolanta Kovalevskaitė, Loïc Boizou, Gabrielė Aleksandravičiūtė, Kristina Brokaitė, Daniel Zeman, Natalia Perkova, Bernadeta Griciūtė | The Lithuanian dependency treebank ALKSNIS v3.0 (Vytautas Magnus University). | lt_alksnis-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/lt_alksnis/index.html" target="_blank">Link</a> |
| Maltese | mudt | Slavomír Čéplö, Daniel Zeman | MUDT (Maltese Universal Dependencies Treebank) is a manually annotated treebank of Maltese. | mt_mudt-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/mt_mudt/index.html" target="_blank">Link</a> |
| Marathi | ufal | Vinit Ravishankar | UD Marathi is a manually annotated treebank consisting primarily of stories from Wikisource. | mr_ufal-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/mr_ufal/index.html" target="_blank">Link</a> |
| North Sami | giella | Trond Trosterud, Lene Antonsen, Francis Tyers | This is a North Sámi treebank based on a manually disambiguated and function-labelled gold-standard. | sme_giella-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/sme_giella/index.html" target="_blank">Link</a> |
| Norwegian | bokmaal | Lilja Øvrelid, Fredrik Jørgensen, Petter Hohle, Ingerid Løyning Dale, Per Erik Solberg, Andre Kåsen | The Norwegian UD treebank is based on the Bokmål section of the Norwegian. | no_bokmaal-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/no_bokmaal/index.html" target="_blank">Link</a> |
| Old Church Slavonic | proiel | Dag Haug | The Old Church Slavonic (OCS) UD treebank is based on canonical Old Church Slavonic data from the PROIEL and TOROT treebanks. | cu_proiel-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/cu_proiel/index.html" target="_blank">Link</a> |
| Persian | seraji | Mojgan Seraji, Filip Ginter, Joakim Nivre, Martin Popel, Daniel Zeman | The Persian Universal Dependency Treebank (Seraji) is based on Uppsala Persian Dependency Treebank (UPDT). | fa_seraji-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/fa_seraji/index.html" target="_blank">Link</a> |
| Polish | pdb | Alina Wróblewska, Daniel Zeman, Jan Mašek, Rudolf Rosa | The Polish PDB-UD treebank is automatically converted from the Polish Dependency Bank 2.0. | pl_pdb-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/pl_pdb/index.html" target="_blank">Link</a> |
| Portuguese | gsd | Alexandre Rademaker, Ryan McDonald, Joakim Nivre, Daniel Zeman, Fabricio Chalub, Carlos Ramisch, Juan Belieni, Vanessa Berwanger Wille, Rodrigo Pintucci | The Brazilian Portuguese UD is converted from the Google Universal Dependency. | pt_gsd-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/pt_gsd/index.html" target="_blank">Link</a> |
| Romanian | nonstandard | Cătălina Mărănduc, Cenel-Augusto Perez, Victoria Bobicev, Cătălin Mititelu, Florinel Hociung, Valentin Roșca, Roman Untilov, Petru Rebeja | The Romanian Non-standard UD treebank (called UAIC-RoDia) is based on UAIC-RoDia Treebank. | ro_nonstandard-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/ro_nonstandard/index.html" target="_blank">Link</a> |
| Romanian | rrt | Verginica Barbu Mititelu, Elena Irimia, Cenel-Augusto Perez, Radu Ion, Radu Simionescu, Martin Popel | The Romanian UD treebank (called RoRefTrees) (Barbu Mititelu et al., 2016) is the reference treebank in UD format for standard Romanian. | ro_rrt-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/ro_rrt/index.html" target="_blank">Link</a> |
| Russian | syntagrus | Kira Droganova, Olga Lyashevskaya, Daniel Zeman | Russian data from the SynTagRus corpus. | ru_syntagrus-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/ru_syntagrus/index.html" target="_blank">Link</a> |
| Scottish Gaelic | arcosg | Colin Batchelor | A treebank of Scottish Gaelic based on the. | gd_arcosg-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/gd_arcosg/index.html" target="_blank">Link</a> |
| Serbian | set | Tanja Samardžić, Nikola Ljubešić | The Serbian UD treebank is based on the [SETimes-SR](http://hdl.handle.net/11356/1200) corpus. | sr_set-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/sr_set/index.html" target="_blank">Link</a> |
| Slovak | snk | Katarína Gajdošová, Mária Šimková, Daniel Zeman | The Slovak UD treebank is based on data originally annotated as part of the. | sk_snk-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/sk_snk/index.html" target="_blank">Link</a> |
| Slovenian | ssj | Kaja Dobrovoljc, Tomaž Erjavec, Simon Krek | The SSJ treebank is the reference UD treebank for Slovenian. | sl_ssj-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/sl_ssj/index.html" target="_blank">Link</a> |
| Spanish | ancora | Héctor Martínez Alonso, Daniel Zeman | Spanish data from the [AnCora](http://clic.ub.edu/corpus/) corpus. | es_ancora-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/es_ancora/index.html" target="_blank">Link</a> |
| Swedish | talbanken | Joakim Nivre, Aaron Smith, Victor Norrman | The Swedish-Talbanken treebank is based on Talbanken, a treebank developed at Lund University. | sv_talbanken-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/sv_talbanken/index.html" target="_blank">Link</a> |
| Tamil | ttb | Loganathan Ramasamy, Daniel Zeman | The UD Tamil treebank is based on the Tamil Dependency Treebank created at the. | ta_ttb-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/ta_ttb/index.html" target="_blank">Link</a> |
| Telugu | mtg | Taraka Rama, Sowmya Vajjala | The Telugu UD treebank is created in UD based on manual annotations of sentences from a grammar book. | te_mtg-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/te_mtg/index.html" target="_blank">Link</a> |
| Turkish | imst | Utku Türk, Şaziye Betül Özateş, Büşra Marşan, Salih Furkan Akkurt, Çağrı Çöltekin, Gülşen Cebiroğlu Eryiğit, Memduh Gökırmak, Hüner Kaşıkara, Umut Sulubacak, Francis Tyers | The UD Turkish Treebank, also called the IMST-UD Treebank, is a semi-automatic conversion of the IMST Treebank. | tr_imst-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/tr_imst/index.html" target="_blank">Link</a> |
| Ukrainian | iu | Natalia Kotsyba, Bohdan Moskalevskyi, Mykhailo Romanenko | Gold standard Universal Dependencies corpus for Ukrainian. | uk_iu-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/uk_iu/index.html" target="_blank">Link</a> |
| Urdu | udtb | Riyaz Ahmad Bhat, Daniel Zeman | The Urdu Universal Dependency Treebank was automatically converted from Urdu Dependency Treebank (UDTB). | ur_udtb-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/ur_udtb/index.html" target="_blank">Link</a> |
| Uyghur | udt | Marhaba Eli, Daniel Zeman, Francis Tyers | The Uyghur UD treebank is based on the Uyghur Dependency Treebank (UDT). | ug_udt-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/ug_udt/index.html" target="_blank">Link</a> |
| Vietnamese | vtb | Lương Nguyễn Thị, Linh Hà Mỹ, Phương Lê Hồng, Huyền Nguyễn Thị Minh | The Vietnamese UD treebank is a conversion of the constituent treebank created in the VLSP project. | vi_vtb-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/vi_vtb/index.html" target="_blank">Link</a> |
| Wolof | wtb | Bamba Dione | UD_Wolof-WTB is a natively manual developed treebank for Wolof. | wo_wtb-ud-2.15.udpipe | <a href="https://universaldependencies.org/treebanks/wo_wtb/index.html" target="_blank">Link</a> |

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
