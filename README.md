# CFILT-Preorder: Source Side reordering Rules for English-Indian language SMT

This package contains a rule based system for reordering English sentences to conform to the word order in Indian languages. It has been developed keeping Hindi in mind as the target language, but has been found to work for other Indian languages too. The reordered English sentences can be used instead of the original sentences for training a phrase SMT system from English to Indian languages. 

## Prerequisites

- OS - Linux
- Perl
- Perl Recursive Descent Parser require: Module: Parse::RecDescent 
  - In Ubuntu, this can be obtained by installing the package: libparse-recdescent-perl
- Stanford Parser Version 3.2.0

## Instructions

1. Download and unzip cfilt_preorder.tar.gz in the stanford home directory 'default: STANFORD_HOME'

## Usage: 

1. Change to the stanford home directory (STANFORD_HOME)
2. Run the command 
    ./reorderEnglish.sh <input_file_path> generic 

    The input file is reordered and the reordered sentences are stored in the file <input_file_path>.v1.0codkilled


## Contributors

- Ananthakrishnan Ramanathan
- Ritesh Shah
- Jayprasad Hegde
- Rajnath Patel 
- Rajen Chatterjee
- Anoop Kunchukuttan
