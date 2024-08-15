# Coca Cola 3D Models Application

This repository contains a 3D web application showcasing Coca Cola branded models using the MVC architecture. This project is part of the coursework for Advancved Computer Scienece at the University of Sussex.

## Live Demo
You can view the live demo of the project [here](https://github.com/Mbanathegoat/mbana3dapp.git).

## Overview
The application displays interactive 3D models of Coca Cola products, such as Coke, Sprite, and Dr. Pepper, allowing users to explore and interact with them. It features a responsive design and integrates various web technologies.

## Features
- **Interactive 3D Models**: Users can interact with and view models from different angles.
- **Responsive Design**: The app is fully responsive, providing an optimal viewing experience across all devices.
- **Gallery**: A gallery showcasing high-quality images of the models.
- **VR Mode**: Option to switch to a VR view for a more immersive experience.
- **Camera Controls**: Various camera angles and views for an enhanced user experience.
- **Animation Controls**: Controls to animate the models in different ways.
- **Rendering Options**: Different rendering modes such as wireframe for model visualization.

## Technologies Used
- **Frontend**: 
  - HTML5
  - CSS3 (Bootstrap, custom CSS)
  - JavaScript (jQuery, Popper.js, Swiper.js)
  - X3DOM for 3D model rendering
  - GLightbox for image galleries
  - FontAwesome for icons
- **Backend**: 
  - PHP (for MVC architecture)
  - SQLite (for data storage)
- **Others**: 
  - Google Fonts for typography
  - AJAX & JSON for asynchronous content loading

## Project Structure
- **Models**: All 3D model files are stored in the root directory.
- **Images**: Image files used in the gallery are located in `/images/gallery_images/`.
- **CSS**: Custom stylesheets are in `/css/`.
- **JavaScript**: Scripts are stored in `/js/`.
- **Pages**: 
  - `index.html`: The homepage of the application.
  - `about.html`: The about page detailing the project.
  - `models.html`: The page displaying the interactive 3D models.

## Usage
To run this project locally, ensure you have a web server with PHP installed. You can simply clone this repository and open the `index.html` file in your web browser.

```bash
git clone https://github.com/Mbanathegoat/mbana3dapp.git
cd your-repo-name
php -S localhost:8000
