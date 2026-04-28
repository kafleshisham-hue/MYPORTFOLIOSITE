# Sisam Kafle - Portfolio

My personal portfolio site. A place to showcase my work in AI/ML and cybersecurity. Built from scratch with vanilla HTML, CSS, and JavaScript—no bloat, no framework overhead. Just clean code and smooth animations.

**Check it out:** [sisam.dev](#) (or your GitHub Pages URL)

## What's Here

- **Dark theme** with electric blue accents (because dark mode is better for your eyes)
- **Smooth animations** that don't feel janky—using vanilla CSS and JS
- **Fast loading** — single HTML file, minimal dependencies
- **Mobile-first** design that actually works on small screens
- **Project showcase** with real work I've done
- **Experience timeline** from my journey in India to Canada
- **Contact form** if you want to reach out
- **Particle background** in the hero (it looks cool, I admit it)

## What You'll See

- **Hero** — My name, what I do (AI, ML, Security), and quick links
- **About** — A bit about my background and what drives me
- **Skills** — What I actually know: Python, TensorFlow, Splunk, Wireshark, etc.
- **Projects** — Real projects I've built: ML models, web apps, security tools
- **Experience** — Timeline of where I've worked
- **Education** — My degrees and certifications
- **Contact** — Shoot me an email or hit me up on LinkedIn/GitHub

## Run It Locally

If you want to check it out before deploying:

```bash
# Clone it
git clone https://github.com/YourUsername/portfolio.git
cd portfolio

# Option 1: Python
python -m http.server 8000

# Option 2: Node
npx http-server

# Then open http://localhost:8000 in your browser
```

## Deploy to GitHub Pages

There's a GitHub Actions workflow set up that automatically deploys when you push to `main`. Just:

1. Push your code to GitHub
2. Go to Settings → Pages
3. Select "Deploy from a branch" → `main` branch → `/root` folder
4. Your site goes live at `https://yourusername.github.io/portfolio`

See [SETUP.md](SETUP.md) for detailed steps.

## The Tech Stack

- **HTML5** — Clean semantic markup
- **CSS3** — Custom animations, CSS variables, no preprocessor
- **Vanilla JavaScript** — No frameworks, no React, no build step
- **Typed.js** — For that cool typing effect
- **Font Awesome** — Icon library
- **Google Fonts** — Space Grotesk (looks sleek)

That's it. No webpack, no Node modules, no dependency hell.

## Colors

- **Dark navy background** — `#0a0e1a` (easy on the eyes)
- **Electric blue accent** — `#00d4ff` (pops)
- **Purple secondary** — `#7c3aed` (depth)
- **Light text** — `#e5e7eb` (readable)

Everything's in CSS variables, so it's easy to tweak if you want to customize.

## Customizing It

All the content is in `index.html`. Pretty straightforward to edit:

**Add your photo:**
Drop your professional headshot (square or close to it) in the `img/` folder as `profile.jpg`. It'll automatically display in the About section in a nice circle. See `img/README.md` for details.

**Update your info:**
```html
<h1>Hi, I'm <span class="hero-name">Your Name</span></h1>
<p class="about-text">Your bio here...</p>
<a href="mailto:your.email@example.com">your.email@example.com</a>
```

**Add your resume:**
```html
<a href="path/to/your-resume.pdf" class="btn">
    <i class="fas fa-download"></i> Download Resume
</a>
```

**Update social links:**
```html
<a href="https://linkedin.com/in/yourprofile" class="social-link">
    <i class="fab fa-linkedin-in"></i>
</a>
```

**Add/edit projects:**
Copy a project card in the Projects section and change the title, description, and tech stack. The emojis stay for visual interest.

## Mobile-Friendly

Works on everything:
- Desktop (obvs)
- Tablets
- Mobile phones (small and large)
- Even watches probably (not tested, but it would work)

## Performance

- **Single file** — Everything in one `index.html`. Load once, done.
- **No build step** — Just open it or push to GitHub
- **Fast animations** — CSS + vanilla JS, no lag
- **Lazy loading** — Images and cards load as you scroll
- **CDN libraries** — Font Awesome and Google Fonts from CDN

## Files

```
.
├── index.html                    # Everything (HTML, CSS, JS)
├── README.md                     # This file
├── SETUP.md                      # How to deploy
├── CONTRIBUTING.md               # Want to fork and improve?
├── LICENSE                       # MIT
├── .gitignore                    # Git stuff
└── .github/workflows/deploy.yml  # Auto-deployment
```

## Browser Support

Anything modern:
- Chrome, Edge, Firefox, Safari
- Mobile: iOS Safari, Chrome Mobile
- Basically any browser from the last 3-4 years

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Future Ideas

Things I'm thinking about adding:
- Blog section
- Contact form backend (right now it opens your email client)
- Dark/light theme toggle
- Project filters
- Testimonials
- Maybe a newsletter signup

## Hit Me Up

📧 **Email:** kafle.shisham@gmail.com  
📱 **Phone:** (416) 854-6394  
📍 **Location:** Oshawa, ON, Canada  
🔗 **LinkedIn:** [linkedin.com/in/sisam-kafle](#)  
💻 **GitHub:** [@your-github](#)

## Libraries I Used

- **Google Fonts** — Space Grotesk
- **Font Awesome** — Icons
- **Typed.js** — Typing effect

---

Built with coffee and no frameworks ☕
