# Tiny Things

A personal sandbox for prototypes, experiments, and tools.

## Structure

```
tiny-things/
├── index.html          # Landing page
├── style.css           # Styles
├── projects/           # Individual project folders
│   └── example/
│       └── index.html
└── README.md
```

## Adding a New Project

1. Create a new folder in `projects/`
2. Add your project files (HTML, CSS, JS, etc.)
3. Update `index.html` to add a card linking to your project

## Local Development

Open `index.html` in your browser or run a local server:
```bash
python3 -m http.server 8000
```

Then visit: http://localhost:8000

## Deployment

This site is ready to deploy to:
- **GitHub Pages**: Push to GitHub and enable Pages in repo settings
- **Vercel**: Connect your GitHub repo for automatic deployments
- **Netlify**: Drag and drop the folder or connect to GitHub
