# GenAI FAQs & Ethical Use of AI

## Short Overview

This is a comprehensive, educational website designed to help students, researchers, and general users understand Generative AI (GenAI), its capabilities, limitations, and ethical considerations. The website provides clear, accessible information about responsible AI use, particularly in academic and professional contexts.

## Features

### 🏠 Landing/Home Page (index.html)
- Eye-catching title section with animated elements
- Introduction to Generative AI
- Quick navigation to all major sections
- Feature cards highlighting key topics
- Responsive design with navy blue theme

### ❓ FAQ Section (faq.html)
- Comprehensive accordion-style FAQs covering:
  - What is Generative AI?
  - How does it work?
  - Examples of GenAI tools (ChatGPT, DALL-E, Copilot, etc.)
  - Strengths and capabilities
  - Limitations and risks
  - Student usage guidelines
  - Job market impact
  - Data privacy concerns
- Properly cited references from authoritative sources

### ⚖️ Ethical Use of AI (ethics.html)
- Tabbed interface covering five major topics:
  1. **Academic Use**: Responsible use in education, appropriate vs. inappropriate uses
  2. **Plagiarism**: Understanding AI plagiarism, citation guidelines, consequences
  3. **Accuracy**: Verification strategies, critical evaluation framework, high-risk areas
  4. **Bias**: Types of bias, recognition strategies, mitigation techniques
  5. **Guidelines**: Core principles, practical checklist, ethical decision-making framework
- Real-world examples and scenarios
- Interactive checklist for ethical AI use
- Comprehensive references

### 💻 Analogy on the Use of AI in Dev Work (article.html)
- Thought-provoking analogy comparing wedding photographers using consumer tools to developers using AI
- Critical analysis of "vibe coders" and AI-assisted development
- Discussion of integrity, creativity, and skill level
- Balanced perspective on tool usage vs. professional expertise
- Reflection on what truly defines professional competence

## Technologies Used

- **HTML5**: Semantic markup for all pages
- **CSS3**: Custom styling with animations and transitions\
- **JavaScript**: Interactive features and animations
- **Bootstrap 5.3.2**: Responsive grid system, components, and utilities
- **Font Awesome 7.1.0**: Icons throughout the site

## Frameworks and Libraries

| Technology | Version | Purpose |
|------------|---------|---------|
| Bootstrap | 5.3.8 | Responsive framework, UI components |
| Font Awesome | 7.1.0 | Icon library |
| JavaScript | ES6+ | Interactive features, animations |
| CSS3 | - | Custom styling, animations, transitions |

## File Structure

```
project-root/
│
├── index.html              # Landing/Home Page
├── faq.html                # FAQ Section
├── ethics.html             # Ethical Use of AI Page
├── article.html            # Analogy on the Use of AI in Dev Work
├── README.md               # Details about the Project
│
└── assets/
    ├── css/
    │   └── style.css       # Custom CSS styles
    │
    ├── js/
    │   └── script.js       # Custom JavaScript
    │
    └── img/                # Images (screenshots of the website)
```

## How to Run the Project

### Option 1: Direct Browser Opening (Simplest Method)
1. Download or clone this repository
2. Navigate to the project folder
3. Double-click or open `index.html` in any modern web browser (Chrome, Firefox, Safari, Edge)
4. Navigate through the site using the top navigation menu

### Option 2: Local Server (Recommended for Development)

#### Using Python:
```bash
# Python 3
cd project-folder
python -m http.server 8000
```
Then open `http://localhost:8000` in your browser

#### Using Node.js:
```bash
# Install http-server globally (one-time setup)
npm install -g http-server

# Run server in project folder
cd project-folder
http-server
```
Then open the provided local address in your browser

#### Using VS Code Live Server:
1. Install "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"
4. Browser will open automatically

### Option 3: Online Deployment

The website is ready to deploy to any static hosting service:
- **GitHub Pages**: Push to GitHub and enable Pages in repository settings
- **Netlify**: Drag and drop the project folder at netlify.com
- **Vercel**: Import from GitHub or upload directly at vercel.com

## Deployment Links
- **Live Demo**: [gen-ai-faqs-ethical-use-of-ai.netlify.app](https://gen-ai-faqs-ethical-use-of-ai.netlify.app)
- **Live Demo**: [gen-ai-faqs-ethical-use-of-ai.vercel.app](https://gen-ai-faqs-ethical-use-of-ai.vercel.app)

### Deployment Instructions:

#### Netlify:
1. Create account at netlify.com
2. Drag and drop project folder or connect GitHub repo
3. Site deployed instantly with custom URL
   
#### Vercel:
1. Create account at vercel.com
2. Import GitHub repository or upload files
3. Automatic deployment with custom domain support

## Screenshots

### Landing/Home Page
![Landing/Home Page](img/landing-hero.png)

### FAQ Section
![FAQ Section](img/faq-page.png)

### Ethical Use of AI Page
![Ethical Use of AI Page](img/ethics-page.png)

### Analogy on the Use of AI in Dev Work
![Analogy on the Use of AI in Dev Work](img/article-page.png)

## Academic Integrity Statement

This website was developed to educate users about ethical AI use. The content emphasizes the importance of academic integrity, proper citation, and responsible technology use. All information is sourced from reputable organizations and properly cited.
