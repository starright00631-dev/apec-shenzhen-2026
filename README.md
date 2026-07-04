# APEC 2026 Shenzhen

An insightful, interactive visitor website for foreign delegates attending the **33rd APEC Economic Leaders' Meeting** in Shenzhen, China (November 2026).

## About

This is a voluntary, open-source project built to help international attendees of APEC 2026 understand Shenzhen — China's innovation capital and the host city of the summit. The site covers practical travel information, city exploration guides, and APEC-specific delegate briefings.

The website is designed with a dignified, editorial aesthetic using jade green and gold accents on warm ivory, reflecting both the significance of an international summit and Chinese cultural aesthetics.

## Pages

| Page | Description |
|------|-------------|
| **Home** | APEC 2026 overview, Shenzhen's story, key facts, summit timeline |
| **Explore Shenzhen** | District guide (Futian, Nanshan, Luohu), food culture, nature & outdoors |
| **Plan Your Visit** | Transportation, visa, accommodation, money & payments, essential apps, weather |
| **APEC 2026 Guide** | APEC overview, member economies, program timeline, venue, protocol, nearby points of interest |

## Content

All content is based on verified public information from:
- Official APEC publications and member economy data
- Shenzhen municipal government sources (eyeshenzhen.com, sz.gov.cn)
- The "Make it Shenzhen" APEC China Year campaign (2025-2026)
- Published travel and infrastructure data

No fabricated data has been added. Photos are sourced from the official Shenzhen government "Make it Shenzhen" campaign and AI-generated hero/venue images.

## Technology

- Pure HTML, CSS, and vanilla JavaScript — no build tools or frameworks
- Tailwind CSS v4 (CDN) for utility styling
- Lucide Icons (CDN) for iconography
- Custom design tokens in `colors_and_type.css`
- `.design` canvas project format for TRAE SOLO rendering

## Structure

```
apec-shenzhen-2026/
├── apec-shenzhen-2026.design    # Canvas project entry
├── colors_and_type.css          # Brand design tokens
├── orchestration-summary.json   # Project metadata
├── generation-tree.json         # Page generation tree
├── assets/                      # Images (real + generated)
│   ├── hero-shenzhen-skyline.jpg
│   ├── explore-districts.jpg
│   ├── apec-venue.jpg
│   └── ... (9 more real government photos)
├── pages/                       # HTML pages
│   ├── home.html
│   ├── explore.html
│   ├── plan.html
│   └── apec-guide.html
└── partials/                    # Shared partials (reserved)
```

## License

MIT License. See [LICENSE](LICENSE) for details.
