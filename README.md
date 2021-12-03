<p align="center">
  <a href="https://www.gatsbyjs.com">
    <img alt="Gatsby" src="https://www.gatsbyjs.com/Gatsby-Monogram.svg" width="60" />
  </a>
</p>
<h1 align="center">
  Gatsby Starter Landing Page
</h1>

**This is a work-in-progress and not ready for general use**

Create custom landing pages using Gatsby and Contentful with this starter-theme combo.
This starter demonstrates how to use Contentful to build dynamic and customizable landing pages with Gatsby and can serve as a starting-point for creating your own custom landing page components that match your visual brand.

Deploy now to [Gatsby Cloud](https://gatsbyjs.com/products/cloud):

[<img src="https://www.gatsbyjs.com/deploynow.png" alt="Deploy to Gatsby Cloud">](https://www.gatsbyjs.com/dashboard/deploynow?url=https://github.com/gatsbyjs/gatsby-starter-landing-page)

[View the Demo][demo]

[demo]: https://landingpagestarter.gatsbyjs.io/

## Quick start

1. **Create a Gatsby site**

   Use the Gatsby CLI to get started locally:

   ```sh
   npx gatsby new my-landing-page-site https://github.com/gatsbyjs/gatsby-starter-landing-page
   ```

2. **Configure your Contentful space**

   Create a new Contentful space or use an existing one, then upload the `data/sample-data.json` file to your space.

3. **Add environment variables**

   Create a `.env` file in the root directory of your site and add the following environment variables. You can copy the `.env.example` file provided. Find the values for these keys in the Contentful web app under _Settings > API Keys_.

   ```sh
   CONTENTFUL_SPACE_ID="<YOUR_SPACE_ID>"
   CONTENTFUL_DELIVERY_ACCESS_TOKEN="<ACCESS_TOKEN>"
   ```

4. **Start developing**

   Navigate to your new site's directory and start the development server.
   **Note:** this starter uses Yarn Workspaces and requires Yarn for development.

   ```sh
   cs my-landing-page-site
   yarn && yarn start
   ```

5. **Open the source code and start editing!**

   Your site should now be running at <http://localhost:8000>

## What's inside?

A quick look at the files and directories included in this project:

```
.
├── README.md
├── gatsby-config.js
├── gatsby-theme-landing-page
│   ├── gatsby-config.js
│   ├── index.js
│   ├── package.json
│   └── src
│       ├── components
│       ├── pages
│       ├── sections
│       └── styles
├── src
│   ├── components
│   ├── gatsby-theme-landing-page
│   └── styles.css
└── .env.example
```

1. **`gatsby-config.js`**: Gatsby config file for the starter, which includes `gatsby-theme-landing-page` as a plugin.
1. **`gatsby-theme-landing-page`**: The theme that includes the Contentful source plugin and most of the functionality. See the theme's [`README.md`](gatsby-theme-landing-page/README.md) for more information.
1. **`src/`**: The source directory for the starter. This includes an example of using the [Shadowing API][] to customize landing pages provided by the theme.
1. **`.env.example`**: Copy this file, rename it to `.env`, and add your Contentful API keys to connect this data to your Contentful space.

[shadowing api]: https://www.gatsbyjs.com/docs/how-to/plugins-and-themes/shadowing/

### Detailed look into the theme

TK

## Installing the theme in an existing site

TK

## Adding a layout

TK

## Customizing the typography and colors

TK

## Customizing and extending components

TK

## 🎓 Learning Gatsby

Looking for more guidance? Full documentation for Gatsby lives [on the website](https://www.gatsbyjs.com/). Here are some places to start:

- **For most developers, we recommend starting with our [in-depth tutorial for creating a site with Gatsby](https://www.gatsbyjs.com/tutorial/).** It starts with zero assumptions about your level of ability and walks through every step of the process.
- **To dive straight into code samples, head [to our documentation](https://www.gatsbyjs.com/docs/).**

## 💫 Deploy

[Build, Deploy, and Host On The Only Cloud Built For Gatsby](https://www.gatsbyjs.com/cloud/)

Gatsby Cloud is an end-to-end cloud platform specifically built for the Gatsby framework that combines a modern developer experience with an optimized, global edge network.
