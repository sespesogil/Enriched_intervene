# Enriched_intervene

SLURM utility based in [intervene](https://github.com/asntech/intervene) with increased functionality: adding gene annotations and association across interesected regions.
Requirements

    R > 3.6
    bedtools
    UpSetR
    regioneR

# Usage

First, indicate the path of your R and bedtools installation (or load corresponding modules, modify the script accordingly)

Then, place all bedfiles containing regions of interest in a folder and then simply run:

```./Enriched_intervene.sh folder_path specie``` <br/>
