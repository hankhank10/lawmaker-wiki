# Lawmaker Game Manual

Official user manual for Lawmaker, a multiplayer political simulation game.

## About

This documentation provides comprehensive guides for players of Lawmaker, covering:

- Game concepts and mechanics
- Party management and strategy
- Legislative system and voting
- Elections and voter simulation
- Government formation and coalitions
- Character management
- Political issues and laws catalog
- Strategy guides and tips

## Building the Documentation

This manual is built with [MkDocs](https://www.mkdocs.org/) using the [Material theme](https://squidfunk.github.io/mkdocs-material/).

### Prerequisites

- Python 3.7 or higher
- pip

### Installation

```bash
# Install dependencies
pip install -r requirements.txt
```

### Development

```bash
# Serve locally with live reload
mkdocs serve

# Then open http://127.0.0.1:8000 in your browser
```

### Building for Production

```bash
# Build static site
mkdocs build

# Output will be in the 'site/' directory
```

## Deployment

This documentation is designed to be deployed as a static site. Compatible with:

- **Cloudflare Pages** (recommended)
- **GitHub Pages**
- **Netlify**
- **Vercel**
- Any static hosting service

### Cloudflare Pages Deployment

1. Connect your repository to Cloudflare Pages
2. Set build command: `mkdocs build`
3. Set build output directory: `site`
4. Deploy!

## Structure

```
game-manual/
├── mkdocs.yml              # Configuration
├── requirements.txt         # Python dependencies
├── README.md               # This file
├── docs/                   # Documentation source
│   ├── index.md           # Home page
│   ├── getting-started.md # Getting started guide
│   ├── game-concept.md    # Core concepts
│   ├── gameplay/          # Gameplay guides
│   │   ├── parties.md
│   │   ├── legislation.md
│   │   ├── elections.md
│   │   ├── characters.md
│   │   ├── cabinet.md
│   │   ├── resources.md
│   │   └── communication.md
│   ├── countries.md       # Countries guide
│   ├── laws-and-policies.md # Laws catalog
│   ├── strategy-guide.md  # Strategy tips
│   ├── faq.md             # FAQ
│   └── roadmap.md         # Development roadmap
└── site/                  # Built site (generated)
```

## Contributing

To contribute to the documentation:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally with `mkdocs serve`
5. Submit a pull request

## License

Check the main Lawmaker repository for license information.

## Links

- **Game Repository:** https://github.com/hankhank10/lawmaker
- **Game Website:** https://lawmakergame.com
- **Manual Site:** https://manual.lawmakergame.com (or your deployment URL)

## Support

For issues with the documentation:

- Open an issue in the main repository
- Contact via official game channels
- Submit pull requests for corrections

---

**Built with MkDocs and Material for MkDocs**
