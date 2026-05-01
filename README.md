# CCA Church Eldoret Area Website

This is the official website for CCA Church Eldoret Area.

## Features
- Responsive design with white, pinkish, red, and blue colors.
- Leadership section with circular image cards.
- Past Events Gallery with images and videos.
- Contact form and giving options.
- Accessible and optimized for performance.

## Local Setup
1. Ensure you have Python installed.
2. Run `python -m http.server 8000` in the project directory.
3. Open `http://localhost:8000` in your browser.

## Deployment to GitHub Pages
1. Install Git from https://git-scm.com/.
2. Create a new repository on GitHub.
3. Run the following commands:
   ```
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/yourrepo.git
   git push -u origin main
   ```
4. In GitHub repo settings, enable Pages from the main branch.
5. The site will be live at https://yourusername.github.io/yourrepo/.

## Adding Images and Videos
- Place images in the `images/` folder.
- Place videos in the `videos/` folder.
- Update the HTML accordingly.

## Accessibility
- The site includes ARIA labels and semantic HTML for better accessibility.