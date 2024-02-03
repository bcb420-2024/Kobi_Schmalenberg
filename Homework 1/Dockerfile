# Dockerfile to build an image with reference to the course bcb420-base-image 
# with the additional packages DESeq2 and pheatmap installed assignment for BCB420 winter 2024.

FROM risserlin/bcb420-base-image:latest

# Run to install the packages for this assignment/future assignments
RUN R -e "BiocManager::install(c('DESeq2', 'pheatmap'))"

# Run to make the home directory for all of our Rstudio work this semester
RUN "mkdir /home/rstudio/data"

# To build: docker build -t <insert image name of choice> . 
