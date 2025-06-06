# Age-Group-Detection using Deep Learning 
This project implements a Convolutional Neural Network (CNN) to classify human face images into age groups such as `Young`, `Middle`, and `Old`.
## 🚀 Project Summary
The notebook trains a baseline neural network on facial images and evaluates its performance on test data. It also includes prediction export to CSV and visual inspection of model outputs.
## 📁 Project Structure
├── IdentificationOfAgeGroup.ipynb # Main notebook (model training & testing)
├── submission.csv # Output predictions on test data
├── agedetectiontrain.zip # [Not included] Training dataset (images + train.csv)
├── agedetectiontest.zip # [Not included] Test dataset (images + test.csv)
> ⚠️ Due to licensing restrictions, the train/test datasets are not included in this repository.

## 📦 Dataset Information
You can download the training and test datasets from the original source or upon request. Each dataset folder contains:
- A folder of facial images (`.jpg`)
- A corresponding CSV file:
  - `ID` column: image filenames (e.g., `352.jpg`)
  - `Class` column: corresponding age group (e.g., `Old`, `Young`, etc.)
### 📚 Dataset Reference
Shankar Setty, Moula Husain, Parisa Beham, Jyothi Gudavalli, Menaka Kandasamy,
Radhesyam Vaddi, Vidyagouri Hemadri, J C Karure, Raja Raju, Rajan, Vijay Kumar,
and C V Jawahar. "Indian Movie Face Database: A Benchmark for Face Recognition
Under Wide Variations"

National Conference on Computer Vision, Pattern Recognition, Image Processing
and Graphics (NCVPRIPG), 2013.
## 📊 Model Performance
- Input image size: `32x32`
- Final prediction output saved to `submission.csv`
- Visual inspection of sample predictions is included
## 🧪 Requirements
- Python 3.x
- TensorFlow / Keras
- NumPy
- Pandas
- PIL (Pillow)
- Matplotlib
- ImageIO
## Sample Prediction Output 
Original: Middle  Predicted: Middle
