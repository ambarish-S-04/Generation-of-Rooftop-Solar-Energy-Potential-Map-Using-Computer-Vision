☀️ Solar Rooftop Analysis & Panel Placement Toolkit
🌍 Overview
Harness the power of the sun — intelligently.
This project offers a comprehensive toolkit to analyze rooftop images, detect usable areas, and optimize solar panel placement using state-of-the-art deep learning and image processing techniques.

✨ Features
🔍 Rooftop Segmentation
Deep learning-based segmentation of rooftop areas and obstacles.

🖼️ Mask Generation
Automatically create binary masks from rooftop images.

🔧 Solar Panel Placement Optimization
Efficient algorithmic layout of solar panels for maximum output.

📊 Performance Evaluation
Visual and quantitative metrics to assess layout quality.

🌈 Visualization Tools
Generates heatmaps, panel layout diagrams, and coverage analysis.

🗂️ Project Structure
├── generate_masks.py                # Binary mask generator for rooftop images
├── rooftop_segmentation_model.py   # Deep learning model for rooftop & obstacle segmentation
├── solar_panel_placement.py        # Main script for panel layout and visualization
├── performance_evaluation.py       # Evaluates panel layout performance
├── testcases/                      # Sample rooftop images for testing
├── results*/                       # Output folders with layout and analysis visuals
├── model_epoch_*.pth               # Pretrained model weights
├── requirements.txt                # Required Python libraries
├── Solar Panel Placement/          # Additional scripts and visualizations
├── Polygon Approximation/          # Utility and geometry tools
🚀 Installation
Clone the repository

git clone https://github.com/ambarish-S-04/solar-rooftop-toolkit.git
cd solar-rooftop-toolkit
Install required dependencies

pip install -r requirements.txt
(Optional) Place Pretrained Weights
Add model files like model_epoch_*.pth to the project root if not already included.

🔧 Usage Guide
✅ 1. Generate Rooftop Masks
Create binary masks from your rooftop images (place images like 1.jpg, 2.jpg, etc., in the working directory):
python generate_masks.py
📝 Output: Binary masks (.png) named after the original files.

🧠 2. Rooftop Segmentation & Obstacle Detection
Use the segmentation model to isolate rooftops and detect any obstacles:
python rooftop_segmentation_model.py
✍️ Customize parameters inside the script as needed.

☀️ 3. Optimize Solar Panel Placement
Analyze usable area and place solar panels automatically:
python solar_panel_placement.py


📈 4. Evaluate Performance
Quantitatively assess panel layout efficiency:


python performance_evaluation.py
🧪 Example Data & Outputs
Test images can be found in the testcases/ directory.
Example outputs (to be added manually later) will be shown below:

📷 Insert panel layout demo image here
🌡️ Insert heatmap / coverage output here
📊 Insert performance graph / metrics screenshot here

📦 Requirements
Dependencies listed in requirements.txt. Major packages include:

numpy, pillow, matplotlib, opencv-python

scikit-image, pandas, seaborn, scipy, shapely

torch, torchvision, cython

Python 3.8+ recommended. CUDA-compatible GPU recommended for segmentation model.

📜 License
This project is licensed under the MIT License.
See the LICENSE file for more details.