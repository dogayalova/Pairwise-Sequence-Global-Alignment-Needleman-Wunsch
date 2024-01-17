# Needleman-Wunsch Global Sequence Alignment Implementation

## Project Overview
This project focuses on the implementation of the Needleman-Wunsch global sequence alignment algorithm, a foundational algorithm in bioinformatics for aligning protein or nucleotide sequences. The implementation is designed to handle both linear and affine gap penalties.

### Key Features
- **Linear and Affine Gap Penalty:** The algorithm supports both linear and affine gap penalty models.
- **BLOSUM62 Scoring Matrix:** Utilizes the BLOSUM62 scoring matrix for match and mismatch evaluations. The matrix is pre-loaded for convenience.
- **BioPython Comparison:** Includes a comparison with the BioPython implementation of the algorithm for validation purposes.

## Inputs and Outputs
The algorithm is designed to take the following inputs:
1. Two amino acid sequences to be aligned.
2. The type of gap penalty: either linear or affine.
3. The scoring matrix and the gap penalty parameter(s).

It outputs:
- The maximum alignment score of the input sequences.
- An alignment (or one of the alignments) achieving this maximum score.

## Implementation Details
- **Template Structure:** A Jupyter notebook template is provided, containing predefined function definitions and sample inputs.
- **Output Section:** The section titled “Your Output” in the notebook is where alignments and alignment scores for the provided inputs should be added.
- **Documentation:** The code includes comments explaining its functionality, along with a high-level description of the implementation.

## Instructions for Use
1. **Initial Setup:** Clone the repository and open the provided Jupyter notebook.
2. **Algorithm Configuration:** Choose the sequences, gap penalty type, and parameters as per your requirement.
3. **Execution:** Run the notebook to view the alignment scores and the corresponding alignments.
