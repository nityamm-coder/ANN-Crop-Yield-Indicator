# 🌾 ANN Crop Yield Predictor

**Professional Crop Yield Prediction System with AI, Dark Mode, and Multi-Language Support**

Made with ❤️ by **Nityam Mishra**

---

## ⚡ Quick Start

```bash
# 1. Install dependencies
pip install flask flask-cors

# 2. Run the backend
python app.py

# 3. Open the frontend
# Double-click index.html or open it in your browser
```

**That's it! You're ready to go!** 🎉

---

## ✨ Features

### **AI-Powered Predictions**
- **Artificial Neural Network (ANN)** trained on real crop data
- Hybrid AI + rule-based validation system
- Different crops give different results (Rice ≠ Wheat)
- Model confidence percentage shown
- Environmental condition analysis

### View Results
- **Estimated Yield**: Tons per hectare
- **Yield Efficiency**: Percentage-based performance
- **Model Confidence**: How confident the AI is
- **Environmental Analysis**: Optimal conditions check
- **Category Badge**: Color-coded (High/Medium/Low)

### 📱 **Responsive Design**
- Works on desktop computers
- Works on tablets
- Works on mobile phones
- Adaptive layout

---

## 📊 How It Works

1. **User Input**: Enter crop type, area, production, rainfall, and temperature
2. **AI Processing**: Neural network analyzes the data
3. **Hybrid Validation**: Combines AI prediction with rule-based checks
4. **Results**: Shows yield category (High/Medium/Low) with confidence

---

## 📚 Technical Details

### Backend (Flask)
- **Framework**: Flask with CORS enabled
- **ML Library**: scikit-learn (MLPClassifier)
- **Data Processing**: pandas, numpy
- **API Endpoints**:
  - `GET /api/crops` - Returns list of available crops
  - `POST /api/predict` - Accepts form data, returns prediction

### Frontend (Vanilla JavaScript)
- **No build process** - Pure HTML/CSS/JavaScript
- **LocalStorage** - Saves theme and language preferences
- **Fetch API** - Communicates with Flask backend
- **CSS Variables** - Dynamic theming
- **Animations** - Pure CSS keyframes

### Crops Supported
Rice, Wheat, Sugarcane, Cotton, Maize, Jowar, Bajra, Ragi, Groundnut, Soyabean, Sunflower, Potato, Onion, Tomato, Apple, Banana, Mango, Tea, Tobacco, Coffee, Carrot, Grapes, Orange

---

## 🚀 Deployment Options
- Deploy Flask to Heroku/PythonAnywhere/Railway
- Update API endpoint in `index.html`
- Host HTML on GitHub Pages/Netlify/Vercel

---

## 📝 License

This project is created for educational purposes.

**Made by Nityam Mishra**  
Powered by Neural Networks
Smart Agriculture for a Better Future

---

## 🎯 Next Steps

Want to enhance this project? Ideas:
- Add more crops
- Include soil quality parameters
- Add weather forecast integration
- Create mobile app version
- Add historical yield charts
- Include fertilizer recommendations

---

**Enjoy your awesome crop yield predictor!**
