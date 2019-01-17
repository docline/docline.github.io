---
layout: default
title: DocLine
---

DocLine project was started in 2004 on the Software Engineering Chair of
the Faculty of Mathematics and Mechanics of Saint-Petersburg State
University in cooperation with CASE-technologies Laboratory of the
Research Institute for Information Technologies.

The goal of DocLine project is to provide a method for developemnt and
maintenance of electronic documentation packages having multiple
commonalities. For example, large requirement specifications (100
pages+) contain a lot of common text fragments, as well as documentation
for product lines, since such products share common functionality.

DocLine highlightes
-------------------

-   Integration with [DocBook](http://www.docbook.org) XML for markup
    and publishing
-   Adaptation (for the case of documentation reuse) of Paul Basset and
    [Stan Jarzabek](http://www.comp.nus.edu.sg/~stan/) approach to reuse
    of arbitrary content
-   Using a visual modeling approach for designing documentation reuse

Current state
-------------

-   We have designed Documentation Reuse Language (DRL)
-   We propose reference model for documentation development process
-   We implemented a DocLine toolset (for Eclipse and for Adobe
    FrameMaker)
-   The method was applied to industrial product line of
    telecommunication systems
-   Refactoring operations are implemented to support documentation
    maintenance:
    -   mining text clones automatically and creating information
        element from them
    -   mining variative text clones automatically (иthe tools can be
        launched from shel in batch mode)

Downloads
---------

Download sources of DocLine for Eclipse
[here](https://github.com/spbu-se/pldoctoolkit).

### Standalone tools:

-   [Duplicate Finder](../index.en) allowing finding and tracking
    inexact (fuzzy) repetitions in documents.

Contacts
--------

Project scientific leader | Dmitry Koznov | `dkoznov [at] yandex.ru`
Technical leader          | Dmitry Luciv  | `dluciv [at] math.spbu.ru`

Publications
------------

| Authors                                                                     | Title                                                                                            | Published                                                                                                                                                                   | Download
|-|-|-|:--:|
| D.V. Koznov, D.V. Luciv, G.A. Chernishev, A.N. Terekhov                     | Detecting Near Duplicates in Software Documentation                                              | ArXiv EPrint, 2017                                                                                                                                                          | [![pdf](/img/pdf.png)](https://arxiv.org/pdf/1711.04705.pdf)
| Dmitry V. Koznov, Dmitry V. Luciv, George A. Chernishev                     | Duplicate management in software documentation maintenance                                       | Proceedings of V International conference Actual problems of system and software engineering (APSSE 2017), CEUR Workshop Proceedings, vol. 1989, pp. 195--201               | [![pdf](/img/pdf.png)](/pdf/articles/dkoznov.dluciv.gchernichev.2017.apsse.pdf)
| L.D. Kanteev, Yu.O. Kostyukov, D.V. Luciv, D.V. Koznov, M.N. Smirnov        | Discovering Near Duplicate Text in Software Documentation                                        | Proceedings of the Institute for System Programming, vol. 29, issue 4, 2017, pp. 303-314                                                                                    | [![pdf](/img/pdf.png)](/pdf/articles/kanteev.kostykov.luciv.koznov.smirnov.2017.ispras.pdf)
| D. V. Luciv, D. V. Koznov, H. A. Basit, and A. N. Terekhov                  | On Fuzzy Repetitions Detection in Documentation Reuse                                            | Programming and Computer Software, 2016, Vol. 42, No. 4, pp. 216--224                                                                                                       | [![pdf](/img/pdf.png)](/pdf/articles/luciv.koznov.basit.terekhov_2016_en.pdf)
| D. Koznov, D. Luciv, H. Basit, O. Lieh, M. Smirnov                          | Clone Detection in Reuse of Software Technical Documentation                                     | Lecture Notes in Computer Science, Vol. 9609, 2016, pp. 170-185 (10th International Andrei Ershov Informatics Conference on Perspectives of System Informatics, PSI 2015)   | [![pdf](/img/pdf.png)](/pdf/articles/koznov.luciv.basit.lieh.smirnov_2016.pdf)
| D.V.Lutsiv, D.V.Koznov, H.A.Basit, O.E.Lieh, M.N.Smirnov, K.Yu.Romanovsky   | An Approach for Clone Detection in Documentation Reuse                                           | Scientific and Technical Journal of Information Technologies, Mechanics and Optics № 4 (92). St-Petersburg, ITMO University, 2014, pp. 106-114. (in Russian)                | [![pdf](/img/pdf.png)](/pdf/articles/dluciv.dkoznov.etall.2014.ifmo.pdf)
| D.V.Luciv, D.V.Koznov, V.S.Andreev                                          | Hierarchical diff algorithm for complicated documents                                            | Software Engineering (papers collection) № 7, edited by A.N.Terekhov and D.Y.Bulychev. SPb.: SPbSU publishing house, 2012, pp. 57-68. (in Russian)                          | [![pdf](/img/pdf.png)](/pdf/articles/luciv.koznov.andreev.2012.sysprog.pdf)
| D.V.Koznov, A.V.Shutak, M.N.Smirnov, M.A.Smarzhevsky                        | Clone Detection in Technical Documentation Refactoring                                           | Computer Tools in Education № 4, 2012, pp. 30-40. (in Russian)                                                                                                              | [![pdf](/img/pdf.png)](/pdf/articles/koznov.shutak.smirnov.smarzhevski.2012.kio.pdf)
| D.V.Koznov, K.Y.Romanovsky                                                  | Automated Refactoring of Software Product Lines Documentation                                    | Software Engineering (papers collection) № 4, edited by A.N.Terekhov and D.Y.Bulychev. SPb.: SPbSU publishing house, 2009, pp. 128-150. (in Russian)                        | [![pdf](/img/pdf.png)](/pdf/articles/DocLine_Refactoring_Sbornik_2009.pdf)
| K.Y.Romanovsky                                                              | Developing reusable documentation of telecommunication systems family using DocLine technology   | Saint-Petersburg University Bulletin. Series 10. 2009. № 2 (in Russian)                                                                                                     | [![pdf](/img/pdf.png)](/pdf/articles/DocLine_Telecom_Vestnik_2009.pdf)
| K.Romanovsky, D.Koznov, L.Minchin                                           | Refactoring the Documentation of Software Product Lines                                          | 3rd IFIP td2 Central and East European Conference on Software Engineering Techniques CEE-SET 2008, Brno (Czech Republic), October 13-15, 2008                               | [![pdf](/img/pdf.png)](/pdf/articles/DocLine_Refactoring_CEESET_2008.pdf)
| Koznov, D., Romanovsky K.                                                   | DocLine: the Method for Software Product Line Documentation Development                          | Programming and Computer Software, editor V.P. Ivannikov, Vol. 34, №4 2008, pp. 216-224                                                                                     | [![pdf](/img/pdf.png)](/pdf/articles/DocLine_Method_Programming_2008en.pdf)
| K.Y.Romanovsky, D.V.Koznov                                                  | DRL - the Language for Designing and Developing Software Product Lines Documentation             | Saint-Petersburg University Bulletin. Series 10, № 4, 2007. С. 110-122 (in Russian)                                                                                         | [![pdf](/img/pdf.png)](/pdf/articles/DocLine_DRL_Vestnik_2007.pdf)
| K.Y.Romanovsky                                                              | The Method for Software Product Line Documentation Development                                   | Software Engineering (papers collection) № 2, edited by A.N.Terekhov and D.Y.Bulychev. SPb.: SPbSU publishing house, 2006, pp. 191-218 (in Russian)                         | [![pdf](/img/pdf.png)](/pdf/articles/DocLine_Method_Sbornik_2006.pdf)
| D. Koznov, A. Peregudov, K. Romanovsky, A. Kashin, A. Timofeev              | The experience of applying UML to the creation of technical documentation                        | Software Engineering (papers collection) № 1, edited by A.N.Terekhov and D.Y.Bulychev. SPb.: SPbSU publishing house, 2005, pp. 18-35 (in Russian)                           | [![pdf](/img/pdf.png)](/pdf/articles/DocLine_UML_Sbornik_2005.pdf)
