# NFT Preview Card Solution

This is a solution to the **NFT Preview Card Component** from [Frontend Mentor](https://frontendmentor.io)

This solution is uploaded as a part of the _**Advanced CSS Techniques Learning Path**_. I submitted the solution for this challenge a few months ago. In this solution, I have added a little more fun effect to the hover states and I have also improved the overall accessibility of the website. T

- [NFT Preview Card Solution](#nft-preview-card-solution)
  - [Built with](#built-with)
  - [Workflow](#workflow)
    - [Folder structure](#folder-structure)
    - [Installing Parcel in the project folder](#installing-parcel-in-the-project-folder)
    - [Link the SCSS file to the HTML](#link-the-scss-file-to-the-html)
    - [Update npm scripts](#update-npm-scripts)
    - [Start development server](#start-development-server)
  - [What I learned](#what-i-learned)
  - [Links](#links)

## Built with

- Semantic HTML5
- SCSS
- CSS
- [Parcel Bundler](https://parceljs.org)

## Workflow

Here's a short form of the overall workflow.

### Folder structure

```
projectFolder/
| > node_modules
| > src/
| >   scss/
| >    style.scss
| >   index.html
```

### Installing Parcel in the project folder

Install parel using `npm`

```
npm install parcel@latest -D
```

### Link the SCSS file to the HTML

Link the SCSS file to the HTML just like normal CSS.

```html
<html>
  <head>
    <link rel="stylesheet" href="./scss/style.scss" />
  </head>
  <body>
    ...
  </body>
</html>
```

### Update npm scripts

```json
{
  // added by user start
  "name": "project-name",
  "source": "src/index.html",
  "scripts": {
    "start": "parcel",
    "build": "parcel build"
  },
  //   added by user end
  "devDependencies": {
    "parcel": "latest"
  }
}
```

### Start development server

Starting the development server is easy by using the `npx` command.

```
npx parcel
```

This should start a development server with the port `localhost:1234` on your system. Open it in your browser to get a live preview.

## What I learned

I learned more about building accessible websites. I used semantic HTML tags to create the website. Along with that, I used `aria` attributes make the links accessible. Used `position: absolute` to create the illustration.

Added a blur effect to the view overlay to make it look better. I think adding a few of my personal touches will make it better and help me learn more things.

## Links

- GitHub Repository: [Visit](https://github.com/Code-Beaker/nft-preview-card-parcel-code-beaker)
- Live site URL(Vercel): [Visit](https://blog-preview-card-parcel.vercel.app/)

Powered by Parcel and hosted with [Vercel](https://vercel.com).
