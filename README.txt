# Printora Studio Website

## Files
- `index.html` — website structure and content
- `css/style.css` — styling and responsive layout
- `js/script.js` — slide carousel, mobile menu, portfolio filters, testimonial controls, quote email draft, and back-to-top
- `images/slide-1.jpg`, `images/slide-2.jpg`, `images/slide-3.jpg` — hero slide image files referenced with `<img src="...">`

## Setup
1. Keep the folder structure unchanged.
2. Add your own slide images in the `images` folder using the exact filenames above, or update each hero `<img src>` in `index.html`.
3. Open `index.html` in a browser.
4. Replace the sample company name, placeholder phone number, email, address, and WhatsApp number before publishing.

The hero slides use local image sources (`img src="images/slide-1.jpg"` etc.), not CSS background image URLs. The portfolio images currently use remote image URLs and need an internet connection unless you download them and change those `src` paths to local files.

The quotation form currently opens a prefilled email draft. It does not store form submissions on a server.
