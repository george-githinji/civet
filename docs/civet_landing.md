
**C**luster **I**nvestigation & **V**irus **E**pidemiology **T**ool

<img src="./figures/civet_logo.png" width="450">

civet is a tool developed with 'real-time' genomics in mind. 

Using a background phylogeny, such as the large phylogeny available through the COG-UK infrastructure on CLIMB, civet will generate a report for a set of sequences of interest i.e. an outbreak investigation. 

If the sequences are already on CLIMB and part of the large tree, civet will pull out the local context of those sequences, merging the smaller local trees as appropriate. If sequences haven't yet been incorporated into the large phylogeny, for instance if they have just been sequenced, civet will find the closest sequence in the large tree, pull the local tree of that sequence out and add your sequence in. The local trees then get collapsed to display in detail only the sequences of interest so as not to inform investigations beyond what was suggested by epidemiological data. 

A fully customisable report is generated, summarising information about the sequences of interest. The tips of these trees can be coloured by any categorical trait present in the input csv, and additional fields added to the tip labels. Optional figures may be added to describe the local background of UK lineages and to map the query sequences using coordinates, again colourable by a custom trait. 