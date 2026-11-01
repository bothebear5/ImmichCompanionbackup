made by Björn F. archived from deleted repo. Not maintained anymore. All the credits to original author

Right-click any image or video to save it directly to your self-hosted Immich server.



Immich Companion is a browser companion for your self-hosted Immich photo library. It lets you save images and videos from any webpage with one right-click, search your photos from anywhere in the browser, and turn every new tab into a feed of your own memories.

It is built for people who already run Immich at home or on their own server. There is no cloud component, no account to create, no telemetry. The extension talks to one place and one place only: the Immich server URL you enter on first run.

SIMPLE AND FAST
- Right-click any image or video and select "Save to Immich" or "Save & share"
- Files are uploaded instantly to your server
- In-page toasts confirm each upload — green on success, blue on duplicate, red with the actual error message on failure
- "Save & share" creates a public Immich share link and copies it to your clipboard in one click

A LIBRARY VIEW THAT FEELS LIKE A PHONE GALLERY
- The toolbar popup opens straight to the most recent items in your library — masonry layout, grouped by month with sticky date headers and a thin year scrubber on the right edge
- Click any year on the scrubber to jump straight to that point in your library
- Smart search runs from the same input — up to 250 CLIP results per query, grouped on the same timeline
- Three quick actions on every result, revealed on hover: copy the image straight to your clipboard, copy a public share link, or download the original — each with inline progress, success, and error feedback
- Choose whether the clipboard action copies the medium-size preview (default, fast and always works) or the full-resolution original
- Address-bar search — type "im" plus a space plus a query for live suggestions
- Inline matches on Google search pages — matching photos appear in a card above Google's results, without any data ever traveling through Google's servers
- "Recent uploads" tab tracks the items you saved through the extension, with one-click open and copy-link actions
- Drag and drop files onto the popup to upload them straight from your computer

A NEW TAB WORTH OPENING
- A random photo from your library on every new tab
- An optional row of photo details under the date: camera, lens, ISO, aperture, shutter, focal length, dimensions, file size — whatever EXIF data Immich has for that photo
- An optional "On this day" memory strip with photos from past years
- Pick a specific album as the background source
- Optional auto-rotate every 30 seconds to 15 minutes
- Or turn the new tab override off entirely — a minimal clock and Google search bar replaces it

ORGANIZED
- Optional default album for every save
- Automatic duplicate detection (using Immich's hash-based dedup, surfaced in the toast)
- Recent uploads kept locally in the popup for quick access

BEAUTIFUL
- Clean modern interface that matches Immich's design language
- Dark and light themes, plus a "match system" option
- Connection status indicator on the toolbar icon (red when the server is unreachable)
- Polished first-run onboarding that walks through creating an API key

PRIVATE AND SECURE
- All data goes directly to YOUR Immich server
- No analytics, no third-party tracking, no telemetry, no telemetry pixels
- API key stored locally in chrome.storage.local
- The full privacy policy spells out exactly what every permission is used for and what theoretical exposures exist (the Google integration in particular)
- Open source — verify the code yourself

REQUIREMENTS
- A self-hosted Immich server (https://immich.app)
- An API key from your Immich account (the welcome page lists the exact required scopes)
- Chrome or Chromium 114 or newer

Perfect for Immich users who want to save inspiration, memes, references, family photos and screenshots from the web straight to their library — without downloading and re-uploading every time.



This is an unofficial community extension and is not affiliated with the Immich project.
