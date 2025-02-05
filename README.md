# Crop, Fertilizer and Plant Disease Detection 

A machine learning and deep learning-based web application for precision farming. It provides:
- **Crop Recommendation**: Suggests the best crop to grow based on soil and weather conditions.
- **Fertilizer Recommendation**: Recommends suitable fertilizers by analyzing soil nutrients.
- **Plant Disease Detection**: Identifies plant diseases from leaf images and provides treatment suggestions.

## Disclaimer 
This project is a proof of concept and should not be used for real farming decisions. The data used is not guaranteed to be accurate.

## Data Sources 
- [Crop Recommendation Dataset](https://www.kaggle.com/atharvaingle/crop-recommendation-dataset)
- [Fertilizer Suggestion Dataset](https://github.com/Gladiator07/Harvestify/blob/master/Data-processed/fertilizer.csv)
- [Plant Disease Dataset](https://www.kaggle.com/vipoooool/new-plant-diseases-dataset)

## Built With 
- **Backend**: Python, Flask
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **ML/DL**: Scikit-learn, PyTorch, OpenCV, TensorFlow

## How to Use 
1. **Crop Recommendation**: Enter soil nutrient values, state, and city to get crop suggestions.
2. **Fertilizer Suggestion**: Input soil nutrients and crop type to receive fertilizer recommendations.
3. **Disease Detection**: Upload an image of a plant leaf to identify diseases and get treatment suggestions.

## Running Locally 
1. Clone the repository:
   ```sh
   git clone https://github.com/SasidharanNachimuthu/crop-fertilizer-recommendation-and-plant-disease-detection.git
   ```
2. Navigate to the project folder:
   ```sh
   cd crop-fertilizer-recommendation-and-plant-disease-detection
   ```
3. Create and activate a virtual environment:
   ```sh
   conda create -n venv python=3.10.4
   conda activate venv
   ```
4. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
5. Replace the OpenWeatherMap API Key in config.py:
   ```sh
   weather_api_key = "<API_KEY>"
   ```
5. Run the application:
   ```sh
   python app.py
   ```
6. Open the provided localhost URL in your browser.

## Future Improvements 📈
- Improve UI/UX for a better user experience.
- Optimize ML/DL models for better accuracy.
- Expand the dataset for enhanced predictions.

