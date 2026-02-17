# Portfolio Website

A modern, responsive portfolio website built with HTML and CSS, automatically deployed to GitHub Pages.

## 🌟 Features

- **Responsive Design**: Looks great on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design with gradient colors and smooth animations
- **Easy to Customize**: Simple HTML and CSS structure for easy modifications
- **GitHub Pages**: Automatically deployed using GitHub Actions

## 📂 Project Structure

```
.
├── index.html              # Main HTML file
├── style.css               # Stylesheet
├── .github/
│   └── workflows/
│       └── deploy.yml      # GitHub Actions workflow for deployment
└── README.md               # This file
```

## 🚀 Getting Started

### View the Portfolio

Once deployed, your portfolio will be available at:
`https://divyasreesivakumar.github.io/test/`

### Local Development

To view the portfolio locally:

1. Clone the repository
2. Open `index.html` in your browser, or
3. Run a local server:
   ```bash
   python3 -m http.server 8080
   ```
   Then visit `http://localhost:8080`

## 🎨 Customization

### Personal Information

Edit `index.html` to update:
- Name in the hero section
- Professional title and description
- About Me section content
- Project details and descriptions
- Skills list
- Contact links (email, GitHub, LinkedIn)

### Styling

Edit `style.css` to customize:
- Colors (see CSS variables in `:root`)
- Fonts
- Layout and spacing
- Animations and effects

### Color Scheme

The default color scheme uses CSS variables defined at the top of `style.css`:

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --text-color: #1f2937;
    --text-light: #6b7280;
    --bg-color: #ffffff;
    --bg-light: #f9fafb;
    --border-color: #e5e7eb;
}
```

## 📦 Deployment

### ⚠️ Required Setup (One-Time)

**Before the workflow can deploy, you MUST enable GitHub Pages:**

1. Go to your repository **Settings** → **Pages**  
   (Or visit: `https://github.com/[username]/[repository]/settings/pages` - replace with your username and repo name)
2. Navigate to "**Pages**" in the left sidebar
3. Under "**Build and deployment**" → "**Source**", select "**GitHub Actions**"
4. Click "**Save**"

This is a one-time setup. Once completed, all future deployments will happen automatically.

### Automatic Deployment

After completing the setup above, the portfolio will deploy automatically:

1. Push your changes to the `main` or `master` branch
2. GitHub Actions will automatically build and deploy your site
3. Your site will be available at `https://[username].github.io/[repository]/`

### Manual Setup

If this is your first time setting up GitHub Pages:

1. Go to your repository Settings
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select "GitHub Actions"
4. The workflow will automatically deploy on the next push

## 📱 Sections

The portfolio includes the following sections:

1. **Navigation**: Fixed navigation bar with smooth scrolling
2. **Hero**: Eye-catching introduction with gradient background
3. **About**: Personal introduction and background information
4. **Projects**: Showcase of featured projects with technologies used
5. **Skills**: Technical skills organized by category
6. **Contact**: Contact buttons with links to email and social profiles
7. **Footer**: Copyright information

## 🛠️ Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- GitHub Actions (for deployment)
- GitHub Pages (for hosting)

## 📄 License

This project is open source and available for anyone to use and customize.