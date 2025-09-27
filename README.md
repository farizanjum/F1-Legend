# 🏎️ F1 Legends - Formula 1 Racing Website

A modern, interactive Formula 1 racing website built with HTML, CSS, and JavaScript featuring real-time data integration and stunning visual design.

## Features

### Live Racing Dashboard
- **Real-time F1 data** integration with OpenF1 API
- **2025 Season Preview** with complete race calendar
- **Live driver standings** and championship information
- **Interactive race progress** tracking
- **Pre-season information** and countdown to next race

### Driver & Team Information
- **Complete 2025 driver lineup** with all 20 drivers
- **Accurate team assignments** including major moves (Hamilton to Ferrari, Sainz to Williams)
- **Driver statistics** and career information
- **Interactive driver cards** with detailed profiles

### Circuit Explorer
- **Interactive world map** with all F1 circuits
- **Circuit-specific information** including lap records and history
- **Detailed circuit layouts** and specifications
- **Filterable circuit categories** by region and type

### Data & Analytics
- **Historical race data** from previous seasons
- **Real-time telemetry display** with mouse interaction
- **Comprehensive statistics** and race analysis
- **Performance metrics** and driver comparisons

## Technologies Used

- **HTML5** - Semantic markup and modern web standards
- **CSS3** - Advanced styling with Tailwind CSS framework
- **JavaScript (ES6+)** - Modern JavaScript with async/await
- **OpenF1 API** - Real-time Formula 1 data integration
- **Responsive Design** - Mobile-first approach
- **Web Animations** - Smooth transitions and effects

## Project Structure

```
F1-Legend/
├── index.html              # Main homepage
├── circuits.html          # Circuit explorer page
├── champions.html         # Driver champions page
├── main.js               # Core JavaScript functionality
├── requirements.txt      # Project dependencies
├── README.md            # Project documentation
└── resources/           # Images and media assets
    ├── hero-f1-car.jpg
    ├── circuit-aerial.jpg
    ├── f1-racing-battle.jpg
    ├── champion-hamilton.jpg
    ├── champion-leclerc.jpg
    ├── champion-schumacher.jpg
    ├── champion-verstappen.jpg
    ├── hamilton-action.jpg
    ├── verstappen-action.jpg
    ├── silverstone-circuit.jpeg
    └── Spa-Francorchamps-circuit.jpg
```

## Quick Start

### Option 1: Local Development Server
```bash
# Navigate to project directory
cd F1-Legend

# Start a local web server (Python 3)
python -m http.server 8080

# Open browser and visit
http://localhost:8080
```

### Option 2: Live Server (VS Code)
1. Install Live Server extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

### Option 3: Direct File Access
Simply open `index.html` in your web browser (some features may be limited due to CORS restrictions).

## Key Features in Detail

### Live Racing Section
- **2025 Season Preview**: Complete race calendar with all 24 circuits
- **Real Driver Lineup**: All 20 drivers with correct team assignments
- **Interactive Elements**: Mouse-controlled telemetry display
- **Season Progress**: Visual progress tracking and countdown timers

### Circuit Explorer
- **Interactive World Map**: Clickable markers for each F1 circuit
- **Detailed Information**: Lap records, circuit history, and specifications
- **Filter Options**: Sort circuits by region, type, or characteristics
- **High-Resolution Images**: Professional circuit photography

### Driver Profiles
- **Complete Roster**: All 10 teams and 20 drivers for 2025
- **Team Changes**: Hamilton to Ferrari, Sainz to Williams, and more
- **Career Statistics**: Wins, podiums, and championship history
- **Visual Design**: Professional cards with team colors

## 2025 Season Highlights

### New Circuits & Features
- **Madrid Street Circuit** - New addition to the calendar
- **9 Sprint Race Weekends** - More action-packed weekends
- **Updated Regulations** - Latest F1 technical regulations
- **Enhanced Safety** - Improved safety measures and standards

### Driver Market Moves
- **Lewis Hamilton** → Ferrari (from Mercedes)
- **Carlos Sainz** → Williams (from Ferrari)
- **Sergio Perez** → Red Bull Racing (confirmed)
- **Rookie Drivers** - New talent entering the sport

### Technical Innovations
- **Advanced Aerodynamics** - New car designs and concepts
- **Sustainable Racing** - Environmental initiatives
- **Digital Integration** - Enhanced fan engagement features
- **Broadcast Technology** - Improved viewing experience

## Development

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (for full functionality)
- Text editor or IDE (VS Code recommended)

### Customization
The website uses CSS custom properties and modular JavaScript, making it easy to customize:

```css
:root {
  --primary-color: #ff1f3b;
  --secondary-color: #00d1ff;
  --background-color: #0f0f0f;
}
```

### Adding New Features
1. Add new HTML sections to the main pages
2. Update JavaScript modules in `main.js`
3. Add corresponding styles in the CSS sections
4. Test functionality across different browsers

## Responsive Design

The website is fully responsive and works on:
- **Desktop** (1920x1080 and above)
- **Laptop** (1366x768, 1440x900)
- **Tablet** (768x1024, 1024x768)
- **Mobile** (375x667, 414x896)

## Design Philosophy

### Visual Design
- **Dark Theme**: Modern dark aesthetic with red accents
- **Typography**: Clean, readable fonts with proper hierarchy
- **Color Scheme**: Red (#ff1f3b) and cyan (#00d1ff) primary colors
- **Animations**: Smooth transitions and micro-interactions

### User Experience
- **Intuitive Navigation**: Clear, logical information architecture
- **Fast Loading**: Optimized assets and efficient code
- **Accessibility**: ARIA labels and keyboard navigation
- **Performance**: Optimized for fast load times

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### Development Guidelines
1. Follow the existing code style and structure
2. Test changes across different browsers
3. Update documentation as needed
4. Ensure responsive design works properly

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- **OpenF1 API** - For providing real-time racing data
- **Tailwind CSS** - For the utility-first CSS framework
- **GitHub** - For hosting and collaboration tools

##  Contact

For questions, suggestions, or collaboration opportunities, please reach out through GitHub Issues or Discussions.

---

**Built with ❤️ for Formula 1 fans everywhere** 🏎️✨

*Last updated: 2025 | F1 Legends v2.0*

