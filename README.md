PHRED Score Analysis using Python

📌 Overview

This project focuses on implementing a Python-based method to analyze sequencing data using Phred quality scores. Phred scores are numerical values that indicate the probability of an incorrect base call in DNA sequencing. They play a critical role in quality control, DNA assembly, variant detection, and overall bioinformatics pipelines.

The project processes FASTQ files, identifies low-quality reads, and outputs results in a structured CSV format.

🎯 Objectives

Implement a Python-based approach to evaluate Phred scores.

Identify and filter low-quality reads.

Export results in CSV for further analysis.

Highlight the role of Phred scores in sequencing reliability.

🧬 What is a Phred Score?

A numerical representation of sequencing quality.

Indicates the probability of an incorrect base call.

🔑 Importance of Phred Scores

✅ Quality Control → Filters poor-quality bases/reads.

✅ Better DNA Assembly → High-quality reads improve sequence assembly.

✅ Accurate Variant Detection → Reduces false positives in mutation analysis.

✅ Universal Standard → Used across all sequencing platforms.

✅ Bioinformatics Pipelines → Integrated into FASTQ processing workflows.

✅ Reliable Genotyping → Enhances confidence in clinical/genomic studies.

⚙️ Methodology

Input FASTQ file

Python-based processing

Quality assessment

Filtering of low-quality reads

Structured CSV output

📊 Output

The output CSV file contains:

Read ID → Unique identifier for each sequencing read.

Sequence → Nucleotide sequence associated with the read.

Mean Phred Score → Average quality score across the read.
