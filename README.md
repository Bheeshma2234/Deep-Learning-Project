# DL Case Study — Mark Sheet OCR

## Project Team

**Developed by:**
- Bhargav
- Vishal
- Pranav
- Bheeshma

## Under the Guidance of

**Panigrahi Srikanth**  
Assistant Professor  
Department of Computer Science and Engineering (AI & ML)  
Chaitanya Bharathi Institute of Technology (CBIT), Hyderabad

---

## 1. Project Overview

Mark Sheet OCR is a deep learning case study focused on extracting text and academic information from mark sheets using Optical Character Recognition (OCR) techniques.

The project explores image processing and OCR-based text extraction to help digitize academic records and organize extracted information into structured outputs for further analysis and verification.

## 2. Objectives

- Extract text from mark sheet images using OCR techniques.
- Apply image-processing methods to improve text recognition.
- Organize extracted information into structured formats.
- Generate spreadsheet-based outputs for easier review.
- Validate extracted information and identify potential recognition errors.
- Reduce manual effort involved in digitizing academic records.

## 3. Technologies Used

- **Programming Language:** Python
- **Development Environment:** Google Colab / Jupyter Notebook
- **Deep Learning and OCR:** PaddleOCR and PaddlePaddle
- **Image Processing:** OpenCV
- **Data Processing:** Pandas and Python utilities
- **Output Generation:** Excel files
- **Storage:** Google Drive, where configured

## 4. Project Workflow

1. **Input:** Provide mark sheet images or the supported input files.
2. **Image Processing:** Prepare the images for OCR processing.
3. **Text Extraction:** Use the OCR model to identify text from the mark sheets.
4. **Data Organization:** Process the extracted text and organize relevant academic information.
5. **Validation:** Check extracted values and flag information that may require manual verification.
6. **Output Generation:** Save the processed results in a structured format, such as an Excel report, where implemented.
7. **Review:** Verify the generated output against the original mark sheets.

## 5. Project Structure

The GitHub repository is organized as follows:

```text
DL Case Study/
├── README.md
└── Mark sheet OCR DL Case Study.ipynb
```

The notebook contains the project's implementation, including the code cells, processing steps, and execution outputs saved in the notebook.

## 6. Requirements

The project uses Python and the libraries required by the notebook.

Depending on the execution environment, the following packages may be needed:

```bash
pip install paddleocr paddlepaddle opencv-python pandas openpyxl
```

**Note:** PaddlePaddle installation requirements can vary by operating system, Python version, and hardware. Follow the official installation instructions if the default command does not work.

## 7. How to Run the Project

### Option 1: Run using Google Colab

1. Open [Google Colab](https://colab.research.google.com/).
2. Download the notebook from this repository.
3. Upload `Mark sheet OCR DL Case Study.ipynb` to Colab.
4. Install any required dependencies specified in the notebook.
5. If the notebook uses Google Drive, mount Drive and provide the appropriate input paths.
6. Upload or locate the required mark sheet images.
7. Execute the notebook cells in the correct order.
8. Review the extracted text and generated outputs.

### Option 2: Run locally using Jupyter Notebook

1. Install Python and Jupyter Notebook.
2. Clone or download this repository.
3. Install the dependencies required by the notebook.
4. Place the input images in the expected directory.
5. Update any file paths or configuration settings as necessary.
6. Open and execute `Mark sheet OCR DL Case Study.ipynb`.
7. Check the output files and verify the extracted information.

## 8. Expected Outputs

Depending on the notebook configuration and execution, the project may produce:

- Extracted text from mark sheet images.
- Processed academic information.
- Structured tabular data.
- Excel reports for reviewing the extracted information.
- Validation results or entries requiring manual review.

Actual outputs depend on the input images, OCR model performance, and the implementation in the notebook.

## 9. Validation and Limitations

OCR accuracy can be affected by:

- Low-resolution or blurry images.
- Uneven lighting and image distortion.
- Different mark sheet layouts and fonts.
- Handwritten entries, stamps, or overlapping text.
- Incorrect interpretation of numbers and special characters.

The extracted information should be checked against the original mark sheets. The system should not be treated as a replacement for official academic verification.

## 10. Privacy and Responsible Use

Mark sheets can contain sensitive personal and academic information. Use authorized data for testing and demonstration. Remove or anonymize personal information before publishing sample images, screenshots, or output files in a public repository.

Do not upload confidential student records, personal identifiers, or private institutional data to a public GitHub repository.

## 11. Conclusion

This project demonstrates the application of OCR and image-processing techniques to the digitization of academic mark sheets. It provides a foundation for extracting, organizing, and reviewing academic information while highlighting the importance of validation and responsible handling of educational records.

## Acknowledgement

We express our sincere gratitude to **Panigrahi Srikanth, Assistant Professor, Department of CSE (AI & ML), Chaitanya Bharathi Institute of Technology (CBIT), Hyderabad**, for guiding us throughout this case study.

We also acknowledge the learning resources and open-source tools that support the exploration of deep learning and OCR technologies.

---

**Project:** DL Case Study — Mark Sheet OCR  
**Institution:** Chaitanya Bharathi Institute of Technology (CBIT), Hyderabad  
**Department:** Computer Science and Engineering (AI & ML)
