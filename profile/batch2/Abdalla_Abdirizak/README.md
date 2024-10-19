# Portfolio Template
![Portfolio](https://github.com/user-attachments/assets/40e0754d-4a49-4736-8325-20a9bd3cd1ef)

This repository contains a portfolio template that can be used to showcase your work, skills, projects, and more. The template is built with HTML, CSS, and JavaScript.

## Features

- Responsive design
- Light/Dark mode toggle
- About Me section
- Resume section
- Projects section
- Research section
- Blog section
- Contact form

## Getting Started

### Prerequisites

- Basic knowledge of HTML, CSS, and JavaScript
- A GitHub account

### Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2. **Customize the template:**

    Open the project in your favorite code editor and modify the HTML, CSS, and JavaScript files located in the `assets` folder to suit your needs. Update the following files:
    
    - `index.html`: Update personal information, section contents, etc.
    - `assets/css/lightmode.css`: Customize styles for the light mode.
    - `assets/css/darkmode.css`: Customize styles for the dark mode.
    - `assets/js/script.js`: Modify the JavaScript code if needed.

3. **Add your content:**

    - Replace the placeholder images in the `assets/images` directory with your own images.
    - Update links, social media handles, and contact information in the `index.html` file.

### Deploying to GitHub Pages

1. **Create a new repository on GitHub:**

    Go to GitHub and create a new repository named `your-username.github.io` (replace `your-username` with your GitHub username).

2. **Push the local repository to GitHub:**

    ```sh
    git remote add origin https://github.com/your-username/your-repo-name.git
    git branch -M main
    git push -u origin main
    ```

3. **Create and switch to the `gh-pages` branch:**

    ```sh
    git checkout --orphan gh-pages
    ```

4. **Remove all files from the `gh-pages` branch:**

    ```sh
    git rm -rf .
    ```

5. **Copy the necessary files into the `gh-pages` branch:**

    ```sh
    cp -r * ../
    ```

6. **Add, commit, and push the changes:**

    ```sh
    git add .
    git commit -m "Initial commit for GitHub Pages"
    git push origin gh-pages
    ```

7. **Enable GitHub Pages:**

    - Go to the repository settings on GitHub.
    - Scroll down to the "GitHub Pages" section.
    - Select the `gh-pages` branch as the source.
    - Click "Save".

8. **Access your portfolio website:**

    Your portfolio should now be live at `https://your-username.github.io`.

## Customization

Feel free to customize the template to better suit your needs. Here are some common customizations:

- **Change Theme:** Modify the CSS files to change the look and feel of the website.
- **Add Sections:** Add more sections by editing the `index.html` file.
- **Update Content:** Replace the placeholder content with your own information.
- **Optimize for SEO:** Add meta tags, titles, and descriptions to improve search engine optimization.

## Contributing

If you'd like to contribute to this template, please fork the repository and use a feature branch. Pull requests are welcome.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

W.S.S.Perera - shashipraba.56@gmail.com
