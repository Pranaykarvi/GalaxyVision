# 🌌 GalaxyVision: Deep Space Image Analysis

## 📌 Project Overview


## 🚀 Features
- **Galaxy Classification:** Identifies galaxy types (Spiral, Elliptical, Irregular).
- **Astrophysical Analysis:** Extracts metadata (Redshift, Brightness, Spectral Type) from SDSS data.
- **Object Detection:** Recognizes stars, nebulae, and galaxies in deep-space images.
- **Hybrid Model:** Combines Convolutional Neural Networks (CNNs) with structured astrophysical data.

## 📂 Dataset Sources
1. **Galaxy Zoo Dataset** - [Zooniverse](https://www.zooniverse.org/projects/zookeeper/galaxy-zoo/) (Labeled galaxy images)
2. **SDSS Sky Survey Data** - [SDSS SkyServer](http://skyserver.sdss.org/) (Spectral and photometric data)
3. **Hubble Space Telescope (HST) Archives** - [HLA](https://hla.stsci.edu/) (High-resolution space images)

## 🏗️ Tech Stack
- **Programming Language:** Python
- **Frameworks:** TensorFlow / PyTorch
- **Data Processing:** OpenCV, NumPy, Pandas
- **Visualization:** Matplotlib, Seaborn

## 🔧 Installation
```bash
# Clone the repository
git clone https://github.com/your-username/GalaxyVision.git
cd GalaxyVision

# Create a virtual environment (optional)
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## 📊 Model Architecture
The model consists of a **Convolutional Neural Network (CNN)** trained on galaxy images and a **Fully Connected Network (FCN)** that integrates SDSS metadata.

## 📈 Training the Model
```bash
python train.py --epochs 50 --batch_size 32 --dataset_path ./data
```

## 🔍 Running Inference
```bash
python predict.py --image_path sample_galaxy.jpg
```

## 🛠️ Future Enhancements
- Fine-tune models with additional space datasets.
- Deploy as a web-based tool using Flask/Streamlit.
- Add support for exoplanet detection using NASA archives.

## 📜 License
This project is open-source under the **MIT License**.

