# Erik Jacome Portfolio Website
This is a personal portfolio website showcasing my work as a full-stack software engineer. It highlights projects that I've worked on, gives an overview of my experience, and helps connect me with new opportunities. The goal is to have a clean, visually engaging, and responsive site that reflects my skills and creativity.

**Link to project:** [https://erikjacome-portfolio.com](https://erikjacome-portfolio.com/)

![Portfolio Screenshot](https://i.imgur.com/xzkNVn8.gif)

## How It's Made:

**Tech used:** HTML, CSS, JavaScript

The portfolio was made with the help of a template and modified with a focus on clean design, intuitive user experience, and responsiveness across different devices. I used HTML for structure, CSS for styling, and JavaScript to add interactivity. Some of the core features include:
- A video background on the homepage to add a creative flair.
- Smooth scrolling and navigation features, thanks to JavaScript.
- A responsive gallery of projects that blurs and darkens on hover, revealing an "Open" text overlay.

For the layout, I made use of semantic HTML tags to keep the code organized and maintainable. The CSS involves Flexbox for the gallery section and CSS Grid for overall alignment, helping maintain the responsiveness across all screen sizes. The JavaScript handles interactions like the play button on the homepage video and project hover effects to enhance the user experience.

## Optimizations

During development, I encountered issues with autoplaying videos on mobile browsers. To ensure compatibility, I implemented a user-initiated play button that enhances both desktop and mobile user experience. Additionally:
- Added fallback video formats (`.webm` and `.mp4`) for better compatibility across different browsers.
- Improved the CSS hover effects for project images to ensure that the text overlay remains sharp and readable, even when the background blurs.
- Reduced the initial load time by optimizing image sizes, using `srcset` for responsive images.

Future optimizations include implementing lazy-loading for images and improving the website's performance by minimizing CSS and JavaScript files.

## Lessons Learned:

One of the key lessons from building this project was the importance of cross-browser compatibility, especially on mobile. Making sure the video works seamlessly on iOS Safari led me to learn more about media formats and user interaction triggers.

I also learned the importance of performance optimization—managing media files and considering ways to improve load speed and responsiveness. This process gave me deeper insight into efficient front-end workflows and better user experience design. The exercise of adding a JavaScript-triggered play button was particularly rewarding, as it highlighted the different approaches required to handle both desktop and mobile environments.
