# Marino Supply Website

A static website for Marino Supply, featuring multiple product categories and built with Tailwind CSS.

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/fabiosimoesds/marino-supply-website.git
   ```

2. Install dependencies:
```bash
npm install

# The serve package will create a local development server (usually at http://localhost:3000) 
npm install -g serve
```

3. Build the CSS:
```bash
# For development (watches for changes)
npm run dev

# For production build
npm run build
```

## Development

1. Start the Tailwind CLI build process and run the server:
```bash
npm run dev
serve
```

2. Open the HTML files in your browser or use a local server

## Deployment to GitHub Pages

1. Build the production CSS:
```bash
npm run build
```

2. Commit all files including the `dist` folder:
```bash
git add .
git commit -m "Your commit message"
git push
```

3. Enable GitHub Pages in your repository settings:
- Go to Settings > Pages
- Select "Deploy from a branch"
- Choose "main" branch and "/ (root)"
- Click Save

Your site will be available at: `https://fabiosimoesds.github.io/marino-supply`

## Technologies Used
- HTML5
- Tailwind CSS
- SVG Patterns
- Responsive Design

## License
MIT License