# PromptWork

A minimal, parsimonious web project following first principles design.

## Project Architecture

This project follows a minimal setup approach with the following structure:

```
PromptWork/
├── index.html          # Main entry point (root directory)
├── README.md           # Project documentation
└── assets/             # Optional: Images, icons, and mockups (when needed)
```

### Design Philosophy

- **First Principles Approach**: Start with the most parsimonious model
- **Minimal Complexity**: Only add features and structure when necessary
- **Scalability Ready**: Easy to expand into a multi-page site when needed

## Installation Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/DopestT/PromptWork.git
   cd PromptWork
   ```

2. **Open locally**:
   - Simply open `index.html` in your web browser
   - No build process or dependencies required

3. **Optional: Use a local server** (for testing):
   ```bash
   # Using Python 3
   python3 -m http.server 8000
   
   # Using Python 2
   python -m SimpleHTTPServer 8000
   
   # Using Node.js (if you have npx)
   npx http-server
   ```
   
   Then open `http://localhost:8000` in your browser.

## Usage Examples

### Basic Usage

1. Open `index.html` directly in your browser for immediate access
2. The page is self-contained with inline CSS for styling
3. No external dependencies required

### Development

- Edit `index.html` to modify content, styling, or behavior
- Add files to `assets/` folder if you need local images or resources
- Keep the structure minimal until additional complexity is warranted

### Adding Assets

If you need to include local images, icons, or mockups:

1. Create an `assets/` folder in the root directory:
   ```bash
   mkdir assets
   ```

2. Organize assets by type (optional):
   ```
   assets/
   ├── images/
   ├── icons/
   └── mockups/
   ```

3. Reference assets in your HTML:
   ```html
   <img src="assets/images/logo.png" alt="Logo">
   ```

## Future Expansion

This minimal setup can easily scale to accommodate:
- Multiple pages (add more `.html` files)
- CSS files (move inline styles to external stylesheets)
- JavaScript files (add interactivity as needed)
- Build processes (when complexity justifies it)

## Contributing

When contributing, maintain the minimal design philosophy:
- Only add what's necessary
- Keep files organized and well-documented
- Test changes locally before committing

## License

This project follows an open-source approach. Please add specific license information as needed.