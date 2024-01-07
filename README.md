---

<p align="center">
  <a href="https://www.gatsbyjs.org">
    <img alt="Gatsby" src="https://www.gatsbyjs.org/monogram.svg" width="60" />
  </a>
</p>

<h1 align="center">Gatsby Blog Theme Starter</h1>

Get started quickly with the Gatsby blog theme! This starter sets up a new Gatsby site preconfigured to seamlessly work with the [official Gatsby blog theme](https://www.npmjs.com/package/gatsby-theme-blog).

## 🚀 Quick Start

1. **Create a Gatsby Site:**

   Use the Gatsby CLI to create a new site, choosing the blog theme starter.

   ```shell
   gatsby new my-themed-blog https://github.com/gatsbyjs/gatsby-starter-blog-theme
   ```

2. **Start Developing:**

   Navigate to your new site’s directory and kickstart the development server.

   ```shell
   cd my-themed-blog/
   gatsby develop
   ```

3. **Customize Your Site:**

   Open the code and start customizing! Your site is running at `http://localhost:8000`. Refer to the [guide](https://gatsbyjs.org/docs/themes/using-a-gatsby-theme) or the [detailed tutorial](https://gatsbyjs.org/tutorial/using-a-theme) to get started.

## 🧐 What's Inside?

Explore the top-level files and directories in a site created using the blog theme starter:

```text
gatsby-starter-blog-theme
├── content
│   ├── assets
│   │   └── avatar.png
│   └── posts
│       ├── hello-world.mdx
│       └── my-second-post.mdx
├── src
│   └── gatsby-theme-blog
│       ├── components
│       │   └── bio-content.js
│       └── gatsby-theme-ui
│           └── colors.js
├── .gitignore
├── .prettierrc
├── gatsby-config.js
├── LICENSE
├── package-lock.json
├── package.json
└── README.md
```

1. **`/content`**: Contains assets the theme expects, such as an avatar image and blog post content. Customize based on your needs.

2. **`/src`**: Customize your site under `/src/gatsby-theme-blog`. Files here override those in the `gatsby-theme-blog` package. [Learn more](https://gatsbyjs.org/docs/themes/using-a-gatsby-theme).

3. **`.gitignore`**: Specifies files not tracked by git.

4. **`.prettierrc`**: Prettier configuration for linting files.

5. **`gatsby-config.js`**: Main configuration for your Gatsby site, including theme plugin inclusion and customization options.

6. **`LICENSE`**: MIT license for Gatsby.

7. **`package-lock.json`**: Auto-generated file based on npm dependencies.

8. **`package.json`**: Manifest file for Node.js projects.

9. **`README.md`**: This file with essential information about your project.

## 🎓 Learning Gatsby

For detailed guidance, refer to the full documentation for Gatsby available [on the website](https://www.gatsbyjs.org/).

Here are some starting points:

### Themes

- Learn more about Gatsby themes in the [theme docs](https://www.gatsbyjs.org/docs/themes/).

### General

- **Start with our [tutorial for creating a Gatsby site](https://www.gatsbyjs.org/tutorial/), suitable for all developers.**

- **Explore code samples in [our documentation](https://www.gatsbyjs.org/docs/), especially the _Reference Guides_ and _Gatsby API_ sections in the sidebar.**
```

---
