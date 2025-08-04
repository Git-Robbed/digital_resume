# Digital Resume Portfolio

A modern, responsive personal portfolio website built with HTML, CSS, and Tailwind CSS. This project showcases professional skills, work experience, and portfolio items in an elegant and interactive design.

## Features

- **Responsive Design**: Optimized for all devices and screen sizes
- **Dark/Light Theme**: Multiple theme variations available
- **Interactive Elements**: Smooth animations and transitions
- **Contact Form**: Functional contact form with PHP backend
- **Portfolio Showcase**: Gallery of work samples and projects
- **Blog Section**: Blog pages for content sharing
- **Modern UI**: Clean, professional design using Tailwind CSS

## Pages Included

- **Home Page**: Landing page with hero section and key information
- **Portfolio**: Showcase of work samples and projects
- **Resume**: Detailed professional experience and skills
- **Blog**: Blog posts and articles
- **Contact**: Contact form and information

## Dark Theme Variants

Each page includes both light and dark theme versions:
- `index.html` / `index_dark.html`
- `portfolio.html` / `portfolio_dark.html`
- `resume.html` / `resume_dark.html`
- `blog.html` / `blog_dark.html`
- `contacts.html` / `contacts_dark.html`

## One-Page Version

Also includes one-page versions for a more compact experience:
- `index_onepage.html` / `index_onepage_dark.html`

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom styling and animations
- **Tailwind CSS**: Utility-first CSS framework
- **JavaScript**: Interactive functionality
- **PHP**: Backend for contact form
- **jQuery**: DOM manipulation and animations

## Setup and Development

1. **Install Dependencies**:
   ```bash
   npm install
   ```

2. **Start Development Server**:
   ```bash
   npm run dev
   ```

3. **Build CSS**:
   The Tailwind CSS is automatically compiled from `src/main.css` to `assets/css/main.css`

## Project Structure

```
├── assets/
│   ├── css/          # Compiled CSS files
│   ├── images/       # Images and media files
│   ├── js/          # JavaScript files
│   └── fonts/       # Font files
├── src/
│   └── main.css     # Source CSS with Tailwind directives
├── mailer/          # PHP mailer configuration
├── *.html           # HTML pages (light and dark themes)
├── package.json     # Node.js dependencies
└── tailwind.config.js # Tailwind CSS configuration
```

## Customization

- **Colors**: Modify the Tailwind config in `tailwind.config.js`
- **Content**: Update HTML files with your personal information
- **Styling**: Edit `src/main.css` for custom styles
- **Images**: Replace images in `assets/images/` with your own

## Contact Form

The contact form uses PHP mailer for sending emails. Configure the mailer settings in the `mailer/` directory.

## License

This project is licensed under the ISC License.

## Author

Built with ❤️ using modern web technologies. 