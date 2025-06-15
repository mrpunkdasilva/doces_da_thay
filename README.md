# Doces da Thay 🍰

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/)

## 📋 Overview

"Doces da Thay" is a responsive e-commerce website for a confectionery business specializing in handmade sweets and desserts. The platform allows customers to browse products, add items to cart, manage wishlists, and complete the checkout process.

## ✨ Features

- **Responsive Design**: Fully responsive layout that works on mobile, tablet, and desktop devices
- **Product Catalog**: Browse through various categories of sweets and desserts
- **Shopping Cart**: Add products to cart and manage quantities
- **Wishlist**: Save favorite items for future purchase
- **User Accounts**: Register, login, and manage personal information
- **Checkout Process**: Secure and streamlined checkout experience
- **Image Gallery**: Showcase of beautiful product photography
- **Contact Form**: Easy way for customers to get in touch

## 🛠️ Technologies

- **Frontend**: HTML5, CSS3, JavaScript, jQuery
- **UI Framework**: Bootstrap
- **Animations**: Animate.css
- **Carousels**: Owl Carousel, SuperSlides
- **Form Validation**: jQuery Form Validator
- **Image Lightbox**: baguetteBox
- **Backend Integration**: PHP for form processing

## 🚀 Getting Started

### Prerequisites

- Docker and Docker Compose (for containerized setup)
- Web browser (Chrome, Firefox, Safari, or Edge recommended)

### Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/doces_da_thay.git
   cd doces_da_thay
   ```

2. Using Docker:
   ```bash
   docker compose up -d
   ```

3. Access the website:
   ```
   http://localhost:8080
   ```

### Manual Setup (without Docker)

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/doces_da_thay.git
   ```

2. Set up a local web server (like Apache or Nginx) and point it to the project directory

3. Access the website through your local server address

## 🐳 Docker Configuration

The project includes Docker configuration for easy deployment:

- `Dockerfile`: Defines the container image based on PHP with Apache
- `docker-compose.yml`: Orchestrates the container setup
- Environment variables can be configured in the `.env` file

## 📁 Project Structure

```
doces_da_thay/
├── css/                  # Stylesheet files
├── images/               # Image assets
├── js/                   # JavaScript files
├── php/                  # PHP backend scripts
├── webfonts/             # Font files
├── *.html                # HTML pages
├── Dockerfile            # Docker configuration
├── docker-compose.yml    # Docker Compose configuration
└── README.md             # Project documentation
```

## 🔧 Customization

- Edit `css/custom.css` for styling customizations
- Modify `js/custom.js` for JavaScript customizations
- Update product information in the HTML files

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
