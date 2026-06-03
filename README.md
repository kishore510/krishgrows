# KrishGrows

Personal site — allotment growing, travel and projects from North Yorkshire.

## Structure
```
krishgrows/
├── shared/brand.css          ← single source of truth for all styles
├── mockpage.html             ← full site mock preview
├── hub/index.html            ← krishgrows.com
├── travel/
│   ├── index.html            ← travel.krishgrows.com
│   ├── content/trips.json    ← edit this to add trips
│   └── trips/                ← individual trip pages
├── allotment/index.html      ← allotment.krishgrows.com
└── projects/
    ├── rover/index.html      ← public project
    └── stonks/index.html     ← private
```

## Adding a trip
Edit `travel/content/trips.json` only — no HTML changes needed.

## Deployment
Cloudflare Pages — each folder maps to its subdomain.
