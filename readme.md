<h1 align="center"> Personal Portfolio </h1>

<img width="945" alt="image" src="./src/assets/hero.png">

### Deployed link: https://portfolio-daniel-zajac.vercel.app/

## Table of Contents 📁

1. [Tech Stack](#tech-stack-)
2. [Implemented Sections](#implemented-sections-%EF%B8%8F)
3. [Use as a theme](#using-as-a-theme-)
4. [Installation Guide](#installation-guide-)
5. [Sample Git Workflow](#sample-git-workflow)
   <br>

## Tech Stack 🧰

<li>Frameworks</li>

- [ReactJS](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)

<li>Libraries/Tools</li>
    
- [ViteJS](https://vitejs.dev/)
- [React Icons](https://react-icons.github.io/react-icons")
- [Framer](https://www.framer.com/)
- [React Lottie](https://www.npmjs.com/package/react-lottie)
- [Meraki UI](https://merakiui.com/components/)

<br/>

## Implemented Sections ☑️

- Hero Section
- Skills & Experience
- Education
- Projects
- Contact Me

## Using as a theme ✨

### Code changes

Three main things have to be changed to customize it your way (please open an issue if you find more such instances):

1. Personal Information

- [/src/constants/index.js](https://github.com/danzajac/portfolio/blob/main/src/constants/index.js) contains all the personal information one needs to change. Each website section is written as a JavaScript object and is pretty intuitive to change.

- Icons
  - Whenever you want to use an icon, you'll have to make sure that the icon is imported.
  - Head to [https://react-icons.github.io/react-icons/search](https://react-icons.github.io/react-icons/search) and search for the desired icon. (Eg: SiReact for ReactJS)
  - Note the package it belongs to (Eg: 'Si' here)
  - Import the icon into [`/src/constants/index.js`](https://github.com/danzajac/portfolio/blob/main/src/constants/index.js) (Eg: `import { ... SiReact, } from "react-icons/si";` here)

2. Website title and icon

- Go to [`index.html`](https://github.com/danzajac/portfolio/blob/main/index.html) and change the [`title`](https://github.com/danzajac/portfolio/blob/main/index.html#L7") to your name.
- Also, change the link to the title [icon](https://github.com/danzajac/portfolio/blob/main/index.html#L5)

3. Assets

- Add any assets (images) to the [`assets`](https://github.com/danzajac/portfolio/tree/main/src/assets) folder.
- Import the asset and export it using the[`/src/assets/index.js`](https://github.com/danzajac/portfolio/blob/main/src/assets/index.js) file.

### Deployment

You can use [Vercel](https://vercel.com/docs) to deploy your site. Follow the instructions in their docs to do so.

## Installation Guide 🧑‍💻

### Using Git and Github

- [Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) the repo
- [Clone](https://docs.github.com/en/get-started/quickstart/contributing-to-projects#cloning-a-fork) the forked repository
- Enter the new `portfolio` directory with `cd portfolio`
- Set the upstream remote to the original repository url so that git knows where to fetch updates from in future: `git remote add upstream https://github.com/danzajac/portfolio.git`

### Install required packages

- `npm install`

### Run server

- `npm run dev`

<br/>

## Sample Git Workflow

- Follow the [installation guide](https://github.com/danzajac/portfolio/blob/main/readme.md#installation-guide) to install the software
- Create a new feature branch with `git checkout -b <name-of-your-feature-branch>`
- Make changes and commit them in the feature branch.
- Once done developing, switch back to the main branch with `git checkout main` ; pull the latest version of the repo with `git pull https://github.com/danzajac/portfolio.git main`
- Switch back to the feature branch with `git checkout <name-of-your-feature-branch>`. Apply the new changes on top of the latest version of the repo with `git rebase main`
- [Resolve merge conflicts](https://help.github.com/articles/resolving-a-merge-conflict-from-the-command-line/) (if any)
- Push your feature branch upto your remote repo with `git push origin <name-of-your-feature-branch>`
- [Submit a Pull Request](https://docs.github.com/en/get-started/quickstart/contributing-to-projects#making-a-pull-request) to the main branch.

#### If you found this repo helpful in anyway, considering giving it a star - it would mean the world to me! 🌟
