Build a complete, modern, production-ready web application called "readme".

Project:
readme is a modern and easy-to-use GitHub README Maker with step-by-step guides for creating professional README files.

GitHub Repository:
https://github.com/kamrullab/readme

The website should feel like a real developer tool, not a generic template website.

==================================================
1. CORE PRODUCT IDEA
==================================================

readme helps developers create professional GitHub README files without manually writing Markdown.

Main workflow:

User opens readme
        ↓
Choose what to create
        ↓
Fill in information
        ↓
Choose sections
        ↓
Choose template
        ↓
Customize
        ↓
Live Preview
        ↓
Generate README.md
        ↓
Copy / Download

The website must support both beginners and experienced developers.

The main focus should be:
- Simplicity
- Developer-friendly UI
- Fast experience
- Clean Markdown generation
- Live preview
- Professional README output
- Helpful guides

==================================================
2. TECH STACK
==================================================

Use:

- React
- Vite
- TypeScript
- Tailwind CSS
- Modern component architecture
- Lucide icons
- Markdown rendering
- GitHub REST API where appropriate
- LocalStorage for saving drafts
- No database required for the first version
- No authentication required for the first version

Keep the code clean, modular, reusable and easy to maintain.

Use reusable components instead of putting everything into one file.

==================================================
3. DESIGN DIRECTION
==================================================

Design a modern developer-focused SaaS/tool website.

Visual style:

- Minimal
- Professional
- Modern
- Developer-oriented
- Clean typography
- Excellent spacing
- Subtle borders
- Rounded cards
- Soft shadows
- Beautiful dark mode
- Light mode
- Responsive design
- Smooth micro-interactions

Do NOT make it look like a generic AI landing page.

Avoid:
- Excessive gradients
- Huge unnecessary text
- Too many animations
- Cluttered dashboards
- Stock photos

Use a GitHub/developer-tool inspired aesthetic.

Primary theme should work beautifully in both dark and light mode.

Use a consistent design system for:
- Buttons
- Inputs
- Cards
- Dropdowns
- Tabs
- Modals
- Alerts
- Code blocks
- Markdown preview

==================================================
4. GLOBAL NAVIGATION
==================================================

Create a responsive navbar.

Logo:

readme

Logo subtitle or small text:

README Maker

Navigation:

- Home
- Create README
- Templates
- Guides
- About
- GitHub

Right side:

- Theme toggle
- GitHub button

On mobile:
- Hamburger menu
- Slide-down/mobile navigation

GitHub button should link to:

https://github.com/kamrullab/readme

==================================================
5. HOME PAGE
==================================================

Create a polished landing page.

Hero section:

Small badge:

"Free & Open Source"

Main heading:

"Create a Professional GitHub README in Minutes"

Subheading:

"Build beautiful GitHub README files without writing Markdown manually."

Buttons:

"Create README"

"Explore Guides"

Secondary text:

"No signup required"

Hero should immediately explain what readme does.

Add a visual README preview on the right side or underneath depending on screen size.

The preview should look like a real GitHub README.

Example:

# 👋 Hi, I'm Your Name

Developer | Open Source Enthusiast

## 🚀 About Me

...

## 🛠️ Skills

...

## 📊 GitHub Stats

...

==================================================
6. HOME PAGE SECTIONS
==================================================

Add:

A. How It Works

3 or 4 steps:

1. Enter your information
2. Choose your sections
3. Customize your README
4. Copy or download

B. Features

Cards:

- Live Preview
- Multiple Templates
- GitHub Profile Import
- GitHub Stats
- Skills Builder
- Project Builder
- Social Links
- Markdown Export
- Download README
- Beginner Friendly
- Dark Mode
- Local Draft Saving

C. README Preview

Show an attractive sample README.

D. Guides section

Show beginner-friendly guides.

Examples:

"How to Create a GitHub Profile README"

"How to Add a README to a Repository"

"How to Edit a README"

"Markdown Basics"

"How to Add GitHub Stats"

E. Open Source section

Explain:

