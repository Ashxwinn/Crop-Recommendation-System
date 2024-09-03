# Crop-Recommendation-System.
### Crop Recommendation System

Description
A system that uses data analysis and machine learning to suggest the most suitable crops for a specific plot of land. It analyzes soil type, weather conditions, and historical crop yield data to help farmers optimize crop selection for better yield and sustainability.

Project Structure:  
1. crop_classification_with_recommendation.ipynb: Jupyter notebook for training the model.  
2. main.py: Script to load the trained model and provide recommendations.  
3. model.pkl:Trained crop recommendation model.  
4. minmaxscaler.pkl: Serialized MinMaxScaler for data normalization.  
5. standscaler.pkl:*Serialized StandardScaler for data standardization.  
6. requirements.txt: List of required Python libraries.

Setup Instructions:
1. Clone the repository: `git clone`  
2. Install libraries: `pip install -r requirements.txt`  
3. Train models in the Jupyter Notebook (`crop_classification_with_recommendation.ipynb`).  
4. Move generated files (`model.pkl`, `minmaxscaler.pkl`, `standscaler.pkl`) to the project directory.  
5. Run the main script: `python main.py`  

Files Description:  
- crop_classification_with_recommendation.ipynb: Contains data preprocessing, model training, and evaluation.  
- model.pkl, minmaxscaler.pkl, standscaler.pkl: Serialized model and scalers.  
- requirements.txt:** Required libraries.  
- main.py:** Script to load models and recommend crops.

Notes: 
- Ensure all `.pkl` files are in the same directory as `main.py`.  
- Update `requirements.txt` if new libraries are needed.

Technologies Used:
- **Python, Pandas, NumPy, Scikit-learn, Jupyter Notebook.**

