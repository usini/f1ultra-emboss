# F1 Ultra Embossing Settings

A web-based configuration manager for F1 Ultra laser embossing equipment. This application allows users to save, organize, and manage their embossing settings with an intuitive interface that supports both French and English languages.

## 🚀 Features

### Core Functionality
- **Save & Manage Settings**: Create, edit, and delete embossing configurations
- **Parameter Control**: Manage all key embossing parameters:
  - Speed (mm/s)
  - Power (%)
  - Frequency (kHz)
  - Number of passes
  - Engraving angle
  - Lines per centimeter
- **Photo Documentation**: Upload and store result photos with your settings
- **Notes & Results**: Add detailed notes about results and observations
- **Visual Previews**: View saved settings with photo previews in an organized grid

### Data Management
- **Import/Export**: Backup and restore your settings as JSON files
- **Local Storage**: All data is stored locally in your browser
- **Settings Validation**: Input validation ensures proper parameter ranges

### User Experience
- **Bilingual Interface**: Switch between French and English
- **Responsive Design**: Works on desktop and mobile devices
- **Dark Theme**: Modern dark interface optimized for extended use
- **Interactive Controls**: Slider and numeric inputs for precise parameter control

## 🛠 Technology Stack

- **Frontend**: Pure HTML5, CSS3, JavaScript (ES6+)
- **Styling**: TailwindCSS via CDN
- **Fonts**: Inter from Google Fonts
- **Storage**: Browser LocalStorage API
- **Image Processing**: Canvas API for photo resizing and optimization

## 📋 Requirements

- Modern web browser with JavaScript enabled
- Support for HTML5 LocalStorage
- No server or installation required

## 🎯 Getting Started

### Quick Start
1. **Clone or Download**: Get the repository files
2. **Open**: Simply open `index.html` in your web browser
3. **Start Using**: Begin adding your embossing settings immediately

### Alternative Access Methods
- **Local File**: Double-click `index.html` to open directly
- **Web Server**: Serve the file through any HTTP server (Apache, Nginx, Python's SimpleHTTPServer, etc.)
- **Live Server**: Use VS Code's Live Server extension for development

## 📖 Usage Guide

### Adding a New Setting
1. Fill in the setting name and parameters in the left panel
2. Adjust sliders or type values directly in the number inputs
3. Optionally upload a photo of your embossing result
4. Add notes about the results or observations
5. Click "Save Setting" to store the configuration

### Managing Existing Settings
- **Edit**: Click the "Edit" button on any saved setting
- **Delete**: Click the "Delete" button and confirm the action
- **View Details**: Click on any photo to see detailed parameters and notes

### Data Management
- **Export**: Click "Export" to download all settings as a JSON backup file
- **Import**: Click "Import" to restore settings from a previously exported file
- **Language**: Use the language switcher (EN/FR) in the top-right corner

### Parameter Ranges
- **Speed**: 0-10,000 mm/s
- **Power**: 0-100%
- **Frequency**: 30-60 kHz
- **Passes**: 1-10
- **Angle**: 0-360°
- **Lines/cm**: 10-300 (predefined values)

## 🔧 Development

### Project Structure
```
f1ultra-emboss/
├── index.html          # Main application file
└── README.md          # Documentation
```

### Key Components
- **Form Section**: Left panel for adding/editing settings
- **Settings Grid**: Right panel displaying saved configurations
- **Modal System**: For confirmations and detailed photo views
- **Language System**: Translation management for bilingual support

### Local Development
```bash
# Simple HTTP server (Python 3)
python -m http.server 8000

# Simple HTTP server (Python 2)
python -m SimpleHTTPServer 8000

# Node.js HTTP server
npx http-server

# Then open http://localhost:8000
```

## 🎨 Customization

The application uses TailwindCSS for styling, making it easy to customize:

- **Colors**: Modify the color classes in the HTML
- **Layout**: Adjust the grid and flexbox classes
- **Themes**: The dark theme can be modified by changing background and text colors
- **Responsive**: Uses responsive classes for mobile adaptation

## 🌐 Browser Compatibility

- **Chrome**: Full support
- **Firefox**: Full support
- **Safari**: Full support
- **Edge**: Full support
- **Internet Explorer**: Not supported (requires modern JavaScript features)

## 📱 Mobile Support

The application is fully responsive and works on:
- Smartphones (iOS/Android)
- Tablets
- Desktop computers
- Touch and mouse interfaces

## 🔒 Data Privacy

- **Local Storage Only**: All data is stored locally in your browser
- **No Server Communication**: The application works entirely offline
- **No Data Collection**: No analytics or tracking implemented
- **Photo Storage**: Images are stored as base64-encoded data in LocalStorage

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

### Areas for Contribution
- Additional language translations
- UI/UX improvements
- New features (settings templates, advanced export formats)
- Bug fixes and optimizations
- Documentation improvements

## 📄 License

This project is open source. Please check the repository for specific license terms.

## 🐛 Known Issues

- Large numbers of photos may impact browser performance due to LocalStorage limitations
- Image files are automatically compressed to manage storage space
- Import/export functionality requires manual file handling

## 💡 Tips

- **Backup Regularly**: Use the export feature to backup your settings
- **Organize Photos**: Use descriptive names for your settings to easily identify them
- **Browser Storage**: Clear browser data will remove all saved settings
- **Mobile Use**: Landscape orientation recommended for mobile devices

## 📞 Support

For issues, questions, or feature requests, please use the GitHub issues section of this repository.

---

*F1 Ultra Embossing Settings - Streamline your laser embossing workflow*