A Bash script for downloading, converting, and analyzing SRA files.
This script streamlines the process of handling sequencing data by automating the conversion of SRA files to FASTQ format and performing quality control analysis.

VERSIONS OF THE SCRIPT
This repository contains two versions of the script, one in English and another in Portuguese. Choose the one that best suits your needs.

   English Version: sra2fastq.sh
   Portuguese Version: sra2fastq_pt.sh

Both scripts have the same functionality, but the language of the comments and user prompts is different.

FEATURES
Downloads SRA files using a list of accession numbers.
Converts SRA files to compressed FASTQ files (paired-end supported).
Performs quality control analysis using FASTQC.
Provides a menu for phase selection, allowing flexibility in execution.

REQUIREMENTS
Before running the script, ensure the following tools are installed and available in your PATH:

   SRA Toolkit
   FASTQC

PHASES
The script offers the following operations through a menu-based interface:

Phase 1: Download SRA files.
Phase 2: Convert SRA files to FASTQ format.
Phase 3: Perform quality analysis of FASTQ files.
All Phases: Execute all phases sequentially.
Phases 2 & 3: Convert and analyze FASTQ files.


IMPORTANT NOTE
The script uses the file SRR_Acc_List.txt (included in the repository) to download SRA files.
If you need to use a different file, update the INPUT_FILE variable in the Phase 1 section of the script.
