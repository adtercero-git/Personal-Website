# Anthony D. Tercero - Personal Website

Welcome to the repository for my personal academic website, hosted on [GitHub Pages](https://pages.github.com/) and built with the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/). This site serves as a professional hub to showcase my research interests, provide access to my CV, and share contact information.

## Features
- **Research Summary**: A brief overview of my research interests and professional focus.
- **Curriculum Vitae (CV)**: Downloadable as a PDF.
- **Contact Information**: Direct methods to reach me.
- **Professional Photo**: A simple personal touch for website visitors.

## Development Setup
If you'd like to run this site locally or make edits, follow the steps below:

### Prerequisites
Ensure you have the following installed:
- [Ruby](https://www.ruby-lang.org/)
- [Bundler](https://bundler.io/)
- [Git](https://git-scm.com/)

### Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/Personal-Website.git
   cd Personal-Website
2. **Install dependencies**: Run Bundler to install the required gems
   ```bash
   bundle install
3. **Serve the site locally**: Start a local Jekyll server
   ```bash
   bundle exec jekyll serve
Open your browser at http://localhost:4000 to preview the site.
4. **Make edits**: 
Customize _config.yml to update site metadata and settings.
Add or edit Markdown files (e.g., about.md) to create new pages.
Push Changes: Once you've made changes, commit and push them back to the repository:
```bash
   git add .
   git commit -m "Update site content"
   git push origin main

**File Structure**
_config.yml: Jekyll configuration file for site settings.
Gemfile & Gemfile.lock: Ruby gems for the website, including the Minimal Mistakes theme.
index.md: The main homepage content.
your-cv.pdf: Downloadable CV file (replace with your actual CV).
assets/: Folder for images, including your professional headshot.
License
This website is built using the Minimal Mistakes Jekyll Theme, which is open-source and licensed under the MIT License.


   
