# Monarch Rental Properties — Site Structure

## Folder Structure
```
/
├── index.html              ← Main website
├── admin/
│   ├── index.html          ← CMS dashboard (login at /admin)
│   └── config.yml          ← CMS field definitions
├── _data/
│   └── properties/
│       ├── 123-lookout-lane.yml
│       ├── 88-river-bend-drive.yml
│       └── ...             ← One .yml file per property
├── images/
│   └── properties/         ← Property photos upload here via CMS
└── netlify.toml            ← Netlify build settings
```

## Managing Properties

1. Go to `rentals.monarch-united.com/admin`
2. Log in with your Google Workspace account (dean@monarch-united.com)
3. Click **Properties** in the sidebar
4. **Add** a new listing, **edit** an existing one, or **delete** one
5. Hit **Publish** — the site updates automatically within ~30 seconds

## Property Status Options
- `vacant` → Green pin + "Available Now" badge
- `occupied` → Amber pin + "Occupied" badge  
- `offmarket` → Gray pin + "Off Market" badge

## Adding Photos
Upload directly in the CMS property editor — drag and drop your photo into the Property Photo field.
