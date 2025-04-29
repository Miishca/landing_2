# Landing Page for Museum

This repository contains the source code for the landing page of a museum. The landing page provides information about the museum's exhibitions, events, and other relevant details.

## Table of Contents

1. [Overview](#overview)
2. [Demo](#demo)
3. [Technologies Used](#technologies-used)
4. [Features](#features)
5. [Installation and Setup](#installation-and-setup)
6. [License](#license)
7. [Contact](#contact)

## Overview

The landing page for the museum is designed to offer an engaging and informative interface for users to learn about the museum, its exhibitions, upcoming events, and more. The page includes sections for exhibitions, events, a gallery, and contact information.

### Demo

- [GitHub Repository](https://github.com/miishca/landing_2)
- [Live Demo](https://miishca.github.io/landing_2/)

## Technologies Used

- **HTML5**: The structure of the landing page is built using HTML5, providing semantic elements for better accessibility and SEO.
- **CSS3**: The styles are written in CSS3, ensuring a modern and responsive design.
- **JavaScript**: Used for interactive elements and functionalities on the page.

## Features

- **Responsive Design**: The layout adjusts to different screen sizes, ensuring a good user experience on both mobile and desktop devices.
- **Swiper**: Used for the gallery slider.
- **Google Fonts**: Montserrat and IBM Plex Sans are used for typography.
- **SCSS**: For styling with variables, mixins, and responsive design techniques.
- **Exhibitions Section**: Showcases current and upcoming exhibitions with images and descriptions.
- **Events Section**: Provides information about upcoming events at the museum.
- **Gallery**: A collection of images showcasing the museum's exhibits.
- **Contact Form**: Allows users to send messages to the museum, along with contact details including phone number, email, and physical address.

## 📦 Installation and Setup

To run the project locally:

1. **Clone the repository**

   ```bash
   git clone https://github.com/miishca/landing_2.git
   cd landing_2
   ```

2. **Install Node.js**

   Ensure you have Node.js installed (version 16 or higher).
   Check version:

   ```bash
   node --version
   npm --version
   ```

3. **Install project dependencies**

   ```bash
   npm install
   ```

4. **Run the development server**

   ```bash
   npm start
   ```

   The local server will automatically open at:

   ```
   http://localhost:1234
   ```

5. **Build for production**

   ```bash
   npm run build
   ```

   The optimized files will be placed in the `dist` folder.

## 🛠️ Troubleshooting

- **If styles don’t load**, check your CSS link path in `index.html`:

  ```html
  <link rel="stylesheet" href="styles/style.css" />
  ```

- **Manually compile SCSS if necessary**:

  ```bash
  npx sass styles/style.scss styles/style.css
  ```

- **If dev server fails to start**, clear Parcel cache:

  ```bash
  rm -rf .parcel-cache dist
  npm start
  ```

- **Check browser console for errors (F12 → Console tab)**

- **Ensure all SCSS imports exist and are correct** in `styles/style.scss`

```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or suggestions, feel free to reach out:

- **Email:** [mykhailoevo@gmail.com](mailto:mykhailoevo@gmail.com)
- **GitHub:** [miishca](https://github.com/miishca)
```
