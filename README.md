# NLP - Urdu Text Segmentation

## Overview
This Jupyter Notebook contains a demo program for segmenting Urdu text into sentences using Natural Language Processing (NLP) techniques. The program utilizes the `UrduHack` library for tokenization and segmentation, and it demonstrates how to read, process, and save segmented sentences.

## Contents
1. **Introduction**
   - Author: Haroon Wajid (21i-1763)
   - Purpose: To provide a foundational understanding of sentence segmentation in Urdu.

2. **Installation**
   - To install the required library, run the following command:
     ```bash
     pip install urduhack[tf]
     ```

3. **Reading Input Files**
   - The program reads text from a file named `sent-test.txt` and segments it into sentences.

4. **Segmentation Process**
   - The segmentation is performed using the `sentence_tokenizer` from the `UrduHack` library.
   - The segmented sentences are stored in a list and can be further processed.

5. **Reading Segmented Output**
   - The program reads from a segmented file named `sent-segmented.txt` to analyze the segmentation results.

6. **Normalization and SentencePiece Encoding**
   - The notebook includes functions for normalizing Urdu text and performing Byte Pair Encoding (BPE) for vocabulary generation.

7. **Accuracy Calculation**
   - The accuracy of the segmentation process is calculated by comparing the total number of segmented sentences to an expected count.

8. **Example Usage**
   - The notebook provides an example of how to encode and decode sentences using the SentencePiece method.

## Requirements
- Python 3.x
- Jupyter Notebook
- `urduhack` library

## How to Run
1. Ensure you have Python and Jupyter Notebook installed.
2. Install the required libraries using the installation command provided above.
3. Open the notebook in Jupyter and run the cells sequentially to see the segmentation process in action.

## Conclusion
This notebook serves as a practical guide for understanding sentence segmentation in Urdu using NLP techniques. It provides a comprehensive approach to handling text data, ensuring accurate segmentation while maintaining the integrity of the language's structure.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
