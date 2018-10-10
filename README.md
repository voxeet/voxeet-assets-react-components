Voxeet Assets React Components
=====================

<p align="center">
<img src="https://www.voxeet.com/wp-content/themes/wp-theme/assets/images/logo.svg" alt="Voxeet SDK logo" title="Voxeet SDK logo" width="100"/>
</p>

## Installation

Before customize the Voxeet React components, try to integrate with the default template and when it's done, you can begin your customization. (https://www.npmjs.com/package/@voxeet/react-components)

This repository contains styles and icons for the Voxeet React components. You can modify the css or replace images.
Feel free to regenerate the css with instructions below

You need to install lessc in order to generate the CSS.

```bash
brew install lessc
```

## Customize

Main colors are inside the ``variables.less`` file
You can also change icons (using the same size should be better to get the same ratio) inside ``images/newicons``

## Usage

Generate CSS file from less files

```bash
lessc less/main.less > voxeet-react-components.css
```

## Include

Copy/paste your files inside your project and keep this tree :

- voxeet-react-components.css
- images (folder)
- fonts (folder)
- sounds (folder)

Add you CSS file inside your HTML page :

```html
<link rel="stylesheet" type="text/css" href="./voxeet-react-components.css" />
```

Or inside your js file 

``javascript
import './voxeet-react-components.css';
``

Start your project and you're good to go !
