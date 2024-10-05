**Simple EJS Website with Layout and Partials**

This project demonstrates how to use EJS (Embedded JavaScript) with partials and layouts in a simple Node.js web application. The website includes a header, footer, and layout template to dynamically render different pages like Home and About using EJS.

**Features**

EJS Partials: Reusable components like headers and footers.
Layout Template: A common layout for all pages with dynamic content.
Dynamic Pages: Pages like Home and About are rendered with dynamic content using EJS.

**Project Structure**

graphql
Copy code
simple-ejs-site/
  ├── views/               # Contains all EJS templates
  │   ├── partials/         # Reusable components like header and footer
  │   │   ├── header.ejs
  │   │   ├── footer.ejs
  │   ├── pages/            # Pages to be rendered inside the layout
  │   │   ├── home.ejs
  │   │   ├── about.ejs
  │   ├── layout.ejs        # Main layout template used by all pages
  ├── app.js                # Main server file
  └── package.json          # Project dependencies and metadata
