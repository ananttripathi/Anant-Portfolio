# Anant Tripathi — Professional Portfolio

A modern, Apple-inspired portfolio website showcasing expertise in AI, Machine Learning, and Data Science.

## 🌟 Features

- **Clean, Professional Design**: Minimalist Apple-inspired aesthetic
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Direct Contact Form**: Visitors can send messages directly to your email
- **Smooth Animations**: Elegant scroll effects and transitions
- **Fast & Lightweight**: Optimized for performance
- **GitHub Pages Ready**: Easy deployment with zero configuration

## 🚀 Quick Start

### Option 1: GitHub Pages (Recommended)

1. **Create a new repository on GitHub**
   - Go to [github.com](https://github.com) and create a new repository
   - Name it: `<your-username>.github.io` (e.g., `ananttripathi.github.io`)
   - Make it public

2. **Upload files**
   - Upload all files from this folder to your repository
   - Or use Git commands:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/your-username/your-username.github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Source: Deploy from a branch
   - Branch: `main` → `/root`
   - Click Save

4. **Visit your site**
   - Your portfolio will be live at: `https://your-username.github.io`

### Option 2: Hugging Face Spaces

1. **Create a Space**
   - Go to [huggingface.co/spaces](https://huggingface.co/spaces)
   - Click "Create new Space"
   - Choose "Static" as Space type

2. **Upload files**
   - Upload `index.html`, `styles.css`, and `script.js`
   - Your site will be live instantly

### Option 3: Local Testing

Simply open `index.html` in your browser to preview locally.

## 📧 Contact Form Setup

The contact form uses **FormSubmit.co** for email forwarding (free, no backend required).

### Current Configuration

The form is pre-configured to send emails to: `ananttripathiakt@gmail.com`

### First-Time Setup

1. The first time someone submits the form, FormSubmit will send a verification email
2. Click the verification link in that email
3. After verification, all future submissions will be delivered instantly

### Customization Options

To customize the form behavior, add these hidden inputs in `index.html`:

```html
<!-- Redirect after submission -->
<input type="hidden" name="_next" value="https://your-site.com/thanks.html">

<!-- Custom subject line -->
<input type="hidden" name="_subject" value="New Portfolio Contact!">

<!-- Disable CAPTCHA -->
<input type="hidden" name="_captcha" value="false">

<!-- Carbon copy to another email -->
<input type="hidden" name="_cc" value="another@email.com">
```

## 🎨 Customization

### Update Personal Information

Edit `index.html` to update:
- Name and title
- About section
- Work experience
- Skills
- Education
- Contact information

### Change Colors

Edit `styles.css` CSS variables:

```css
:root {
    --color-accent: #0071e3;  /* Main accent color */
    --color-text: #1d1d1f;    /* Primary text color */
    /* ... more variables ... */
}
```

### Add Profile Photo

1. Add your photo to the folder (e.g., `profile.jpg`)
2. Update the hero section in `index.html`:

```html
<div class="hero-image">
    <img src="profile.jpg" alt="Your Name">
</div>
```

3. Add styling in `styles.css`:

```css
.hero-image {
    max-width: 400px;
    margin: 40px auto 0;
}

.hero-image img {
    width: 100%;
    border-radius: 50%;
}
```

## 📱 Sections

1. **Hero** - Eye-catching introduction
2. **About** - Professional summary with key statistics
3. **Work Experience** - Detailed career timeline
4. **Skills** - Technical capabilities organized by category
5. **Education** - Academic background
6. **Contact** - Direct messaging form and contact information

## 🔧 Technologies

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with custom properties
- **JavaScript (Vanilla)** - No dependencies, pure JS
- **FormSubmit.co** - Contact form email service

## 📊 Performance

- **No external dependencies** - Except for Google Fonts
- **Fast load times** - Minimal, optimized code
- **SEO friendly** - Semantic HTML structure
- **Accessible** - WCAG compliant

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📝 License

This portfolio template is free to use and customize for personal purposes.

## 🤝 Contact

**Anant Tripathi**
- Email: ananttripathiakt@gmail.com
- LinkedIn: [linkedin.com/in/ananttripathiak](https://linkedin.com/in/ananttripathiak)
- GitHub: [github.com/ananttripathi](https://github.com/ananttripathi)

---

Built with ❤️ using modern web technologies

