# PROMPT FOR GENERATING index.html and style.css

## copy paste this prompt in chatgpt and take the html generated and paste it in index.html and style.css

Generate a complete tech portfolio website for a Computer Science student, with two separate files:

index.html – full HTML structure

style.css – all styling (no Tailwind, no Bootstrap, pure CSS)

``` prompt
# Role
You are an expert Senior Frontend Engineer and UI/UX Designer. Your task is to build a high-performance, responsive personal portfolio website using **only** HTML and CSS.

# Context & User Data
Please populate the site with the following details. If a field is empty, use a professional placeholder.

**Personal Details:**
- Full Name: {{Maanas S}}
- Role/Title: {{Computer BTech Engineer}} (e.g., "Systems Engineer")
- Tagline: {{Play Valorant}}
- Location: {{Bengaluru}}

**Education:**
- University: {{VIT University}}
- Degree: {{BTech}}
- Grad Year: {{2029}}

**Technical Skills:**
- Languages: {{C++, Python, HTML}}
- Tools/Platforms: {{vs code}}
- Core Concepts: {{Create Website}}

**Projects (Highlight 2-3):**
1. {{vodka}}: {{nice}}
2. {{jack daniels}}: {{good}}
3. {{brocode}}: {{better}}

**Interests:**
- Hobbies: {{Football}}
- Soft Skills: {{I am }}

**Links:**
- GitHub: {{GITHUB_URL}}
- LinkedIn: {{LINKEDIN_URL}}
- Email: {{EMAIL_ADDRESS}}

# Design Requirements
1. **Theme:** Dark mode default. Use a "Hacker/Terminal" aesthetic (e.g., dark gray backgrounds, neon accent colors).
2. **Typography:** Use distinct monospaced fonts for headers.
3. **Responsiveness:** Must look perfect on mobile and desktop.
4. **Layout:** Single-page scrolling design with a sticky navigation bar.

# Technical Constraints
- **File Structure:** You must provide exactly **two** files:
  1. `index.html`
  2. `style.css`
- **No External Libraries:** Do not use Bootstrap, Tailwind, or external JS frameworks. Use vanilla CSS (Flexbox/Grid).
- **JavaScript:** If any interactivity is needed (like a mobile menu toggle), write the JavaScript strictly **inside a `<script>` tag at the bottom of the HTML file**. Do not create a separate .js file.

# Output Instructions
Please generate the full code for these two files below.

## File 1: index.html
- Should link to `style.css`.
- Should contain semantic HTML5 tags (<header>, <main>, <section>, <footer>).
- Should contain the embedded JS for the mobile menu or simple animations.

## File 2: style.css
- Should contain all styling, variables for colors, and media queries for responsiveness.
```
