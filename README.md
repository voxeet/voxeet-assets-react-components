Voxeet Assets React Components
=====================

<p align="center">
<img src="https://www.voxeet.com/wp-content/themes/wp-theme/assets/images/logo.svg" alt="Voxeet SDK logo" title="Voxeet SDK logo" width="100"/>
</p>

## Installation

This repository contains styles and icon for the Voxeet React components. You can modify the css or replace images.
Feel free to regenerate the css with instructions below

You need to install lessc in ordre to generate the CSS.

```bash
brew install lessc
```

## Customize

Main colors are inside the ``variables.less`` file

## Usage

Generate CSS file from less files

```bash
lessc less/main.less > voxeet-react-components.css
```

## Include

When your CSS file in generated, add it inside your HTML page :

```html
<link rel="stylesheet" type="text/css" href="./voxeet-react-components.css" />
```

Or inside your js file 

``javascript
import './voxeet-react-components.css';
``
