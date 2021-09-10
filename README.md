## Setup

To edit the links / info, navigate to ./src/data/index.js

#### colorMode

You can choose between a light or dark color theme by editing the colorMode variable

```javascript
export let colorMode = "light";
/* or */
export let colorMode = "dark";
```

#### personalInfo

Here you will change the name, photo and bio of your site.

- photo needs to be a link

```javascript
export let profileInfo = {
  name: "Tanner Thomas",
  photo:
    "https://pbs.twimg.com/profile_images/1180727567550046208/FfZHC8NX_400x400.jpg",
  bio: "photographyer && web developer",
};
```

#### links

Here you will add all of your links. You can add a site name, link to your site, and
a colorScheme to display your link

- link needs to have https://
- if you dont know what color to use, leave it blank

```js
export let links = [
  { site: "Twitter", link: "https://twitter.com", color: "blue" },
  { site: "Youtube", link: "https://youtube.com", color: "red" },
  { site: "Instagram", link: "https://instagram.com", color: "pink" },
  { site: "Github", link: "https://github.com", color: "purple" },
  { site: "Facebook", link: "https://facebook.com", color: "blue" },
  { site: "Portfolio", link: "https://facebook.com", color: "" },
];
```
