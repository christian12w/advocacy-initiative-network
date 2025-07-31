# Website Project

## Overview
This project is a website built using Tailwind CSS for styling. It includes a simple structure with a main HTML file, CSS files for styles, and configuration files for managing dependencies and build processes.

## Project Structure
```
website-project
├── src
│   └── styles.css        # Contains Tailwind CSS directives for styles
├── dist
│   └── styles.css        # Compiled CSS output
├── index.html             # Main HTML document
├── package.json           # npm configuration file
├── tailwind.config.js     # Tailwind CSS configuration
├── postcss.config.js      # PostCSS configuration
└── README.md              # Project documentation
```

## Setup Instructions
1. **Clone the repository**:
   ```
   git clone <repository-url>
   cd website-project
   ```

2. **Install dependencies**:
   ```
   npm install
   ```

3. **Build the CSS**:
   To compile the CSS from `src/styles.css` to `dist/styles.css`, run:
   ```
   npm run build:css
   ```

4. **Watch for changes**:
   To automatically rebuild the CSS when changes are made, run:
   ```
   npm run watch:css
   ```

## Usage
Open `index.html` in your web browser to view the website. The styles will be applied from the compiled CSS file located in the `dist` directory.

## Contributing
Feel free to submit issues or pull requests for improvements or bug fixes.

## License
This project is licensed under the MIT License.