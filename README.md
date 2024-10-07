# JIBO Kids Corpus

## Overview

The JIBO Kids Corpus is composed of structured and semi-structured speech from 110 children from pre-kindergarten through grade 1. This release version contains 383 individual wav files sampled at 16 kHz. Corresponding word-level transcriptions are also included.

## Distribution Directory Structure

Following is a description of the directory structure in this release:

```
* data/: The data directory contains the actual .wav files, along with their word-level transcription (in .txt files).
    * data/letters_digits/: This directory contains session recordings from children attempting the letter and digit identification task.
    * data/brush/: This directory contains session recordings from children attempting the explanation task 'brushing their teeth'.
    * data/colors/: This directory contains session recordings from children attempting the explanation task 'mixing paint into colors'.
    * data/blocks/: This directory contains session recordings from children attempting the explanation task 'determining the number of cubes'.
```

## File Naming Scheme

Each child was anonymized in the format TXYY7ZZZ, where: X in \{1,2\} is the year of the study,  YY in \{01, 02, 03\} is the child's year in school - 01 - Pre-kindergarten, 02 - Kindergarten,  03 - grade 1. ZZZ is a unique identifier for each child.  Boys are odd numbered and girls are even numbered. Thus, T1027235 is child 235, a male kindergartener whose data was collected
in year one of the study.

## Recording Conditions and Data Collection

Additional information about the specfic setup used for data collection, as well information about the tasks is present in the paper accompanying this dataset.

## Contact Information

Further information about this corpus can be found at :

Refer specific questions to:

- Abeer Alwan
- Distinguished Professor, Electrical and Computer Engineering, UCLA
- Email: alwan@ee.ucla.edu
