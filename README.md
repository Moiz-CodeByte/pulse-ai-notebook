# Pulse AI - AI Based Heart Disease Detection System MRI

## Overview

Pulse AI is a cardiac MRI-based heart disease detection notebook project. It focuses on training and evaluating deep learning models for MRI image classification, with the best VGG16 fine-tuned model used as the main model artifact.

This repository contains the research notebooks, extracted metrics, figures, and supporting analysis scripts. The proper implementation of the best VGG16 model is available at [Moiz-CodeByte/pulse-ai](https://github.com/Moiz-CodeByte/pulse-ai), and the live project is available at [https://pulseai.abdulmoiz.net/](https://pulseai.abdulmoiz.net/).

## Model Download

The trained best VGG16 model can be downloaded from Google Drive:

[Download best VGG16 model](https://drive.google.com/file/d/1Mx6UfN7jbGhY586NN53qxyoZTEmnGWIG/view?usp=sharing)

## Features

- **Cardiac MRI Classification**
  - MRI image preprocessing workflow
  - Deep learning-based disease classification
  - Best model selection using evaluation metrics

- **VGG16 Fine-Tuning**
  - Transfer learning with VGG16
  - Fine-tuned training pipeline
  - Saved model artifact available separately through Google Drive

- **Notebook Experiments**
  - Training and evaluation notebooks
  - 5-class classification experiments
  - Model performance metrics and visual outputs

- **Visualization and Analysis**
  - Confusion matrix figures
  - Dataset distribution charts
  - Training history plots
  - MRI comparison and sample output images

## Technology Stack

- **Language**: Python
- **Notebook Environment**: Jupyter Notebook / Google Colab
- **Deep Learning**: TensorFlow / Keras
- **Model Architecture**: VGG16
- **Visualization**: Matplotlib, Seaborn
- **Supporting Scripts**: Flask API and Node.js analysis service examples

## Repository Contents

- `Pulse-ai.ipynb` - Main Pulse AI notebook
- `ai-based-heart-disease-detection-system-mri.ipynb` - Original MRI detection notebook
- `notebooks/active/` - Active notebooks, extracted text, and metrics
- `notebooks/archive/` - Archived backend notebooks, scripts, and generated figures
- `notebooks/archive/figures/` - Confusion matrices, dataset distribution plots, training history charts, and sample outputs
- `notebooks/archive/scripts/` - Supporting Flask and Node.js scripts

## Installation

### Prerequisites

- Python 3.8 or higher
- Git
- Jupyter Notebook or Google Colab

### Clone the Repository

```bash
git clone https://github.com/Moiz-CodeByte/pulse-ai-notebook.git
cd pulse-ai-notebook
```

### Set Up Virtual Environment

```bash
# Create a virtual environment
python -m venv .venv

# Activate the virtual environment
# On Windows
.venv\Scripts\activate

# On macOS/Linux
source .venv/bin/activate
```

### Install Dependencies

Install the required Python packages used by the notebooks:

```bash
pip install tensorflow keras numpy pandas matplotlib seaborn scikit-learn opencv-python jupyter
```

### Download the Model

Download the trained model from:

[https://drive.google.com/file/d/1Mx6UfN7jbGhY586NN53qxyoZTEmnGWIG/view?usp=sharing](https://drive.google.com/file/d/1Mx6UfN7jbGhY586NN53qxyoZTEmnGWIG/view?usp=sharing)

Place the downloaded model file in:

```text
notebooks/active/models/
```

Model files are intentionally ignored by Git because trained `.keras` files can exceed GitHub's file size limit.

## Usage

### Run the Notebook

```bash
jupyter notebook
```

Open `Pulse-ai.ipynb` or the notebooks inside `notebooks/active/` and run the cells in order.

### View Results

1. Open the active or archived notebooks.
2. Review training metrics and model evaluation outputs.
3. Check generated figures in `notebooks/archive/figures/`.

### Use the Full Implementation

For the production-ready implementation of the best VGG16 model, visit:

[Moiz-CodeByte/pulse-ai](https://github.com/Moiz-CodeByte/pulse-ai)

Live project:

[https://pulseai.abdulmoiz.net/](https://pulseai.abdulmoiz.net/)

## References

- **Project Deployment**: [https://pulseai.abdulmoiz.net/](https://pulseai.abdulmoiz.net/)
- **GitHub Repository**: [https://github.com/Moiz-CodeByte/pulse-ai](https://github.com/Moiz-CodeByte/pulse-ai)
- **Notebook Repository**: [https://github.com/Moiz-CodeByte/pulse-ai-notebook](https://github.com/Moiz-CodeByte/pulse-ai-notebook)
- **Kaggle Notebook**: [AI Based Heart MRI Detection System - Pulse AI](https://www.kaggle.com/code/moizkalid/ai-based-heart-mri-detection-system-pluse-ai)
- **Google Colab Notebook**: [https://colab.research.google.com/drive/1mZ1CFhKMvCUXa0Qp2dUeGSBlb38P7rim](https://colab.research.google.com/drive/1mZ1CFhKMvCUXa0Qp2dUeGSBlb38P7rim)
- **CAD Dataset VGG16 Notebook for Testing**: [https://www.kaggle.com/code/moizkalid/cad-pulse-ai-vgg16](https://www.kaggle.com/code/moizkalid/cad-pulse-ai-vgg16)
- **CAD Dataset CNN Notebook for Testing**: [https://www.kaggle.com/code/moizkalid/cad-cnn-pulse-ai](https://www.kaggle.com/code/moizkalid/cad-cnn-pulse-ai)

## Project Structure

- `notebooks/active/` - Current working notebooks and metrics
  - `Pulse-ai.ipynb` - Active Pulse AI notebook
  - `Pulse-ai-extracted.txt` - Extracted notebook content
  - `Pulse-ai-metrics.txt` - Model metrics summary

- `notebooks/archive/` - Archived experiments and backend work
  - `Pulse_AI_Backend.ipynb` - Backend experiment notebook
  - `Pulse_AI_Backend_5Class.ipynb` - 5-class backend experiment notebook
  - `figures/` - Generated visualizations
  - `scripts/` - Flask and Node.js helper scripts

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---
For any questions or support, please contact at [hello@abdulmoiz.net](mailto:hello@abdulmoiz.net).
