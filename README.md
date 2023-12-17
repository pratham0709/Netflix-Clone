<div align="center">

  <img src="https://user-images.githubusercontent.com/99184393/211183762-03b6e9b4-9fcd-4874-a0e4-20cf00537c06.gif" alt="logo" width="400" height="auto" />

  <h1>NETFLIX 2.0 with TailwindCss!</h1>

<br />

<!-- Table of Contents -->

## :notebook_with_decorative_cover: Table of Contents

- [About the Project](#star2-about-the-project)
  - [Screenshots](#camera-screenshots)
  - [Tech Stack](#space_invader-tech-stack)
  - [Environment Variables](#key-environment-variables)
- [Getting Started](#toolbox-getting-started)
  - [Prerequisites](#bangbang-prerequisites)
  - [Installation](#gear-installation)
  - [Run Locally](#running-run-locally)
  - [Deployment](#triangular_flag_on_post-deployment)
- [Contact](#handshake-contact)

<!-- About the Project -->

## :star2: About the Project

<!-- Screenshots -->

### 📸 Screenshots
![image](https://github.com/pratham0709/Netflix-Clone/blob/main/Screenshots/1.png)
![image](https://github.com/pratham0709/Netflix-Clone/blob/main/Screenshots/2.png)
![image](https://github.com/pratham0709/Netflix-Clone/blob/main/Screenshots/3.png)
![image](https://github.com/pratham0709/Netflix-Clone/blob/main/Screenshots/4.png)
![image](https://github.com/pratham0709/Netflix-Clone/blob/main/Screenshots/5.png)
![image](https://github.com/pratham0709/Netflix-Clone/blob/main/Screenshots/6.png)
![image](https://github.com/pratham0709/Netflix-Clone/blob/main/Screenshots/7.png)


<p align="center">

[![built with love](https://forthebadge.com/images/badges/built-with-love.svg)](https://github.com/pratham0709/Netflix-Clone)

</p>


<div align="center">
<a href="https://netflix-sclone.netlify.app" target="_blank"><img  src='./demo/ezgif-1-2a6c90cdd6.gif' alt='image'/></a>
</div>

## <a href="https://pratham07-netflixclone.netlify.app/" target="_blank">LIVE DEMO 💥</a>

![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)
![forthebadge](https://forthebadge.com/images/badges/for-you.svg)
![forthebadge](https://forthebadge.com/images/badges/powered-by-coffee.svg)

<br />

### :gear: Installation

Install my-project with npm

```bash
npx create-next-app@latest my-project --typescript
```

```
cd my-project
```

Install dependencies

### :test_tube: Install Tailwind CSS 

#### Install Tailwind CSS

Install tailwindcss and its peer dependencies via npm, and then run the init command to generate both `tailwind.config.js` and `postcss.config.js`.

```bash
npm install -D tailwindcss postcss autoprefixer
```

```bash
npx tailwindcss init -p
```

#### Configure your template paths

Add the paths to all of your template files in your `tailwind.config.js` file.
<br>

```js
module.exports = {
  content: [
    "./pages/**/*.{js,ts,jsx,tsx}",
    "./components/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

#### Add the Tailwind directives to your CSS

Add the `@tailwind` directives for each of Tailwind’s layers to your `./styles/globals.css` file.

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

<!-- Deployment -->

### :triangular_flag_on_post: Deployment

To deploy this project run

##### Deploy on Vercel

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

## :handshake: Contact

Your Name - [@twitter_handle](https://twitter.com/Pratham_jadhav_) - prathameshj792@gmail.com

Project Link: [https://github.com/pratham0709/NETFLIX-Clone.git](https://github.com/pratham0709/Netflix-Clone)

<hr />
<br />

<div align="center">Don't forget to leave a star ⭐️</div>
