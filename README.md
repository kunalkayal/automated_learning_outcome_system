
# Automated Learning Outcome Extraction System

## Introduction

The **Automated Learning Outcome Extraction System** utilizes **Natural Language Processing (NLP)** to automate the extraction and classification of learning outcomes from educational texts. The system aligns these outcomes with **Bloom's Taxonomy**, providing educators and learners with valuable insights. By replacing manual processes with automation, this project enhances efficiency, accuracy, and scalability in educational assessments.

---

## Features
- **Automated Extraction**: Extract learning outcomes from syllabi and course materials.
- **Bloom's Taxonomy Integration**: Categorizes outcomes based on cognitive levels.
- **Machine Learning Powered**: Implements advanced ML algorithms for accurate text analysis.
- **Real-time Feedback**: Assists educators in identifying and addressing learning gaps.
- **Enhanced Curriculum Design**: Facilitates personalized learning and assessments.

---

## System Requirements

### Hardware
- **Processor**: Core i3/i5 or better.
- **Memory**: Minimum 8 GB RAM.
- **Storage**: Minimum 60 GB usable space.
- **GPU**: NVIDIA graphics card with CUDA Compute Capability (3.5 to 8.6).

### Software
- **Operating System**:
  - Windows 10/11 (64-bit) or Linux (kernel 3.10.0+, glibc 2.17+).
- **Python Environment**:
  - Python 3.x
  - [Anaconda Distribution](https://www.anaconda.com/)
  - NLTK Toolkit
- **Google Colab**: For project implementation and testing in a cloud environment.

---

## Installation

Follow these steps to set up and run the project on Google Colab:

1. **Clone or Download the Repository**:  
   ```bash
   git clone https://github.com/your-repo-name/automated-learning-outcome-system.git
   cd automated-learning-outcome-system

    Open the Notebook:
        Upload the project notebook to Google Colab.

    Install Required Libraries: In the first cell of the Colab notebook, include:

    !pip install nltk
    !pip install docx2txt

    Upload Dataset:
        Upload the educational text files or course syllabus in .pdf format to Colab.

    Run the Notebook:
    Execute the notebook cells step by step to preprocess the data, extract learning outcomes, and classify them.

---
## Methodology

1. **Data Collection**: Gather course syllabi, textbooks, and instructional materials.
2. **Data Preprocessing**:
        Tokenization, stop-word removal, and lemmatization.
    Rule-Based Extraction: Use patterns like POS tagging and keyword detection.
    Machine Learning: Train models (e.g., SVM) to classify outcomes into Bloom's 

3. **Taxonomy categories**.
    Evaluation: Measure accuracy, precision, and recall to refine models.

---
## Outputs
1. **Accuracy Results**:

- ChatGPT: 80%
- SVM: 78.33%
- BERT: 50%
---
## Key Benefits:

- Identify cognitive domains of learning outcomes.
- Suggest personalized learning recommendations.
- Streamline curriculum updates and feedback.

---
## Future Scope

- Achieve a target accuracy of 90% using advanced deep learning algorithms.
- Expand applicability to diverse disciplines and educational levels.
- Develop a user-friendly graphical interface.
- Integrate additional data sources for broader coverage.

---
## References
For a detailed list of references, refer to the project documentation.

---
## License
This project is licensed under the MIT License.

---
## Acknowledgments

Special thanks to:

Google Colab for providing a cloud-based development environment.
The developers and contributors who supported this project.



