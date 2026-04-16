# JIBO Kids Corpus

## Overview

The JIBO Kids Corpus is composed of structured and semi-structured speech from 110 children from pre-kindergarten through grade 1. This release version contains 383 individual wav files sampled at 16 kHz. Corresponding word-level transcriptions are also included.

Some changes have been made to how the corpus is distributed so that access is more reliable for users. In particular, the audio archive is no longer expected to download as part of `git clone`.

## Distribution Directory Structure

The original directory structure can be retrieved as follows.

Primary download method:

1. Clone this repository:

```bash
git clone https://github.com/balaji1312/Jibo_Kids
cd Jibo_Kids
```

2. Download the two release files from the GitHub Releases page:

[GitHub Releases](https://github.com/balaji1312/Jibo_Kids/releases)

3. Place both files in the repository directory and run:

```bash
cat jibo_release_part_aa jibo_release_part_ab > combined.zip
unzip combined.zip
```

Backup download method:

If the GitHub Releases download is unavailable, use the Zenodo record mirror:

[Zenodo Mirror](https://zenodo.org/records/13964792)

After downloading the same release files, place them in the repository directory and run:

```bash
cat jibo_release_part_aa jibo_release_part_ab > combined.zip
unzip combined.zip
```

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

## Citation

If you found this work useful in your research, please cite:

```bibtex
@article{shankar2024jibo,
  title={The JIBO Kids Corpus: A speech dataset of child-robot interactions in a classroom environment},
  author={Shankar, Natarajan Balaji and Afshan, Amber and Johnson, Alexander and Mahapatra, Aurosweta and Martin, Alejandra and Ni, Haolun and Park, Hae Won and Perez, Marlen Quintero and Yeung, Gary and Bailey, Alison and others},
  journal={JASA Express Letters},
  volume={4},
  number={11},
  year={2024},
  publisher={AIP Publishing}
}
```

## Contact Information

Further information about this corpus can be found at :

Refer specific questions to:

- Abeer Alwan
- Distinguished Professor, Electrical and Computer Engineering, UCLA
- Email: alwan@ee.ucla.edu
