This is a container repository connecting two submodules.

One is a fork and adaption from
https://github.com/snakemake-workflows/rna-seq-star-deseq2
so most credit for that goes to the authors of that package:

- Johannes Köster (@johanneskoester), https://koesterlab.github.io
- Sebastian Schmeier (@sschmeier), https://sschmeier.com
- Jose Maturana (@matrs)

The other one contains the code for sRNA-seq analysis (which uses some modules from the first repository).

In order to run the pipeline look for

pipelines/srna-seq/rnai_mutants/run.sh

and make sure the raw sequencing files are available in

pipelines/srna-seq/rnai_mutants/units.csv
