# Zachary Ryan - Portfolio Website

Welcome to my personal portfolio website! This site showcases my background, skills, projects, and achievements as I pursue a career in cybersecurity.

## About the Website

This portfolio website highlights my journey from being a U.S. Navy veteran to becoming a cybersecurity student. It features the following sections:

- **About Me:** An overview of my background, including my transition from the Navy to cybersecurity.
- **Skills:** A display of technical and professional skills with interactive icons that pop out when hovered over—even if you quickly slide your cursor across multiple icons.
- **Projects:** Personal projects that demonstrate my coding proficiency and problem-solving abilities.
- **Achievements:** A summary of academic and extracurricular accomplishments, including certifications and club involvement.
- **Contact:** Clickable links for connecting via LinkedIn, GitHub, email, and phone.

## Tech Stack

This website was built using:

- **HTML:** For the site structure.
- **CSS:** For styling, layout, and responsive design.
- **JavaScript:** For interactive animations (e.g., the sticky pop effect on skill icons).
- **Google Fonts:** For enhanced typography.
- **Devicon CDN:** For the technology icons.

## Features

- **Responsive Design:** Optimized for both desktop and mobile devices.
- **Smooth Scrolling Navigation:** Easy access to each section.
- **Interactive Skill Icons:** When you hover over a skill icon, it scales up by 40% (to 140% of its original size). JavaScript adds a temporary pop effect, so multiple icons can pop out briefly if you slide your mouse quickly.
- **Project Cards:** Each project includes a description and a link to its GitHub repository.
- **Clickable Contact Information:** Easily accessible links for connecting via LinkedIn, GitHub, email, and phone.

## File Structure

├── assets/ # Contains images, icons, and the resume file ├── index.html # Main HTML file with embedded CSS and JavaScript └── README.md # Project documentation (this file)

bash
Copy

## How to Use

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Zachary200114/portfolio-website.git
   Open index.html in your browser to view the website.
   JavaScript Functionality
   The website uses JavaScript to create a "sticky pop" effect on the skill icons. When your cursor enters a skill icon, the icon temporarily scales up by 40%, even if you quickly slide your mouse across several icons. Here's the key JavaScript snippet used:
   ```

javascript
Copy
const icons = document.querySelectorAll('.skill-logo');
icons.forEach(icon => {
icon.addEventListener('mouseenter', () => {
icon.classList.add('pop');
// Remove the pop effect after 500ms (adjustable)
setTimeout(() => {
icon.classList.remove('pop');
}, 500);
});
});
This code allows multiple icons to remain popped out briefly, enhancing the interactive experience.

Future Improvements
Enhance animations and other interactive elements.
Implement a dynamic contact form.
Optimize performance further for faster load times.
Improve accessibility for a wider range of users.
Contact
Feel free to reach out if you'd like to collaborate, discuss cybersecurity topics, or just connect:

Email: Zxrst175@mail.rmu.edu
LinkedIn: Zachary Ryan
GitHub: Zachary200114
© 2025 Zachary Ryan. All rights reserved.