"readme is open source."

Button:

"View on GitHub"

Link:

https://github.com/kamrullab/readme

F. Final CTA

"Ready to build your README?"

Button:

"Create My README"

==================================================
7. CREATE README PAGE
==================================================

This is the main application.

Route:

/create

Create a professional README builder interface.

Desktop layout:

LEFT:
Form / controls

RIGHT:
Live preview

On mobile:
Stack controls and preview.

Provide a sticky preview if appropriate.

==================================================
8. README BUILDER
==================================================

Create a multi-section form.

Section 1:

Personal Information

Fields:

- Full Name
- GitHub Username
- Profile Picture URL
- Professional Title
- Short Bio
- Location
- Email
- Website

Example:

Name:
Kamrul Hossain

Username:
kamrullab

Title:
System Administrator & Web Developer

Bio:
Building things for the web and exploring technology.

==================================================
9. GITHUB IMPORT
==================================================

Add:

"Import from GitHub"

User enters:

GitHub Username

Button:

"Import Profile"

Use GitHub public API to retrieve public profile information.

Retrieve where available:

- Name
- Username
- Avatar
- Bio
- Location
- Website
- Followers
- Following
- Public repositories

Do not expose or request private tokens.

Handle:
- Invalid username
- API errors
- Rate limits
- Empty profile fields

Show a loading state.

After import:

"Profile imported successfully"

Allow the user to edit imported information.

==================================================
10. README SECTIONS
==================================================

Allow users to enable/disable sections.

Use checkboxes or toggle cards.

Sections:

- Header
- About Me
- Skills
- Tech Stack
- Social Links
- Projects
- Experience
- Education
- Certifications
- GitHub Stats
- GitHub Streak
- Top Languages
- Contribution Graph
- Contact
- Support
- Visitors Counter
- Custom Section

Every section should be independently editable.

Allow drag-and-drop section ordering if practical.

The generated README must follow the selected order.

==================================================
11. ABOUT ME
==================================================

Provide a textarea.

Example placeholder:

"Write a short introduction about yourself..."

Allow Markdown.

==================================================
12. SKILLS BUILDER
==================================================

Create an easy skill selector.

Categories:

Languages:
- JavaScript
- TypeScript
- Python
- Java
- C
- C++
- PHP
- Go
- Rust

Frontend:
- React
- Next.js
- Vue
- Angular
- Tailwind CSS

Backend:
- Node.js
- Express
- Django
- Laravel
- FastAPI

Database:
- MySQL
- PostgreSQL
- MongoDB
- Redis

DevOps:
- Linux
- Docker
- Kubernetes
- GitHub Actions
- Nginx
- Cloudflare

Allow:

"Add Custom Skill"

Each selected skill should appear in the README preview.

==================================================
13. SOCIAL LINKS
==================================================

Fields:

- GitHub
- LinkedIn
- Facebook
- X/Twitter
- YouTube
- Instagram
- Website
- Email

Allow custom social links.

Validate URLs.

Generate clean Markdown automatically.

==================================================
14. PROJECT BUILDER
==================================================

Allow users to add multiple projects.

Each project:

- Project Name
- Description
- GitHub URL
- Live Demo URL
- Technologies
- Image URL

Buttons:

"Add Project"

"Remove Project"

"Move Up"

"Move Down"

Generated result:

## 🚀 Projects

### Project Name

Project description.

[GitHub] [Live Demo]

==================================================
15. EXPERIENCE BUILDER
==================================================

Allow multiple experience entries.

Fields:

- Job Title
- Company
- Location
- Start Date
- End Date
- Description
- Responsibilities

Support:

"Present"

Generate a professional Experience section.

==================================================
16. EDUCATION BUILDER
==================================================

Fields:

- Degree
- Institution
- Start Year
- End Year
- Description

Allow multiple entries.

==================================================
17. CERTIFICATIONS
==================================================

Fields:

- Certificate Name
- Issuer
- Date
- Credential URL

Allow multiple certificates.

==================================================
18. GITHUB STATS
==================================================

