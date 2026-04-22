# TW Electrical Contractor — Website Files

## Folder Structure
```
tw-electrical/
├── index.html          # Homepage
├── about.html          # About page
├── services.html       # Services page
├── contact.html        # Contact page (static form)
├── style.css           # All site styling
└── images/             # Place all images here
    ├── logo.png
    ├── og-preview.jpg
    ├── van.jpg
    ├── project-kitchen.jpg
    ├── project-kitchen-2.jpg
    ├── project-downlights.jpg
    ├── project-house.jpg
    ├── project-consumer-unit.jpg
    ├── project-industrial.jpg
    ├── project-industrial-2.jpg
    ├── project-farm.jpg
    └── project-narrowboat.jpg
```

## Image Renaming Guide
Rename your uploaded files to these exact filenames and drop them into the `images/` folder:

| Your uploaded file                   | Rename to                    |
|--------------------------------------|------------------------------|
| TW_Full_Logo_-_With_NIC.png          | logo.png                     |
| Front.png                            | og-preview.jpg (save as JPG) |
| back_van_no_plate.png                | van.jpg                      |
| 20201121_162628.jpg                  | project-kitchen.jpg          |
| 20201121_162643.jpg                  | project-kitchen-2.jpg        |
| 20200216_151352.jpg                  | project-downlights.jpg       |
| nikki_house.jpg                      | project-house.jpg            |
| Mains_unit.jpg                       | project-consumer-unit.jpg    |
| The_farm_board.jpg                   | project-industrial.jpg       |
| The_farm_board_2.jpg                 | project-industrial-2.jpg     |
| farm_mains.jpg                       | project-farm.jpg             |
| 20211204_134405.jpg                  | project-narrowboat.jpg       |

## Upload Instructions
1. Keep the folder structure above.
2. Drag the entire `tw-electrical` folder (or its contents) into your static host.
3. Set `index.html` as the default document if asked.

## Recommended Hosts
- **Netlify** — easiest drag-and-drop, free SSL, built-in form handling.
- **Cloudflare Pages** — fast global CDN, generous free tier.
- **Vercel** — instant deploys, great performance.
- **GitHub Pages** — free, reliable, needs a GitHub account.
- **Hostinger / Namecheap** — UK-friendly classic hosting with FTP.

## Notes
- The email `info@twelectricalcontractor.co.uk` is a placeholder — swap for your real email in all HTML files.
- The contact form is visual-only. To make it send submissions on Netlify, add `netlify` as an attribute on the `<form>` tag.
- The footer year is hardcoded to 2026. Ask if you'd like it auto-updated via JS.
