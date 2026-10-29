# Costa del Mar — Less rush. More shore.

## Open the preview

Extract the ZIP. Open **Website/OPEN-WEBSITE.html** in a modern browser. The complete preview embeds all images, fonts, styling and scripts, so it works without installation or a server. Internet is needed only for external Facebook, email, Maps and weather links.

The **Highlights** folder contains the three requested screenshots, separately from the website source.

## Editable website

- `index.html`: page content, structure and contact links.
- `styles.css`: colours, layout, typography and mobile behaviour.
- `app.js`: journal, trip planner, packing lists, calculator and exports.
- `assets`: actual published resort photos, local fonts and wave icon.
- `licenses`: open font licences.
- `asset-sources.json`: exact original photo pages and downloaded image sources.
- `RESEARCH.md`: verified facts, uncertainty and launch decisions.
- `VALIDATION.md`: completed checks.

After editing source, run `python build-preview.py` from the Website folder to rebuild the self-contained HTML. The ordinary index.html works alongside its assets and can be served by any static host. No public deployment was made.

## Working features

- Quick arrival/departure and guest planning, with live trip summary.
- Day, overnight and group inquiry directions.
- Six-scene journal and fullscreen photo viewer.
- A reviewable resort inquiry with copy, email and text-download options.
- Trip-brief download and tentative calendar-file export.
- Reusable day, overnight and camping-question checklists.
- Group cost calculator using the visitor's quoted and estimated figures.
- Address copying, Maps search, official weather and resort update links.

Nothing is sent automatically. Dates are not reserved, payments are not processed and availability is not shown live. Calendar exports only create a downloadable tentative plan for the visitor to import. Checklist state is stored locally when available; the trip form does not store personal notes remotely. Current rates and commercial terms must be confirmed by the business.

The owner must approve branding, photo permissions, current contacts, facilities and written terms before launch. A dated older cover photograph is included alongside more recent images; no guarantee of present property conditions is implied.
