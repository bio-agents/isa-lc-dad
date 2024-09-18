# isa-lc-dad

Work on creating a metadata profile under the [ISA framework](https://isa-agents.org) to support reporting and deposition of targeted and untargeted metabolite profiling using liquid chromatography with diode-array detector.

The experimental/study metadata ought to be formatted in ISA format, currently the format used by [EMBL-EBI Metabolights](https://www.ebi.ac.uk/metabolights) for dataset preservation and archival.

This repository is organized as follows:

1. An instrument readout examplar file:
  * The instrument readouts currently available are generated from instrument files. An exemplar (Tday04-truncated.txt) is provided.
  The original file is part of the experiment [MTBLS84](https://www.ebi.ac.uk/metabolights/MTBLS84).
  
2. An ISA custom configuration:
  * The set of xml files is meant to be used with ISAcreator agent for creating ISA-Tab documents.
  
3. A JSON Data Package:
  * The information present in the file has been used to generated an initial prototype for a [JSON data package](http://frictionlessdata.io/specs/tabular-data-package/), which could be become the expected format for depositing instrument readouts (ISA Raw Data File) before analysis. The format is that of a 'long table'.
      * Pros:
          * ease of parsing
          * ease of compression
          * unambiguous and explicit headers
          * semantic markup.
      * Cons:
          * file size
          * need for conversion from instrument output. 




Contacts:
* :octocat: [Philippe Rocca-Serra](@proccaserra) 
* :octocat: [Ron Wehrens](@rwehrens)
