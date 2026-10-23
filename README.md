# qr

Simple QR code generator that runs in the browser (url, wifi, whatsapp, vcard). No build step and no server are required.

## Usage

Open `index.html` in a browser, or serve this folder with any static file server:

```bash
python3 -m http.server
# then open http://localhost:8000
```

Choose a code type, fill in its fields, and the QR code is generated on the page:

- **url** - a web link
- **wifi** - network name and password for a Wi-Fi join code
- **whatsapp** - a phone number for a WhatsApp chat code
- **vcard** - contact details for an address-book code

## License

GNU General Public License v3.0. See [LICENSE](LICENSE).
