# Personal Portfolio Website

A clean, modern portfolio website built with React to showcase your skills, projects, and professional experience.

## 🚀 Features

- Responsive design that works on all devices
- Clean and modern UI
- Dark/Light mode
- Smooth scroll animations
- Project showcase with filter options
- Skills section with progress bars
- Contact form
- SEO optimized

## 📦 Technologies Used

- React.js
- CSS3 with Flexbox/Grid
- React Router
- React Icons
- Email.js for contact form

## 🛠️ Installation & Setup

1. Clone the repository:
   ```
   git clone https://github.com/danush189/Basic-React-Website.git
   ```

2. Navigate to the project directory:
   ```
   cd Basic-React-Website
   ```

3. Install dependencies:
   ```
   npm install
   ```

4. Start the development server:
   ```
   npm start
   ```

5. Open your browser and visit `http://localhost:3000`

## 📂 Project Structure

```
├── public/
│   ├── index.html
│   └── assets/
├── src/
│   ├── components/
│   │   ├── Header/
│   │   ├── Hero/
│   │   ├── About/
│   │   ├── Skills/
│   │   ├── Projects/
│   │   ├── Contact/
│   │   └── Footer/
│   ├── assets/
│   │   ├── images/
│   │   └── icons/
│   ├── styles/
│   │   └── global.css
│   ├── App.js
│   └── index.js
└── README.md
```

## 📱 Responsive Design

The website is fully responsive and works seamlessly across devices:
- Desktop: 1024px and above
- Tablet: 768px to 1023px
- Mobile: 767px and below

## 🎨 Customization

You can easily customize this portfolio by:

1. Updating your personal information in `src/data/personalInfo.js`
2. Adding your projects in `src/data/projects.js`
3. Modifying skills in `src/data/skills.js`
4. Changing colors and styling in `src/styles/global.css`

## 🚀 Deployment

This portfolio can be easily deployed to:

- GitHub Pages
- Netlify
- Vercel
- Firebase

### Deploying to GitHub Pages

1. Install gh-pages:
   ```
   npm install --save gh-pages
   ```

2. Add these scripts to your `package.json`:
   ```json
   "predeploy": "npm run build",
   "deploy": "gh-pages -d build"
   ```

3. Add homepage to `package.json`:
   ```json
   "homepage": "https://danush189.github.io/Basic-React-Website"
   ```

4. Deploy:
   ```
   npm run deploy
   ```

## 🔄 Future Updates

- Add blog section
- Implement animations with Framer Motion
- Add multi-language support
- Add themes customization

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📞 Contact

If you have any questions, feedback, or would like to connect, feel free to reach out!

- GitHub: [danush189](https://github.com/danush189)

---

Made with ❤️ and React