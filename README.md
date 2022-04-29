# fastqc_pdf Tool
Run FASTQC tool on large number of samples parallelly.


# Advantage of fastqc_pdf tool:
1. Instead of single prcess at a time, multithreading is added to run on larger samples. 
2. It can generate PDF reports instead of HTML reports.


# Dependencies to install:
Download FastQC, add executable permision to fastqc and add it to your path in .bashrc file.

pip3 install weasyprint

sudo apt install parallel

# Download and run fastqc_pdf
git clone https://github.com/ranjanjs34/fastqc_pdf.git
cd fastqc_pdf
chmod +x ./fastqc_pdf
Run as: ./fastqc_pdf

## Citation: Andrews, S. (2010). FastQC: A Quality Control Tool for High Throughput Sequence Data [Online].
