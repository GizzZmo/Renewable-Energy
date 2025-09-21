# Global Renewable Energy Trends Dashboard 🌱⚡

An interactive web dashboard for exploring global renewable energy trends from 2023-2025, featuring AI-powered analysis and comprehensive data visualizations.

## 🌟 Features

- **Interactive Global Dashboard**: Explore renewable energy capacity, growth rates, and investment data across multiple years
- **Energy Type Deep Dive**: Detailed analysis of Solar, Wind, and Hydro power with country-by-country breakdowns
- **Regional Analysis**: Compare renewable energy mixes across continents (Asia, Europe, North America, South America, Africa)
- **AI-Powered Insights**: Generate future trend projections, investment analysis, and regional comparisons using Gemini AI
- **Responsive Design**: Fully responsive interface that works on desktop, tablet, and mobile devices
- **Real-time Charts**: Dynamic visualizations using Chart.js with smooth transitions and hover effects

## 🚀 Quick Start

### Option 1: GitHub Pages (Recommended)
The dashboard is deployed and ready to use at:
```
https://[your-username].github.io/Renewable-Energy/
```

### Option 2: Local Development
1. **Clone the repository**:
   ```bash
   git clone https://github.com/GizzZmo/Renewable-Energy.git
   cd Renewable-Energy
   ```

2. **Open the dashboard**:
   - Simply open `index.html` in your web browser
   - Or use a local server for better performance:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

3. **Access the dashboard**:
   - Open your browser and navigate to `http://localhost:8000`

## 📊 How to Use

### Global Overview
1. **Select Year**: Use the year dropdown (2023-2025) to see how metrics have evolved
2. **View Key Metrics**: Observe total capacity, annual growth, and investment figures
3. **Explore Charts**: Interactive donut chart shows energy mix, line chart displays growth trends
4. **AI Projections**: Click "Project Future Trends" for AI-generated forecasts

### Energy Type Analysis
1. **Select Energy Type**: Click tabs for Solar, Wind, or Hydro
2. **Country Rankings**: View top 5 countries by capacity for each energy type
3. **Technology Insights**: Read expert analysis on market trends and innovations
4. **Investment Analysis**: Generate AI-powered investment potential reports

### Regional Analysis
1. **Choose Region**: Select from Asia, Europe, North America, South America, or Africa
2. **Compare Energy Mix**: See how different regions prioritize renewable sources
3. **Regional Insights**: Read context about local policies and market drivers
4. **AI Summaries**: Generate detailed regional analysis reports

### Advanced Features
- **Regional Comparison**: Compare two regions side-by-side with AI analysis
- **Policy Recommendations**: Get AI-generated policy suggestions based on report conclusions
- **Smooth Navigation**: Use the sticky navigation bar to jump between sections

## 🛠️ Technical Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Tailwind CSS
- **Charts**: Chart.js
- **AI Integration**: Google Gemini API
- **Typography**: Inter font family
- **Icons**: Emoji-based icons for accessibility

## 🔧 Configuration

### AI Features Setup (Optional)
To enable AI-powered features, you'll need a Google Gemini API key:

1. Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Generate an API key
3. In `index.html`, find the line: `const apiKey = "";`
4. Replace with your API key: `const apiKey = "your-api-key-here";`

**Note**: AI features will show placeholder messages if no API key is provided.

## 📱 Browser Support

- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 Data Sources

The dashboard presents synthesized data representing global renewable energy trends:
- Capacity data in Gigawatts (GW)
- Growth percentages year-over-year
- Investment figures in billions USD
- Regional breakdowns by continent
- Country-specific rankings

## 🎨 Design Philosophy

- **Progressive Disclosure**: Information flows from high-level overview to detailed analysis
- **Interactive Exploration**: Users control their discovery journey through filters and selections
- **Visual Hierarchy**: Color-coded sections and consistent typography guide attention
- **Mobile-First**: Responsive design ensures accessibility across all devices

## 🤝 Contributing

Contributions are welcome! Here are some ways you can help:

1. **Report Issues**: Found a bug or have a suggestion? Open an issue
2. **Submit PRs**: 
   - Fork the repository
   - Create a feature branch: `git checkout -b feature/amazing-feature`
   - Commit changes: `git commit -m 'Add amazing feature'`
   - Push to branch: `git push origin feature/amazing-feature`
   - Open a Pull Request

3. **Improve Documentation**: Help make the README clearer or add more examples
4. **Data Updates**: Suggest data source improvements or additional metrics

## 📊 Performance

- **Lightweight**: ~45KB HTML file with external CDN dependencies
- **Fast Loading**: Optimized Chart.js rendering with lazy loading
- **Responsive**: Smooth animations and transitions under 60fps
- **Accessible**: WCAG AA compliant color contrasts and semantic HTML

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Chart.js**: For excellent charting capabilities
- **Tailwind CSS**: For utility-first styling approach
- **Google Fonts**: For the Inter typography
- **Google Gemini AI**: For intelligent content generation

## 📞 Support

If you encounter any issues or have questions:
1. Check existing [Issues](https://github.com/GizzZmo/Renewable-Energy/issues)
2. Create a new issue with detailed description
3. Contact the maintainer: [Your Contact Info]

---

**Made with 💚 for a sustainable future**
