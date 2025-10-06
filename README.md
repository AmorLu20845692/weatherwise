# 🌦️ WeatherWise - Intelligent Weather Analysis & Advisory System

WeatherWise is a comprehensive Python application that combines real-time weather data retrieval, interactive visualizations, and natural language processing to provide users with intelligent weather analysis and recommendations.

![Build With AI](https://img.shields.io/badge/Built_with-AI-blueviolet?logo=openai)
![Python](https://img.shields.io/badge/Made_with-Python-3776AB?logo=python)
![Visualisation](https://img.shields.io/badge/Includes-Visualisations-orange?logo=plotly)

## ✨ Features

### 🌍 Weather Data Retrieval
- Real-time weather data for any global location
- 5-day forecast with hourly detail
- Robust error handling and retry logic
- Uses wttr.in API (no API key required)

### 📊 Interactive Visualizations
- **Temperature Trends**: Multi-line charts showing daily temperature ranges
- **Precipitation Forecast**: Dual-chart approach with daily totals and hourly timing
- Professional styling with contextual information

### 🤖 Natural Language Interface
- Ask weather questions in plain English
- Intelligent parsing of location, time, and weather attributes
- Conversational responses with helpful advice

### 🎯 User Experience
- Intuitive menu-driven interface
- Multi-location weather comparison
- Comprehensive error recovery
- Input validation and user guidance

## 🚀 Getting Started

### Prerequisites
```bash
pip install requests matplotlib pyinputplus
```

### Running the Application
1. Open `starter_notebook.ipynb` in Google Colab or Jupyter
2. Run all cells to load the application
3. Execute the main application cell to start WeatherWise
4. Follow the interactive menu prompts

### Usage Examples
- **Basic Weather**: "What's the weather like in London?"
- **Specific Queries**: "Will it rain tomorrow in Tokyo?"
- **Planning**: "How hot will it be in Sydney this week?"

## 📁 Project Structure

- `starter_notebook.ipynb` — Complete WeatherWise application
- `PROMPTING.md` — AI development process documentation
- `ai-conversations/` — AI interaction logs (5 conversations)
- `submission/reflection.md` — Project development reflection
- `ASSIGNMENT.md` — Original assignment specification

## 🛠️ Technical Implementation

### Core Components
- **Weather Data Module**: API integration with comprehensive error handling
- **Visualization Engine**: Matplotlib-based charts with professional styling
- **NLP Parser**: Pattern matching for natural language understanding
- **UI Framework**: pyinputplus-based menu system with validation

### Design Patterns
- Modular function design with single responsibilities
- Consistent error handling across all components
- User-centered interface design with progressive disclosure
- Robust input validation and sanitization

## 🎯 Assignment Requirements Met

✅ **Weather Data Component**: wttr.in API integration with error handling  
✅ **Visualizations**: Temperature trends and precipitation forecasts  
✅ **Natural Language Interface**: Question parsing and response generation  
✅ **User Interface**: Menu system with pyinputplus validation  
✅ **AI Documentation**: 5 conversation logs with prompting techniques  
✅ **Modular Design**: Clean function structure with proper documentation  
✅ **Error Handling**: Comprehensive error recovery throughout application  

## 🤖 AI Development Process

This project demonstrates intentional AI-assisted development through:
- **Option Analysis**: Systematic evaluation of implementation approaches
- **Iterative Improvement**: Progressive refinement of code quality
- **Edge Case Exploration**: Proactive identification of potential issues
- **Best Practice Integration**: Professional software engineering patterns

See `PROMPTING.md` for detailed documentation of AI interaction strategies.

## 🎨 Screenshots & Examples

The application provides:
- Clean, emoji-enhanced menu interfaces
- Professional weather data visualizations
- Natural language conversation capabilities
- Robust error handling with helpful suggestions

## 🚀 Future Enhancements

- Data caching for improved performance
- Multiple weather source integration
- Unit testing framework
- Mobile-responsive interface
- Historical weather analysis

---

**Author**: Amor Lu  
**Email**: Amor20845692@outlook.com  
**Course**: Programming Assignment - WeatherWise Implementation
