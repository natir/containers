################## BASE IMAGE ######################

FROM biocontainers/biocontainers:latest

################## METADATA ######################

LABEL base_image="biocontainers:latest"
LABEL version="1"
LABEL software="bcalm"
LABEL software.version="2.2.0"
LABEL about.summary="BCALM 2 is a bioinformatics tool for constructing the compacted de Bruijn graph from sequencing data."
LABEL about.home="https://github.com/GATB/bcalm"
LABEL about.documentation="https://github.com/GATB/bcalm"
LABEL about.license_file="https://raw.githubusercontent.com/GATB/bcalm/master/LICENSE"
LABEL about.license="MIT"
LABEL extra.identifiers.biotools="bcalm"
LABEL about.tags="Genomics"

################## MAINTAINER ######################

MAINTAINER Pierre Marijon <pierre.marijon@inria.fr>

################## INSTALLATION ######################

RUN conda install bcalm

WORKDIR /data/

CMD ["bcalm"]
