# SignBuddy review playground

A standalone static review site for checking British Sign Language entries before changes are merged into the main SignBuddy app.

## UCL BSL SignBank lookup

The preview opens the official UCL BSL SignBank dictionary for manual English-word searches. It does not scrape SignBank, proxy its content, embed its video files, or redistribute its data.

UCL explicitly permits external links to individual sign pages, but prohibits scraping and external direct links to video files without written permission. Its dictionary data and videos are for non-commercial public use and are not available for bulk redistribution or licensing. Read the official terms: https://bslsignbank.ucl.ac.uk/about/dictionary/

For this reason, this playground links users to the SignBank search page rather than pretending it has an open API. If SignBuddy needs integrated video results, we should contact UCL DCAL (bslsignbank@ucl.ac.uk) to discuss permission or collaboration.

## BSL review checklist

The six starter entries (hello, thank you, please, help, family, school) remain placeholders. Use the SignBank lookup to inspect the actual BSL signs and variants. Review selections are stored in this browser only.

## Hosting

Static HTML, CSS and JavaScript, hosted independently by GitHub Pages. No Vercel project or server-side API is used.