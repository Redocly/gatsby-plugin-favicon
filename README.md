# gatsby-plugin-favicon

Generates all favicons for Web, Android, iOS, ...

## Install

`yarn add gatsby-plugin-favicon`

or

`npm install gatsby-plugin-favicon`

## How to use

1. Include the plugin in your `gatsby-config.js` file.
2. Add a `favicon.png` file in your `src` folder. The recommended size for the
   file is: 1500x1500px.

```javascript
// in gatsby-config.js
plugins: [
  {
    resolve: `gatsby-plugin-favicon`,
    options: {
      logo: "./src/favicon.png",
      background: '#fff',
      title: 'Gatsby site',
      icons: {
        android: true,
        appleIcon: true,
        appleStartup: true,
        coast: false,
        favicons: true,
        firefox: true,
        opengraph: false,
        twitter: false,
        yandex: false,
        windows: false
      }
    }
  }
];
```
