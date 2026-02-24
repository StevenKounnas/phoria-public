# Marketplace Pages

Public marketplace pages for Roomio and Captur3d.

## Contents

- `index.html` - Landing page with links to both marketplaces
- `roomio-marketplace.html` - Roomio marketplace page
- `captur3d-marketplace.html` - Captur3d marketplace page
- `images/` - Image assets (to be added by Arty)

## Deployment

### Deploy to Netlify

1. Push this repository to GitHub
2. Connect to Netlify
3. Deploy with default settings (publish directory: `.`)

### Manual Deploy

You can also drag and drop this folder directly into Netlify's deploy interface.

## Updating Content

### Updating Copy

Both marketplace pages contain marketing copy and feature descriptions. To update:

1. Edit the HTML files directly
2. Commit and push changes
3. Netlify will automatically redeploy

### Adding Images

The Roomio marketplace page is awaiting images from Arty. Once ready:

1. Add image files to `images/roomio/`
2. Update image paths in `roomio-marketplace.html`
3. Commit and push changes

## Structure

```
marketplace-pages/
├── index.html                     # Landing page
├── roomio-marketplace.html        # Roomio marketplace
├── captur3d-marketplace.html      # Captur3d marketplace
├── images/
│   ├── roomio/                    # Roomio images (awaiting Arty)
│   └── captur3d/                  # Captur3d images
├── netlify.toml                   # Netlify configuration
└── README.md                      # This file
```

## Access

These pages are **publicly accessible** without password protection. They are designed to be shared with potential customers and partners.
