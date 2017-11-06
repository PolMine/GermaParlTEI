# GermaParl - Corpus of Plenary Protocols

The GermaParl corpus has been prepared in the
[PolMine Project](https://polmine.github.io/) based on the
protocols of plenary debates that are published by the German Bundestag.


## Data format

The raw data is prepared using an automated procedure and results in XML files.
Corpus XML is modelled on the standards of the
[Text Encoding Initiative (TEI)](http://www.tei-c.org). As there is not 
yet a specified TEI guideline for protocols of parliamentary bodies, the
scheme that was used is derived from the TEI specification for performance
texts. The structure of performance texts (drama etc.) matches the 
requirements for the structural annotation of plenary protocols
reasonably well. Recommendations and ideas how to improve the annotation
is welcome.


## Dissemination and Documentation

The standard way for disseminating the corpus is a linguistically annotated
version that has been indexed upon importing it into the
[IMS Open Corpus Workbench](http://cwb.sourceforge.net/). The CWB indexed
version of the corpus is offered wrapped into a R data package. For most
non-technical users, this is the most convenient way to work with GermaParl:
The R package [polmineR](https://CRAN.R-project.org/package=polmineR)
offers targetted functionality to work with GermaParl (see als the
[development version of polmineR at GitHub](https://github.com/PolMine/polmineR)).


The documentation of the GermaParl R data package offers a more extensive
documentation of the data. See also the
[website with the package documentation](http://polmine.sowi.uni-due.de/docs/GermaParl/)
as a shortcut to access the documentation for GermaParl. 
See the package vignette, in particular.


## License

The raw data (txt and pdf documents) are in the public domain. The
prepared corpus comes with a CLARIN PUB+BY+NC+SA license (see file LICENSE.md
in this folder).

## Using and quoting GermaParl

We are still evaluating different options for a 'rock solid' way to quote
GermaParl using persistent identifieres. For the time being, the best 
academic practice that may be available is to quote GermaParl roughly as follows, 
if you use it in your academic work:

Blaette, Andreas (2017): GermaParl. Corpus of Plenary Protocols of the German Bundestag.
TEI files, availables at: https://github.com/PolMine/GermaParlTEI.

If you plan to use GermaParl in a commercial setting that is not covered by
the license, please get in touch with us (andreas.blaette@uni-due.de).

## Future plans

The procedure used for corpus preparation is suited for adding new protocols to
the corpus on a regular basis, and for adding older protocols. Beta versions 
for older or newer protocols may exist, but are not yet sufficiently consolidated and/or 
documented to be published.


## Feedback

One big advantage of publishing the TEI files of the GermaParl corpus at GitHub
is that the issues tracker can be used to raise issues. Your feedback is highly 
welcome! We hope we can gradually improve data quality. Flaws you come 
accross are essential for the progress that can be made to improve data quality.

