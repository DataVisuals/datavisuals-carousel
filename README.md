# DataVisuals Applications Carousel

An interactive carousel showcasing DataVisuals applications with smooth animations, responsive design, and modern UI.

🔗 **Live Demo:** [https://datavisuals.github.io/datavisuals-carousel](https://datavisuals.github.io/datavisuals-carousel)

## Features

- **Interactive Carousel** - Browse through 6 DataVisuals applications
- **Auto-Advance** - Automatically cycles every 5 seconds
- **Manual Navigation** - Arrow buttons and dot indicators
- **Keyboard Support** - Use left/right arrow keys to navigate
- **Touch Gestures** - Swipe left/right on mobile devices
- **Responsive Design** - Works beautifully on all screen sizes
- **Smooth Animations** - Floating icons and smooth transitions

## Applications Featured

1. 📐 **Andraw** - Interactive diagramming and visualization tool
2. 🔗 **LineageViewer** - Data lineage visualization tool
3. 📈 **Stock Analysis Platform** - Market analysis and portfolio tracking
4. 📅 **Calendar App** - Event management and scheduling
5. 🌳 **ViewDependencies** - Dependency tree visualization
6. ✓ **Expectations** - Data validation framework

## Local Development

Simply open `index.html` in your web browser:

```bash
open index.html
```

Or use a local server:

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js
npx http-server
```

Then visit `http://localhost:8000`

## Technologies Used

- HTML5
- CSS3 (Flexbox, Animations, Gradients)
- Vanilla JavaScript (No dependencies!)
- Touch Events API
- Keyboard Events API

## Browser Support

| Browser | Support |
|---------|---------|
| Chrome  | ✅ Full |
| Firefox | ✅ Full |
| Safari  | ✅ Full |
| Edge    | ✅ Full |
| Mobile  | ✅ Full (with touch gestures) |

## Customization

### Adding New Applications

1. Add a new slide div in the carousel-slides section
2. Follow the existing card structure
3. Add a new indicator dot
4. Update slide count if needed

### Updating Information

- **Last Updated Dates**: Update the `last-updated` span in each card
- **Icons**: Replace emoji with Font Awesome or custom images
- **Colors**: Modify the gradient in the `.carousel-wrapper` class
- **Timing**: Change auto-advance interval in the JavaScript (default: 5000ms)

## Project Structure

```
datavisuals-carousel/
├── index.html          # Main carousel page
└── README.md          # This file
```

## License

This project is part of the DataVisuals organization resources.

## Links

- 🏠 [DataVisuals Organization](https://github.com/DataVisuals)
- ⭐ [All Repositories](https://github.com/DataVisuals?tab=repositories)

---

<div align="center">
  Built with ❤️ by the DataVisuals team
</div>
