# PermaDist Permanent File Distributor

A clean, browser-based file management tool that simulates permanent file distribution with a modern, intuitive interface.

![PermaDist Preview](https://via.placeholder.com/800x400/1a5c7a/ffffff?text=PermaDist+File+Distributor)

## Features

- **Drag & Drop Upload** - Easily add files by dragging them into the upload zone or clicking to browse
- **File Selection Management** - Preview selected files with size information and remove individual files
- **Permanent Distribution** - Simulate making files permanently available with a single click
- **Persistent File List** - Distributed files remain in the list until manually cleared
- **File Metadata** - View file names, sizes, and distribution timestamps
- **Responsive Design** - Works seamlessly on desktop and mobile devices
- **Modern UI** - Clean, glass-morphism design with smooth animations

## Quick Start

### Option 1: Direct Usage
Simply open the `index.html` file in your web browser. No server required!

### Option 2: Local Development
```bash
# Clone the repository
git clone https://github.com/yourusername/perma-dist.git

# Navigate to the project directory
cd perma-dist

# Open in your browser
open index.html
```

## How It Works

1. **Upload Files**
   - Drag files into the drop zone or click to select files
   - Selected files appear in the preview list with their sizes

2. **Distribute Permanently**
   - Click "Distribute permanently" to move files to the distributed section
   - Files are stored in memory with a timestamp and unique ID

3. **Manage Files**
   - Remove individual files from the upload selection
   - Clear all distributed files with one click
   - Files persist in the distributed section until manually cleared

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with glass-morphism effects
- **Vanilla JavaScript** - No external libraries or frameworks
- **Font Awesome** - Icons for better visual communication

## Project Structure

```
perma-dist/
├── index.html          # Main application file
└── README.md           # Project documentation
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## Customization

### Styling
The application uses CSS custom properties (variables) that can be modified in the `<style>` section:

```css
:root {
  /* Add your custom variables here */
}
```

### File Storage
By default, files are stored in memory. To persist files across sessions, you can:
- Integrate with localStorage
- Connect to a backend API
- Use IndexedDB for client-side persistence

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Font Awesome](https://fontawesome.com/) for the icons
- [Google Fonts](https://fonts.google.com/) for the system font stack

## 📞 Contact

Your Name - [@yourtwitter](https://twitter.com/yourtwitter) - email@example.com

Project Link: [https://github.com/yourusername/perma-dist](https://github.com/yourusername/perma-dist)

---

**Built with ❤️ for permanent file distribution**
