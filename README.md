# Remonline Client Helper (unofficial)

Unofficial helper extension for the Remonline web app (https://web.roapp.io).
It adds client links near order labels and hides the Actions button on order tables.

## Features
- Adds a "Client" link next to order labels.
- Hides the "Actions" button on order table pages.
- Runs only on https://web.roapp.io/*.

## Installation (unpacked)
1. Open `chrome://extensions`.
2. Enable Developer Mode.
3. Click "Load unpacked" and select the repo root.
4. After edits, click "Reload" on the extension.

## Configuration
- Open the extension options and set **Client base URL**.
- The link format is `{base}/client/order/{orderNumber}`.
- Default base URL: https://stat-fixwill.ru (change it if needed).

## Permissions
- `host_permissions`: https://web.roapp.io/*
- `storage`: saves the base URL for client links

## Privacy
This extension does not collect or transmit user data. It only modifies the
web.roapp.io UI in the browser. Any opened client links go to the base URL
configured in options.

## Support
- Support page: https://github.com/aquadancer/Stat-fix-chrome-extension/issues
- Contact email: ai_kolesnik@mail.ru
- Issue tracker: https://github.com/aquadancer/Stat-fix-chrome-extension/issues

## Disclaimer
Not affiliated with or endorsed by Remonline.
