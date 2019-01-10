---
layout: default
title: Duplicate Finder
---

This tool is designed for detection and analysis of near duplicates in
software documentation. Two text fragments are considered near
duplicates if they contain common information expressed identically in
terms of syntax (i.e. using the same text) while still having a number
of differences that, however, do not make up the bulk of both fragments.

Our tool works in two modes:

*  fast, automatic detection of near duplicates in a document;
*  interactive search that involves the user.

The first mode\'s purpose is to provide an express estimate of the
number of near duplicates in a document. However, due to being
automatic, it does not allow to identify semantically correct duplicates —
often, meaningless phrases that are identical syntax-wise are merged,
while significant duplicates are not extracted fully. There are other
problems as well. Nevertheless, this mode provides an adequate general
idea on the \"density\" of duplicates in a document. From there on, the
interactive mode is suggested for acquiring correct information and
using near duplicates in documentation reuse.

The tool's source code is available
[here](https://github.com/spbu-se/pldoctoolkit/blob/master/doc-clone-miner/README_en.md).

This research, including tool implementation, is carried out as a part
of [DocLine](docline/index.en) research project.

Contacts
--------

Project scientific leader | Dmitry Koznov | `dkoznov [at] yandex.ru`
Technical leader          | Dmitry Luciv  | `dluciv [at] math.spbu.ru`


Publications
------------

| Authors                                                                      | Title                                                          | Published                                                                                                                                                                   | Download
|-|-|-|:--:|
| D. Luciv, D. Koznov, G. Chernishev, H.A. Basit, K. Romanovsky, A. Terekhov   | Duplicate finder toolkit                                       | Proceedings of the 40th International Conference on Software Engineering (ICSE 2018), ACM, 2018. — P. 171–172                                                               | [![pdf](/img/pdf.png)](/pdf/articles/dluciv.dkoznov.gchernichev.hbasit.kromanovsky.aterekhov.2018.icse.pdf)
| D. Luciv, D. Koznov, G. Chernishev, A. Terekhov, K. Romanovsky, D. Grigoriev | Detecting Near Duplicates in Software Documentation | Programming and Computer Software, 2018, Vol. 44, No. 4, pp. 335–343                                                                                                                 | [![pdf](/img/pdf.png)](/pdf/articles/dluciv.dkoznov.gchernichev.aterekhov.kromanovsky.dgrigoriev.2018.programming.en.pdf)
| D.V. Koznov, D.V. Luciv, G.A. Chernishev, A.N. Terekhov                      | Detecting Near Duplicates in Software Documentation            | ArXiv EPrint, 2017                                                                                                                                                          | [![pdf](/img/pdf.png)](https://arxiv.org/pdf/1711.04705.pdf)
| Dmitry V. Koznov, Dmitry V. Luciv, George A. Chernishev                      | Duplicate management in software documentation maintenance     | Proceedings of V International conference Actual problems of system and software engineering (APSSE 2017), CEUR Workshop Proceedings, vol. 1989, pp. 195–201                | [![pdf](/img/pdf.png)](/pdf/articles/dkoznov.dluciv.gchernichev.2017.apsse.pdf)
| L.D. Kanteev, Yu.O. Kostyukov, D.V. Luciv, D.V. Koznov, M.N. Smirnov         | Discovering Near Duplicate Text in Software Documentation      | Proceedings of the Institute for System Programming, vol. 29, issue 4, 2017, pp. 303-314                                                                                    | [![pdf](/img/pdf.png)](/pdf/articles/kanteev.kostykov.luciv.koznov.smirnov.2016.ispras.pdf)
| D. V. Luciv, D. V. Koznov, H. A. Basit, and A. N. Terekhov                   | On Fuzzy Repetitions Detection in Documentation Reuse          | Programming and Computer Software, 2016, Vol. 42, No. 4, pp. 216–224                                                                                                        | [![pdf](/img/pdf.png)](/pdf/articles/luciv.koznov.basit.terekhov_2016_en.pdf)
| D. Koznov, D. Luciv, H. Basit, O. Lieh, M. Smirnov                           | Clone Detection in Reuse of Software Technical Documentation   | Lecture Notes in Computer Science, Vol. 9609, 2016, pp. 170-185 (10th International Andrei Ershov Informatics Conference on Perspectives of System Informatics, PSI 2015)   | [![pdf](/img/pdf.png)](/pdf/articles/koznov.luciv.basit.lieh.smirnov_2016.pdf)
| D.V.Lutsiv, D.V.Koznov, H.A.Basit, O.E.Lieh, M.N.Smirnov, K.Yu.Romanovsky    | An Approach for Clone Detection in Documentation Reuse         | Scientific and Technical Journal of Information Technologies, Mechanics and Optics № 4 (92). St-Petersburg, ITMO University, 2014, pp. 106-114. (in Russian)                | [![pdf](/img/pdf.png)](/pdf/articles/dluciv.dkoznov.etall.2014.ifmo.pdf)