Provide toggles for:

- GitHub Stats
- Top Languages
- GitHub Streak
- Contribution Graph
- Profile Views

Let the user choose whether to include them.

Generate appropriate Markdown/image URLs.

Make sure generated URLs use the selected GitHub username.

Do not hardcode the username.

==================================================
19. TEMPLATE SYSTEM
==================================================

Create a Templates page:

/templates

Provide multiple templates.

Initial templates:

1. Minimal
2. Professional
3. Developer
4. Modern
5. Open Source
6. Profile Focused

Each template should have:

- Preview
- Template name
- Short description
- Use Template button

Template selection should change the README output.

Create the template system in a reusable architecture.

Example:

templates/
    minimal
    professional
    developer
    modern
    opensource
    profile

==================================================
20. CUSTOMIZATION
==================================================

Allow users to customize:

- Section order
- Heading style
- Emoji usage
- Divider style
- Badge visibility
- GitHub stats visibility
- Social links
- Custom sections

Provide a simple customization panel.

Do not overwhelm the user with unnecessary settings.

==================================================
21. LIVE MARKDOWN PREVIEW
==================================================

The right panel should update instantly whenever the form changes.

Show:

"README Preview"

Render actual Markdown.

Support:

- Headings
- Paragraphs
- Lists
- Links
- Images
- Code blocks
- Tables
- Badges

The preview should visually resemble GitHub Markdown rendering.

Add tabs:

Preview
Markdown

Preview:
Rendered README

Markdown:
Raw generated README.md

==================================================
22. COPY README
==================================================

Add:

"Copy README"

button.

When clicked:

Copy generated Markdown to clipboard.

Show:

"README copied!"

Do not copy HTML.

Copy only raw Markdown.

==================================================
23. DOWNLOAD README
==================================================

Button:

"Download README.md"

Generate a real file:

README.md

Download it directly.

Use the browser File/Blob API.

No backend required.

==================================================
24. SAVE DRAFT
==================================================

Use LocalStorage.

Buttons:

"Save Draft"

"Load Draft"

"Clear Draft"

Automatically save changes when practical.

Do not require login.

Show:

"Draft saved locally"

Make it clear that the draft is stored in the user's browser.

==================================================
25. RESET
==================================================

Add:

"Reset Builder"

Before deleting data show confirmation.

Example:

"Are you sure you want to reset your README?"

Buttons:

Cancel
Reset

==================================================
26. GUIDES PAGE
==================================================

Route:

/guides

This is an important part of readme.

Create a documentation/learning center.

Title:

"GitHub README Guides"

Subtitle:

"Learn how to create, customize and maintain a professional GitHub README."

Guide cards.

Categories:

Getting Started
Markdown
GitHub
README
Customization

Initial guides:

1. What is a GitHub README?
2. How to Create a GitHub Profile README
3. How to Create a Repository README
4. How to Edit a README
5. How to Add Images
6. How to Add Links
7. Markdown Basics
8. Markdown Headings
9. Markdown Lists
10. Markdown Tables
11. How to Add Badges
12. How to Add GitHub Stats
13. How to Add Social Links
14. How to Organize a Developer README
15. README Best Practices

==================================================
27. GUIDE DETAIL PAGE
==================================================

Example route:

/guides/github-profile-readme

Create a beautiful documentation layout.

Desktop:

Left:
Guide navigation / table of contents

Center:
Article

Right:
On-page table of contents if appropriate

Mobile:
Collapsible table of contents.

Each guide should contain:

- Title
- Short description
- Reading time
- Table of contents
- Explanation
- Markdown examples
- Code blocks
- Screenshots/placeholders where appropriate
- Related guides

Add:

"Create README with readme"

CTA at the bottom.

==================================================
28. MARKDOWN GUIDE
==================================================

Create a complete beginner-friendly Markdown guide.

Explain:

# Heading

## Subheading

**Bold**

*Italic*

[Link](URL)

![Image](URL)

- List

1. Numbered list

```code
Code