# Brand Assets Repository

Official brand assets repository with raw file links for use in other applications.

## 🌐 Brand Website

Visit our brand assets website: [View Brand Assets](https://ranyaconnectallfixr.github.io/Brand/)

The website showcases all available brand assets with direct download links and usage examples.

## 📁 Repository Structure

```
Brand/
├── index.html           # Brand assets website
├── assets/
│   ├── logos/          # Brand logos in various styles
│   │   ├── logo.svg           # Primary logo (blue background)
│   │   ├── logo-dark.svg      # Dark variant
│   │   └── logo-light.svg     # Light variant
│   ├── icons/          # Brand icons
│   │   └── icon.svg           # Circular brand icon
│   └── images/         # Additional brand images
└── README.md
```

## 🔗 Using Raw File Links

All assets can be accessed directly via raw GitHub URLs for use in your applications:

### Available Assets

#### Logos

- **Primary Logo**: `https://raw.githubusercontent.com/ranyaconnectallfixr/Brand/main/assets/logos/logo.svg`
- **Dark Logo**: `https://raw.githubusercontent.com/ranyaconnectallfixr/Brand/main/assets/logos/logo-dark.svg`
- **Light Logo**: `https://raw.githubusercontent.com/ranyaconnectallfixr/Brand/main/assets/logos/logo-light.svg`

#### Icons

- **Brand Icon**: `https://raw.githubusercontent.com/ranyaconnectallfixr/Brand/main/assets/icons/icon.svg`

## 💻 Usage Examples

### HTML

```html
<img src="https://raw.githubusercontent.com/ranyaconnectallfixr/Brand/main/assets/logos/logo.svg" alt="Brand Logo">
```

### Markdown

```markdown
![Brand Logo](https://raw.githubusercontent.com/ranyaconnectallfixr/Brand/main/assets/logos/logo.svg)
```

### CSS

```css
.logo {
  background-image: url('https://raw.githubusercontent.com/ranyaconnectallfixr/Brand/main/assets/logos/logo.svg');
  background-size: contain;
  background-repeat: no-repeat;
}
```

### React/JSX

```jsx
<img 
  src="https://raw.githubusercontent.com/ranyaconnectallfixr/Brand/main/assets/logos/logo.svg" 
  alt="Brand Logo"
/>
```

## 📝 Brand Guidelines

- Use the primary logo on light backgrounds
- Use the dark logo on dark backgrounds
- Use the light logo when the primary logo doesn't provide enough contrast
- Maintain aspect ratio when resizing logos
- Do not modify or alter the brand assets

## 🚀 Local Development

To view the brand website locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/ranyaconnectallfixr/Brand.git
   cd Brand
   ```

2. Open `index.html` in your browser:
   ```bash
   # On macOS
   open index.html
   
   # On Linux
   xdg-open index.html
   
   # On Windows
   start index.html
   ```

   Or use a local web server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   ```

## 📄 License

All brand assets are proprietary and owned by the brand owner. Unauthorized use is prohibited.

## 🤝 Contributing

To add new brand assets:

1. Add your asset files to the appropriate directory (`assets/logos/`, `assets/icons/`, or `assets/images/`)
2. Update `index.html` to include the new asset
3. Update this README with the new asset information
4. Submit a pull request

## 📞 Contact

For questions or additional brand asset requests, please open an issue in this repository.
