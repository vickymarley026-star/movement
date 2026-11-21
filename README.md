# Movement Publisher — local website recreation

This is a self-contained, responsive front-end recreation based on the publicly accessible Movement Publisher website at https://movement-publisher.base44.app/.

## Run locally
- Open `index.html` directly in a browser, or
- From this folder run `python -m http.server 8000` and visit http://localhost:8000.

## Included
- Responsive landing page with navigation and major published sections
- Team, services, portfolio, testimonials, video-review placeholders and author resources
- Interactive cover-size estimate and simple royalty estimate
- Newsletter form front-end interaction (demo only)

## Asset and fidelity notes
The original site's publicly indexed text and a small number of publicly accessible image URLs were used. The logo and one team portrait are loaded from the original public site. Some original cover images, team portraits, hero photography, video embeds, and exact styling values were not exposed by the available public page capture; those areas use faithful visual placeholders or an available public image. Therefore this is a substantial front-end recreation, not a byte-for-byte copy of the private Base44 project.

To achieve a pixel-identical reproduction, provide an export of the original Base44 project or its source/assets (and screenshots at desktop and mobile breakpoints). Private backend functions, authentication, data collections, and integrations are not recreated in this static front-end.
