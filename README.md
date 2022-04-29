# fastqc_pdf Tool
Run FASTQC tool on large number of samples (fastq) parallelly.


# Advantage of fastqc_pdf tool:
1. Multithreading is added to run on larger samples (You can you use the maximum CPU cores in QC) in order to save time.  
2. It can generate PDF reports instead of HTML reports.


# Dependencies to install:
Download FastQC, add executable permision to fastqc and add it to your path in .bashrc file.

pip3 install weasyprint

sudo apt install parallel

# Download and run fastqc_pdf

git clone https://github.com/ranjanjs34/fastqc_pdf.git

cd fastqc_pdf

chmod +x ./fastqc_pdf

Execute the binary as: ./fastqc_pdf

## Citation: Andrews, S. (2010). FastQC: A Quality Control Tool for High Throughput Sequence Data [Online].
