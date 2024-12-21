# AcciMaps Analysis

A comprehensive workflow for processing PDF and PNG files, extracting text, and performing graph-based community analysis. This repository includes a Jupyter Notebook for processing, installation guides, and supporting documentation.

## Files Included

1. **Structure.pdf**  
   Contains the setup instructions and detailed environment requirements for running the Jupyter Notebook.

2. **Installation Guide.pdf**  
   Provides detailed descriptions of the cells in the notebook, their purpose, and their integration into the overall workflow.

3. **PDF2_Multiple.ipynb**  
   A Jupyter Notebook implementing the pipeline for processing PDF and PNG files, including text extraction, graphical analysis, and clustering.

## Features

- Converts PDFs to PNGs and processes images for contour detection.
- Applies OCR for text extraction and outputs results in structured JSON format.
- Detects graph communities using algorithms like Girvan-Newman and Louvain.
- Visualizes results with GraphML files and provides embeddings for clustering.
- Supports advanced debugging and data validation steps.

## Installation

### Prerequisites

- Python 3.x
- Virtual environment setup
- Jupyter Notebook installed
- Required Python libraries: `pdf2image`, `opencv-python-headless`, `numpy`, `pandas`, and `PaddleOCR`

### Step-by-Step Installation

Follow the setup instructions provided in the **Structure.pdf** document or refer to the "Installation Guide" section of the repository.

### Quick Setup

1. Create and activate a virtual environment:
   ```bash
   python3 -m venv accimap_env
   source accimap_env/bin/activate  # macOS/Linux
   accimap_env\Scripts\activate     # Windows
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Usage

1. Open the `PDF2_Multiple.ipynb` notebook in Jupyter.
2. Follow the step-by-step execution of the cells as described in **Installation Guide.pdf**.
3. View results in structured JSON formats, debug images, or GraphML files for analysis.

## Output

- **Processed Files**: Generated PNGs, debug images, and JSON outputs for text and rectangle data.
- **Graph Analysis**: Adjacency matrices, GraphML files, and clustering results.
- **Visualisation**: Community graphs with modularity and embedding-based clustering.

## Documentation

For detailed documentation, refer to:
- `Structure.pdf` for setup guidance.
- `Installation Guide.pdf` for detailed workflow and cell descriptions.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## Licence

[MIT Licence](LICENSE)
