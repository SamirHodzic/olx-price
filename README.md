# olx-price

**OLX API requests (Chrome Extension, Manifest V3)**

A tiny Chrome extension that automatically appends `has_price=1` to OLX requests (by default to all `/api/*` endpoints) so that search results without prices can be filtered out no matter which page you are on.

---

## Installation

1. Clone this repository:

```bash
git clone https://github.com/SamirHodzic/olx-price.git
cd olx-price
```

2. Load the extension in Chrome:

   * Open `chrome://extensions/`.
   * Enable **Developer mode** (top-right).
   * Click **Load unpacked** and select this project folder.

4. Ensure the extension is enabled.


## Security & Privacy

This extension runs locally in your browser and only modifies outgoing requests to `olx.ba` (or hosts matched by the rule). It does not collect or transmit any data outside your browser/OLX.

Note: modifying requests to non-API endpoints (images, styles, scripts) may break caching or site behaviour — by default the rules target `/api/*` to reduce risk.

## License

MIT — see `LICENSE` for details.