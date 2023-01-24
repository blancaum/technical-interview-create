[![create-brand](https://user-images.githubusercontent.com/13077932/214291464-41f7f2a5-506f-43d7-99a1-fe4fb85b7326.png)](https://www.create-store.com/es/)


# ![logo](https://user-images.githubusercontent.com/13077932/214291561-27787104-4633-42ea-933d-ce72654eb429.png) [Technical Interview CREATE](https://blancaum.github.io/technical-interview-create/) ![logo](https://user-images.githubusercontent.com/13077932/214291561-27787104-4633-42ea-933d-ce72654eb429.png)

## Author: Blanca Ubis Martínez

## Project Requirements:

For this project, it was required to:
1. Replicate a webpage for mobile, tablet and desktop using HTML, CSS and preferably not a CSS framework (such as Bootstrap).
2. Add a hover state for the menu links, and animate it.
3. Try to make a tablet version (between 500px and 1024px) that could be adequate given the mobile (Fig. 1) and desktop (Fig. 2) requirements.


![mobile](https://user-images.githubusercontent.com/13077932/214293416-549f1e5c-36d5-4c8a-96d0-c0c03c8f0916.png)
- Fig. 1: Mobile version required.

![desktop](https://user-images.githubusercontent.com/13077932/214293422-1d9b4ad5-ed3c-4598-92ad-fa8c675b7f8f.png)
- Fig. 2: Desktop version required.

## Results:

The results are a **completely responsive web** that **matches perfectly** the images sent. See the [deployed webpage](https://blancaum.github.io/technical-interview-create/).
Furthermore:
1. I have chosen to not show the aside on the mobile version (as shown on the image requirements) and to put the aside below the articles on the tablet version.
2. The menu has a hover transition that makes the background color appear gradually.
3. The links are functional and work exactly as they do on the Create Store webpage (using target blank when necessary).

![mobile-results](https://user-images.githubusercontent.com/13077932/214295613-0f481655-c672-4cf2-bbb2-8f153992af36.png)
- Fig. 3: Mobile version results.

![tablet-results](https://user-images.githubusercontent.com/13077932/214295686-95e2fe34-e557-4087-9d90-91535b6a6d60.png)
- Fig. 4: Tablet version results.

![desktop-results](https://user-images.githubusercontent.com/13077932/214295847-e1f6f271-82a6-43ba-b678-ae9d04a184c1.png)
- Fig. 5: Desktop version results.

## Additional Information:

Based on the [**Adalab Starter Kit**](https://github.com/Adalab/adalab-web-starter-kit).

In this project you will find 3 types of files and folders:

- The files that are on the root of the repository, such as gulpfile.js, package.json... They are the configuration of the project, and they allow us to install the necessary npm packages, to join the HTML and SCSS partials and to create the development (folder `public`, not in github) and production ( folder `docs`) folders. See below for more information on the specific commands.
- The folder `src/`:  our web page files, such as HTML, CSS, JS...
- The folder `docs/`, generated automatically when we deploy the project. This kit reads the files that are inside `src/`, it process them and it generates the necessary files and folders inside `docs/`.

## Quick Start Guide

> **NOTE:** You must have installed [Node JS](https://nodejs.org/) to work with this project.

### Steps to follow if we want to start this project on our own computer:

1. **Clone this repository**
2. **Abre una terminal** en la carpeta raíz de tu repositorio.
3. **Instala las dependencias** locales ejecutando en la terminal el comando:

```bash
npm install
```

### Steps for starting the project:

Once we have installed the dependencies, we are going to start the project. **The project must be started every time you start programming ** To do this run the command:

```bash
npm start
```

This command:

- **Opens a Chrome window and displays your web page**, just like the VS Code Live Server (Go live) plugin does.
- It also **watches** all the files inside the `src/` folder, so that every time you modify a file it **refreshes your page in Chrome**.
- It also **processes the files** HTML, SASS / CSS and JS and **generates and saves them in the `public/`** folder. For example:
  - Converts SASS files to CSS.
  - Combines the different HTML files and groups them into one or several HTML files.

After running `npm start` you can see the how the webpage works and edit the files inside the `src/` folder if you want to change anything. However, if you want to make any commit with the changes you will have to make your own repository.

### Steps to generate the docs folder:

Run the following command:

```bash
npm run docs
```

- This will generate a `docs/` folder that we will upload to the repository.
- Later, with GitHub pages we will tell it to use it to generate the web of our project.
- We will have to execute this command at the end of the project when it is finished and we want to publish it.
- If we make any changes we will have to run it again and upload the `docs/` folder back to the repository.
