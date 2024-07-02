# Personal Resume Website

This is a personal resume website built with HTML and CSS. The website is designed to showcase your contact information, skills, education, and work experience in a clean and professional layout. It is fully responsive and adapts to different screen sizes for an optimal viewing experience on both desktop and mobile devices.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Demo

You can view a live demo of the website [here](https://fazilsourcecode.github.io/RESUME/).

## Features

- Responsive design
- Clean and professional layout
- Easy to customize
- Includes sections for contact information, skills, education, and work experience
- Uses Font Awesome for icons

## Installation

To get a local copy of the website up and running, follow these simple steps:

1. Clone the repository:

    ```sh
    git clone https://github.com/fazilsourcecode/resume-website.git
    ```

2. Navigate to the project directory:

    ```sh
    cd RESUME
    ```

## Usage

To customize the resume with your own information, edit the `index.html` and `styles.css` files.

### HTML

Update the following sections in `index.html`:

- **Header**: Replace `YOUR NAME` and `YOUR TITLE` with your own name and title.
- **Contact**: Replace the email, GitHub, and LinkedIn placeholders with your own contact information.
- **Skills**: List your own skills.
- **Education**: Update the education section with your own details.
- **About**: Add a brief paragraph about yourself.
- **Work Experience**: List your job titles, company names, and achievements.

### CSS

You can further customize the styles in `styles.css` to match your personal preferences.

### Example

Here is an example of how to customize the HTML:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RESUME</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <div class="container">
        <header>
            <h1><span>M</span>OHAMED <span>F</span>AZIL</h1>
            <p class="title">RESUME</p>
        </header>
        <div class="main-content">
            <div class="left-column">
                <section class="contact">
                    <h2>Contact</h2>
                    <p><i class="fas fa-envelope"></i> <a href="mailto:mohamedfazil0705@gmail.com">mohamedfazil0705@gmail.com</a></p>
                    <p><i class="fab fa-github"></i> <a href="https://github.com/fazilsourcecode" target="_blank">fazilsourcecode</a></p>
                    <p><i class="fab fa-linkedin"></i> <a href="https://www.linkedin.com/in/mohamed-mdfazil/" target="_blank">Mohamed Fazil</a></p>
                </section>
                <section class="skills">
                    <h2>Skills</h2>
                    <p>HTML, CSS, JS, Java, C, C++</p>
                </section>
                <section class="education">
                    <h2>Education</h2>
                    <p><strong>B TECH IT</strong></p>
                    <p>BS Abdur Rahman Crescent University<br>2022-2026</p>
                </section>
            </div>
            <div class="right-column">
                <section class="about">
                    <h2>About</h2>
                    <p>I am a motivated B.Tech Information Technology student with a strong foundation in JavaScript, Java, HTML, CSS, and Data Structures. My academic journey has equipped me with the technical skills and problem-solving abilities necessary for software development. With a keen interest in backend development, I am eager to contribute to innovative projects and learn from industry professionals. I am passionate about creating efficient and scalable backend solutions, and I am excited about the opportunity to grow my skills in a dynamic and challenging environment.</p>
                </section>
                <section class="experience">
                    <h2>Work Experience</h2>
                    <div class="job">
                        <h3>Intern</h3>
                        <p>CIIC | 2024 - JUL</p>
                        <ul>
                            <li> Achievements : AI Fraud Detections Project</li>
                            
                        </ul>
                    </div>
                </section>
            </div>
        </div>
    </div>
</body>
</html>
```css
