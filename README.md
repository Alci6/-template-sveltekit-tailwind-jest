# Sveltekit with Typescript, TailwindCSS, Jest and Storybook

> ✨ Community template for Sveltekit + Typescript + TailwindCSS + Jest + Storybook

Clone the repository

```
npx degit alcibiadesc/template-sveltekit YOUR-FOLDER-NAME
```

Enter in the folder and install all

```
cd YOUR-FOLDER-NAME
npm install
```



## Versions

* Svelte: 3.46.0
* TailwindCSS: 3.0.18
* Jest: 27.5.0
* Testing-Library: 3.0.3
* Storybook: 6.5.0-alpha.38
* Eslint: 7.32.0
* Prettier: 2.4.1

more info inside *package.json*

## Boilerplate that you can delete
I use to delete /lib because I use a custom version of [Atomic Design](https://atomicdesign.bradfrost.com/) template folder instead: 
* Components/
  * atoms/
  * molecules/
  * organisms/
  * pages/

I added a Button in ./src/components/atoms/ from Storybook to test that works with alias (dynamic path) and with tailwind (you can delete it) 

## Basic Available Scripts

### npm run dev

Runs the app in the development mode. Open [http://localhost:3000](http://localhost:3000/) to view it in the browser.

The page will reload if you make edits. 

### npm run build

Builds a static copy of your site to the `build/` folder. Your app is ready to be deployed!

### npm run test

Launch jest battery of tests

### npm run test:watch

Launch jest battery of tests in every change of document.

### npm run storybook
Launch storybook. You can enter openning [http://localhost:6006](http://localhost:6006) to view it in the browser.

### others scripts

more info inside *package.json*
