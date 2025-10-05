# Green View - Fresh Produce Marketplace

A modern web application prototype for connecting local fresh produce vendors with buyers, featuring real-time location-based deals and interactive maps.

## Features

- 🗺️ Interactive map with vendor locations
- 📱 Responsive design for mobile and desktop
- 🛒 Browse fresh produce deals by category
- 📍 Location-based vendor discovery
- 📞 Direct contact with vendors
- 🏪 Vendor dashboard for inventory management

## Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Styling**: Tailwind CSS (CDN)
- **Maps**: Leaflet.js with routing
- **Icons**: Lucide Icons
- **Deployment**: Vercel

## Getting Started

### Local Development

1. Clone the repository:
```bash
git clone <your-repo-url>
cd petogram_prototype-1
```

2. Install Vercel CLI (optional for local dev):
```bash
npm install -g vercel
```

3. Run locally:
```bash
# Option 1: Open index.html directly in browser
# Option 2: Use Vercel dev server
vercel dev
```

### Deployment to Vercel

#### Option 1: Deploy via Vercel CLI

1. Install Vercel CLI:
```bash
npm install -g vercel
```

2. Login to Vercel:
```bash
vercel login
```

3. Deploy:
```bash
vercel
```

#### Option 2: Deploy via GitHub Integration

1. Push your code to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your GitHub repository
5. Vercel will automatically detect the configuration and deploy

#### Option 3: Deploy via Vercel Dashboard

1. Go to [vercel.com](https://vercel.com)
2. Click "New Project"
3. Drag and drop your project folder
4. Vercel will deploy automatically

## Project Structure

```
petogram_prototype-1/
├── index.html          # Main application file
├── vercel.json         # Vercel configuration
├── package.json        # Project metadata
└── README.md          # This file
```

## Configuration

The `vercel.json` file configures:
- Static file serving for the HTML file
- Routing to serve the app from the root URL
- SPA (Single Page Application) routing for client-side navigation

## Environment Variables

No environment variables are required for this static application.

## API Usage

The app uses the following external APIs:
- **BigDataCloud**: For reverse geocoding (converting coordinates to addresses)
- **Leaflet**: For map functionality
- **Tailwind CSS**: For styling (CDN)

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally
5. Submit a pull request

## License

MIT License - see LICENSE file for details.
