# FYLE_Arpit
# Digital Marketing Agency Website

This project is a digital marketing agency website built with HTML, CSS, and JavaScript, utilizing Bootstrap for responsive design. The website includes sections such as Hero, Services, Clients, and a contact form.

## Table of Contents

- [Getting Started](#getting-started)
- [Folder Structure](#folder-structure)
- [Features](#features)
- [Dependencies](#dependencies)
- [Scripts](#scripts)
- [Contact](#contact)

## Getting Started

To get started with this project, you can clone the repository and open the `index.html` file in your browser.

### Prerequisites

Ensure you have the following installed on your development machine:
- A modern web browser (e.g., Google Chrome, Mozilla Firefox)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/digital-marketing-agency.git
    ```
2. Navigate to the project directory:
    ```bash
    cd digital-marketing-agency
    ```
3. Open the `index.html` file in your preferred web browser.

## Folder Structure



## Features

- **Hero Section**: Displays a prominent introduction to the agency with a contact button.
- **Services Section**: Showcases the various services offered by the agency.
- **Clients Section**: Displays logos of notable clients.
- **Contact Form**: Allows users to get in touch with the agency.

## Dependencies

This project relies on the following external libraries and frameworks:

- [Bootstrap 4.5.2](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
- [Font Awesome 5.15.4](https://fontawesome.com/)
- [jQuery 3.5.1](https://jquery.com/)

## Scripts

### Modal Script

Handles the opening and closing of the contact form modal.

```javascript
// Get the modal
var modal = document.getElementById("contactModal");

// Get the button that opens the modal
var btn = document.getElementById("openModalBtn");

// Get the <span> element that closes the modal
var span = document.getElementsByClassName("close")[0];

// When the user clicks the button, open the modal
btn.onclick = function() {
    modal.style.display = "block";
}

// When the user clicks on <span> (x), close the modal
span.onclick = function() {
    modal.style.display = "none";
}

// When the user clicks anywhere outside of the modal, close it
window.onclick = function(event) {
    if (event.target == modal) {
        modal.style.display = "none";
    }
}



Feel free to modify the content to match your project's specific details and repository information.
