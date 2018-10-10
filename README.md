Voxeet Assets React Components
=====================

## Installation

This repository contains styles and icon for the Voxeet React components. You can modify the css or replace images.
Feel free to regenerate the css with instructions below

You need to install lessc in ordre to generate the CSS.

``
brew install lessc
``

## Customize

Main colors are inside the ``variables.less`` file

## Usage

Generate CSS file from less files

``
lessc less/main.less > voxeet-react-components.css
``

## Include

When your CSS file in generated, add it inside your HTML page :

``
<link rel="stylesheet" type="text/css" href="./voxeet-react-components.css" />
``

Or inside your js file 
``
import './voxeet-react-components.css';
``
