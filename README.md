# AI-380H: AI in Healthcare

A collection of teaching materials, Jupyter notebooks, and slides created by Joshua Ludolf for an AI in Healthcare course. The repository focuses on applied topics across medical imaging, clinical natural language processing (NLP), and predictive modeling.

## Repository contents

### Notebooks
- Brain CT Medical Imaging Tutorial — [Notebook](https://github.com/Joshua-Ludolf/AI-380H-AI-In-Healthcare/blob/main/Brain%20CT%20Medical%20Imaging%20Tutorial.ipynb) · [Open in Colab](https://colab.research.google.com/github/Joshua-Ludolf/AI-380H-AI-In-Healthcare/blob/main/Brain%20CT%20Medical%20Imaging%20Tutorial.ipynb)
- EBM-NLP LLM Tutorial — [Notebook](https://github.com/Joshua-Ludolf/AI-380H-AI-In-Healthcare/blob/main/EBM-NLP%20LLM%20TUTORIAL%20-%20Joshua%20Ludolf.ipynb) · [Open in Colab](https://colab.research.google.com/github/Joshua-Ludolf/AI-380H-AI-In-Healthcare/blob/main/EBM-NLP%20LLM%20TUTORIAL%20-%20Joshua%20Ludolf.ipynb)
- MIMIC NLP — [Notebook](https://github.com/Joshua-Ludolf/AI-380H-AI-In-Healthcare/blob/main/MIMIC%20NLP%20-%20Joshua%20Ludolf.ipynb) · [Open in Colab](https://colab.research.google.com/github/Joshua-Ludolf/AI-380H-AI-In-Healthcare/blob/main/MIMIC%20NLP%20-%20Joshua%20Ludolf.ipynb)
- Predicting In‑Hospital Mortality — [Notebook](https://github.com/Joshua-Ludolf/AI-380H-AI-In-Healthcare/blob/main/Predicting%20In-Hospital%20Mortality%20-%20Joshua%20Ludolf.ipynb) · [Open in Colab](https://colab.research.google.com/github/Joshua-Ludolf/AI-380H-AI-In-Healthcare/blob/main/Predicting%20In-Hospital%20Mortality%20-%20Joshua%20Ludolf.ipynb)

### Slides
- Brain CT Medical Imaging Tutorial — [Slides](https://github.com/Joshua-Ludolf/AI-380H-AI-In-Healthcare/blob/main/Brain%20CT%20Medical%20Imaging%20Tutorial.pptx)
- EBM-NLP LLM Tutorial — [Slides](https://github.com/Joshua-Ludolf/AI-380H-AI-In-Healthcare/blob/main/EBM-NLP%20LLM%20TUTORIAL%20-%20Joshua%20Ludolf.pptx)
- MIMIC SQL — [Slides](https://github.com/Joshua-Ludolf/AI-380H-AI-In-Healthcare/blob/main/MIMIC%20SQL%20-%20Joshua%20Ludolf.pptx)
- MIMIC NLP — [Slides](https://github.com/Joshua-Ludolf/AI-380H-AI-In-Healthcare/blob/main/MIMIC%20NLP%20-%20Joshua%20Ludolf.pptx)

## Quick start

You can run the notebooks in your browser with Google Colab (no local setup required):

- Click any “Open in Colab” link above.
- If a notebook references data, see the Data access section below.

To run locally:

1. Clone the repository
   ```bash
   git clone https://github.com/Joshua-Ludolf/AI-380H-AI-In-Healthcare.git
   cd AI-380H-AI-In-Healthcare
   ```
2. Create a Python environment (optional but recommended)
   ```bash
   python -m venv .venv
   # macOS/Linux
   source .venv/bin/activate
   # Windows (PowerShell)
   .venv\Scripts\Activate.ps1
   ```
3. Install common dependencies (adjust per notebook)
   ```bash
   pip install -U jupyter numpy pandas matplotlib seaborn scikit-learn
   # Optional, depending on the notebook(s):
   # pip install pydicom nibabel SimpleITK transformers torch nltk spacy
   ```
4. Launch Jupyter and open a notebook
   ```bash
   jupyter notebook
   ```

## Data access and prerequisites

- MIMIC (III/IV) content: Access requires credentialing and data use agreement. Ensure you have proper authorization and follow all data handling policies. No protected health information (PHI) should be uploaded to this repository or Colab.
- EBM‑NLP: Some notebooks may reference the EBM‑NLP dataset. Follow the dataset’s access instructions and terms of use.
- Imaging examples: If required, provide local paths to sample DICOM/NIfTI data or use sample data referenced within the notebook. Install imaging libraries (e.g., pydicom, nibabel, SimpleITK) as needed.

## Notes

- The exact package set varies by notebook; Colab typically includes many of the required libraries. If an import error occurs, install the missing package with `pip install <package>` in a notebook cell.
- GPU acceleration (when available) can speed up model training. In Colab, enable GPU from Runtime → Change runtime type.

## License

See the [LICENSE](./LICENSE) file for details.

## Acknowledgments

Course materials authored and maintained by Joshua Ludolf for AI‑380H: AI in Healthcare.