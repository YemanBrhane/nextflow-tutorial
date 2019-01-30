RNA-Seq toy pipeline 
======================

A proof of concept of a RNA-Seq pipeline intended to show Nextflow
scripting and reproducibility capabilities.

Prerequisits
----------------

1) Install Docker on your computer. Read more here https://docs.docker.com/

2) Install Nextflow (version 0.24.x or higher)

    `curl -fsSL get.nextflow.io | bash`

3) Pull the required Docker image as shown below: 

    `make pull`

    or build one

    `make build`


4) Launch the pipeline execution: 

    `nextflow run main.nf` 