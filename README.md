# Zoom Recording Context Menu Enabler

This Chrome extension enables the right-click context menu on Zoom recording pages.

## Installation

1. Open Chrome and navigate to `chrome://extensions/`
2. Enable "Developer mode" (toggle in the top right)
3. Click "Load unpacked"
4. Select this folder (`zoom-downloadable`)


## Usage

Once installed, the extension will automatically run on any Zoom recording URL matching:
`https://*.zoom.us/rec/play/*`

This includes all Zoom subdomains (e.g., company-name.zoom.us, university.zoom.us, etc.).

The extension intercepts the context menu event, allowing you to use the standard browser right-click menu instead of Zoom's custom implementation.
