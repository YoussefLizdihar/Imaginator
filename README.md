# Imaginator - AI Image Generator

Imaginator is an AI-powered image generation tool that allows users to create images from text prompts. This project leverages the OpenAI API to generate images quickly and efficiently.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technology Stack](#technology-stack)
- [Architecture](#architecture)
- [Challenges](#challenges)
- [Learnings](#learnings)
- [Live Demo](#live-demo)
- [About](#about)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

Imaginator is a tool that allows users to convert text prompts into images using the power of AI. Whether you're an artist looking for inspiration or just curious about AI-generated art, Imaginator provides a simple and intuitive interface to explore creative possibilities.

## Features

1. **Quick Image Generation**:
    - Generate images from text prompts quickly and efficiently using the OpenAI API.
    - ![Quick Image Generation](https://github.com/YoussefLizdihar/Imaginator/blob/main/images/1.png)

2. **Multiple Image Outputs**:
    - Choose the number of images to generate, from 1 to 4, to suit your needs.
    - ![Multiple Image Outputs](https://github.com/YoussefLizdihar/Imaginator/blob/main/images/3.png)

3. **Easy Download**:
    - Download the generated images directly to your device with a single click.
    - ![Easy Download](https://github.com/YoussefLizdihar/Imaginator/blob/main/images/2.png)

3. **Image Editor**:
    - Edit the generated images directly with a single click and use the filters as you want to make it even better and then save it.
    - ![Image Editor](https://github.com/YoussefLizdihar/Imaginator/blob/main/images/4.jpeg)

## Installation

To get a local copy up and running follow these simple steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/YoussefLizdihar/imaginator.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd imaginator
    ```

3. **Open the project in your preferred code editor**.

## Usage

1. **Open the `index.html` file in your browser** to access the Imaginator interface.
2. **Enter a text prompt** in the input field.
3. **Select the number of images** you want to generate.
4. **Click the "Generate" button** to see the AI-generated images.
5. **Download your favorite images** using the download button provided.

## Technology Stack

### Frontend
- **HTML**: Used for structuring the web page.
- **CSS**: Used for styling the web page.
- **JavaScript**: Used for adding interactivity to the web page.

### Backend
- **OpenAI API**: Used for generating images from text prompts using AI.

## Architecture

### HTML Structure
- A top navigation bar with links to the home page and about page.
- An image generator section with a form for inputting text prompts and generating images.
- An image gallery section displaying the generated images.
- An accordion section for FAQs.
- A footer with copyright information.

### JavaScript Functionality
- **Form Submission**: Handles form submission to generate AI images using the OpenAI API.
- **Image Generation**: Sends a request to the OpenAI API with the user's prompt and desired number of images.
- **Image Update**: Updates the image gallery with the generated images.
- **Image Editing**: Allows users to edit the generated images using a built-in editor with options for filters and transformations.
- **Accordion**: Toggles FAQ sections open and closed.

### Styling
- External stylesheets are linked for base styles.
- The CSS handles the layout, styling of the top bar, image generator section, image gallery, accordion, and other UI components.

## Key Components

### HTML
- Topbar Menu
- Image Generator Section
- Image Gallery Section
- FAQ Section
- Footer

### JavaScript
- **Form Handling**: Handles the image generation form submission.
- **API Interaction**: Interacts with the OpenAI API to generate images.
- **Image Display**: Updates the image gallery with generated images.
- **Image Editor**: Provides basic editing functionalities (filters, rotate, flip).
- **Accordion**: Manages the FAQ accordion behavior.

### CSS
- **General Styling**: Fonts, colors, layout, and responsiveness.
- **Specific Components**: Styling for topbar, forms, buttons, image gallery, FAQ accordion, and footer.

## Challenges

Throughout the development of Imaginator, several challenges were encountered and overcome:

- **API Integration**: Ensuring smooth communication with the OpenAI API.
- **Responsive Design**: Making sure the app works well on different devices.
- **Error Handling**: Gracefully handling errors and providing feedback to the user.

## Learnings

This project provided valuable insights into:

- Integrating third-party APIs.
- Managing asynchronous operations in JavaScript.
- Enhancing user experience through responsive design.

## Live Demo

Check out the live demo of Imaginator [here](https://j2g6bfkrwob3a4y9lu2uja.on.drv.tw/www.imaginatorai.com/).

## About

Imaginator was inspired by my passion for artificial intelligence and digital art. I wanted to create a tool that allows anyone to generate images from text prompts easily. This project represents a culmination of my learning journey at Holberton School.

- **LinkedIn**: [Youssef Lizdihar](https://www.linkedin.com/in/yousseflizdihar)
- **GitHub**: [yousseflizdihar](https://github.com/yousseflizdihar)
- **Twitter**: [yousseflizdihar](https://twitter.com/yousseflizdihar)
- **GitHub Repository**: [Imaginator](https://github.com/yousseflizdihar/imaginator)

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. **Fork the Project**
2. **Create your Feature Branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit your Changes** (`git commit -m 'Add some AmazingFeature'`)
4. **Push to the Branch** (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Youssef Lizdihar - [youssef.lizdihar@gmail.com](mailto:youssefyd.3d@gmail.com)

Project Link: [https://github.com/yousseflizdihar/imaginator](https://github.com/yousseflizdihar/imaginator)
