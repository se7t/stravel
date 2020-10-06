<p align="center">
  <a href="https://www.github.com/se7t/stravel">
    <img alt="Stravel" src="./static/Logo.svg" />
  </a>
</p>
<h1 align="center">
  Travel Agency Website
</h1>

<h3>A static website created using many modern technologies, with Material UI used as a base for styling. Customized and optimized for all devices. Fully responsive and dynamic, with content served using a CMS.</h3>
<br/>

## 🔬 Technologies used

1.  **GatsbyJS**

    This project is a static site, therefore it is build with GatsbyJS.

    `https://www.gatsbyjs.com/`

1.  **Material UI**

    This library is a fundamental part of the entire project. It provides basic styling to components, which are then customized.

    `https://material-ui.com/`

1.  **Contentful CMS**

    A blog page is available, which is why I have decided to use CMS to manage posts.

    `https://www.contentful.com/`

1.  **React Hook Form**

    Contact page contains a form, and React Hook Form provides an easy to manage form hooks (duh).

    `https://react-hook-form.com/`

1.  **TheySaidSo REST API**

    TheySaidSo API provides a way to fetch a quote of a given category, which is then displayed on the Services, FAQ, and Contact page.

    `https://theysaidso.com/`

1.  **useFetch**

    This project uses both REST (for TheySaidSo API), and GraphQL (for Contentful CMS), therefore I have decided upon using the useFetch library, as it provides support for both of these.

    `https://use-http.com/`

<br/>

## 📖 What's inside? [WIP]

Here is a rundown of how the project tree looks like.

    .
    ├── node_modules
    ├── src
    ├── .gitignore
    ├── .prettierrc
    ├── gatsby-browser.js
    ├── gatsby-config.js
    ├── gatsby-node.js
    ├── gatsby-ssr.js
    ├── LICENSE
    ├── package-lock.json
    ├── package.json
    └── README.md

1.  **`/node_modules`**: ---

2.  **`/src`**: ---

3.  **`.gitignore`**: ---

4.  **`.prettierrc`**: ---

5.  **`gatsby-browser.js`**: ---

6.  **`gatsby-config.js`**: ---

7.  **`gatsby-node.js`**: ---

8.  **`gatsby-ssr.js`**: ---

9.  **`LICENSE`**: ---

10. **`package-lock.json`**: ---

11. **`package.json`**: ---

12. **`README.md`**: ---

## 🧰 Prerequisites

In order to run this project, you need to create a _.env.development_ file in root directory with the following content:

```
CONTENTFUL_SPACE_ID=YOUR_SPACE_ID_GOES_HERE
CONTENTFUL_ACCESS_TOKEN=YOUR_ACCESS_TOKEN_GOES_HERE
```
