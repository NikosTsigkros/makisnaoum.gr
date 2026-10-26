# makisnaoum.gr

Static Greek website for «Η Αθέατη Πνευματική Πραγματικότητα» by Μάκης Ναούμ.

## Development

Project working directory: `C:\DEV\makisnaoum.gr`.

Open `index.html` directly, or serve this directory with any static HTTP server. No build step, Node.js server, PHP, database, or dependencies are required.

- `index.html`: homepage, book reader, Orthodox faith clarification, and author contact.
- `style.css`: responsive styling.
- `app.js`: chapter navigation, reading controls, and sharing.
- `book-data.js`: book text loaded by the browser, including offline use.
- `chapters.json`: corresponding structured chapter text. Keep this synchronized with `book-data.js` when editing book content.
- `book.pdf`: original book.
- `diagram-31.png`, `diagram-32.png`: original book pages containing the diagrams.

Contact links open the visitor's email application and address messages to `makisnaoum52@gmail.com`.

## Deploy to Plesk

Upload the website files to the domain's document root (usually `httpdocs`). `index.html` must be directly inside that directory. Do not upload `.git` or development documentation. Configure the domain DNS and HTTPS in your hosting control panel.

Verify the homepage, chapter navigation, PDF download, diagrams, and contact link after deployment.
