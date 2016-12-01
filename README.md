# Pinnacle
A modern OctoberCMS starter theme based on the Sage theme by Roots.

`Disclaimer: This theme is not finished. Therefore not everything may work as intended. It is not recommended to use this theme in production environments.`

## Requirements
* See requirements for OctoberCMS. You can find them [here](https://octobercms.com/docs/setup/installation#system-requirements).
* Node.js (not needed on your server, you can install Node locally to build your assets on your computer)

## Installation
1. Install OctoberCMS. See the instructions [here](https://octobercms.com/docs/setup/installation).
1. Once OctoberCMS is installed, clone this repository to a folder in the themes folder of your installation.
1. Activate Pinnacle as your theme in the backend of OctoberCMS.
1. Open your preferred terminal (I use Git Bash on Windows) and enter `npm install -g gulp bower` to globally install Gulp and Bower.
1. Then enter `npm install` to install the required Node packages.
1. Once that's finished, enter `bower install` to download the dependencies used for Pinnacle.
1. Afterwards, you should be able to run `gulp` to build the assets or `gulp watch` to watch for changes, build automatically and open a browsersync tab.
1. Have fun developing!

## How to use Pinnacle
If you check the theme folder, you'll notice that there are a few new files and folders:

* **bower.json**  
  This file contains the bower dependencies for Pinnacle.
* **gulpfile.js**  
  The gulpfile contains all the tasks that Gulp runs on builds.
* **package.json**  
  This file contains the packages for Node.
* **src/manifest.json**  
  This manifest contains the source SCSS and JS that will be compiled to the assets folder.

* **src/**  
  This folder contains the source files for the assets. Place your images in the **src/images/** folder, scripts in the **src/scripts/** folder and **scr/styles/** folder. Remember that new SCSS files have to be added to the **src/styles/main.scss** file and script files have to be added in the **src/manifest.json**.

## Credits
[The Roots Team](https://roots.io/sage/)  
[Scott Webb](https://unsplash.com/@scottwebb)
